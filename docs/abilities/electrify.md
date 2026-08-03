# Electrify

Point at something and zap it. Mobs freeze solid; so do players — no walking, no jumping, until you let
them go.

- **Right-click** — zap whatever you're aiming at: a mob, a block, or just the air.
- **X** — un-zap it. **U** undoes that if you didn't mean it.
- **Shift** — show me what I've zapped.

It doesn't wear off. Whatever you electrify stays electrified until you deal with it.

Blocks the staff is currently *moving* — a Defense Wall, a block trail, a Move Surface slab — can't be
zapped. They get torn down and rebuilt every tick, so the mark would just end up floating in the air where
the block used to be. Blocks you **place against** something electrified do pick up the charge, though.

## Reveal

Hold **Shift** with Electrify out and everything you've zapped lights up:

- **Blocks** get a white wireframe, sized to the block's actual shape (a slab gets a slab-shaped box, not a
  full cube), and you can see it through walls.
- **Entities** throw off sparks.

Your game decides this from your own crouch, so it shows up the moment you press the key and can never
disagree with what's really electrified. It's just for you — nobody else sees your reveal.

## Conductive blocks

Electrified **copper** and **water** carry the current: anything alive within 5 blocks takes half a heart
every half second. A pool becomes a trap.

Short range, by the way — nowhere near the beam's reach.
