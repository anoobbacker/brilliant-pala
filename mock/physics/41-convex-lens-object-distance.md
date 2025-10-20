# Question
A convex lens of focal length 10 cm produces an image which is having same size as that of the object. The magnitude of the object distance from the lens in cm is

## See the idea first

Imagine holding a magnifying glass (a convex lens) and placing a coin at just the right distance so its image looks the same size on a screen on the other side. When does a lens copy an object without magnifying or shrinking it? Intuitively, it must place the image as far from the lens as the object is — a kind of symmetric “flip.” That special distance turns out to be twice the focal length.

We’ll rebuild this from simple rays and geometry — no memorized formulas.

---

## Build from first principles (ray logic → geometry)

### Step 1: Two “easy” rays a convex lens gives you
- Ray A: Through the lens center → goes straight (thin lens approximation).
- Ray B: Parallel to the axis before the lens → passes through the focal point F after the lens.

These two rays meet at the image. That lets us use similar triangles.

### Step 2: Magnification from the center ray
Look at the straight ray through the center. The triangles formed by the object and image with the lens give:

```math
\text{magnification } m \equiv \frac{\text{image height}}{\text{object height}}
= \frac{h'}{h} = \frac{v}{u}
```

Here:
- u = object distance from lens
- v = image distance from lens
- h, h' = object and image heights

So “same size” means |m| = 1 ⇒ |v| = |u|. For a real image formed by a convex lens, that means v = u in magnitude.

### Step 3: Relate u, v to focal length f (derive the lens formula quickly)
Use the parallel-to-axis ray (Ray B). It hits the lens at height h and then goes in a straight line through the focal point F to the image top at height h'. Because it’s one straight line, its slope is the same in both segments:
- From lens to F: slope = h / f
- From F to image: slope = h' / (v − f)

Equal slopes give:

```math
\frac{h}{f} = \frac{h'}{v - f}
\quad\Rightarrow\quad
\frac{h'}{h} = \frac{v - f}{f}
```

But from Step 2, h'/h = v/u. Set them equal:

```math
\frac{v}{u} = \frac{v - f}{f}
\quad\Rightarrow\quad
vf = uv - uf
\quad\Rightarrow\quad
uv = f(u + v)
```

Divide both sides by fuv:

```math
\frac{1}{f} = \frac{1}{u} + \frac{1}{v}
```

That’s the thin lens equation — we’ve reconstructed it from ray geometry.

### Step 4: Apply “same size” condition
Same size ⇒ v = u (in magnitude). Substitute v = u into the lens equation:

```math
\frac{1}{f} = \frac{1}{u} + \frac{1}{u} = \frac{2}{u}
\quad\Rightarrow\quad
u = 2f
```

Given f = 10 cm:

```math
u = 2 \times 10 \text{ cm} = 20 \text{ cm}
```

Answer: 20 cm.

---

## Visual aid (what to picture)
- A vertical lens in the middle.
- Object on the left at distance u; image on the right at distance v.
- One ray from the top of the object goes straight through the center of the lens to the image.
- A second ray goes horizontally to the lens, then bends through the focal point on the right and meets the first ray at the image.
- When the image is the same size, both object and image are at equal distances from the lens, and those distances turn out to be 2f.

---

> ### 🧠 Quick Exam Tips
> - Equal-size (real) image with a convex lens ⇒ object at 2f, image at 2f.
> - Magnification m = v/u (sign tells inversion; magnitude tells size factor).
> - Lens formula (derived from similar triangles): 1/f = 1/u + 1/v.
> - If u > 2f → image diminished; if f < u < 2f → image magnified; u = f → image at infinity.

---

## Conceptual follow-ups
- What if the object is inside the focal length (u < f)? The image is virtual, upright, and larger than the object — there’s no way to get “same size” in that case.
- What happens if u = 3f? Use the lens equation to find v; check that the magnification |m| = v/u is less than 1 (image is smaller).

## Real-world connection
Cameras and copy machines aim for “1:1” reproduction by placing sensor/film and subject each at about 2f from the lens — that’s the “copying” distance.

## Misconception clinic
- “Equal size means put the object at the focal point.” Not true: at u = f, the image goes to infinity (rays emerge parallel). Equal size needs u = 2f.
- “Same size means same side.” For a real image with a convex lens, the image forms on the opposite side. Same size means equal distances, not same side.

## Extension challenge
In a microscope objective, why is the object placed just beyond f rather than at 2f? Hint: you want a large magnification, so you work with u slightly greater than f to make v very large.

## Practice questions
1) A convex lens has f = 5 cm. Where must the object be for the image to be the same size?
2) If u = 15 cm and f = 10 cm, find v and the magnification. Is the image bigger or smaller than the object?

Answers:
1) u = 2f = 10 cm.
2) 1/f = 1/u + 1/v ⇒ 1/10 = 1/15 + 1/v ⇒ 1/v = 1/10 − 1/15 = 1/30 ⇒ v = 30 cm; m = v/u = 30/15 = 2 (image is twice as tall, inverted).

---

> The reflective essence
> Nature loves symmetry. When a lens neither enlarges nor shrinks, distances balance on both sides: 2f and 2f. Recognizing such symmetries lets you solve fast without memorizing.