<p align="center">
  <img src="docs/assets/banner.png" alt="Command Block Staff" width="760">
</p>

<div align="center">

[![Download from Modrinth](https://img.shields.io/modrinth/v/command_block_staff_addon?style=flat&logo=modrinth&logoColor=white&label=Download%20from%20Modrinth&color=00af5c)](https://modrinth.com/mod/command_block_staff_addon/versions)
[![Download from CurseForge](https://img.shields.io/badge/Download_from-CurseForge-f16436?style=flat&logo=curseforge&logoColor=white)](https://www.curseforge.com/minecraft/mc-mods/command-block-staff-addon/files)
[![Modrinth downloads](https://img.shields.io/modrinth/dt/command_block_staff_addon?style=flat&logo=modrinth&logoColor=white&label=downloads&color=00af5c)](https://modrinth.com/mod/command_block_staff_addon)
[![CurseForge downloads](https://img.shields.io/curseforge/dt/1585146?style=flat&logo=curseforge&logoColor=white&label=downloads&color=f16436)](https://www.curseforge.com/minecraft/mc-mods/command-block-staff-addon)
[![Minecraft](https://img.shields.io/modrinth/game-versions/command_block_staff_addon?style=flat&label=Minecraft&color=54ba58)](https://modrinth.com/mod/command_block_staff_addon/versions)
![Loaders](https://img.shields.io/badge/loaders-Fabric_%7C_NeoForge-dbb18a?style=flat)
[![Requires AvM Staff Mod](https://img.shields.io/badge/requires-AvM_Staff_Mod-9b59d0?style=flat)](https://modrinth.com/mod/avm-staff)
[![Report a bug](https://img.shields.io/github/issues/Pandzio21/command-block-staff?style=flat&logo=github&label=Report%20a%20bug&color=24292f)](https://github.com/Pandzio21/command-block-staff/issues)
[![Docs](https://img.shields.io/badge/Read_the-docs-8ca1af?style=flat&logo=readthedocs&logoColor=white)](https://pandzio21.github.io/command-block-staff/)

</div>

An add-on for the **AvM Staff Mod** *(Animation vs Minecraft)* that turns a command block placed in the
staff into a six-ability power tool — grab entities with a beam, electrify mobs, place & fill blocks
WorldEdit-style, fire projectiles, raise a shield dome, and run command effects, all from your hand.

> **Closed source.** This repository is for **bug reports, ideas, and discussion** — the mod's source
> code is not published here. Suggestions are very welcome! Open an [Issue](../../issues) or start a
> [Discussion](../../discussions).

**Author:** Pandzio21
**Download:** https://modrinth.com/mod/command_block_staff_addon
**Wiki / docs:** https://pandzio21.github.io/command-block-staff/
**Minecraft:** 1.21 · **Loaders:** Fabric & NeoForge

---

## Installation

Drop **both** jars into your `.minecraft/mods` folder:

- `staff-mod-1.0.0-beta.1-fabric.1.21.jar` — the base **AvM Staff Mod**
- `staff-mod-commandblock-1.0.0-beta.1-fabric.1.21.jar` — **this add-on**

**Dependencies:** Fabric API, Fabric Language Kotlin, Architectury — for **Minecraft 1.21**.
The add-on does **not** work on its own; it requires the base AvM Staff Mod.

---

## Abilities

Switch with **`Z` + scroll**. Insert a command block into the staff to begin.

| # | Ability | What it does |
|---|---------|--------------|
| 1 | **Beam** | Grab an entity in your look direction and reel it in (adjustable distance). |
| 2 | **Electrify** | Zap and tag mobs/blocks; clear all with **F4**. |
| 3 | **Placement** | Place & fill blocks (modes below). |
| 4 | **Projectile** | Launch projectiles; left-click for the quick chooser. |
| 5 | **Shield** | Toggle a translucent protective dome (adjustable radius). |
| 6 | **Commands** | Left-click a mob — or yourself — for a quick effect chooser. |

### Placement modes (cycle with **Left Alt**)
- **Single Block** — place on a block face or in mid-air.
- **Fill** — WorldEdit-style: left-click Pos1, right-click Pos2 → fills the cuboid (live preview).
- **Attack Tracker** / **Block Tracker** — tracking/auto-build utilities.
- **Easy stairs** — in Placement, **jump while walking forward** to build a staircase under you.

---

## Controls

| Key | Action |
|-----|--------|
| `Z` + scroll | Change ability |
| `` ` `` + scroll | Adjust the current ability's setting |
| `Left Alt` | Cycle placement mode |
| `V` | Open ability settings screen |
| `F4` | Clear electrified |
| `G` | Fast Choose (hold + scroll favorites, release to confirm) |
| `R` | Add/remove the staff item *(base mod)* |
| Left-click | Quick chooser — effects (Commands), projectiles (Projectile), Fill Pos1 (Placement) |

All keybinds are rebindable under **"Staff Mod"** in Controls. A **Mod Menu** config screen exposes
HUD/feedback toggles, billboard scale & duration, and default beam/dome sizes.

---

## License

This add-on is proprietary (**All Rights Reserved**, © Pandzio21) — see [`LICENSE.txt`](LICENSE.txt).
It links against the **AvM Staff Mod** by opekope2, which is licensed under
**LGPL-3.0-or-later**; that mod is used unmodified and its source is available at
https://github.com/opekope2/StaffMod.
