# Vampirism Fire 8.1g

---

## Main

- Added new clan: **SH**
- Added **Tournament Points System**
- Added a new multiboard section displaying each player's selected race
- [Ring-Of-Protection] armor bonus increased **6 → 9**
- [Barricade-Builder] life timer increased to **120 seconds** (now matches Barricade Wall timer)
- [Siege-Attack-Type] Nerfed. It's damage against infernals was reduced from **100% -> 50%**
- Observers will now see human & vampires are ally. This way they can see them typing in the chat.


---

## Training Mode

- New command `-fast` to finish buildings/research instantly.
- New command `-copy` to duplicate an unit. Can do `-copy` + <amount>
- New command `-str`, `-agi`, `-int` + <amount> to set hero stats
- New command `-armor` to set armor value
- New command `-create` as alternative of `-getMe`

- Main builders no longer gain their invulnerability until the min 5 
- 5 Seconds after the **training mode** start, main builders get **9999999** HP
- [Worker-motivation] gametime requirements are removed.

---

## Human

- Human starting HP reduced **1000 → 600**
- [Human-HP] research re-added to the Research Center:
  - Unlocks at **minute 12**
  - Gold cost: **0**
  - Research time: **0 seconds**

- [Sacrificial-Tower] damage gain increased:
  - Level 1: **100 → 150**
  - Level 2: **500 → 750**
  - Level 3: **2500 → 5000**

- [Carnelian-Wall] and [Pearl-Tower] now require a **House** to be built

- [Eclipse-Tower]
    Gold bounty awarded was fixed to **15** gold.

- [Super-Eclipse-Tower]
    Gold bounty award was fixed to **35** gold.


---

## Orc

- **Ward duration** increased **120 → 240 seconds**
- [Slayer-Training] lumber cost increment decreased from **+1000 -> +250**
- [Healing-Tower]
    Heal cooldown increased from 1 -> 10 sec
    Improved the auto heal function, it should now work for all healing/super healing towers.
- [Fang-Blades] upgrade is back
- [Super-Gold-Mine] is nerfed 
    Lumber cost 55 000 -> 60 000
- [Upgraded-Super-Gold-Mine]
    Lumber cost 42250 -> 48 000


---

## Architect

- [Infinite-Tower] attack speed increased **0.1 → 0.010**
- [Aqua-Outpost-Tower] fixed an issue where cancelling an upgrade granted unintended bonus mana
- [Upgraded-Shrine-Tower]
  - Now has a distinct color from Shrine Tower
  - Now requires **Citadel** to be built

- Added new models for **Super / Ultra / Elite Gold Mines** to better match race design
- [Advanced-Disaster-Tower] color for better distinction between upgrades
- [Shrine-Tower] projectile changed to fit the tower better

---

## Vampires

- Minions can no longer attack the warlock.
- Infernal meteor can no longer explode on the warlock.
- Buying a 2k item now also put [Nocturnes-Edge] on cooldown.
- [Speed-Frenchman] can now attack Main Builders
- Tax and Bounty gain system reworked (thanks to WingSpan)
  - Now more accurate when awarding *gold* to Vampires

---

## Bug Fixes & QoL Improvements

- Architect and Orc **Tower Builders** can now be found using the command `-orc`
- Architect and Orc **Furbolg Harvesters** can now be found using:
  - `-f`
  - `-furb`
  - `-furbolg`
- Killing an Architect **Mini Gold Mine** no longer preserves its income
- Fixed an issue allowing Vampires to teleport near walls
- **Range indicator** system improved (thanks to WingSpan):
  - It is now more precise
  - Displays range for the caster of the ability instead of only the tower owner
- End Game UI (CTRL + Q) can now be opened by observers 15 and 16
- Slayer now spawns with **Aeth** (ghost ability) to prevent body blocking
  - Expires at **minute 5**



---

## Special thanks

- Big thanks to WingSpan for making the **Tournaments points system** and other improvements like **Tower Range Indicator**.
