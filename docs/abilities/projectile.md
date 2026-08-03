# Projectile

Fire from the staff tip toward your aim. **V** opens the launcher. Modes cycle with **Left Alt**.

- **Arrow Cannon** — hold right-click to spam your selected type (arrow, fireball, TNT, food, or a custom).
  Arrows home onto the entity you're aiming at.
- **Advanced control** — hold to steer a projectile.
- **Control Projectiles** — build a swarm and send it all at once. See below.

**`` ` `` + scroll** sets throw distance.

## Control Projectiles

Built to work like the scene from the series: gather a cloud of projectiles around you, pick a target, then
launch the lot.

| Input | |
|---|---|
| **Build modifier + right-click** | Summon a projectile into the swarm. Hold to paint a whole cloud. |
| **Right-click** | Lock a target — an entity or a block. |
| **Right-click again** | Fire everything at it. |
| **Left-click** | Fire one at a time out of the staff tip. Hold to keep firing. |
| **Scroll** | Pick the type. |

Summoned projectiles spawn aimed the way you're facing and are non-solid while they float, so they can't
bump or bounce off you. A locked entity is tracked — it still gets hit if it moves. The staff holds the cast
pose the whole time.

In survival, summoning an **arrow** uses one from your inventory (toggle with the *Control: consume arrows*
server setting). Only arrows cost anything — fireballs, TNT and food don't need to be carried. The swarm is
yours to build: it doesn't vacuum up spent arrows, so it isn't a shield.

Switching **into** this mode with a mouse button already held won't fire — the first shot always needs a
fresh press. Switching **out** of it mid-hold won't launch the projectile you were steering either.

## Custom projectiles

In the launcher → **✦ Custom Projectiles…**, add any entity by ID, name it, and fire it like a built-in
type. They appear in the quick chooser too.
