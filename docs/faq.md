# Troubleshooting

**An ability does nothing when I right-click.** It might be switched off on the server — check
`/commandstaff settings` → Abilities, or look for a 🔒 or a "disabled on this server" message.

**Placement does nothing.** You probably haven't picked a block yet. Press **V**. The staff tells you, and
the beam stays off until you have one. Air/Remove mode is the exception — that needs no block.

**"Cannot be used in staff."** Whatever you put in isn't on that staff's allow-list. The command block is
enabled out of the box, so if it's refusing, something has edited the item tags.

**My keys do nothing.** They only work while you're actually holding the command-block staff — that's
deliberate, so they don't interfere with normal play.

**The structure preview won't place.** Use **Enter**. Right-click had to go, because the staff's own use
swallowed it first. Arrows move the hologram, **Shift + ↑/↓** moves it vertically, **X** cancels.

**Riding doesn't animate.** GeckoLib isn't installed. It's optional — flying works without it, you just
don't get the model.

**The game crashes on startup with a mixin error mentioning GeckoLib.** You're on 1.21.1 with GeckoLib's
**1.21** build. That combination crashes on its own, with or without this mod. Use a 1.21.1 build or drop
it — see [Installation](installation.md).

**A placement mode stopped working after I changed worlds.** Fixed. Your game used to hang on to the old
world's mode while the server reset it, so the HUD showed one thing and the server thought another. Same
cause as Beam Hold occasionally doing nothing in a fresh world.

**My custom commands vanished.** They live in your config folder and on the staff itself. To tie them to a
world instead, use **💾 Save to World** in the Custom tab — see [Commands](abilities/commands.md).

**Building makes me crouch.** It shouldn't. The build modifier is its own key (**Tab** by default), not
Shift. If it's still on Shift, have a look in **Options → Controls → Command Block Staff Addon**.

---

Found something broken? [Open an issue](https://github.com/Pandzio21/command-block-staff/issues) with your
version, your loader, and a `latest.log` if it crashed.
