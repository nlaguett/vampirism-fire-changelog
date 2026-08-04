# Vampirism Fire 8.3

---

## Main

- Disabled tracker spawn if a slayer is in a claimed base ally base.
- Builders no longer have permanent vision in the vampire base.
  - Before
  
    <img src="Capture d'écran 2026-07-23 143440.png" width="400" alt="Vision-Bug">
  
  - After
  
    <img src="Capture d'écran 2026-07-23 143956.png" width="400" alt="Vision-Fixed">

- [Holy-Blood-Tower] can now be paused by flag.
- Fixed an issue that would allow observers to vote in the custom mode.
- [Big-Magic-Potion]
  - Gold cost reduced from **9 -> 5**
  - Lumber cost reduced from **22 000 -> 17 000**
- Fixed an issue that would allow observers to vote in the custom mode option.

- Harvesters now have sleep effect if they are not harvesting.

  <img src="Capture d'écran 2026-07-23 151622.png" width="400" alt="Afk-Harvester">

- [Race-Selection]
  - Changed the placements of the race buttons
  - Before :
  
    <img src="Capture d'écran 2026-08-04 112123.png" width="400" alt="Race-Selection">

  - After :
  
    <img src="Capture d'écran 2026-07-29 145320.png" width="400" alt="Race-Selection">

---

## Custom Mode 

- Added new vamp mode to the custom mode option instead of alternative to pro mode and custom mode.

- New custom mode option **no edge bases**
  - All edges bases removed when the game start. 

<p>
  <a href="Capture d'écran 2026-07-16 142133.png"><img src="Capture d'écran 2026-07-16 142133.png" width="260" alt="edge-base1"></a>
  <a href="Capture d'écran 2026-07-16 142120.png"><img src="Capture d'écran 2026-07-16 142120.png" width="260" alt="edge-base2"></a>
  <a href="Capture d'écran 2026-07-16 142059.png"><img src="Capture d'écran 2026-07-16 142059.png" width="260" alt="edge-base3"></a>
</p>


### Solo Vamp Mode

- Updated income values : 
  - Minutes 12–17: **60** gold/minute
  - Minutes 18–23: **100** gold/minute
  - Minutes 24–35: **150** gold/minute
  - Minutes 1–11 and minute 36 onward remain unchanged.

- Chain cd 50% reduction removed
- When the vampire cast a chain, a second chain will be casted on a random furb within 500 range of the vampire.
---

## Human

- Critters now correctly award mana to the **main-builder** when killed.
- [Black-Magic-Spire] reworked + fixed.
  - Removed the minions abilities
  - Purge ability should now correctly purge the banish ability.

- [Temple-of-Prayers]
  - Fixed all pacts rewards.
  - Fixed the UI that shows pacts duration for each player.

    <img src="Capture d'écran 2026-07-23 140526.png" width="620" alt="Pacts-UI">

  - Hover :

    <img src="Capture d'écran 2026-07-23 140532.png" width="620" alt="Pacts-UI-duration">
---

## Orc

- Fixed an issue that would require 2 gold mines instead of 1 to upgrade **Fortress**
- Fixed an issue that would allow orcs to train 2 slayers.
- [Main-Builder] mana regeneration increased from **0.100 -> 0.200**
- Wall tower tint changed to orange :
    
    <img src="Capture d'écran 2026-07-23 161941.png" width="300" alt="Orc-Wall-Tower">

---

## Architect

- [Main-Builder] mana regeneration increased from **0.100 -> 0.200**

- Re added [The-Casino]
  - Added ability tooltip **Casino Rules**
  - Added **Gambling Dice**
    - Requires 5 gold, 120 cd
    - 3/6 chance: Get 7 gold (earn 2 gold)
    - 2/6 chance: Nothing (you lose 5 gold)
    - 1/6 chance:
    - Tax Tower

- [Tax-Tower]
  - 1 attack speed, 600 NORMAL damage, 5000 hp. 
    - Can be upgraded 3 times requiring cita, cc, boo
      - Cita level 2: 10000 hp, 1800 dmg. Cost 15000w
      - Cc level 3: 15000 hp, 5400 dmg. Cost 40,000w
      - Boo level 4: 20000 hp, 0.5 attack speed, 15,000 damage, cost 100,000w

- [Metal-Amethyst-Wall]
  - Tint changed :

    <img src="Capture d'écran 2026-07-17 122706.png" width="300" alt="Metal-Amethyst">

- [Bounty-Jade-Wall] 
  - tooltip fixed.
  - Tints changed to golden color :
  
    <img src="Capture d'écran 2026-07-17 122415.png" width="400" alt="Bounty-Jade-Wall">

- [Marble-Wall] re added
  - Passive ability :
    - For each armor within **500 range** of the wall, gain **+25 armor**. For each minion within **500 range** of the wall gain **+10 armor**.
    - Repair time **35**
    - Base armor **100**
    - Gold cost : **45g**
    - Lumber cost : **85 000**
    - Base hp : **28 000**
    
---

## Vampires

- [Altar-Of-Blood]
  - Now owned by both of the vampires.
  - Fixed the issue where Altar of Blood would require "nearby patron" to buy minions.
  - Fixed an issue that would provide visions in the middle of the map to the builders.
  - Can be selected from a button and binded like the research center.

  <img src="Capture d'écran 2026-07-21 232852.png" width="400" alt="Altar-Of-Blood">
  
- Reverted back the bounty gain from Awakening.

- [Blood-Particle] Level 2
  - Cost increased from **7 -> 10 lumber**

- [Unholy-Infernal]
  - Now unlock at the **min 16** mark.

- Removed the unintended **Vampire poison** upgrade from the **vampiric research center**

- Changed all hotkeys to buy items and upgrade for the vampires to fit grid hotkeys (qwerty).

- [Silent-Whisper]
  - CD increased from **45 -> 60** seconds
  - Mana cost increased from **600 -> 800**
  - Stock cooldown increased from **120 -> 240** seconds
 
  - When holding 2 *Silent Whisper* in vampire inventory slot, it combine to upgraded version : 
  - CD reduced from **60 -> 30** seconds
  - Mana cost reduced from **800 -> 0**

- [Dark-Spear]
  - Now regenerate **100 mana** for each unit killed
  - Now regenerate **400 mana** for each slayer kill instead of **100**

- [Nocturnes-Edge] item removed.

- Levels upgrades locked if the vampire is level *23* before min *15*.

- [Cloak-of-Power]
  Gold cost increased from **2400 -> 2600**
  Damage gain reduced from **12250 -> 10 000**

- [Awakening]
  Fixed an issue that would award more gold than intended.

- [Sphere-Of-Doom] now correctly display red screen when bought.

---

## Qol Changes 



## Bases change

- Fixed a shifted tree base *19*