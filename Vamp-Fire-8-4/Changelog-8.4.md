# Vampirism Fire 8.4

---

## Main

- Finish a wall will now display the message "Wall finished!"
- Leakrate setting can now be increased by 1 per click instead of 5.
- Improved the loading screen fading effect.
- Improved the map load at map initialization.
- Slayer taverns now gain the ghost and invulnerabiliity until they finish to train their slayer or reach min 2.
- Gold mine income removed from the Mode Selection.
- `-show` command UI design reworked.
    
    Before:

    <img src="Capture d'écran 2026-09-10 114224.png" width="620" alt="Old-showMode-UI">

    After:

    <img src="Capture d'écran 2026-09-10 113737.png" width="620" alt="New-showMode-UI">

- Mode selection UI will now show the mode buttons for all players.

    Before:
    
    <img src="Capture d'écran 2026-09-10 114657.png" width="620" alt="Old-modeSelectionUI">

    After:
    
    <img src="image.png" width="620" alt="New-modeSelectionUI">

## Main balance

- Builders will now gain **4g** at the min 4 instead of the min 5.
- [Workers] 
    - hatchet timer was reduced from min 3:30 to min 2.
    - Wood gain was increased by **+50%**.

- [Goblin-Tower-Builder]
    - Gold cost reduced from **150 -> 100**

## ELO system

- Ranked games now use the match result and both teams' average ELO to calculate rating changes. Winning gains ELO and losing costs ELO; the previous system could award ELO to a losing player.
- Human ELO changes also reflect how long each builder survived. Early deaths cost more, while builders who hold out for most of a lost game lose less. Builders who leave are rated for the time they played, and bitten builders are rated as human losses.
- Vampire partners receive the same ELO change. Winning faster gives both vampires a larger gain.
- Separate ELO ladders were added for standard 10v2, Solo Vampire, and 1v1 games, with distinct Human and Vampire ratings in each.
- The host can choose Ranked or Unranked when selecting a mode. A game only affects ELO if its mode's required lobby size is met at lock-in: 10 builders and 2 vampires for the shared ladder, 5 builders and 1 vampire for Solo Vampire, or 1 builder and 1 vampire for 1v1. Unranked games still count toward games played and wins.


## Human

- [Sacrificial-Tower] added to quell reach.
- [Human's-Vault] name fixed (was W by mistake).
- [Fang-Blade] gold cost reduced from **40 -> 34**.
- [Gold-Buy] ability is now available at the min **5 -> 4**
- [Base-Of-Operations] gold cost reduced from **1000 -> 600**.
- [Orange-Calcite-Outpost] now require **Citadel Of Faith**

## Architect

- [Gold-Buy] ability now available min **6 -> 5**
- [Base-Of-Operations] gold cost reduced from **1000 -> 800**
- [Orange-Aqua-Outpost] now require **Citadel Of Faith**


## Orc

- [Gold-Buy] ability is now available min **6 -> 5**

## Vampires

- [Health-Beam] mana cost nerf
    - Level 1 : **100 -> 200**
    - Level 2 : **150 -> 325**
    - Level 3 : **300 -> 450**
    - Level 4 : **375 -> 550**
    - Level 5 : **775 -> 850**
    - level 6 : **950 -> 1200**
    - level 10 : **3400 -> 3800**

- [Blood-Particle] level 2 was removed.

- **Vampires** spawn timer reduced from **55 -> 35** seconds.

- Mana resistance shield stock timer reduced from 7:05 min -> 6:00.

- [Demonic-Remains], [Sword-Of-Dracula] stock timer adjusted : 
    - 23 -> 24 -> 25 to 22 -> 23 -> 24 minutes.

- [Infernal]
    - Stock start delay reduced from **420 -> 300** seconds.

- [Burst-Gem] 
    - Stock start delay changed from **0 -> 12** minute.
    - Second burst gem allowed at the min 24.
    - Burst gem gold cost reduced from **240 -> 175** gold.

- [Ricochet-Gem]
    - Stock start delay changed from 15 -> 24 minute.
    - Second Ricochet Gem allowed at the min 36.

- [Dracula's-Cloak] 
    - Now require the recipe **Recipe - Dracula's Cloak** again and it's gold cost was increased from **175 -> 500** gold.
    - [Gauntlets-Of-The-Underworld]
        - Gold cost reduced from **2000 -> 1500**
    - The combined item **Dracula's Cloak** damage was reduced from **10500 -> 8500**
    - Now has scaling damage of +250 dmage per min starting from the min 36 until the min 60.

- [Gauntlets-Of-Hellfire]
    - Now unlocked at the min 34 for 2400 gold. Gold cost reduced at min 35 to 2200 gold and min 36 for 2000 gold.

- [Gauntlet-Of-Renfield]
    - Stock timer increased from **54 -> 55** min.
    - Attack speed gain increased from **30% -> 50%**.



- [Sphere-Of-Doom]
    - Gold cost reduced from **700 -> 650**

- [Income-Changes] : 
    - *24* min income timer changed to *23* minute
    - *36* min income timer changed to *35* minute.

- [Assassin] | [Meat-Carrier] | [Grave-Robber]
    - Stock starting time reduced from **12 -> 10** min.

- [Frozen-Infernal] | [Corrupted-Infernal]
    - Now available at the min **24 -> 23**.

- [Infernal-Meteor]
    - Now available at the min **15 -> 14**.

- New item : [Stanimir-Remains] (idea stolen from v7)
    - Same unlock timers as [Sword-Of-Dracula] or [Demonic-Remains].
    - 22 min gold cost **1050g**, 23 min gold cost **950g** and 24 min gold cost **850g**.
    - Gives +4000 damage, no other stats.

- New item [Silent-Sphere-Of-Doom]
    - Gold cost **850g**
    - Does not warn when bought.

- New item [Gauntlet-Of-Damnation]
    - Combine with **Gauntlet of Hellfire**
    - Gold cost : **2000** gold.
    - Passive ability : Stack +100 damage per hit when attacking a wall. Effect lost after 4 seconds without attacking a wall.
    - Available at the min 42.

- New item [Nocturnes-Edge]
    - **+450 STR**
    - **+450 AGI**
    - **+1000 INT**
    - Gold cost 2000 gold
    - Available at the min **34**.

## other stuff
- Fixed tooltips : Punisher, dracula equipment, Gauntlet of Renfield, Silent-Whisper.