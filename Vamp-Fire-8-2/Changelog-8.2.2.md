# Vampirism Fire 8.2.2

---

## Main

- Disabled tracker spawn if a slayer is in a claimed base.


---

## Custom Mode 

- New custom mode option **no edge bases**
  - All edges bases removed when the game start. 
![edge-base1](<Capture d'écran 2026-07-16 142133.png>)
![edge-base2](<Capture d'écran 2026-07-16 142120.png>)
![edge-base3](<Capture d'écran 2026-07-16 142059.png>)


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


---

## Orc



---

## Architect

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

- [Jade-Wall] tooltip fixed.

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



---

## 📋 Summary of Changes
<!-- Briefly explain what was changed, why it was changed, and any notable technical details. -->
- **What changed:** 

1. Fixed vampires not being able to teleport onto French Men (Including Speed French Men). 
2. Orc Race being able to research slayer tech 2 more times for a total of 5 was updated to match the other races at max 3.
3. A bunch of Icon and tooltip QoL changes, images below.
---

## 🖼️ Visual Comparison

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/09827078-33cc-4eae-a9ad-1e47753a16f2" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/eeb3b6f1-f50d-4919-8498-844ecd74b9df" width="450" alt="After"> |
| *Old icon just shows hero icon which doesn't change through upgrades* | *Short caption describing the new behavior* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/003eb0b5-353e-4632-b6b5-8224bbe0f786" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/108a96ea-df7b-408f-8e24-8b4a2be9c896" width="450" alt="After"> |
| *Old book did not match theme of Vampires* | *New necromancy book is advanced necromancer book which looks better* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/2e5b0c41-e83c-4f86-9063-79dcf58944ca" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/9a87939e-00ed-4175-a505-0032d9b6253f" width="450" alt="After"> |
| *All Requirements refer to 'Any Tech 1' which defaults to "Human's Vault" but we currently have "Orc's Vault" which can cause confusion* | *Changed "Orc's Vault" to be "Human's Vault" for their race now so that requirements align with the same building name for clarity, until we enforce better conditions based on race* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/98ffe091-2f45-435a-b034-fc3fb7deb71c" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/4958d644-b2b1-4bd3-84bb-56552ace4b8f" width="450" alt="After"> | 
| *Old Claws of Attack that contained +20/+80/+100, description and icons not intuitive* | *Updated icons with better text descriptions and combination guide, Small Claws of Attack + Large Claws of Attack > Ultimate Claws of Attack* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/d93f749a-54d3-415c-a076-b9694818cbb8" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/522594bd-3d5d-4d04-ac78-24d5177e6a25" width="450" alt="After"> |
| *Old "Magic Plating" which uses the same icon as Vampire's Mana Resistance shield and isn't consistent with previous icons* | *Updated it to a slightly more adjacent shield that isn't used elsewhere and synergizes better* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/20914129-57c2-4c4c-82fd-73dcee7e3c9c" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/f6a615e0-2f4d-4b9f-b707-ba36c5050f37" width="450" alt="After"> |
| *Old icon for tower defenses which then for the 2nd upgrade turns into a book and is not consistent at all* | *Updated to be a more understanding upgrade icon and consistent with level 1 and 2* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/6e0c833d-9f7b-4665-89e1-dab567498281" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/3b7270b7-7a04-407c-b172-9004264df6d8" width="450" alt="After"> |
| *Single healing tower vitality icon doesn't make sense with a shield* | *Updated to a more reflective upgrade icon for healing towers HP, being a priest upgrade icon* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/28e473a9-389b-41c6-aba9-b4df302c4583" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/721a594e-765e-42c6-8504-c572a5df4dfb" width="450" alt="After"> |
| *Old gold plating description lackluster in clarity* | *New description provides colours of walls for reference* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/8b00e0c9-6fef-458e-ab46-75b2665bd862" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/3afa742f-1738-4093-a60b-0980a3247743" width="450" alt="After"> |
| *Old holy essence icon being a pink potion felt it could be more clear it was tied to tower upgrade rather than ability like the pulse potion clear* | *Updated icon to starfall and also updated description to be more descriptive of why exactly this upgrade is beneficial* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/9c9eff13-0aa2-4b57-ba27-e1406b14efe3" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/83efcf79-21ea-447e-b8e5-b719b6c17065" width="450" alt="After"> |
| *Old engineer icon is just reusing repairing icon* | *Replaced with actual engineering icon which hopefully conveys more quickly and eye appealing without reuse from other abilities* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/6c53f2fe-f14c-4db3-b372-e735342dac59" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/ad20f8f2-b9f3-4525-9d98-77de2ee7f83b" width="450" alt="After"> |
| *Old devotion aura description and icon* | *Replaced with more applicable vamp type aura and better description which changes with each level and clarifies with armor stacking or not* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/e846347f-1d44-4ad6-8c0a-5745e4e1f8ff" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/76159cc1-6a09-4b64-a2ae-c40c3622bdfd" width="450" alt="After"> |
| *Old mana resistance shield research that lacks warning detail* | *Added additional warning for it not stacking with the item to clear any confusion* |

| **Before** | **After** |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/246824a4-851e-4b29-8a56-4bde82101bcc" width="450" alt="Before"> | <img src="https://github.com/user-attachments/assets/c63f402a-7bf1-458e-b738-51932aa18b8b" width="450" alt="After"> |
| *Old vampire RC upgrade stats store, few dated icons and lacking text* | *Updated a few icons and enhanced text descriptions/colours for clarity* |

