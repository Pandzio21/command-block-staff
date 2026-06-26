# Command Block Staff

An add-on for the **AvM Staff Mod** *(Animation vs Minecraft)* that turns a command block placed in the
staff into a six-ability power tool — grab entities with a beam, electrify mobs, place & fill blocks
WorldEdit-style, fire projectiles, raise a shield dome, and run command effects, all from your hand.

> **Closed source.** This repository is for **bug reports, ideas, and discussion** — the mod's source
> code is not published here. Suggestions are very welcome! Open an [Issue](../../issues) or start a
> [Discussion](../../discussions).

**Author:** Pandzio21
**Download:** https://modrinth.com/mod/command-block-staff-addon
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
