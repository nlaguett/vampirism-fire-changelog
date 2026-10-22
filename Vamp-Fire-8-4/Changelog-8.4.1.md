# Vampirism Fire 8.4.1

---

## Main

- [Temple-Of-Prayers] now unlocks at minute **12 -> 11**.
- Reverted an unintended level 3 (150 seconds cooldown) on the Slayer's [Building-Protection].
- `-oust` and `-oustHuman` can now be used in your claimed base from minute **5 -> 4**.
- Builder skins requiring 50 / 100 / 150 / 200 games played now unlock at exactly that number of games (they needed one more game before).
- Fixed some demon building models not loading since Warcraft III patch 3.0.


## Vampires

- [Dracula's-Reaver-Of-Fire] level 2 now requires **Vampiric Boots** and **2 Ultimate Claws of Attack** (instead of 2 Large Claws of Attack). 
Now has **Vampiric-boots** ability.
- Tax now expires at minute **35 -> 34**.
- [Dracula's-Helm] scaling damage starts 2 minutes earlier: +50 per minute from minute **9**, up to +200 at minute **12**.
- [Dracula's-Equipment] scaling damage and HP start 1 minute earlier: from minute **19**, maxed at minute **22**.
- [Gauntlets-Of-The-Damnation]
    - Gold cost reduced from **2,000 -> 1,500**.
    - Now sold in the **Recipe Shop** (minute 42) instead of the Demonic Gate.
    - Requires **Gauntlets of Hellfire**: buying it forges it onto your Hellfire (which is consumed). Buying it without Gauntlets of Hellfire refunds 500 gold.
    - The **+100 damage per hit** only works on a Damnation forged onto Gauntlets of Hellfire. It keeps working when handed to another vampire.
    - Fixed Gauntlets of Hellfire disappearing when a vampire held it together with a Damnation (for example after passing a Damnation to a teammate).
- [Nosferatu's-Mantle]
    - Now requires the **Sword of Dracula**: buying it forges it onto your Sword (which is consumed). Bought without a Sword, it is fully refunded.
    - Fixed its aura: your and allied minions within **2000** range gain **+10 armor**. It stacks with other armor auras.
    - Its **+25 damage per wall hit** now adds to Gauntlets of Hellfire / Gauntlets of the Damnation (e.g. Hellfire + Mantle = **+80** per hit) instead of being ignored while a gauntlet is held.
- [Stanimir-Remains] is now sold in the **Demonic Gate** (it takes the slot freed by the Gauntlets of the Damnation).
    - **1,050g** at minute 22, **950g** at minute 23, **850g** from minute 24.
    - Grants **+4,000 damage**.
    - Two Stanimir Remains combine into **Stanimir's Combined Remains** (+8,000 damage).
    - Combines with [Nocturnes-Edge] into an upgraded Nocturne's Edge.
- Buying [Gauntlets-Of-Hellfire], [Gauntlets-Of-The-Underworld], [Nosferatu's-Mantle] or [Nocturnes-Edge] now puts the **other three on cooldown**.
- New Demonic Gate item order:
    - Row 1: Demonic Remains, Sword of Dracula, Stanimir Remains, Sphere of Doom
    - Row 2: Silent Sphere of Doom, Gauntlets of the Underworld, Nosferatu's Mantle, Gauntlets of Hellfire
    - Row 3: Nocturne's Edge, Punisher
- [Punisher] now grants **+135 Strength** per wall hit (instead of +115 to every attribute).
- [Gauntlets-Of-Renfield] is now an upgrade at the **Vampiric Research Center** instead of a Demonic Gate item.
    - Cost: **3,800 gold**, available at minute **50** (was 55).
    - Permanently gives the main vampire **+50% attack speed**.

- New item: [Nightpiercer] (the upgraded Dark Spear)
    - Combine **Recipe - Nightpiercer** (150 gold, Recipe Shop, from minute 14) with **Dark Spear**, **Nosferatu's Essence** and **Mana Resistance Shield**.
    - **+300 damage** while carried; its toggle grants **+550 damage** (instead of the Dark Spear's +450).
    - **+100** to all stats and **+60** movement speed.
    - **+40%** mana regeneration.
    - Immunity to Mana Energy Towers.

- New item: [Nightmare's-Teller]
    - Combine the free **Recipe - Nightmare's Teller** (Recipe Shop, from minute **42**) with **Sword of Dracula**, **Stanimir's Combined Remains** and **Nocturne's Edge** (4,550 gold of components).
    - **+20,000 damage**, +250 Strength and Agility, +1,000 Intelligence.
    - Melee hits deal **double damage** to Human units and structures above 50% HP (capped at 2.5k extra per hit, **40k** extra against walls).
    - **Global aura:** +150 armor and **+2,000 HP** to every Vampire and Minion unit on the map.
    - **Stanimir's Curse:** Human units and structures within **1,000** range lose **50 armor** (Diamond Walls 75, Onyx Walls 100).
    - Keeps Nocturne's Edge's invulnerability active and Mana Energy Tower immunity, and the Sword of Dracula's +1,500 Infernal HP bonus.

- [Scythe-Of-Necromancy] Reaper fixes:
    - Now attacks the buildings of dead builders (they were skipped, so the Reaper expired immediately).
    - Stays for its full lifetime when there is nothing to destroy, and picks up any new target in the meantime.
