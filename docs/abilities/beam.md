# Beam

A tractor beam that holds an entity at the staff tip. Whip the camera and it follows; release to throw.

- **Hold** — hold right-click to grab. Release while swinging to fling the entity in that direction; it
  takes impact damage when it hits the ground or a wall. A quick grab-and-release doesn't launch anything
  into orbit — only an actual swing throws.
- **Bound** — right-click sticks the entity to the tip so it follows you hands-free; right-click again to
  release. It won't clip mobs into walls.

Cycle the two with **Left Alt**. **`` ` `` + scroll** sets beam distance. Works on mobs and players.

Whatever you have gripped **can't hurt you** while you hold it — neither the mob itself nor anything it
fires. The grab parks it right on top of you, which otherwise handed it a free melee window.

## Choke

Hold **C** while gripping a mob to choke it — 1♥ per second. It's on its own key, so sneaking stays free for
everything else.

## The beam itself

Everyone gets their own beam colour, configurable and synced, so you can tell whose is whose. It bends and
whips on fast turns and straightens out when you hold steady.

In **third person** the beam comes off the real animated staff — it follows the arm swing and body sway
exactly, because the origin is read from where the staff is actually being drawn. That works per player, so
everyone's beam tracks their own staff, not just yours. In first person the held item is glued to the
camera, so it uses a tuned offset instead (with separate values for each perspective, and a flip if your
main hand is left).

Everything else emits from that same point — projectiles, electrify, command casts — so what you see and
what the game fires from agree.
