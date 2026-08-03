# Placement

Pick a block with **V**, then build. **Left Alt** cycles the modes.

Haven't picked one yet? The staff says so instead of quietly doing nothing, and the beam stays off rather
than promising a block that isn't coming.

The **Pick Block** key (Left Ctrl by default, rebindable) + right-click is an eyedropper in every mode.
If you've got sneak on the same key, the mode action wins and the picker steps aside — move either one and
you get both back.

## Single Block

Click to place on the face you're looking at. Works in mid-air too. **Hold the build modifier** (++tab++)
to paint a trail as you walk.

**Shift + right-click** cycles what a click does:

| | |
|---|---|
| **Place** | Normal — needs an empty spot |
| **Replace** | Overwrites whatever you're aiming at |
| **Air / Remove** | Deletes it (no block needed) |

## Fill

Left-click one corner, right-click the other, and it fills — with a live preview, up to 32768 blocks.
**Shift + right-click** flips between filling and deleting.

## Move Surface

Grab a whole wall, floor or ceiling and drag it around.

- **Right-click** grabs the surface you're looking at. **Right-click again** lets go.
- **`` ` `` + scroll** moves it. The **build modifier** switches between **Move** and **Resize** (resize
  makes it thicker or thinner instead of sliding it).
- **U** undoes the move.

Direction comes from where you're looking and **keeps updating as you turn** — spin around mid-move and it
carries on the new way. Scroll up always pushes away from you. Vertical needs a deliberate steep look, so
glancing down at a wall won't quietly turn a sideways push into a downward one.

It takes the blocks **behind** the face too, so a thick wall moves as one piece instead of shedding its
front layer. That's capped, so aiming at a hillside doesn't drag half the terrain with it.

Unbreakable blocks are never part of a selection, and a move will never write over or clear one — bedrock,
barriers and command blocks stay exactly where they are, whether you slide a slab into them or resize
through them.

If part of your selection actually gets destroyed while you're holding it (sand falls, a creeper, someone
mines it), those blocks drop out instead of reappearing when you move. A block that merely *changes* —
grass going to dirt once you move it somewhere dark — stays put in the selection.

Put the staff away (different slot, different ability, different mode) and the surface is released: the
blocks stay where they are, **U** still undoes it, and the beam and label go with it.

## Block Tracker

Three sub-modes, also on **Left Alt**.

### Floor Maker

Walk forward and it paves under you. The beam comes off the staff tip in your colour and sticks to the
block it's laying.

### Defense Wall

Hold right-click and a wall hangs in front of you, following your aim **in 3D** — sweep it from the ground
up over your head and it tracks the whole way.

- **`` ` `` + scroll** sets how far out it sits. It shoves and hurts anything it runs into, **any** time it
  actually moves — including swinging it sideways through a mob, not just sliding it in and out. The push
  follows the wall's own direction of travel, so pulling it back drags mobs toward you and pushing it down
  presses them into the ground.
- **Damage depends on the block.** Dirt barely stings; iron, diamond and obsidian hit progressively harder.
- **Pick a different block while it's up** and the wall re-materialises in the new one.
- **Left-click** lets go, and it stays standing for good — through item switches and death, like blocks you
  placed by hand. Building a new wall leaves the old one alone.
- **Shift + right-click** takes the standing wall back over; plain right-click starts a fresh one.

The label is an attack tracker — `tp @e[tag=<block>_attack_tracker] ^ ^ ^<distance>` — in your beam's
colours, following the wall every tick.

### Shaper

**Build modifier + right-click** switches shape (Wall / Stairs / Platform). Hold right-click to build.

- **Sneak while shaping** and it destroys instead, carving a 3×3 out of whatever you point at.
- Stairs are sized by looking up **or down**: straight up is a full flight up, straight down cuts one into
  the ground. **`` ` `` + scroll** fine-tunes on top. They play a break sound when you shrink them and run
  at **any angle**, not just north/south/east/west.
- **Stairs clear their own headroom** — four blocks above every step, so a flight cut into a hillside is
  actually walkable. Bedrock and other unbreakables are left alone.
- Going **down**, each step replaces the ground it cuts through, so you end up with a staircase and not a
  hole. "Full stairs" only applies going up.

## Easy stairs

Jump while walking forward with the **build modifier** held and a block drops under you.

The **V** chooser has tabs and search, and you can drag its corner to resize it.
