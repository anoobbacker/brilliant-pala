## Question
The minimum separation between object and its real image in cm for a concave mirror of focal length 5 cm is

---
# Answer
## Visual solution (no formulas)
- Picture a concave mirror. When the object is very far, the real image forms near the focus — they’re far apart.
- Slide the object closer. The image moves away from the mirror; the two creep toward each other along the same side.
- At the special spot where rays hit the mirror and come straight back (the mirror’s “center of curvature”), the image lands exactly on the object. They overlap.
- Move past that spot (but still outside the focus) and they separate again; go inside the focus and the image turns virtual (not allowed here).

So the smallest possible gap between the object and its real image is zero — they coincide at the center of curvature.

Answer: 0 cm

## Creative twists
- Mixing up mirrors with lenses: for a lens the object and real image are on opposite sides, so the smallest gap isn’t zero; for a concave mirror they can sit on the same spot.
- Thinking “real images can’t overlap the object.” They can: the mirror sends every ray back through the source at the center of curvature.
- Being lured by the given focal length and trying to compute something fancy. Here, the minimum gap doesn’t depend on the number.
- Lens version: With a convex lens, the object and real image lie on opposite sides. The shortest total span happens when they’re symmetrically placed — a different outcome than the mirror case.
- Engineering echo: Put a light at a concave mirror’s center of curvature; the reflected beam retraces its path and returns to the source. That “image at the source” is exactly the zero-separation situation used for optical alignment.

## Goal
Find the minimum possible distance between an object and its real image formed by a concave mirror with focal length 5 cm.

## Intuition first: how could the image ever “touch” the object?
- Think of a shiny concave spoon focusing sunlight to a point. That point is the mirror’s focus F.
- Now imagine putting a small LED at a special location called the center of curvature C (twice the focal length, 2f). Rays from the LED hit the mirror and reflect straight back onto themselves because at C they hit the mirror perpendicularly (normal incidence). So the light reconverges exactly where it started.
- That means the real image forms right on top of the object when the object is at C. So it’s reasonable to suspect the minimum separation could be zero.

We’ll now derive this result from first principles.

## Rebuilding the mirror formula from scratch (no memorized formulas)
Set up:
- Let P be the pole (the center of the mirror surface), and the principal axis be the horizontal line through P.
- Let C be the center of the sphere of which the mirror is a part; PC = R is the radius of curvature.
- Let F be the focal point; we’ll discover that PF = f = R/2.
- Put a small object point O at distance u from P on the principal axis (in front of the mirror).
- Its image I forms at distance v from P (also in front, for a real image).
- Consider a paraxial ray (close to the axis) from O that strikes the mirror at a point very near P, at height h above the axis.

Key small-angle geometry:
- The normal to the mirror at that point points to C, making a small angle θ with the axis. For small h, tanContinuing…

- The normal to the mirror at that point points to C, making a small angle θ with the axis. For small h, tan θ ≈ θ ≈ h/R.
- The incident ray from O makes a small angle α with the axis. For small h, tan α ≈ α ≈ h/u.
- The reflected ray toward I makes a small angle β with the axis. For small h, tan β ≈ β ≈ h/v.

Law of reflection (angle of incidence = angle of reflection) in small-angle form:
- The normal bisects the angle between the incident and reflected rays. So the normal’s angle equals the average of α and β:
  

```math
  \theta = \frac{\alpha + \beta}{2}
  ```
  
  Multiply both sides by 2:
  

```math
  \alpha + \beta = 2\theta
  ```

Substitute the small-angle relations:
```math
\frac{h}{u} + \frac{h}{v} = 2\,\frac{h}{R}
```
Divide by h (not zero):
```math
\frac{1}{u} + \frac{1}{v} = \frac{2}{R}
```

Define focal length f:
- Parallel rays (object “at infinity”: u → ∞) must focus at F (distance v = f). Plugging u → ∞ gives 1/v = 2/R, so:
  

```math
  f = \frac{R}{2}
  ```

Hence the mirror formula becomes:
```math
\frac{1}{u} + \frac{1}{v} = \frac{1}{f}
```

Notes:
- We treated distances u, v, f as positive lengths measured from the mirror to the left (incoming side). For a concave mirror, this yields real images for u > f.

## What is the “separation” and how to minimize it?
- For a concave mirror, both the object and its real image lie on the same side of the mirror. So their separation along the axis is the absolute difference:
  

```math
  s = |u - v|
  ```

- Constraint linking u and v:
  

```math
  \frac{1}{u} + \frac{1}{v} = \frac{1}{f}, \quad u > f, \ v > 0
  ```

### Approach 1 (symmetry logic)
- The equation is symmetric in u and v. The function s = |u − v| is minimized when u = v.
- Set u = v in the constraint:
  

```math
  \frac{1}{u} + \frac{1}{u} = \frac{1}{f} \;\Rightarrow\; \frac{2}{u} = \frac{1}{f} \;\Rightarrow\; u = 2f
  ```
  
  Then v = 2f too, so
  

```math
  s_{\min} = |u - v| = |2f - 2f| = 0
  ```

### Approach 2 (algebra + calculus check)
- From the mirror equation,
  

```math
  \frac{1}{v} = \frac{1}{f} - \frac{1}{u} = \frac{u - f}{uf}
  \;\Rightarrow\;
  v = \frac{uf}{u - f}
  ```
- Then
  

```math
  s = |u - v| = \left|u - \frac{uf}{u - f}\right| 
              = \left|\frac{u(u - f) - uf}{u - f}\right|
              = \left|\frac{u(u - 2f)}{u - f}\right|
  ```
- For u > f, the denominator is positive. The absolute value is minimized when the numerator is zero, i.e., u = 2f, giving s = 0. This is indeed the minimum because s ≥ 0 always.

### Approach 3 (physical picture)
- At the center of curvature C (distance R = 2f), each ray leaves O, hits the mirror perpendicularly, and returns along its own path. So all rays reunite at O. The image overlaps the object: separation is zero.

## Numerical answer for f = 5 cm
```math
s_{\min} = 0 \text{ cm}
```

## Why this is physically OK
- A “real image” means light actually converges to a point in space. If the object is at C, the convergence point is at the object itself. The image exists but is superimposed on the object. You may not “see” a separate image because it coincides with the object, but optically it is a valid real image.

## Dimensional and reasonableness checks
- Mirror formula: 1/u + 1/v = 1/f. Each term has units 1/length. Consistent.
- Symmetry: Swapping object and image distances doesn’t change the formula. The “closest” they can be is when they’re equal.
- Limiting cases: As u → ∞, v → f. As u → f+, v → ∞. The separation spans from very large to potentially zero, consistent with the curve.

## Simple experiment you can do
- Take a concave shaving mirror. Put a small bright LED on the axis. Move the LED until its sharp real image forms at the same spot as the LED (you’ll notice reflected light sending back a bright, focused glow onto the LED). This happens near 2f (the center of curvature). The image sits on the object.

---

## Conceptual follow-up questions
1. If the image is to be real and located twice as far from the mirror as the object, where must the object be placed relative to f?
2. If the object is just beyond the focal length (u slightly > f), why does the image distance v become very large?
3. If you move the object from ∞ to f, how does the separation |u − v| change qualitatively?
4. For a convex mirror (which only forms virtual images), is there any real-image separation to minimize? Why not?

## Application questions
- Headlights and solar cookers: Why do designers place the light source close to the focal region? What happens if you place it exactly at C instead?
- Satellite dishes: The feed antenna sits near the focus. How would the performance change if you misplace it toward 2f instead of f?
- Optical testing: Why is placing a point source at the center of curvature useful for testing mirror figure (rays should retroreflect precisely)?

## Common misconceptions and reasoning traps
- “Minimum separation must be 2f or 10 cm.” That’s for a convex lens where object and real image lie on opposite sides, so separation is u + v, minimized at 4f. For a concave mirror, both are on the same side, so separation is |u − v|, minimized at 0.
- “An image can’t form where the object is.” It can—if rays reconverge to those object points. The image overlaps the object; it’s still a real image.
- “Sign conventions change the answer.” Different sign conventions may flip signs in intermediate steps, but a physically measured separation is non-negative and here reaches 0 at u = v = 2f.

## Extension challenges
1. Lens vs mirror contrast: Derive from first principles the minimum object–image distance for a thin convex lens and show it equals 4f. Explain the difference from mirrors using ray geometry.
2. Non-paraxial effects: For larger apertures (not small angles), spherical aberration means not all rays focus at the same point. How would this affect the idea of “image coinciding with the object” at C?
3. Variable focal length system: Suppose you have a mirror with adjustable curvature (adaptive optics). How would the minimum separation change as you vary f while keeping the object fixed?
4. Mixed system: An object in front of a concave mirror with a thin lens inserted between object and mirror. How does the lens shift the position of the image and change the minimum possible separation?

## Reflective insight
The essence is symmetry and geometry: for a concave mirror, the object and its real image share the same side of the mirror, and the mirror equation is symmetric in object and image distances. The “closest” two symmetric quantities can get—under a fixed reciprocal sum—is when they’re equal. That equality (u = v) selects the center of curvature (u = v = 2f), where every ray retraces its path, making the image coincide with the object. Understanding this symmetry lets you generalize confidently to new setups, such as why lenses give a minimum of 4f instead of 0.
