## Question
A convex lens of focal length 30 cm produces a real image three times the size of the object. The magnitude of object distance (in cm) from the lens is

## Big picture
A convex lens bends light rays so that rays coming in parallel to its axis meet at a point called the focus. This happens because light slows down in glass, and the curved surfaces steer edge rays more than central rays. If an object is placed in front of such a lens, two easy-to-track rays help us predict where the image forms:
- A ray through the lens’s center goes straight (almost undeviated).
- A ray parallel to the axis bends to pass through the focus.

By following where these two rays meet, we can locate the image and relate all distances using simple geometry—no memorized formulas needed.

## Step 1: Set up a clear diagram in your head
- Let the lens be at the vertical line x = 0.
- Object of height h is at x = −u (so u is its distance from the lens; we’ll use u > 0 as a magnitude).
- Image of height h′ forms at x = +v (v > 0 for a real image on the other side).
- Focal length is f (for a convex lens, f > 0). The right focal point is at (f, 0).

## Step 2: Derive magnification from a straight line (central ray)
Take the ray from the top of the object A(−u, h) through the lens center O(0, 0). It goes straight.

The line through A and O has slope:
```math
m_{\text{center}}=\frac{0-h}{0-(-u)}=-\frac{h}{u}
```

At the image plane x = v, the y-value of this straight line gives the image height h′:
```math
h' = m_{\text{center}} \cdot v = -\frac{h}{u}\,v
```
So the magnification (size ratio) is
```math
m=\frac{h'}{h}=-\frac{v}{u}
```
- The minus sign tells us the image is inverted when it’s real.
- The magnitude is |m| = v/u (dimensionless, as a ratio of lengths).

## Step 3: Derive the thin lens relation from ray intersection
Now use the second easy ray: from the top of the object A(−u, h), send a ray parallel to the axis. It arrives at the lens at (0, h), then refracts and passes through the right focus F(f, 0).

The line from (0, h) to (f, 0) has slope:
```math
m_{\text{focus}}=\frac{0-h}{f-0}=-\frac{h}{f}
```

Its equation (starting at x=0 with y=h) is:
```math
y = h + m_{\text{focus}}\,x = h - \frac{h}{f}\,x
```

At the image plane x = v, this ray’s height is:
```math
y(v) = h - \frac{h}{f}\,v
```

But the image point must lie where both rays meet, so this must equal h′ from Step 2:
```math
h - \frac{h}{f}\,v = -\frac{h}{u}\,v
```

Divide by h (nonzero), rearrange:
```math
1 - \frac{v}{f} = -\frac{v}{u}
\quad\Rightarrow\quad
1 = \frac{v}{f} - \frac{v}{u}
```
Divide both sides by v:
```math
\frac{1}{v} = \frac{1}{f} - \frac{1}{u}
\quad\Rightarrow\quad
\frac{1}{f} = \frac{1}{v} + \frac{1}{u}
```

This is the thin lens relation derived from geometry and similar triangles. Dimensional check: each term has units of 1/length, so it’s consistent.

Note on signs: Here we used u, v, f as positive magnitudes (distances). In the standard Cartesian sign convention, u would be negative for a real object on the left, giving 1/f = 1/v − 1/u. Both are the same relation stated with different sign choices.

## Step 4: Use the given magnification to solve
“Real image three times the size” means |m| = 3, so from Step 2:
```math
\left|\frac{h'}{h}\right| = \frac{v}{u} = 3 \quad\Rightarrow\quad v = 3u
```

Plug into the thin lens relation (with magnitudes):
```math
\frac{1}{f} = \frac{1}{v} + \frac{1}{u}
= \frac{1}{3u} + \frac{1}{u}
= \frac{1+3}{3u}
= \frac{4}{3u}
```
Solve for u:
```math
u = \frac{4}{3}\,f
```

Given f = 30 cm:
```math
u = \frac{4}{3}\times 30\ \text{cm} = 40\ \text{cm}
```

Answer: 40 cm.

## Step 5: Physical sanity checks
- If u = 40 cm and f = 30 cm, the object is between f and 2f (between 30 and 60 cm). That’s exactly where convex lenses produce real, inverted, magnified images.
- Compute v: v = 3u = 120 cm, which is beyond 2f, again matching the known behavior.
- Check the lens equation: 1/30 = 1/120 + 1/40 = 1/120 + 3/120 = 4/120 = 1/30. Works.

## Final result
The magnitude of the object distance is 40 cm.

---

## Conceptual follow-up questions
1. If the image were half the size of the object (real image), where would the object be relative to f and 2f?
2. What happens to the image when the object is placed exactly at 2f? At f?
3. If the image is virtual and upright with magnification 2, what can you say about the object’s position relative to the focal length?
4. Why does a ray through the center of a thin lens go straight? What assumptions make this a good approximation?

## Application questions
- Camera focusing: Why must a camera move its sensor or lens when focusing on a closer subject? Relate to how v changes as u decreases.
- Projector design: To make a large image on a distant screen, where should the slide be placed relative to the lens?
- Vision correction: How does a converging (convex) spectacle lens for farsightedness use the idea of virtual images to help the eye focus?

## Common misconceptions and reasoning traps
- Confusing size with distance: A bigger image doesn’t mean it’s closer to the lens. In fact, for a convex lens, a larger real image often forms farther away (v larger).
- Ignoring inversion: Real images made by a convex lens are inverted; magnification magnitude ignores the minus sign but the sign contains physical meaning.
- Plug-and-chug without units: Always check the dimensions in 1/f = 1/v + 1/u. All must be in the same units.
- Forgetting the “thin lens” and “## Common misconceptions and reasoning traps (continued)
- Forgetting the “thin lens” and “paraxial” approximations: Our derivation assumes a thin lens (thickness negligible) and small angles (rays close to the axis). For thick lenses or wide-angle rays, the simple relations need corrections.
- Mixing sign conventions with magnitudes: Decide whether you’re using signed distances (Cartesian convention) or magnitudes. Don’t combine them mid-calculation. If you use magnitudes, keep track of inversion separately (the minus in m = −v/u).
- Assuming any convex-lens image is real: A convex lens makes a virtual, upright, magnified image if the object is inside the focal length (u < f). Real images occur when u > f.
- Treating magnification as “just a number”: The sign of magnification carries physical meaning (negative = inverted, positive = upright for the usual convention). The magnitude |m| tells size change.
- Unit slips: Using f in cm but v and u in m breaks 1/f = 1/v + 1/u. Keep all in the same units.
- Over-reliance on ray rules without understanding: The “parallel-to-focus” and “through-center” rays aren’t magic; they’re consequences of how refraction angles steer light, and of symmetry at the lens center.

## Extension challenges
- Analytical challenge: Starting from the derived relations, eliminate v to express magnification purely in terms of u and f. Then study how |m(u)| behaves as u approaches f from above and as u → ∞. What are the asymptotes and limits?
- Graphical analysis: Rearrange the lens relation to 1/v = 1/f − 1/u. If you plot 1/v versus 1/u, what does the graph look like? How could you experimentally find f from the intercept?
- Experimental design: Devise a simple lab to measure f using sunlight (effectively parallel rays). Then validate with several u, v pairs and check if 1/f ≈ 1/v + 1/u within experimental error. Identify main error sources (alignment, measuring from lens center, parallax).
- Real-world optics: Explore what changes if you use two lenses in series (like a telescope or microscope). Can you reason how the first lens creates an intermediate image that becomes the “object” for the second?
- Engineering perspective: Investigate why camera lenses aren’t single thin lenses. Research aberrations (spherical, chromatic) and how compound lenses correct them. Tie back to our “paraxial” assumption.
- Interdisciplinary modeling: Build a simple ray-tracing spreadsheet or code: define rays by slope and height, apply refraction rules at the lens plane (using the focus property), and compute intersections to recover the lens equation numerically.

## Reflective insight: the essence of the concept
A convex lens performs a trade between angle and position:
- Rays coming in parallel (zero angle) are brought to a specific position (the focus).
- Rays passing through the lens center keep their direction (angle unchanged), so their straight line encodes where the image must be.

From just these two geometric facts plus similar triangles, everything else falls out:
- The location rule 1/f = 1/v + 1/u comes from making those two rays meet.
- The size rule m = −v/u comes from how a straight line scales height with distance.

The deep “why” is that a lens is a linear, symmetric mapper of rays near the axis: positions and angles transform linearly. That linearity forces these elegant reciprocal relations. Once you grasp this mapping idea, you can confidently tackle unfamiliar optics setups—mirrors, multi-lens systems, or even approximate real cameras—by following rays, enforcing intersections, and checking consistency with dimensions and limits.