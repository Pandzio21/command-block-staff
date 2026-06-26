# Commands (Ability 6)

A point-and-click **command dispenser** — apply effects, give items, load structures, modify entities and
more, all from a menu. No typing required, and it runs via direct game API (not chat commands).

## How it works

1. Press **V** to open the **command selection** screen (searchable, tabbed grid with Favorites & Recent).
2. Pick an entry → set its parameters → **Save**. This **loads** the command into the staff.
3. **Right-click** to **cast** it. The colorized command types out at your staff tip and streaks to the
   target's head — the AvM signature look.

### Targeting

- **Right-click** casts on the entity you're aiming at, or **yourself** if you're not aiming at one.
- **Shift + right-click** explicitly targets the aimed entity (or yourself).
- **Left-click** opens a quick-chooser of your favorited commands and runs one immediately.

## What's in the catalog

| Category | Examples |
|----------|----------|
| **Effects** | Any status effect, with duration & amplifier |
| **Experience** | Add levels / points |
| **Attributes / Misc** | Heal, feed, clear effects, kill |
| **Give** | Give any item (with a live item search) |
| **Modify Entity** | Glowing, no-gravity, invulnerable, silent, ignite/extinguish, **staff light** |
| **Structure** | Load any structure with a **movable hologram preview** (move with arrows, **Enter** to place) |
| **Custom** | Your own commands — define once, run forever |

## Custom commands

The **Custom** tab lets you save your own commands (name + command string). Left-click runs, right-click
edits/renames/deletes. They run at permission level 2 (command-block style) and can be favorited.

## Extras

- **Favorites** — right-click any entry (built-in or custom) to favorite it; the Favorites tab and the
  left-click quick-chooser pull from there.
- **Undo** — press ++u++ to revert your last reversible action (effects, attribute/entity changes, XP).
  Custom/raw commands and structure placements can't be undone.
- A floating command label appears over the target after casting and fades after a few seconds.
