## Question
Consider two spherical planets of same average density. Planet 2 is 8 times as massive as planet. The ratio of the acceleration due to gravity on the second planet to that on the first is

---
# Answer
## Quick visual solution

- Picture planet 2 as a scaled-up twin of planet 1, made of the same stuff (same “crowdedness” of material).  
  Eight times the mass means you’ve scaled every length by 2, because doubling height, width, and depth multiplies “stuff” by 2×2×2 = 8.

- Gravity at the surface is like the crowding of invisible pull-threads coming out of the planet.
  - More stuff → more threads: 8 times as many.
  - But the surface you stand on is now a bigger skin. Doubling size makes the skin area 4 times larger (twice as tall and twice as wide).
  - Thread crowding at the surface = threads spread over skin = eight divided by four = two times as dense.

- More thread-crowding means stronger pull. So surface gravity doubles.

Answer: g on planet 2 : g on planet 1 = 2 : 1.

## Creative twists
- Seeing “8 times mass” and forgetting you’re also standing farther out on a bigger planet.
- Mixing up how area and volume scale: doubling size makes volume 8× but area only 4×.
- Thinking “same density ⇒ same gravity” without noticing the larger radius.
- Light analogy: A bigger lantern with 8 times more bulbs but a globe twice as big spreads light over 4× the surface—brightness at the surface doubles.
- Field-line picture in engineering: More source (mass/charge) gives more lines; enlarging the object spreads lines over a bigger skin. Line density at the surface tells you the “pull” or “push.”

## Restating the problem in simple words
Two spherical planets are made of the same “stuff” (same average density). Planet 2 has 8 times the mass of Planet 1. How many times stronger is the surface gravity on Planet 2 compared to Planet 1?

We’ll build the answer from scratch, using physical reasoning before any formulas.

---

## Step-by-step reasoning from first principles

### 1) What sets the strength of gravity at a planet’s surface?
- Everyday sense: A planet pulls you down. The bigger the planet (more mass), the stronger the pull. But if you’re farther away from its center (larger radius), the pull gets weaker.
- Newton’s idea: The gravitational pull between a planet of mass M and a small object of mass m at distance R from its center is:

```math
F = \frac{G M m}{R^2}
```

- Why this makes sense:
  - Proportional to M: more mass → stronger pull.
  - Inversely proportional to R²: spread-out influence (like light intensity fading with distance) over the surface of an expanding sphere.
  - For a spherical planet, the planet acts as if all its mass is concentrated at the center (shell symmetry).

- The acceleration (gravity) you feel at the surface is force per unit mass:

```math
g = \frac{F}{m} = \frac{G M}{R^2}
```

This is the surface gravity.

### 2) How are mass, radius, and density connected?
If two planets are made of the same “stuff,” they have the same average density ρ. Density means mass per volume:

```math
\rho = \frac{M}{V}
```

A sphere of radius R has volume:

```math
V = \frac{4}{3}\pi R^3
```

So:

```math
M = \rho V = \rho \left(\frac{4}{3}\pi R^3\right)
```

This says: at fixed density, mass grows with the cube of the radius.

### 3) Combine the ideas to express g in terms of density and radius
Plug M = ρ(4/3)πR³ into g = GM/R²:

```math
g = \frac{G\,(\rho \,\frac{4}{3}\pi R^3)}{R^2} 
  = \left(\frac{4}{3}\pi G \rho\right) R
```

Key insight: If density ρ is the same, surface gravity g is directly proportional to radius R.

- Dimensional check:
  - [G] = m³/(kg·s²), [ρ] = kg/m³, [R] = m → GρR has units m/s². Good.

### 4) Apply to the given masses
We are told Planet 2 has 8 times the mass of Planet 1: M₂ = 8M₁. With the same density:

```math
M \propto R^3 \quad \Rightarrow \quad R \propto M^{1/3}
```

So:

```math
R_2 = R_1 \cdot (M_2/M_1)^{1/3} = R_1 \cdot 8^{1/3} = 2 R_1
```

Now use g ∝ R (for same ρ):

```math
\frac{g_2}{g_1} = \frac{R_2}{R_1} = 2
```

You can also compute it directly from g = GM/R²:

```math
\frac{g_2}{g_1} = \frac{G M_2 / R_2^2}{G M_1 / R_1^2}
= \frac{M_2}{M_1}\left(\frac{R_1}{R_2}\right)^2
= \frac{8}{(2)^2} = \frac{8}{4} = 2
```

So Planet 2’s surface gravity is twice that of Planet 1.

---

## Final answer
```math
\boxed{\dfrac{g_2}{g_1} = 2}
```

---

## Multiple ways to see it (flexible thinking)

- Algebraic (used above): Combine g = GM/R² with M = ρ(4/3)πR³ → g ∝ ρR → same ρ ⇒ g ∝ R. Since M₂ = 8M₁ ⇒ R₂ = 2R₁ ⇒ g₂/g₁ = 2.
- Scaling intuition: Doubling radius at the same density makes volume (and mass) 8 times bigger. Gravity at the surface scales like mass divided by radius squared: 8/(2²) = 2.
- Proportional to mass’s cube root: For fixed ρ, R ∝ M^{1/3}, hence g ∝ M/R² ∝ M/M^{2/3} = M^{1/3}. Then g₂/g₁ = (8)^{1/3} = 2.

---

## Real-world connection
The formula we found for constant density,

```math
g = \left(\frac{4}{3}\pi G \rho\right) R,
```

explains why larger planets of similar density have stronger gravity. For example, Earth vs Moon:

```math
\frac{g_E}{g_M} \approx \frac{\rho_E}{\rho_M}\cdot \frac{R_E}{R_M}
\approx \frac{5.51}{3.34} \cdot 3.67 \approx 6.05,
```

matching the observed ratio ~6. This shows how density and size both matter.

---

## Conceptual follow-up questions
1. If two planets have the same radius but Planet A is denser, which has greater g? By what factor?
2. If a planet’s radius doubles but its mass stays the same (not realistic, but a thought experiment), what happens to g?
3. If M increases by a factor k and density stays the same, by what factor does g change?
4. If density doubles while radius halves, how does g change?

---

## Application questions
- Planet design concept: If engineers imagine building a rotating space habitat, why does the artificial “gravity” felt at the rim depend on the radius (similar to g ∝ R for fixed ρ)?
- Exoplanet inference: Astronomers estimate an exoplanet’s mass and radius. How can the relation g = GM/R² help predict whether it can hold an atmosphere?
- Geophysics: How do changes in Earth’s average density (e.g., due to iron core) explain why Earth’s g is higher than a same-sized rocky planet with lower density?

---

## Common misconceptions and how to avoid them
- Mistake: “If mass is 8 times bigger, gravity is 8 times bigger.” Fix: Remember distance from the center also changes; at the surface you’re farther away on a bigger planet.
- Mistake: Forgetting that for same density, R ∝ M^{1/3}, not R ∝ M. Volumes scale with the cube of size.
- Mistake: Mixing up area and volume scaling. Area ∝ R², volume ∝ R³. Keep the “square vs cube” straight.

---

## Extension challenges
- Derive g purely in terms of density and mass: eliminate R to get g ∝ G M^{1/3} ρ^{2/3} and check dimensions.
- Suppose Planet B’s density is 3 times Planet A’s, but radius is half. Compute g_B/g_A.
- If you compress a planet (increase density) without changing its mass, what happens to g at the new surface? Explain physically.
- Given an exoplanet with g measured and radius known, estimate its average density.

---

## Reflective insight — the deep “why”
Surface gravity balances two effects:
- More mass pulls harder.
- But a bigger planet puts you farther from the center.

For planets of the same density, mass grows like R³ while distance weakens gravity like 1/R². The net effect is linear: g ∝ R. That single insight explains the whole problem and lets you reason about any scaled planet without memorizing formulas.