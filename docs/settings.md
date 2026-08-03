# Settings

Three places, by scope.

**Client config** — Mod Menu / the mod-list config button. Per-player display and feel: HUD toggles,
billboard scale/time, dome and beam defaults, shield colour/wobble, structure-preview colours, block-UI
rows, *Commands: max boxes*, *beam grab pulls entity to you*, per-type projectile speeds, ride-particle
trail, ability-number layout. Cloth Config gives a nicer version of this screen if installed.

**Server settings** — `/commandstaff settings` (op only). One screen, three tabs:

- **Settings** — server-wide rules: shield durability + max damage, max controlled projectiles, projectile
  collect speed, defense-wall max distance, abilities-while-riding, *control: consume arrows*, quick-choose
  toggles.
- **Abilities / Commands** — a node graph to disable any ability, mode, sub-mode or command server-wide.
  Click to select (Shift = range, Ctrl = toggle one), then **Enable / Disable**. Disabled commands show a 🔒
  in the picker. Saved per-world.

  Covers modes as well as whole abilities: Beam Hold / Bound / **Choke**, **Move Surface** (Move and
  Resize), Single Block's **Place / Replace / Air-Remove**, Fill's two sub-modes, each Block Tracker mode
  and Shaper shape, and every projectile mode and type.

  The Commands tab also lists **every custom command authored on this server**, with its own search box.
  They select exactly like nodes — plain click, Ctrl to toggle one, Shift for a range — and the same
  **Enable / Disable** buttons apply. A blue border means selected, red means disabled.

**In-game** — most per-ability values are adjustable on the fly with **`` ` `` + scroll** and **Left Alt**,
no menu needed.
