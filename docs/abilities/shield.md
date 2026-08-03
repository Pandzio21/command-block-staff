# Shield

Right-click toggles a force-field dome. **`` ` `` + scroll** sets its radius (1.5–8, in 0.1 steps, eased so
it grows smoothly instead of snapping).

While it's up:

- All incoming damage is cancelled, explosions ignored (knockback included). **The void still kills you** —
  a force field is not a parachute.
- Mobs and players inside are pushed out; items and XP pass through.
- Harmful projectiles bounce off with a spark instead of being absorbed.

Small shields are egg-shaped and round into a dome as they grow; the surface wobbles (configurable). Turn on
**Shield durability** and it absorbs a set amount before shattering. It clears on death, and other players
see your dome's colour and wobble. It scales with your `generic.scale`, so a giant player gets a giant dome
rather than one around their feet.

## Whitelist

Anyone whitelisted can stand inside without being shoved out, and is protected from damage while they're in
there.

- **Shift + right-click** a player or mob to add them.
- **V** opens the whitelist menu — separate tabs for players and mobs, with search.

The list lives **on the staff**, so it survives restarts and travels with the item if you hand it to someone
else. Offline players stay listed so you can still manage them, duplicate mob names are numbered (1), (2)…,
and mobs drop off the list when they die.

### Your mount is automatic

Ride a horse, donkey, pig — anything — with Shield selected and it's whitelisted for you automatically, and
**locked** there until you dismount. The menu shows it as **⚓ Riding** instead of Remove.

Without this the barrier would treat your own mount as an intruder and shove it out from under you the
moment the dome came up. The lock covers every way of removing it, so it can't be dropped by accident while
you're still on it. Dismount and it goes back to being a normal entry — it stays whitelisted, so getting
back on later needs nothing.
