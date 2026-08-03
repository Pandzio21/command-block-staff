# Placement

Pick a block with **V**, then build. Modes cycle with **Left Alt**.

If you haven't picked a block yet, the staff says so instead of doing nothing quietly, and the beam stays
off rather than promising a block that isn't coming.

The **Pick Block** key (default Left Ctrl, rebindable) + right-click is an eyedropper in every mode —
point at a block to select it. If you've put sneak on the same key, the mode action wins and the picker
stands down; rebind either one to get both.

## Single Block
Click to place on the face you're looking at (also works in mid-air). **Hold the build modifier** (++tab++)
to paint a trail as you move.

**Shift + right-click** cycles the sub-mode:

| Sub-mode | |
|---|---|
| **Place** | Normal — needs an empty spot |
| **Replace** | Overwrites whatever you're aiming at |
| **Air / Remove** | Deletes it (needs no selected block) |

## Fill
Left-click sets corner 1, right-click sets corner 2; the region fills with a live preview (cap 32768).
**Shift + right-click** toggles **Solid ↔ Air/Remove**, so Fill can also delete.

## Move Surface
Grab a whole wall, floor or ceiling and move it around.

- **Right-click** selects the surface you're aiming at, **right-click again** releases it.
- **`` ` `` + scroll** moves it. The **build modifier** switches **Move ↔ Resize** (Resize thickens or
  thins it instead of sliding it).
- **U** undoes the move.

The direction comes from where you're looking and **keeps updating as you turn** — turn around mid-move and
it carries on the way you're now facing. Scroll up always pushes away from you, whichever way that is.
Vertical takes a deliberate steep look up or down, so glancing down at a wall won't quietly turn a sideways
push into a downward one.

Unbreakable blocks are never part of a selection, and a move will never write over or clear one — bedrock,
barriers and command blocks stay put whether you slide a slab into them or resize through them.

It grabs the blocks **behind** the face too, so a thick wall moves as a whole instead of shaving off its
front layer — capped, so aiming at a hillside doesn't drag half the terrain along. If part of the selection
gets actually destroyed while you're holding it (sand falls, a creeper, someone mines it) those blocks drop
out instead of reappearing when you move it — but a block that merely *changes*, like grass going to dirt
once you move it somewhere dark, stays in the selection.

Putting the staff away — switching hotbar slot, ability or mode — lets the surface go: the blocks stay where
they are, **U** still undoes the move, and the beam and label disappear with it.

## Block Tracker
Three sub-modes (also **Left Alt**):

### Floor Maker
Walk forward to lay a permanent path under you. The beam comes off the staff tip in your colour and sticks
to the block being laid.

### Defense Wall
Hold right-click to keep a wall in front of you, following your aim **in 3D** — sweep it from ground level
up over your head and it tracks the whole way, no dead zone.

- **`` ` `` + scroll** sets its distance. It shoves and hurts whatever it runs into — **any** time the
  wall actually moves, including sweeping it sideways across a mob, not just while sliding it in and out.
  The push follows the wall's own direction of travel in full 3D: pull it back toward you and it drags
  mobs toward you, push it down and it presses them down.
- **Damage scales with the block.** Dirt barely stings; iron, diamond and obsidian hit progressively
  harder.
- **Pick a different block while the wall is up** and it re-materialises in the new one.
- **Left-click** lets go — the wall stays standing for good. It survives switching items and dying, like
  blocks you placed by hand, and building a new wall leaves it alone instead of taking it back over.
- **Shift + right-click** re-grabs the wall that's already there; plain right-click starts a fresh one.

The label is an attack tracker — `tp @e[tag=<block>_attack_tracker] ^ ^ ^<distance>` — in the beam's
colours, tracking the wall every tick, distance included.

### Shaper
**Build modifier + right-click** switches shape (Wall / Stairs / Platform); hold right-click to build.

- **Sneak while shaping destroys** instead of building — carves a 3×3 out of whatever you point at.
- Stairs are sized by looking up **or down**: straight up is a full flight up, straight down cuts one
  descending into the ground. **`` ` `` + scroll** fine-tunes on top of that. They play a break sound when
  you shrink them and can run at **any angle**, not just N/S/E/W.
- **Stairs clear their own headroom** — four blocks above every step get carved out, so a flight cut into
  a hillside is actually walkable. Unbreakable blocks (bedrock, barrier) are left alone.
- Going **down**, each step replaces the ground it cuts through, so you get a proper staircase rather than
  a hole. "Full stairs" only applies going up — descending is a single layer per step.

## Easy stairs

Jump while walking forward with the **build modifier** held and a block drops under you.

The **V** chooser has tabs and search, and you can drag its corner handle to resize it.
