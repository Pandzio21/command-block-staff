# Electrify

Zap a mob, player or block. Electrified mobs are frozen in place, and so are players — they can't walk or
jump until you let them go.

- **Right-click** — electrify what you're aiming at (an entity, a block, or straight into the air).
- **X** — un-electrify what you're aiming at. Undoable with **U**.
- **Shift** — reveal everything you've electrified.

Electrification **doesn't wear off**. It stays until you remove it.

Blocks the staff is actively moving — a Defense Wall, a block trail, a Move Surface slab — can't be
electrified. They're torn down and rebuilt every tick, so the mark would just end up stranded on empty air.
Blocks you **place against** an electrified one do pick up the charge.

## Reveal

Hold **Shift** with Electrify selected and everything you've zapped lights up:

- **Blocks** get a white wireframe box, sized to the block's real shape — a slab gets a slab-sized box, not
  a full cube — and it's visible through walls.
- **Entities** spark with particles.

It's drawn on your own machine off your own crouch, so it appears the instant you press Shift and can't get
out of step with what's actually electrified. Only you see your own reveal.

## Conductive blocks

Electrified **copper** and **water** carry the current: anything living within 5 blocks takes ½♥ every half
second. Turns a pool into a trap.

Short range — not the staff's full beam reach. The electric beam leaves the actual staff tip, and a floating
label tags the target.
