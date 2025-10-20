# Question
The radius of curvature of a convex mirror is 25cm. Calculate its focal length  
1) 12.5 cm  
2) 50 cm  
3) 30 cm  
4) 25 cm

## See the idea before the formula

Think of a shop’s dome mirror (convex). It makes your reflection look smaller because it spreads light out — rays bounce as if they’re coming from a point behind the mirror. That “as-if” point is the focal point of a convex mirror.

“Radius of curvature” is the radius of the big imaginary sphere the mirror is part of. If you completed the mirror into a full sphere, its center is the center of curvature, and the radius of that sphere is R.

---

## Why is f = R/2? Build it from the bounce rule

Start from the only law you need: angle of incidence equals angle of reflection.

- At any point on a spherical mirror, the normal (the “straight-out” line) points to the center of curvature C.
- Consider a ray coming in parallel to the axis. It hits the mirror at a small height h from the axis.
- The normal at that point is tilted by a small angle θ from the axis (because the mirror is part of a circle of radius R).
- The incoming ray makes an angle θ with the normal, so it reflects making the same angle on the other side. That means the reflected ray is tilted by about 2θ from the axis.
- Small-angle geometry links these pieces:
  - The height h is approximately h ≈ Rθ.
  - The reflected ray meets (or appears to meet) the axis at the focus F, so tan(2θ) ≈ 2θ ≈ h/f.

Put these together:

```math
\tan(2\theta) \approx 2\theta \approx \frac{h}{f}
\quad\text{and}\quad
h \approx R\theta
```

So:

```math
\frac{R\theta}{f} \approx 2\theta \quad\Rightarrow\quad f \approx \frac{R}{2}.
```

This works for both concave and convex spherical mirrors (same magnitude). For a convex mirror, the focus is virtual (behind the mirror), but its distance from the pole is still half the radius of curvature.

---

## Solve the problem

Given radius of curvature R = 25 cm:

```math
f = \frac{R}{2} = \frac{25\ \text{cm}}{2} = 12.5\ \text{cm}.
```

Answer: 1) 12.5 cm

Note on sign: Many IGCSE questions just want the magnitude. If your course uses sign conventions, the convex mirror’s focus is virtual and lies behind the mirror.

---

## Visual aid (in words)

- Draw a horizontal line (principal axis). Put the mirror at the center with its shiny side facing left (convex bulge toward the left).
- Mark C to the right (behind the mirror), a distance R from the mirror’s pole P.
- A ray from the left, parallel to the axis, hits the mirror above the axis. The normal at that point points to C.
- The reflected ray goes upward, diverging, but if you extend it backward, it meets the axis at F, halfway between P and C (so PF = R/2).

---

> ### 🧠 Quick Exam Tips
> - For any spherical mirror: focal length magnitude f = R/2.
> - Convex mirror: focus is virtual (behind the mirror).
> - Radius and focal length have the same unit; dividing by 2 keeps units right.

---

## Conceptual follow-ups
- What if R doubles? Then f doubles. If R = 50 cm, f = 25 cm.
- What if we use a concave mirror with R = 25 cm? Magnitude is the same: |f| = 12.5 cm, but the focus is real (in front of the mirror).

## Real-world link
- Car side mirrors are convex. A smaller radius of curvature means a shorter focal length, which spreads rays more and gives a wider field of view (but smaller images).

## Misconception clinic
- Many students think “convex mirrors don’t have a focus.” Actually, they do — it’s a virtual focus. Rays appear to come from there; they don’t actually meet.
- A common mistake is mixing up lenses and mirrors: For thin lenses, f is not generally R/2 because lenses have two surfaces and refractive indices matter.

## Quick practice
1) A convex mirror has R = 40 cm. What is f?
2) A spherical mirror has f = 15 cm. What is R? Is the focus real or virtual if it’s convex?

Answers:
1) f = 20 cm.
2) R = 30 cm; if convex, focus is virtual.

> ### 🌱 Reflective essence
> Nature loves symmetry: when reflection doubles the angle, the geometry halves the distance. That’s why, for a spherical mirror, the focus sits at half the radius.