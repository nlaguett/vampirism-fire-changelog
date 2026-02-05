# Vampirism Fire 8.1c

---

## Main

- Custom mode countdown changed back to 30s
- Added Waterwalker statue 
- Update clan tags
- Updated player skins
- Added -ff, -kill commands Aliases as -gg and -sui.
- Updated Quest page *(f9)*
- [Wall-Of-Seeing] and [Feeding-Block] can now be repaired.
- Fixed some tooltip and skins issues.

---


# Human

---

- Temple of prayer is now unlocked at the min *12* instead of *14*

- Pacts rebalance:
- [Frail-bricks] 
    Vampires damage decreased * *17* -> * *12*
    Reduced the purge silence timer

- [Twilight] :
Mana regeneration of the vampires reduced from *40%* -> *30%*
**Formula** changed from :
R2I(Round((Pow(2,((Floor(GameTime()/60)-14)/10))*14)*numAncients/2));
-> R2I(Round((Pow(2,((Floor(GameTime()/60)-14)/10))*17)*numAncients/2));

- [noble-sacrifice] formula value changed :
    (Round((Pow(2,((Floor(GameTime()/60)-14)/9.5))*20)*numAncients/2))
    Pow *22* -> *20*
    Fixed the text displaying the *reward* amount

- [Quell-Reach]
    Fixed the text displaying the *reward* amount

- [Sentry-ward]
    hp decreased *6000* -> *3000*
    Added Health regeneration

---

# Orc

---

- [Super-Arcane-Tower] Changed the color model
- [Super-Tower-Buiilder] Added *repair* animation
- [Engineers] from slayer's ability lvl 3 cd increased from 240 -> 360

---


## Architect 

---

- [Disaster-Tower]
    - Changed attack art animation
    - Hotkey changed from F -> D

- [Advanced-Disaster-Tower]
    Hotkey changed from F -> D
    Requirements added -> [Advanced-Research-Center]

- [Ultimate-Disaster-Tower]
    no longer upgrade to Super flame
    Fixed it's base hp, it's now *6500 hp*
    Hotkey changed from F -> D
    Gold cost increased to *3g* (was 0)
    Requirements added -> [Citadel-Of-Faith]

- [Lumber-mill] can now train 'Mal'Ganis' Harvester.
- [Super-Tower-Builder] Added *repair* animation
- Removed [Mini-Goldmine] animation to hopefully fix the fps issue for architect. Let me know if it's any better

# Models 
- Many models resized.
- [House], [Lumber-House], [Deforestation-House] models changed.

---

## Vampires


---

- Fixed Mr.Boom will now correctly kill architect and orc stb on explode.


---

## Special Thanks

- Big thanks to kayfour who worked with me on the version