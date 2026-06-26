# FAQ & Troubleshooting

## The staff says "cannot be used in staff"
The inserted item isn't in that staff's allow-list. The command block is enabled by default; if you changed
tags, re-add it.

## Right-click does nothing
Make sure you have the **command block** inserted and an ability selected (**Z + scroll**). If a specific
ability is dead, it may have been **disabled server-side** via `/commandstaff settings` → Abilities — check
for a 🔒 or a "disabled on this server" message.

## Does it work in multiplayer?
Yes. Shields, beams, the ride animation and HUD sync to other players. Server-wide rules live under
`/commandstaff settings` (op-only).

## Fabric or NeoForge?
Both, on **Minecraft 1.21**. Use the matching jar for your loader, and don't mix loaders — see
**[Installation](installation.md)**.

## Do I need GeckoLib / Cloth Config / Mod Menu?
- **GeckoLib** — required (the ride animation).
- **Mod Menu** / **Cloth Config** — optional; they just give you the config screen / a prettier one.

## The structure preview won't place with right-click
Use **Enter** to place — right-click was removed because the staff's own use consumed the press. Arrows move
the hologram, **Shift + ↑/↓** moves it vertically, **X** cancels.

## Is the mod open source?
No — it's closed source. This site and the GitHub repo are for **bug reports, ideas and discussion**.
Suggestions welcome: [open an issue](https://github.com/Pandzio21/command-block-staff/issues).

## Found a bug?
Please [open an issue](https://github.com/Pandzio21/command-block-staff/issues) with your Minecraft version,
loader, mod version, and a `latest.log` if it crashed.
