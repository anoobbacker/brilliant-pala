# Question
A 2 cm long object is placed perpendicular to the principal axis of a concave mirror.  

The distance of the object from the mirror is 30 cm, and its image is formed 60 cm from the mirror  on the same side of the mirror as the object.  

What is the height of the image?

Options:  
A) 4 cm  
B) 40 cm  
C) 4 m  
D) none

---
# Answer
## Quick visual solution
- Picture the mirror as an “eye.” The top of the object and the top of the image lie along the same reflected ray, so they subtend the same angle at the mirror.
- When two things look under the same angle from one point, their sizes grow in direct proportion to how far they are from that point — like shadows getting bigger as the wall moves farther away.
- Here the image is twice as far from the mirror as the object (60 cm vs 30 cm), so the image must be twice as tall.
- Object height = 2 cm → Image height = 4 cm (and inverted, since it’s a real image).

Answer: A) 4 cm

---

## Creative twists
- Is the image farther than the object? Yes → expect a larger image. Double the distance → double the size.
- Concave mirror making a real image on the same side? Yes → image is upside-down but that doesn’t change the height’s magnitude.
- Mixing up the ratio (using 30/60 instead of 60/30). Ask: which is farther? The image. Then the image must be larger.
- Forgetting inversion: real concave images are upside-down, but the question asks only for height.
- Picking 40 cm or 4 m by thinking “bigger” without proportional sense.
- If the image were at 15 cm instead, it would be half as far as the object (30 cm) → image half as tall.
- Same idea works for thin lenses and even pinhole cameras: distance scales the size.
- Projector on a screen: move the screen twice as far → the picture doubles in size.
- Shadow on a wall: step the wall back → the shadow scales up proportionally.
- One picture: From the mirror’s “eye,” object top and image top line up on the same ray. Same angle + farther distance = bigger size. Here, 2× farther → 2× taller → 4 cm.

## First-Principles Solution (no memorized formulas)

### 1) Visual and physical setup
- Imagine the concave mirror with its principal axis as a horizontal line.
- The object is a vertical stick of height $h_o = 2$ cm placed at distance $u = 30$ cm from the mirror (perpendicular to the axis).
- The image forms on the same side (in front of the mirror) at distance $v = 60$ cm, which means it’s a real image and will be inverted.

Key physical law: Law of reflection — the angle of incidence equals the angle of reflection. We’ll use just one special ray to do the geometry: the ray from the top of the object that hits the mirror at the pole (the center of the mirror). At the pole, the normal to the mirror is the principal axis, so reflection is symmetric about the axis.

### 2) Geometry of similar triangles from the pole ray
- Draw a ray from the top of the object to the pole (point P). After reflection, this ray will head toward the top of the image.
- The incoming and outgoing parts of that ray make equal angles with the principal axis but on opposite sides due to reflection symmetry.

That means the “slope” of the line on the object side equals the “slope” (with opposite sign) on the image side:
- On the object side: slope = rise/run = $h_o/u$
- On the image side: slope = rise/run = $(-h_i)/v$ (negative because the image is inverted below the axis)

So,
```math
\frac{h_o}{u} = -\frac{h_i}{v}
\quad\Rightarrow\quad
\frac{h_i}{h_o} = -\frac{v}{u}
```
This ratio $m = h_i/h_o$ is the magnification. It is dimensionless (check: cm/cm cancels), as it should be.

### 3) Proportional reasoning (quick intuition)
- If the image forms twice as far from the mirror as the object ($v = 2u$), it must appear twice as large in linear size (but inverted). That’s exactly what the ratio above says.

### 4) Compute the height
Given $u = 30$ cm and $v = 60$ cm:
```math
m = -\frac{v}{u} = -\frac{60}{30} = -2
\quad\Rightarrow\quad
h_i = m\,h_o = (-2)\times (2\ \text{cm}) = -4\ \text{cm}
```
The negative sign means the image is inverted. The magnitude is 4 cm.

Answer: 4 cm (inverted), i.e., Choice A.

---

## Cross-checks and Intuition

- Dimensional check: $v/u$ is unitless, so $h_i$ has units of cm, which matches.
- Physical check with a ray diagram: Object between focus and center (actually here $f=20$ cm; see note below), image forms beyond center, enlarged and inverted — consistent with $h_i = 4$ cm inverted.
- Optional consistency check (not needed for the height, but useful context): Using $1/f = 1/u + 1/v$ with $u=30$ cm and $v=60$ cm gives $f=20$ cm for the concave mirror. Since $20 < 30 < 40$, the object is between $F$ and $C$, so the image is real, inverted, beyond $C$, and magnified — exactly what we found.  

Real-world mental model: The mirror turns “angles” into positions. The angular size of the object as seen from the pole is $\approx h_o/u$. The image must reproduce that angle on the other side, $\approx |h_i|/v$, but inverted. Equating those angles gives $|h_i|/v = h_o/u$, hence $h_i = -(v/u)h_o$.

---

## Multiple Approaches

- Analytical (used above): Law of reflection at the pole → similar triangles → $h_i/h_o = -v/u$.
- Intuitive proportionality: Double the distance from the mirror doubles the image size. Here $v/u = 2$, so the image is twice as tall (but flipped).       
- Experimental: In a lab, place a candle 30 cm from a concave mirror. Move a screen until the sharp image appears at 60 cm. Measure object and image heights; you’ll find the image height is about twice the object height and inverted.

---

## Final Answer
A) 4 cm (inverted)

---

## Conceptual Follow-up Questions
1. If the image formed at 15 cm on the same side, what would be the image height for the same object? What does its being closer than the object imply about size and orientation?
2. If the image instead formed 60 cm behind the mirror (opposite side, i.e., virtual), what would be the height and orientation?
3. Where should you place the object so that the image is the same size as the object? What are $u$, $v$, and $f$ in that case?
4. If you move the object to 50 cm, would the image be bigger or smaller than the object? Where would the image form?

---

## Application Questions (Real-life and Engineering)
- Makeup/shaving mirrors: When do they produce upright, magnified images vs inverted images? What does that say about the object’s distance relative to the focal length?
- Solar furnace/flashlight design: Why is placing a light source at the focal point useful? How does moving the source closer/farther affect beam divergence and brightness?
- Satellite dishes and radio telescopes: How does a concave “mirror” (dish) scale the “image” of incoming waves at the receiver? Why is focal length crucial?

---

## Common Misconceptions and Traps
- Forgetting inversion: Real images from concave mirrors (when object is beyond focal length) are inverted, so $h_i$ is negative by sign convention.        
- Mixing lens and mirror sign rules: For mirrors, “same side as object” for a real image; for lenses, real images are on the opposite side from the object. 
- Treating $v/u$ as having units: Magnification is dimensionless; $v$ and $u$ must share the same units.
- Thinking “perpendicular to the axis” changes the result: It just defines height cleanly; the size relation still comes from geometry and reflection symmetry.
- Using the mirror formula without understanding: The magnification formula arises from angle equality and similar triangles, not from memorization.        

---

## Extension Challenges
1. Derive the mirror equation $1/f = 1/u + 1/v$ from first principles using small-angle/paraxial geometry for a spherical mirror (connect object point, image point, center of curvature, and pole).
2. For a rod placed at an angle to the principal axis, determine the length and orientation of its image (you’ll need to project endpoints).
3. Explore non-paraxial effects: If the object is very tall, how might spherical aberration affect the image height and sharpness?
4. Design task: Choose a focal length for a concave mirror so that a 2 cm tall LED at 25–35 cm produces real images between 40–70 cm with magnification between 1.5 and 2.5. Quantify tolerances.

---

## Reflective Insight (the deep “why”)
At its core, a mirror maps rays by preserving angles about the normal. The ray through the pole is special because its normal is exactly the principal axis; reflection there is perfectly symmetric. That symmetry forces the angular sizes on the object and image sides to match in magnitude. Since angular size is “height divided by distance,” the image height must scale in direct proportion to its distance from the mirror. That is why $h_i/h_o = -v/u$ — not a memorized rule, but a geometric inevitability from the law of reflection.