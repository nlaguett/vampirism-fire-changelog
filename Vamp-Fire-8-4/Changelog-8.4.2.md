# Vampirism Fire 8.4.2

---

## Main

- After picking a race, players no longer stare at an empty map: the race menu stays open and shows **who is ready**, **who is still choosing**, the **game mode** with any changed settings, and **rotating tips**.
- Vampires now see the same screen while the builders choose their races (it used to show nothing).
- The mode-selection and vampire-selection windows no longer overlap the window border.


## Humans

- The Orc [Goblin-Tower-Builder] can be trained again (it required an upgrade that didn't exist), so Orcs can build the **Castle of Heaven** again.
- The [Heavenly-Architect] is now trained **only at the Castle of Heaven** (no longer at the Command Center or Base of Operations).


## Vampires

- [Sword-Of-Dracula] damage increased from **1,750 -> 2,150**.
- [Nosferatu's-Mantle] damage increased from **1,250 -> 3,000**.
- [Punisher] armor stacking restored: each qualifying wall hit gives **+135 Strength**, **+115 Agility** and **+115 Intelligence**.
- [Dracula's-Cloak] scaling damage (+750 per minute after minute 36) is now **bonus (green) damage** instead of base damage.
- [Devotion-Aura] research fixed:
    - It now **stacks** with the Sword of Dracula and Nightmare's Teller auras (it used to add nothing once a vampire held either item).
    - Researching it no longer **lowers** a teammate's aura level.
- [Nightmare's-Teller] can also be built with **Stanimir's Nocturne** in place of Nocturne's Edge, together with one more **Stanimir Remains** or **Stanimir's Combined Remains**.
- [Gauntlets-Of-The-Damnation] and **Recipe - Nightmare's Teller** are now shown in the Recipe Shop from the start with a countdown to minute **42**. Their minute-42 announcement has new colours.
- [Silent-Sphere-Of-Doom] has its own icon.

- Demonic Gate fixes:
    - Fixed items appearing **twice** after the minute 23 / 24 price changes.
    - Fixed **Gauntlets of Hellfire** and **Gauntlets of the Underworld** disappearing from the Demonic Gate.

- Shop hotkeys now follow the button grid (Q W E R / A S D F / Z X C):
    - Demonic Gate: Demonic Remains **Q**, Sword of Dracula **W**, Stanimir Remains **E**, Sphere of Doom **R**, Silent Sphere of Doom **A**, Gauntlets of the Underworld **S**, Nosferatu's Mantle **D**, Gauntlets of Hellfire **F**, Nocturne's Edge **Z**, Punisher **X**.
    - Recipe Shop: every item has its own slot and key, Q to C.

- [Scythe-Of-Necromancy] Reaper improvements:
    - It now **blinks** to buildings more than 900 range away (the blink never went off before).
    - New target order: **Blood Boxes**, then **Command Center / Base of Operations**, then **Comet Towers**, then **gold mines**, then the most **valuable buildings**.
    - After those it clears the **rest of the base**, nearest building first.
    - Two Reapers in the same base now **split** the buildings instead of attacking the same one.
    - From minute 35, a Scythe use now counts as soon as its Reaper **hits** a building.
