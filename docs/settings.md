# Settings

There are three places to configure the addon.

## 1. Client config (Mod Menu)

Open via **Mod Menu → Command Block Staff Addon → Config** (Fabric) or the **mod's Config button**
(NeoForge mod list). If **Cloth Config** is installed you get a nicer screen; otherwise a built-in tabbed
one. These are **per-player display / feel** options:

- **General** — Ability HUD, chat feedback, info-text labels, billboard scale & time, dome defaults, shield
  colour & wobble, structure-preview colours, ability-number position & colour.
- **Custom** — beam distance, dome radius, block-UI rows, **Commands: max boxes**, "beam grab pulls entity
  to you", and the ride-particle trail.
- **Projectiles** — launch speed per projectile type.
- **HUD** — ability-number toggle, position and colours.

## 2. Server settings — `/commandstaff settings`

Op-only. A fused screen with **three tabs**:

- **Settings** — server-wide gameplay rules: shield durability & max damage, max controlled projectiles,
  projectile collect speed, defense-wall max distance, abilities-while-riding, **control: consume arrows**,
  quick-choose toggles.
- **Abilities** / **Commands** — a **node-graph** where you can **disable** any ability, mode, sub-mode or
  individual command server-wide. Click a node to select (Shift = range, Ctrl = toggle one), then
  **Enable / Disable**. Disabled commands show a 🔒 in the picker.

These apply to the whole world/server and are saved per-world.

## 3. In-game controls

A lot is adjustable on the fly without any menu — see **[Controls](controls.md)** (`` ` `` + scroll to
adjust the current ability's main setting, `Left Alt` to change mode, etc.).
