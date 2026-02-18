
# bo3-mod-menu

A Black Ops 3 Zombies mod menu written in GSC. Manipulate gameplay 
with god mode, custom weapons, zombie modifiers, and more. Includes 
a HUD timer and zombie counter.

---

## Features
- God Mode
- Ray Gun
- Black Ops 2 Weapons (Ballista, M27 via Skye's Weapon Ports)
- All Map Perks
- Max Points
- Skip to Round 100
- Change Zombie Health
- Change Zombie Speed
- Refill Ammo
- HUD Timer
- Zombie Counter

---

## Dependencies
This mod relies on the following Black Ops 3 game scripts at runtime 
(not included):
- `scripts/zm/_hud_message.gsc`
- `scripts/zm/_zm_score.gsc`
- `scripts/zm/zombie_utility.gsc`

These are part of the base game and will be present in your BO3 
installation.

---

## Installation
1. Download the files
2. Navigate to your Black Ops 3 directory
3. Create a `mods/` folder if one doesn't exist
4. Drop the mod contents into `mods/`
5. Launch BO3 and enable the mod from the mods menu

---

## Known Bugs
- Points keybind inconsistent — works sometimes but not reliably
- Skye's Weapon Ports only working for Ballista and M27

---

## Credits
- [@TheSkyeLord](https://www.ugx-mods.com/forum/full-weapons/84/skyes-weapon-ports-to-bo3-master-hub/16874/) — BO2 Weapon Ports
- [@pistakilla](https://github.com/pistakilla/t7-gsc-scripts/tree/main/zm_timer) — Timer Help
- [@Joshr520](https://github.com/Joshr520/BO3-Autosplits) — Zombie Timer Reference
- [@Cabcon](https://cabconmodding.com/threads/black-ops-3-zombie-gsc-modding-how-to-start-coding-a-mod-startup-mod-download.2245/) — Starter File
- [@IceGrenade](https://www.youtube.com/watch?v=1ahHTW4hhzk) — Tutorials