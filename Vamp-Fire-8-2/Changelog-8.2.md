# Vampirism Fire 8.2

---

## Main

- Version is fully rewritten in Lua and will hopefully improve the in game performances.
- **WaterWalker007** statue now play the soundboard **This is WaterWalker007** when clicked.
- Default camera distance increased **1640 → 2500**
- When a *Vampire* dies, **50%** of the value of all researched upgrades is refunded.
- *Vampires* can no longer destroy the **Slayer's Tavern** before **minute 2**.
- [Ring-Of-Protection] HP bonus reduced **1000 → 250**.
- [Heavenly-Architect] build limit set to **1**.
- [Goblin-Tower-Builder] build limit set to **3**.
- [Main-Builder] mana regeneration increased from **0.100 -> 0.200**


### Skin System
- New UI implemented for changing skins.
- The interface can be opened using the button located in the **bottom-left corner** of the screen.
- Displays every unlockable skin along with its unlock requirements.
- Selected skins are now **saved automatically**, so they no longer need to be selected every game.



---

## Custom Mode Rework

The following modes have been **removed**:
- Anonymous Mode
- No Allied Vision Share

The following modes have been **added**:
- Solo Vamp Mode
- Feed Lobby Mode

### Solo Vamp Mode

- Vampire income now starts at **minute 0** instead of **minute 12**.
- Income starts at **20 gold/min** and increases by **+5 gold/min** every minute until minute 12.
- Attacking walls grants pillage gold over time, scaling from **2 → 8 gold/sec** with game time.
- Destroying a base grants **40%** of its total value as bounty.
- Vampire abilities **Health Beam** and **Chain of Death** have their cooldown reduced by **50%**.

### Feed Lobby Mode

- Builders receive their first gold income at **minute 4** instead of **minute 5**.
- Builders receive **5 gold** instead of **4 gold** at minute 4.
- Slayer Coin level cap based on game time has been removed.

### Solo Double Vamp Mode

- Fixed the `-rg` command.
- It now correctly transfers gold back from the Brown Vampire.

### Tax System

- Tax before **minute 25** reduced **65% → 55%**
- Tax cap before **minute 35** increased **3600 → 4000**

---

## New Commands

- Added `-racepref <race>`
  - If no race is manually selected, your preferred race will automatically be chosen.

---

## Training Mode

- [Frozen-Infernal]
  - Removed the **24-minute** unlock requirement.

- Fixed the `-sharecontrol` command.


---

## Visual & UI Improvements

### Slayer's Tavern

- Added the new **Blademaster Slayer**.
![alt text](Images/image-19.png)

---

### Orc Slayers

- Updated **Slayer Learned Abilities** tooltip with the correct values and improved readability.
- Fixed missing tooltip text for the **Goblin Engineer** ability.
- Updated **Building Protection** tooltip with more detailed information.

---

### House / Stronghold / Fortress

- Replaced the **Worker Peon** model with the **Fel Peon**.
  - Fixed portrait.
  ![Worker-Harvester](Images/image-20.png)
- Replaced the **Grunt Harvester** model with the **Fel Grunt**.
  - Fixed portrait.
  ![Grunt-Harvester](Images/image-21.png)
- Replaced the **Fang Harvester** model from **Shaman** to **Felguard**.
  - Added the **Doom Guard** soundset.

    ![Fang-Harvester](Images/image-22.png)
- Replaced the **Kodo Spawn Deforester** model from **Baine** to **Drak'thul**.
  - Renamed to **Fire Spawn Deforester**.
![Fire-Spawn-Harvester](Images/image-23.png)
- Restored the original skin color for the **Satyr Harvester**.
    ![Satyr-Harvester](Images/image-24.png)
- Changed the **Orc Tower Builder** model from **Fel Peon** to **Fel Shaman**.
  - Fixed portrait.

    ![Orc-Tower-Builder](Images/image-25.png)

![Harvesters](Images/image-26.png)

---

### Tent / Huge Tent

- Updated icons to use the **Pig Farm** icon.

---

### Research Center

- Updated **Improved Worker Motivation** tooltip to include the HP bonus.
  - Icon changed from **Peon** to **Fel Peon**.
- Updated **Slayer Adept Training** tooltip to include all training levels.
  - Icon changed from **Human Slayer** to **Orc Slayer**.

---

### Advanced Research Center

- Updated **Iron Plating** and subsequent upgrades to include the missing **+50 Onyx Armor** bonus.
- Removed the redundant wall list from **Gold Collector**.
- Corrected **Engineer's Vitality** tooltip to display the proper HP bonus (+400 per level).
- Improved the wording of the **Holy Water** tooltip.

---

### Vault / Citadel / Command Center / Base of Operations

- Fixed **Super Tower Builder** portrait.
- Replaced the **Goblin Tower Builder** model from **Fel Shaman** to **Goblin**.
![Goblin-Tower-Builder](Images/image-27.png)
---

### Witch Doctor

- Fixed missing name for **Sentry Ward**.
![Sentry-Ward](Images/image-28.png)
---

## Human

- [Human-Slayers]
  - Updated 'Slayer Learned Abilities' to include correct stats and make numbers easier to see.
      - Added missing level 3 tracker in list.
  - Updated text for 'Building Protection' to be more specific.
  - Updated text for 'Summons Tracker' to be more specific.
  - Updated text for 'Garlic Concoction' to be more specific.

- [House/Stronghold/Fortress]
  - Added 'DoomGuard' soundset to 'Fang Harvester', previously none.
  - Updated 'Satyr Harvester' to use Satyr Shadowdancer (Blue).

- [Research-Center]
  - Updated 'Improved Worker Motivation' text description to include Hitpoints.
   - Updated 'Slayer Adept Training' text description to include levels.

- [Advanced-Research-Center]
  - Updated 'Iron Plating' and the remaining to include missing Onyx +50 armor stat.
  - Removed list of walls for 'Gold collector' as redundant text.
  - Updated Engineers Vitality to correct Hitpoints upgrade (400 ahead for each level).
  - Slight text adjustment to Holy Water.

- [Eclipse-Tower] and [Super-Eclipse-Tower]
  - Fixed the Selection Scale value.
  - Changed the projectile

- [Super-Eclipse-Tower]
  - Added new tint for distinction purpose between the tower level 1 and level 2
![Super-Eclipse-Tower](Images/Images/image-29.png)

---

## Orc

- [Burning-Oil]
  - Research time reduced **25 → 10 seconds**.

---

## Architect


- [Architect-Slayers]
  - Updated 'Slayer Learned Abilities' to include correct stats and make numbers easier to see.
      - Added missing level 3 tracker in list.
  - Updated text for 'Building Protection' to be more specific.
  - Updated text for 'Summons Tracker' to be more specific.
  - Updated text for 'Garlic Concoction' to be more specific.

- [House/Stronghold/Fortress]
  - Updated 'Satyr Harvester' to use Satyr Shadowdancer (Blue).
  ![alt text](Images/image-32.png)

- [Research-Center]
  - Updated 'Improved Worker Motivation' text description to include Hitpoints.
   - Updated 'Slayer Adept Training' text description to include levels.

- [Advanced-Research-Center]
  - Updated 'Iron Plating' and the remaining to include missing Onyx +50 armor stat.
  - Removed list of walls for 'Gold collector' as redundant text.
  - Updated Engineers Vitality to correct Hitpoints upgrade (400 ahead for each level).
  - Slight text adjustment to Holy Water.

- [Icons]
  - Replaced 'Architect's Vault' human's icon with appropriate icon.
  - Replaced 'Advanced Research Center' human's icon with appropriate icon.
  - Replaced 'Citadel of Faith' human's icon with appropriate icon.
  - Replaced 'Command Center' human's icon with appropriate icon.
  - Replaced 'Base of Operations' human's icon with appropriate icon.


- Added [Barricade-Builder]
  - Barricades now last **30 seconds**.

- [Emerald-Wall]
  - Lumber cost reduced **12,000 → 10,000**.

---

## Vampires

- [Hellfire-Pit]
  - Fixed a bug where vampires could buy additional Vampire units.

- [Dark-Assault] 
  - No longer affect dead players & observers.

- [Vampiric-Boots]
  - Fixed the Bloodlust dummy ability causing collision issues.

- [Curse-Of-Doom]
  - Cooldown reduced **45 → 20 seconds**.

- Vampires now count as **2 votes** during Custom Mode voting.

- [Wizard-Frenchie]
  - Temporarily removed until fixed.

- [Farsight] and [Chain-Of-Death]
  - Both abilities are now automatically learned when the Vampire spawns.
  - Vampires start with:
    - **Farsight:** Level 2
    - **Chain of Death:** Level 1

- [Vampiric-Awakening]
  - Now gives **<bounty-awarded> * 3**
  - Replace temporarily the ground textures by undead earth for 3 seconds.
  ![Awakening-Blight](Images/Capture d'écran 2026-07-15 134251.png)
- [Mana-Resistance-Shield] (upgrade)
  - Now has a *buff* as indicator for the builders to scout if vampires bought the upgrade.
![Mana-Resistance-Shield](Images/image-30.png)
- [Teleportation-Rod] (upgrade)
  - Now has a *buff* as indicator for the builders to scout if vampires bought the upgrade.
![Teleportation-Rod](Images/image-31.png)
- [Research-Center]
  - Removed abilities from Pages 1 and 2.
  - Pages 2 and 3 are now accessed using a new button located in the **bottom-left corner** of the screen.
  - Ability pages can now be freely grouped and organized.


## Map Changes

- Base reworks:
  - Bases **1, 3, 4, 7, 9, 10, 11, 12, 13, 15, 19, 24, 26**
  - Base 1 : ![Base 1](Images/image-4.png)
  - Base 3 : ![Base 3](Images/image-5.png)
  - Base 4 : ![Base 4](Images/image-6.png)
  - Base 7 : ![Base 7](Images/image-7.png)
  - Base 9 : ![Base 9](Images/image-8.png)
  - Base 10 : ![Base 10](Images/image-9.png)
  - Base 11 : ![Base 11](Images/image-10.png)
  - Base 12 : ![Base 12](Images/image-11.png)
  - Base 13 : ![Base 13](Images/image-13.png)
  - Base 15 : ![Base 15](Images/image-12.png)
  - Base 19 : ![Base 19](Images/image-14.png)
  - Base 24 : ![Base 24](Images/image-15.png)
  - Base 26 : ![Base 26](Images/image-16.png)

  - Added a new portal top -> bot : ![top-portal](Images/image-17.png) ![bot-portal](Images/image-18.png)

---
