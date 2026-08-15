# Vampirism Fire 8.3.4

---

## Main

### Desync fixes

- Fixed the biggest remaining cause of desync: the **Classic / Custom / Pro mode selection** was never synchronized — the host's choice only applied on the host's machine while everyone else silently fell back to Classic. The mode choice, all Custom-panel settings, and the Custom vote now sync to every player. **Custom and Pro lobbies are playable again.**
- Fixed the Blood Altar selection desync (buying minions while multiple vampires had the altar selected).
- Fixed a desync class caused by stale unit references after Warcraft recycles unit handles.
- Fixed the AFK name counter causing state divergence between machines.

### Bug fixes

- **Slayers can be retrained again** after the Slayer's Tavern is destroyed mid-training, or after your slayer dies. Previously either case could permanently lock you out of training a slayer for the rest of the game.
- **Trees now always regrow at minute 4.** The regrow could silently skip spots (dense trees or buildings near the spot blocked it), leaving bases permanently exposed. All 34 spots now restore reliably; the Treant visuals are unchanged.
- **[Heavenly-Blood-Tower]** armor reduction no longer stops at **-4096** — it keeps shredding for as long as the vampire stays under fire (it is an end-game upgrade and now plays like one). The reduction is visible on the target's armor display, and armor now correctly restores 5 seconds after the tower stops firing.
- Fixed a bug where a vampire that **died while being shredded** by a Blood Tower kept up to -4096 armor permanently after reviving.
- **Removed debug commands from public games**: a leftover diagnostic let any player type `-reveal` for permanent full-map vision. Debug tools are now hard-disabled outside development builds.

### Base commands

- `-allow` / `-unallow` now accept **colours, slot numbers, and partial names** (e.g. `-allow red`, `-allow 2`) — previously they required an exact name match that was impossible to type for clan-tagged players.
- `-disallow` now works as an alias of `-unallow` (the F9 log always advertised it).
- `-b` / `-base` / `-showbases` now **mark every unclaimed base on the minimap** (icons plus ping sweep), visible only to the player who asked.
- Using `-allow`, `-unallow` or `-unclaim` without owning a base now explains itself instead of failing silently.
- `-claim` can no longer be used by vampires.

### Quality of life

- Every combat tower now shows its **range circle** when selected (Sacrificial Towers, Necropolis Tower and Black Magic Spire were missing it).
- Map loading and start-up freeze reduced (assets are preloaded during the loading screen).

---

## Human

- **[Sacrificial-Tower]** level 1 build time reduced **30s → 15s**.

---

## Vampires

- **Dracula's Cloak** now combines from **Gauntlets of the Underworld + Demonic Remains** only — no recipe item needed. The unused 125g "Recipe – Dracula's Cloak" has been removed from the Recipe Shop.
- Fixed the Dracula's Cloak tooltips: three different texts claimed three different damage values; all now state the real numbers (**+8000 damage, +2500 str/agi/int — 10500 total damage with the strength bonus**) and the real ingredients.
- Recipe Shop tiers are strictly time-gated: minute-15 recipes (Dracula's Gear, Ricochet Gem, Bloodletting) and minute-36 recipes (Cloak of Power, Rain of Blood) cannot be bought early.
- Advanced Recipe Shop unlock restored to **minute 15** (was briefly open from minute 0).
- Orc goldmine bounties adjusted: **15 / 25 / 40** (from 20 / 40 / 60).

---

## Other

- New in-game issue log: the map writes a per-game log file under `CustomMapData\VampirismFire2\logs\` to help the team diagnose reported problems.
- Various tooltip and text corrections.
