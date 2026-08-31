# Vampirism Fire 8.3.6

---

## Bug Fixes & QoL Changes

---

## Main

- **[Holy-Water] now actually works.** It played its dispel effect and cleared the buff icon, but the tower stayed stunned. It now genuinely frees your towers, and also clears the stun from **[Tower-Disable]**, whose visual effect used to stay stuck on the building afterwards.
- **[Holy-Water]** target art repaired — the ability's own effect never displayed because its art path was corrupted.
- **A dead Slayer is now revived, not replaced.** Losing your Slayer re-opened the training cap while the body was still raisable at the tavern, so taking both routes left you with **two Slayers**. Reviving is now the only way back, and the tavern no longer offers a train button beside the revive.
- **Retrained Slayers are no longer deleted.** The record of your Slayer was never cleared on death, so a newly trained one was treated as a duplicate and destroyed on the spot, leaving you selecting the corpse.
- The **"has left the game"** message now shows the leaving player's colour instead of plain white, and **observers can see it** — it previously stopped short of the observer slots entirely.
- Fixed the **Unholy Essence** announcement printing a mangled, greyed-out name when the last Ancient Vampire left.
- **`-show` now works for observers.** It was registered only for the twelve playing slots, so observers could never open the mode panel.
- `-b` / `-base` / `-showbases` now **ping the actual base entrances** instead of approximate rect centres, and the static minimap icons are gone — the pings sweep in waves and stay visible only to you.
- The **opening portal ritual** now runs during the "Vampires arrive" countdown instead of from the first frame. It used to be on screen throughout race and mode selection, drawing its lightning through the selection panels and reappearing over them whenever the game was unpaused.
- Mode selection rebuilt as a single tabbed panel, with ELO tracked per mode.

---

## Vampires

- **[Urn-of-Farsight]** and **[Urn-of-Reveal]** tooltips corrected. Both claimed a 30 second cooldown; Farsight is 20 and Reveal is 10. The Urn of Reveal also described "a large area" when it reveals the **entire map**, and its recipe understated the duration as 10 seconds when it is 25.

---

## Balance Changes

---

## Human

- **[Temple-of-Prayers]** now pays a full two-vampire reward in **Solo Vamp Mode**. Every pact payout scales with the number of Ancient Vampires and is normalised around a standard two-ancient game, so a lone vampire halved every human pact reward — on top of the solo vampire already collecting the lone-vamp economy bonuses. All five pacts now pay a normal game's rate.

---

## Vampires

- **[Urn-of-Farsight]** mana cost reduced **200 → 50**.

---

## Other

- Personal Slayer names now apply correctly for players in a clan. The lookup matches the decorated in-game name, so a player whose clan tag was missing from the table silently kept the default Slayer name.
