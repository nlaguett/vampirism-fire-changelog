# Vampirism Fire 8.3.6

---

## Main

### New mode selection panel

- The three-button mode menu, the Custom settings panel and the read-only Pro panel are gone. They are replaced by **one tabbed window**: **Classic / Solo Vamp / Feed Lobby / New Vamps / Pro / Custom / 1V1**.
- Each tab now tells you what the mode actually does before you pick it (its balance changes, its ladder, and the settings the host can still tune).
- Every mode except Classic exposes the same set of host boosts: **vampire bounty, vampire experience, vampire revives, gold coin leak rate, human bonus lumber, goldmine income, no edge base**. **Custom** additionally unlocks resource sharing, damage sharing, new partner, new vamp partner, solo vamp, solo double vamp, feed lobby and new vamps.
- **Two new modes are selectable straight from the lobby:**
  - **SOLO VAMPIRE** — one vampire against the whole lobby, with its own balance and its own ladder.
  - **1V1** — exactly one builder against one vampire, with its own ladder.
- A tab is greyed out **only when the mode structurally cannot run** (1V1 needs exactly 1 builder + 1 vampire; Solo Vampire needs at least 5 builders and exactly 1 vampire). Every other mode can be played in a small lobby — it simply goes unranked.
- **The lobby vote only opens when the host actually changed something.** A stock preset locks in and the game starts immediately, so Classic and an untouched Pro game no longer cost the lobby 30 seconds. When the vote does open, it lists **only what changed** (old → new) instead of dumping the whole settings table.
- **RANKED / UNRANKED is now a host toggle on every mode.** Tweaking a preset's boosts no longer silently forces the game unranked.
- Multiplier buttons are symmetric again: `-` and `+` move by the same step and clamp to the allowed range. Previously `+` moved by 0.05 while `-` moved by 0.25, so overshooting a value could never be walked back.
- Fixed the **vampire bounty multiplier being silently ignored outside Custom** — a bounty boost set on Pro, or on any Classic-derived preset, did nothing. It now applies to kills, black building bounty and the tax system in every mode.
- The **New Partner** option was being applied but had no button anywhere to set it. It now has one.

### Ranked play & ELO

- **Solo Vampire and 1V1 each rate into their own ladder.** Every other mode continues to share the 10v2 ladder.
- The multiboard **ELO column now shows the rating for the ladder this game rates into**, and greys it out in an unranked game so nobody reads it as a score that is about to move.
- **Existing save files are not wiped.** Old saves load normally and start the two new ladders at 1500.
- The ranked check is judged **once, at lock-in** — leavers no longer void a game that started as ranked.

### `-show`

- `-show` now lists the **ranked status and the ladder** you are playing on, plus the value of **every** mode option. It is generated from the same source as the selection panel, so the two can no longer disagree.
- **Observers can now use `-show`** — it was registered for playing slots only and silently did nothing for them.
- Removed three rows that were listed but that nothing in the game could ever set (allied vision removal, no tax, anonymous mode).

### Desync fixes

- Fixed a **mode-selection desync around lobby start**: if a player left while the mode menu was being built, the host's pick could pass validation on one machine and fail on another — leaving one player in Solo Vamp and another in Classic. The host's own slot counts now travel with the pick, so every machine checks the same numbers.

---

## Vampires

### Solo Vamp — income rebalance

- The lone vampire's passive gold is now **one combined payout** instead of the solo ramp stacking on top of normal ancient income, and the whole curve has been retuned: **300 gold total by minute 10**, **500 by minute 15**, then step-ups at minutes **16, 18, 24, 36 and 48**. The early game is tighter, the late game is considerably stronger. The minute-24 / 36 / 48 lump sums are unchanged.

### Solo Vamp — Chain of Death

Solo Vamp Mode, the 1V1 preset and the Custom solo-vamp toggle now use a **solo-tuned Chain of Death**. **Classic, Pro, Feed Lobby and New Vamps keep the spell exactly as it is today.**

- Damage lost per bounce reduced **10% → 5%**.
- Cooldown reduced **10s → 8s**.
- New **level 16** — **515 damage** (previously capped at 475).
- **From minute 36 the spell grows again**: cooldown drops **8s → 5s**, announced on screen when it happens.
- It is still the same button, it levels the same way with your skill points, and it keeps every existing interaction: the engineer insta-kill, the "cannot cast on another vampire" guard, the Furbolg mark, the Refresh Potion cooldown reset and Twilight Gamble.

### Other

- **Removed the Orc Witch Doctor wards.**

---

## Human

### Slayer

- **A dead Slayer must now be revived at the Tavern instead of retrained.** Previously the revive button and the train button were both available at once, and using both left you holding **two Slayers**.
- Fixed a related bug where a retrained Slayer was deleted outright, and where the game kept pointing at the Slayer's corpse instead of the living unit.
- A Tavern destroyed **mid-training** still correctly gives your Slayer training back — that case is unchanged.

### Holy Water

- **Holy Water now actually lifts the tower stun.** Pulse Grenade and Tower Disable froze towers with a stun the dispel could not remove, so Holy Water played its effect, cleared the buff icon, and left the tower stunned anyway.
- A cleanse now also clears the **Tower Disable thunderclap visual**, which used to stay stuck on the tower.
- Fixed **Holy Water's own target effect never playing** (broken art path).
- Dead structures are no longer processed by the dispel.
- Tooltip fix: Holy Water's area was listed as **350** on the ability and **325** on the research — the real value is **400**, and both now say so.

### Urn

- **Urn of Farsight** mana cost reduced **200 → 50**. Urn of Reveal is unchanged at 200.
- Urn tooltips corrected — three of them disagreed with the actual item:
  - **Urn of Farsight**: cooldown is **20s**, not 30s.
  - **Urn of Reveal**: **10s cooldown over the entire map**, not 30s over "a large area" — its text was a copy of Farsight's. Both ability tooltips now also state their duration.
  - **Urn recipe**: duration is **25s**, not 10s.

### Temple of Prayers

- **Every Temple of Prayers pact paid half in Solo Vamp Mode.** The payout formula normalises around a two-ancient game, and Solo Vamp has only one ancient — so all five pacts paid 50% while the lone vampire was already collecting the full solo economy bonuses. **All five pacts now pay in full.** Solo Double Vamp was already correct and is unchanged.

### Auto-Repair

- Orc repair units (**builder, furbolg harvester and all engineer tiers**) now **stay rooted in place while Auto-Repair is toggled on**, and get their normal movement back the moment you toggle it off — no more workers wandering off the wall they were repairing.

---

## Other

### Base commands

- `-b` / `-base` / `-showbases` now **pings the real base entrance** (the glowing rune) instead of the centre of a map region, so the pings actually mark where you would walk in.
- The static minimap markers are gone; pings now roll across every unclaimed base in waves. The engine only keeps a handful of pings alive at once, so previously **half the bases never appeared**.

### Presentation

- The **opening portal ritual now runs during the 55-second countdown** instead of during the race and mode vote. Its lightning used to draw straight through the selection panels, disappear when the game was paused, and come back on top of the UI.
- New **loading screen** fade image (full 1920x1080).

### Text & messages

- The **player-leave message is coloured with the player's own colour** again instead of rendering white, and it is now announced across the observer slots too.
- Fixed the **Unholy Essence line printing a grey "X(Left)"** mid-sentence when a player left at the wrong moment.
- **Slayer names**: **PiciuU's** Slayer is named **"Pikachu"** again — the name never applied once a clan tag was on the player name. **Valentine's** Slayer is now named **"Deviant"**.
- Removed the repeated **"You can't spawn trackers inside another player's base"** message. The order is still blocked, it just no longer spams the screen.
- Removed leftover development messages from the Auto-Repair toggle.

---
