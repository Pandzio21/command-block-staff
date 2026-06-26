# Troubleshooting

**An ability does nothing on right-click.** It may be disabled server-side — check `/commandstaff settings`
→ Abilities, or look for a 🔒 / "disabled on this server" message.

**"Cannot be used in staff."** The inserted item isn't in that staff's allow-list. The command block is
enabled by default; if you've edited the item tags, re-add it.

**Structure preview won't place.** Use **Enter** — right-click was dropped because the staff's own use
swallowed it. Arrows move the hologram, **Shift + ↑/↓** moves it vertically, **X** cancels.

**Riding doesn't animate.** GeckoLib isn't installed — it's required for the ride.

---

Found a bug? [Open an issue](https://github.com/Pandzio21/command-block-staff/issues) with your version,
loader, and a `latest.log` if it crashed.
