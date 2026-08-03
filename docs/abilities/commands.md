# Commands

Point-and-click commands. Effects, items, structures, entity tweaks — all applied through the game's own
API rather than by typing in chat.

**V** opens the picker: searchable, with Favorites and Recent. Pick something, set its parameters, hit
**Save**, and it's loaded into the staff. **Right-click** casts it — the command types itself out at the
staff tip in colour, then streaks over to whatever you're pointing at.

- **Right-click** casts on the entity you're aiming at, or yourself otherwise.
- **Shift + right-click** forces the aimed entity (or yourself).
- **Left-click** runs a favorited command immediately.

## Catalog

| Category | |
|----------|--|
| Effects | Any status effect, with duration and amplifier |
| Experience | Add levels or points |
| Attributes / Misc | Heal, feed, clear effects, kill, **spread players** |
| Give | Any item, with a live search — modded items included |
| Modify Entity | Glowing, no-gravity, invulnerable, silent, ignite/extinguish, staff light |
| Structure | Load any structure with a movable hologram preview — arrows move it, **Enter** places |
| Custom | Your own commands |

**Give** works with modded items: pick one from the search and it inserts the full `namespace:id`. Typing a
bare name works too — if it isn't a vanilla item, it's looked up across every mod.

Commands can target the **ender dragon**. Its hitbox is made of parts rather than the entity itself, which
is why it used to be unselectable.

**Spread Players** scatters everyone around the target within a range you set (default 16 blocks). Each
player lands on the surface of their column, so nobody ends up inside terrain or falling out of the sky, and
positions are re-rolled to keep people apart.

## Custom commands

The **Custom** tab is for your own. Give one a name and a command string; left-click runs it, right-click
edits it. They run at permission level 2 and can be favourited like anything else.

### Waiting between lines

A custom command can be several lines, run top to bottom like an mcfunction. Put a `wait` on its own line
and everything **after** it is delayed:

```
say three
wait 1s
say two
wait 1s
say one
wait 20t
summon lightning_bolt ~ ~ ~
```

| | |
|---|---|
| `wait 1t` | one tick |
| `wait 20` | 20 ticks — a bare number means ticks |
| `wait 2s` | two seconds |
| `wait 1m` | one minute |

Waits add up, so two in a row is the sum of both. Decimals are fine (`wait 1.5s`). The billboard and sound
still fire the moment you cast, so a delayed function doesn't look like it did nothing.

### Saving them to the world

The Custom tab has a **💾 Save to World** tile. It writes your whole list into the world folder
(`avm_staff_customcommands.json`), so the commands belong to the save rather than to one client's config
file: they travel with the world, survive reinstalls, and are handed to every player who joins.

Merging is additive and matched on the command text, so joining a world can only ever *give* you commands —
it never deletes or rewrites ones you wrote yourself. Saving requires op, since it writes world data
everyone then receives.

**U** undoes the last reversible action (effects, attribute/entity changes, XP). Raw/custom commands and
structure placements aren't undoable.
