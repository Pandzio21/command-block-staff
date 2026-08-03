# Troubleshooting

**An ability does nothing on right-click.** It may be disabled server-side — check `/commandstaff settings`
→ Abilities, or look for a 🔒 / "disabled on this server" message.

**Placement does nothing.** You probably haven't picked a block — press **V**. The staff tells you, and the
beam stays off until you have one. (Air/Remove mode is the exception; it needs no block.)

**"Cannot be used in staff."** The inserted item isn't in that staff's allow-list. The command block is
enabled by default; if you've edited the item tags, re-add it.

**Structure preview won't place.** Use **Enter** — right-click was dropped because the staff's own use
swallowed it. Arrows move the hologram, **Shift + ↑/↓** moves it vertically, **X** cancels.

**Riding doesn't animate.** GeckoLib isn't installed. It's optional — the flight works without it, you just
don't get the animated model.

**The game crashes on startup with a mixin error mentioning GeckoLib.** You're on 1.21.1 with GeckoLib's
**1.21** build. That combination crashes on its own, without this add-on. Use a 1.21.1 build of GeckoLib, or
remove it — see [Installation](installation.md).

**A placement mode does nothing after I change worlds.** Fixed — the client used to keep the previous
world's mode while the server reset it, so the HUD showed one mode and the server was on another. Same cause
as Beam Hold occasionally doing nothing in a fresh world.

**My custom commands disappear.** They live in your client config and on the staff item. To tie them to a
world instead, use **💾 Save to World** in the Custom tab — see [Commands](abilities/commands.md).

**Building makes me crouch.** It shouldn't — the build modifier is its own key (default ++tab++), not
Shift. If it's still on Shift, check **Options → Controls → Command Block Staff Addon**.

---

Found a bug? [Open an issue](https://github.com/Pandzio21/command-block-staff/issues) with your version,
loader, and a `latest.log` if it crashed.
