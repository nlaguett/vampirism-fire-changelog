# Vampirism Fire 8.3.6

---

## Main

### Desync fixes

- **Found and fixed the desync.** The release build pipeline was corrupting the packaged map: the copy step could fire more than once and overwrite the minified script with a stale debug build, so the map players actually downloaded did not match the source it was built from. Release maps are now packaged deterministically.
- Restored the **mode and Custom-panel synchronisation** that a previous revert had removed — the host's mode choice and every Custom setting sync to all players again.
- Fixed the clan-tag leave poll reading network-layer state that flips at a different moment on each machine.
- Fixed a race in save/load and a stray Waterwalker timer, both able to diverge state between clients.
- Handle-keyed tables are now iterated in a fixed order, removing a class of divergence caused by Lua iterating pointer keys differently per machine.

### Bug fixes

- **[Holy-Water] now actually works.** It played its dispel effect and cleared the buff icon, but the tower stayed stunned — the Pulse Grenade stun is a Storm Bolt class effect that a plain buff purge cannot lift. It now genuinely frees your towers, and also clears the stun from **Tower Disable**, whose visual effect used to stay stuck on the building afterwards.
- **[Holy-Water]** target art repaired — the ability's own effect never displayed because its art path was corrupted.
- **A dead Slayer is now revived, not replaced.** Losing your Slayer restored the training cap while the body was still raisable at the tavern, so taking both routes left you with **two Slayers**. Reviving is now the only way back, and the tavern no longer offers a train button beside the revive.
- **Retrained Slayers are no longer deleted.** The record of your Slayer was never cleared on death, so a newly trained one was treated as a duplicate and destroyed on the spot, leaving you selecting the corpse.
- The **"has left the game"** message now shows the leaving player's colour instead of plain white, and **observers can see it** — it previously stopped short of the observer slots entirely.
- Fixed the **Unholy Essence** announcement printing a mangled, greyed-out name when the last Ancient Vampire left.

### Base commands

- `-b` / `-base` / `-showbases` now **ping the actual base entrances** rather than approximate rect centres, and the static minimap icons are gone — the pings sweep in waves and are visible only to you.

### Quality of life

- **`-show` now works for observers.** It was registered only for the twelve playing slots, so observers could never open the mode panel.
- The **opening portal ritual** now runs during the "Vampires arrive" countdown instead of from the first frame. It used to be on screen throughout race and mode selection, drawing its lightning through the selection panels and reappearing over them whenever the game was unpaused.
- Mode selection rebuilt as a single tabbed panel, with ELO tracked per mode.

---

## Human

- **[Temple-of-Prayers] pays in full during Solo Vamp Mode.** Every pact payout scales with the number of Ancient Vampires and is normalised around a standard two-ancient game, so a lone vampire halved every human pact reward — on top of the solo vampire already collecting the lone-vamp economy bonuses. All five pacts now pay a normal game's rate.

---

## Vampires

- **[Urn-of-Farsight]** mana cost reduced **200 → 50**.
- **[Urn-of-Farsight]** and **[Urn-of-Reveal]** tooltips corrected. Both claimed a 30 second cooldown; Farsight is 20 and Reveal is 10. The Urn of Reveal also described "a large area" when it reveals the **entire map**, and its recipe understated the duration as 10 seconds when it is 25.

---

## Other

- Personal Slayer names now apply correctly for players in a clan. The lookup matches the decorated in-game name, so a player whose clan tag was missing from the table silently kept the default Slayer name.
