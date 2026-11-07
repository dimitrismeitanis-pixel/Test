# Reconstruction check: Hanuman and mythical lion forearm tattoo

This compares ChatGPT's flat line-art reconstruction with the five photos of the real tattoo.
The marked-up visual comparison is in [`fix-sheet.png`](fix-sheet.png).

**Verdict:** the overall layout is close and most elements are right. Four things are wrong,
and two of them (the dagger and the back leg) change how the design reads on the arm.

## What's wrong

### 1. Dagger: wrong angle and too short
- **Real tattoo:** the dagger in Hanuman's lower hand hangs almost straight down along the forearm, with a slight lean to the right.
  The blade is long: it runs past the sash and well into the swirl clouds below. The pointed, leaf-shaped pommel sits above the fist.
- **ChatGPT:** the blade is tilted about 30° and stops much higher.

### 2. The creature's back leg is on the wrong side
- **Real tattoo:** the back leg comes out from behind Hanuman's hip, to the **right of the dagger**. It curves out toward
  the outer side of the arm and then down. It is covered in layered scale/flame-curl texture, and the claws sit at the
  **bottom right**, pointing down. Two flame tufts rise from the knee/haunch, and the leg sits on solid black dotwork clouds.
- **ChatGPT:** the leg bends down and to the **left**, under the dagger, so it ends up in the bottom centre.
  The right edge of the design has clouds where the leg should be.

### 3. The area below the sash is too busy
- **Real tattoo:** below Hanuman's sash it's mostly stacked, open swirl clouds drawn as clean lines on bare skin, with only
  a little soft shading at the edges. The black clouds run only along the bottom edge (the wrist end).
- **ChatGPT:** this area is full of heavy hatching and bevels, plus the misplaced leg.

### 4. The line style is too heavy (an AI "engraving" look)
- **Real tattoo:** thin, even single lines, soft stipple/whip shading and plenty of open skin. The creature's mane
  is made of light, wispy flame strokes.
- **ChatGPT:** every shape has a doubled outline with a white gap and a fake drop shadow, plus dense engraving
  hatching everywhere. The double outline belongs **only** around the black dotwork clouds, which is how the real tattoo does it.

## Already right (keep)
- Row of flames along the top, with a horizontal-hatched sky behind
- Sword raised overhead with the blade pointing right, and the flame-shaped guard
- Solid black backdrop behind Hanuman's head with a scalloped edge
- Open-mouthed monkey face with the swirl on the cheek
- Beaded necklace with the teardrop pendant at the navel, the layered collar and the lotus pendant
- Net/lattice panels and the scale-pattern sash, with the cloth fold hanging over the sash
- Creature's head on the upper left: striped horn, rosette on the harness, raised curled front paw
- Front leg with claws on the lower left
- Hanuman's tail curling up the right edge, ending in a flame
- Black dotwork clouds with a white gap and outline around them

## Prompt to get ChatGPT to fix it

Attach the reconstruction **and** the tattoo photos, then paste:

```text
Edit the attached line-art reconstruction so it matches the real tattoo in the attached photos.
Keep the overall composition, the characters and everything that is already correct. Only change these things:

1. DAGGER: Hanuman's lower hand holds the dagger with the blade pointing almost straight down
   (a slight lean to the right, not a 30-degree diagonal). Make the blade much longer, so it runs
   past the sash and deep into the swirl clouds below. Keep the pointed leaf-shaped pommel above the fist.

2. BACK LEG: move the creature's back leg to the RIGHT side of the design, to the right of the dagger.
   It comes out from behind Hanuman's hip, arcs outward to the right edge, then curves down. It has
   layered scale/flame-curl texture, and the claws sit at the bottom-right corner pointing down. Add two flame tufts
   rising from the knee. Put it on solid black dotwork clouds. Remove the leg that currently sits in the bottom
   centre under the dagger.

3. LOWER CENTRE: below Hanuman's sash, use stacked, open swirl clouds drawn as clean lines on white,
   with very little shading. Black dotwork clouds only along the bottom edge.

4. LINE STYLE: thin, even, single-weight tattoo linework with soft stipple shading and lots of open white space.
   NO doubled outlines, NO drop shadows or bevels, NO dense engraving hatching. The double outline with a white gap
   is used ONLY around the black dotwork clouds. Draw the lion's mane as light, wispy flame strokes.

Keep unchanged: the flame row and hatched sky at the top, the raised sword pointing right, the black scalloped
backdrop behind Hanuman's head, the face, the necklace and pendants, the lattice panels and sash, the creature's head
with the striped horn, the rosette harness and the raised front paw, the front leg on the lower left, and Hanuman's tail.
Output: black-and-white line art on a white background, portrait format, suitable as a tattoo reference.
```

Image generators usually fix two or three points per pass. If the first result only fixes some
of them, re-run the prompt with just the remaining numbered items.

## Notes
- The photos show a design wrapped around a forearm, so the left and right parts are compressed by the
  arm's curve. Exact proportions at the sides can't be measured from them; what's listed above is what's clearly visible.
- This is a custom piece by a tattoo artist. If you want it (or something close to it) tattooed, the best result is to
  take the photos to that artist, or have your own artist redraw it as a proper stencil. AI line art isn't
  clean enough to stencil directly.
