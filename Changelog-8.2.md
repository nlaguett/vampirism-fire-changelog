# Vampirism Fire 8.2

---

## Main

- Version is fully rewritten in Lua and will hopefully improve the in game performances.
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

![Skin System](image.png)

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

---

### Orc Slayers

- Updated **Slayer Learned Abilities** tooltip with the correct values and improved readability.
- Fixed missing tooltip text for the **Goblin Engineer** ability.
- Updated **Building Protection** tooltip with more detailed information.

---

### House / Stronghold / Fortress

- Replaced the **Worker Peon** model with the **Fel Peon**.
  - Fixed portrait.
- Replaced the **Grunt Harvester** model with the **Fel Grunt**.
  - Fixed portrait.
- Replaced the **Fang Harvester** model from **Shaman** to **Felguard**.
  - Added the **Doom Guard** soundset.
- Replaced the **Kodo Spawn Deforester** model from **Baine** to **Drak'thul**.
  - Renamed to **Fire Spawn Deforester**.
- Restored the original skin color for the **Satyr Harvester**.
- Changed the **Orc Tower Builder** model from **Fel Peon** to **Fel Shaman**.
  - Fixed portrait.

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

---

### Witch Doctor

- Fixed missing name for **Sentry Ward**.

---

## Human

- [Eclipse-Tower] and [Super-Eclipse-Tower]
  - Fixed the Selection Scale value.
  - Changed the projectile

- [Super-Eclipse-Tower]
  - Added new tint for distinction purpose between the tower level 1 and level 2

---

## Orc

- [Burning-Oil]
  - Research time reduced **25 → 10 seconds**.

---

## Architect

- Added [Barricade-Builder]
  - Barricades now last **30 seconds**.

- [Emerald-Wall]
  - Lumber cost reduced **12,000 → 10,000**.

---

## Vampires

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

- [Mana-Resistance-Shield] (upgrade)
  - Now has a *buff* as indicator for the builders to scout if vampires bought the upgrade.

- [Teleportation-Rod] (upgrade)
  - Now has a *buff* as indicator for the builders to scout if vampires bought the upgrade.

- [Research-Center]
  - Removed abilities from Pages 1 and 2.
  - Pages 2 and 3 are now accessed using a new button located in the **bottom-left corner** of the screen.
  - Ability pages can now be freely grouped and organized.
![alt text](image-1.png)
![alt text](image-2.png)

---