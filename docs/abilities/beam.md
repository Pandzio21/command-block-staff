# Beam

A tractor beam. Grab something, whip the camera, let go — it goes flying.

- **Hold** — hold right-click to keep hold of it. Let go mid-swing and it launches, taking impact damage
  when it lands. A quick grab-and-release won't fling anything into orbit; you have to actually swing.
- **Bound** — right-click to stick it to the staff tip. Now it just follows you around, hands free.
  Right-click again to drop it. It won't shove mobs into walls.

**Left Alt** switches between the two, **`` ` `` + scroll** sets how far out the beam reaches. Works on
mobs and players alike.

Whatever you're holding **can't hurt you** — not the mob, not anything it shoots. The grab parks it right
on top of you, so without that it'd get a free shot every time.

## Choke

Hold **C** while you've got something to choke it, half a heart a second. It's a separate key on purpose,
so sneaking stays free for everything else.

## The beam itself

Everyone gets their own colour, so in multiplayer you can tell at a glance whose beam is whose. It bends
and whips when you turn fast and settles straight when you hold still.

In third person the beam comes off the **real staff** — the one on your player model, swinging with your
arm — because the origin is read from where the game is actually drawing it. That works for everyone you
can see, not just you. First person is different: the held item there is glued to the camera, so it uses a
tuned offset instead (separate values per perspective, and it flips if you're left-handed).

Everything else fires from that same point — projectiles, electrify, command casts — so what you see and
what the game uses agree.
