# Question
A candle flame 3 cm is placed at distance of 3 m from a wall. How far from wall must a concave mirror be placed in order that it may form an image of flame 9 cm high on the wall:  
1) 225 cm  
2) 450 cm  
3) 300 cm  
4) 650 cm

## See the scene first

Imagine a candle 3 m in front of a wall. You want a concave mirror to throw a sharp, enlarged image of the flame onto the wall, and you want that image to be 9 cm tall (the real flame is 3 cm tall).

Key observation: A concave mirror forms a real image in front of the mirror (on the same side as the object). So to project the image onto the wall, the wall must lie in front of the mirror. That means the mirror must be placed beyond the candle (farther from the wall than the candle), so that the image forms back toward the wall.

Text sketch (left to right):
Wall (x = 0) —— 3 m —— Candle (x = 3 m) —— (D − 3 m) —— Mirror (x = D)
The image forms on the wall, so its distance from the mirror equals D.

---

## Build the relation from first principles

Start from the simplest question: How does image size compare to object size?

- When a mirror forms a real image, rays from the top of the object and their reflected counterparts make similar triangles with the mirror’s axis.
- Similar triangles mean: the “stretch factor” along the axis is the same as the “stretch factor” in height.

So the linear magnification m (how many times taller the image is compared to the object) equals the ratio of image distance to object distance (measured from the mirror):

$$
m = \frac{\text{image height}}{\text{object height}} = \frac{v}{u}

$$

We’ll use magnitudes here since we only need sizes. The inversion (upside-down image) just gives a minus sign, which doesn’t affect height.

Given:
- Object height ho = 3 cm
- Image height hi = 9 cm ⇒ m = hi/ho = 9/3 = 3

Let:
- D = distance of mirror from the wall (what we must find)
- Then image distance from mirror v = D (because the image is on the wall)
- Object distance from mirror u = distance from mirror to candle = D − 300 cm (since candle is 300 cm = 3 m from wall)

Now apply m = v/u:

$$
\frac{v}{u} = 3 \quad \Rightarrow \quad \frac{D}{D - 300} = 3

$$

Solve:

$$
D = 3(D - 300) \Rightarrow D = 3D - 900 \Rightarrow 2D = 900 \Rightarrow D = 450 \text{ cm}

$$

Answer: 450 cm (Option 2)

Dimensional check: Every term is in cm, magnification is dimensionless — consistent.

Quick physical check: If D = 450 cm, then u = 450 − 300 = 150 cm and v = 450 cm, so v/u = 3, giving a 3× enlargement (from 3 cm to 9 cm). Works.

---

## Alternative analytical lens (optional)

If you also use the mirror formula for consistency:

$$
\frac{1}{f} = \frac{1}{u} + \frac{1}{v} = \frac{1}{150} + \frac{1}{450} = \frac{4}{450}
\Rightarrow f = 112.5 \text{ cm}

$$

So a concave mirror with focal length 112.5 cm would do this when placed 450 cm from the wall. (You weren’t asked for f, but it’s a good self-check.)

---

## Experimental intuition

- Put the mirror beyond the candle and face it toward the candle.
- Slide the mirror farther from the wall; as you do, the image on the wall grows or shrinks. When its height is 9 cm (3× the flame), you’ve reached D = 450 cm.

---

> ### 🧠 Quick Exam Tips
> - For a concave mirror projecting onto a wall, the wall must be in front of the mirror; place the mirror beyond the object.
> - Use magnification: m = hi/ho = v/u (magnitudes).
> - Translate the geometry carefully: v = mirror-to-wall distance, u = mirror-to-candle distance.
> - Set D/(D − 300) = 3 ⇒ D = 450 cm.

---

## Conceptual follow-ups

- What if you wanted a 6 cm image instead? Then m = 2, so D/(D − 300) = 2 ⇒ D = 600 cm.
- What if you put the mirror between the candle and the wall? A concave mirror’s real image forms in front of it (toward the candle), so it cannot land on the wall behind the mirror.

---

## Misconception clinic

- Many students think m = u/v. Actually, from similar triangles, m = v/u (magnitudes).
- “The image can appear behind a concave mirror on the wall.” For a real image, concave mirrors form images in front of the mirror. To hit the wall, the wall must be on that same side.
- Units trip-up: Convert 3 m to 300 cm before plugging into options in cm.

---

## Mini practice

1) If the flame were 4 cm and you still want a 12 cm image on the wall 3 m behind it, where do you place the mirror?
   - m = 12/4 = 3; same geometry ⇒ D = 450 cm again.

2) If you place the mirror 500 cm from the wall, what image height do you get?
   - u = 500 − 300 = 200 cm, v = 500 cm, m = 500/200 = 2.5 ⇒ hi = 2.5 × 3 cm = 7.5 cm.

---

> “Optics is geometry with light.” Learn to sketch the setup, label distances, and use similar triangles. Once you see the picture, the algebra almost writes itself.