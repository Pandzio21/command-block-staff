# Settings

Three places, depending on who the setting belongs to.

## Client config

Mod Menu, or the config button in the mod list. Everything here is yours alone — how it looks and feels,
not what it does: HUD toggles, billboard scale and lifetime, default dome and beam values, shield colour
and wobble, structure-preview colours, block-UI rows, *Commands: max boxes*, *beam grab pulls entity to
you*, per-type projectile speeds, the ride particle trail, and where the ability numbers sit.

If you've got Cloth Config installed you get a nicer version of the same screen.

## Server settings

`/commandstaff settings`, op only. One screen, three tabs.

**Settings** holds the server-wide rules: shield durability and how much it takes, max controlled
projectiles, projectile collect speed, defense-wall max distance, whether abilities work while riding,
*control: consume arrows*, and the quick-choose toggles.

**Abilities** and **Commands** are a node graph of everything the staff can do. Click to select — Shift for
a range, Ctrl to toggle one — then **Enable** or **Disable**. It goes as deep as individual modes: Beam
Hold / Bound / Choke, Move Surface's Move and Resize, Single Block's Place / Replace / Air-Remove, each
Block Tracker mode and Shaper shape, every projectile mode and type. Disabled commands show a 🔒 in the
picker, and it all saves per-world.

The Commands tab also lists **every custom command anyone has written on this server**, with its own search
box. They behave exactly like nodes — same clicks, same Enable/Disable buttons. Blue border means selected,
red means disabled.

## In the game

Most per-ability values don't need a menu at all: **`` ` `` + scroll** tunes whatever the current ability
tunes, and **Left Alt** cycles its modes.
