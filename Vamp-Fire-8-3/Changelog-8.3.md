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

- [Bouncy-Orb] (Fix)
  - Level 1 Now correclty require citadel of faith.
  - Level 2 now correctly require command center.
  - Level 2 gold cost was increased from **0 -> 10g**
- [Temple-of-Prayers]
  - Fixed all pacts rewards.
  - Fixed an issue that would not apply pact effect on wall.
  - Fixed an issue that would not destroy pact effect when a pact expire.
  - Fixed the UI that shows pacts duration for each player.

    <img src="Capture d'écran 2026-07-23 140526.png" width="620" alt="Pacts-UI">

  - Hover :

    <img src="Capture d'écran 2026-07-23 140532.png" width="620" alt="Pacts-UI-duration">
---

## Orc

- Fixed an issue that would require 2 gold mines instead of 1 to upgrade **Fortress**
- Fixed an issue that would allow orcs to train 2 slayers.
- Fixed an issue that allowed Orcs to research Slayer Tech two extra times; it is now capped at level 3 like the other races.
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

- Vampires can now use tp rod on frenchies.

- [Blood-Particle] Level 2
  - Cost increased from **7 -> 10 lumber**

- [Urn-Of-Reveal]
  - Duration increased from **10 -> 25 seconds**.
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

- Updated multiple icons and tooltips for clarity and consistency:
  - Replaced the static Slayer Tech hero icon with icons that change through the upgrade levels.
  - Replaced the Vampire Necromancy Book icon with the Advanced Necromancy Book icon.
  - Renamed **Orc's Vault** to **Human's Vault** so requirements consistently refer to the same building name.
  - Updated the Small, Large, and Ultimate Claws of Attack icons and descriptions, including their combination guide.
  - Replaced the reused **Magic Plating** icon with a distinct shield icon.
  - Updated the Tower Defenses upgrade icons so levels 1 and 2 use a consistent visual theme.
  - Replaced the Single Healing Tower Vitality icon with a clearer healing-tower upgrade icon.
  - Expanded the Gold Plating tooltip with wall-color references.
  - Updated the Holy Essence icon and description to better communicate its tower-upgrade purpose.
  - Replaced the reused Engineer repair icon with an engineering icon.
  - Updated the Devotion Aura icon and level descriptions, including armor-stacking behavior.
  - Added a warning that Mana Resistance Shield research does not stack with the item.
  - Updated several Vampire Research Center upgrade icons, descriptions, and colors.

### Visual Comparison

| Before | After |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/09827078-33cc-4eae-a9ad-1e47753a16f2" width="450" alt="Old Slayer Tech icon"> | <img src="https://github.com/user-attachments/assets/eeb3b6f1-f50d-4919-8498-844ecd74b9df" width="450" alt="Updated Slayer Tech icon"> |
| <img src="https://github.com/user-attachments/assets/003eb0b5-353e-4632-b6b5-8224bbe0f786" width="450" alt="Old Necromancy Book icon"> | <img src="https://github.com/user-attachments/assets/108a96ea-df7b-408f-8e24-8b4a2be9c896" width="450" alt="Updated Necromancy Book icon"> |
| <img src="https://github.com/user-attachments/assets/2e5b0c41-e83c-4f86-9063-79dcf58944ca" width="450" alt="Old vault requirement"> | <img src="https://github.com/user-attachments/assets/9a87939e-00ed-4175-a505-0032d9b6253f" width="450" alt="Updated vault requirement"> |
| <img src="https://github.com/user-attachments/assets/98ffe091-2f45-435a-b034-fc3fb7deb71c" width="450" alt="Old Claws of Attack icons"> | <img src="https://github.com/user-attachments/assets/4958d644-b2b1-4bd3-84bb-56552ace4b8f" width="450" alt="Updated Claws of Attack icons"> |
| <img src="https://github.com/user-attachments/assets/d93f749a-54d3-415c-a076-b9694818cbb8" width="450" alt="Old Magic Plating icon"> | <img src="https://github.com/user-attachments/assets/522594bd-3d5d-4d04-ac78-24d5177e6a25" width="450" alt="Updated Magic Plating icon"> |
| <img src="https://github.com/user-attachments/assets/20914129-57c2-4c4c-82fd-73dcee7e3c9c" width="450" alt="Old Tower Defenses icons"> | <img src="https://github.com/user-attachments/assets/f6a615e0-2f4d-4b9f-b707-ba36c5050f37" width="450" alt="Updated Tower Defenses icons"> |
| <img src="https://github.com/user-attachments/assets/6e0c833d-9f7b-4665-89e1-dab567498281" width="450" alt="Old Healing Tower Vitality icon"> | <img src="https://github.com/user-attachments/assets/3b7270b7-7a04-407c-b172-9004264df6d8" width="450" alt="Updated Healing Tower Vitality icon"> |
| <img src="https://github.com/user-attachments/assets/28e473a9-389b-41c6-aba9-b4df302c4583" width="450" alt="Old Gold Plating description"> | <img src="https://github.com/user-attachments/assets/721a594e-765e-42c6-8504-c572a5df4dfb" width="450" alt="Updated Gold Plating description"> |
| <img src="https://github.com/user-attachments/assets/8b00e0c9-6fef-458e-ab46-75b2665bd862" width="450" alt="Old Holy Essence icon"> | <img src="https://github.com/user-attachments/assets/3afa742f-1738-4093-a60b-0980a3247743" width="450" alt="Updated Holy Essence icon"> |
| <img src="https://github.com/user-attachments/assets/9c9eff13-0aa2-4b57-ba27-e1406b14efe3" width="450" alt="Old Engineer icon"> | <img src="https://github.com/user-attachments/assets/83efcf79-21ea-447e-b8e5-b719b6c17065" width="450" alt="Updated Engineer icon"> |
| <img src="https://github.com/user-attachments/assets/6c53f2fe-f14c-4db3-b372-e735342dac59" width="450" alt="Old Devotion Aura description"> | <img src="https://github.com/user-attachments/assets/ad20f8f2-b9f3-4525-9d98-77de2ee7f83b" width="450" alt="Updated Devotion Aura description"> |
| <img src="https://github.com/user-attachments/assets/e846347f-1d44-4ad6-8c0a-5745e4e1f8ff" width="450" alt="Old Mana Resistance Shield warning"> | <img src="https://github.com/user-attachments/assets/76159cc1-6a09-4b64-a2ae-c40c3622bdfd" width="450" alt="Updated Mana Resistance Shield warning"> |
| <img src="https://github.com/user-attachments/assets/246824a4-851e-4b29-8a56-4bde82101bcc" width="450" alt="Old Vampire Research Center upgrades"> | <img src="https://github.com/user-attachments/assets/c63f402a-7bf1-458e-b738-51932aa18b8b" width="450" alt="Updated Vampire Research Center upgrades"> |



## Bases change

- Fixed a shifted tree base *19*
