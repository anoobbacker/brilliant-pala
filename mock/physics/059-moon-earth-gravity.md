## Question
The mass of moon is $1 \%$ of the mass of earth. The ratio of gravitational pull of the earth on moon to  that of the moon on earth will be

**Options:**

1. $1: 1$
2. $1: 10$
3. $1: 100$
4. $2: 1$

## Big idea in plain words
When two things interact, the “pull” or “push” is a partnership: each object affects the other equally strongly but in opposite directions. You feel the wall push you as hard as you push the wall. Gravity is just this mutual pull acting at a distance. So Earth and Moon pull on each other with equal force. What differs is how much each one accelerates (lighter objects accelerate more under the same force).

## Build-up from first principles

### 1) Everyday observation → Mutual interactions
- If you push a heavy fridge, you feel it push back on your hands.
- In skating, two people push off each other and move apart; the lighter one speeds up more.
- Why? If the forces weren’t equal and opposite, the pair’s center of mass would start moving by itself from internal pushes—like a car speeding up with no engine. That would violate conservation of momentum. So internal forces must come in equal-and-opposite pairs.

This is the deep reason behind Newton’s third law: for isolated pairs, forces are equal in magnitude and opposite in direction.

### 2) What sets “how strong” gravity is?
Let’s reason without memorizing formulas.

- Influence grows with each mass:
  - If you double the Moon’s mass, there’s twice as much “stuff” to pull on (so force should double).
  - If you double Earth’s mass, there’s twice as much “source” of gravity (so force should also double).
  - Together, this says force is proportional to the product of masses: $F \propto m_1 m_2$.

- Influence weakens with distance:
  - Imagine gravity spreading out uniformly in space. The surface area of a sphere grows as $4\pi r^2$.
  - If the same “influence” spreads over a larger sphere, the intensity at distance r should thin out like $1/r^2$.
  - So $F \propto 1/r^2$.

Putting these together, the only simple way consistent with symmetry and experiments is
```math
F \propto \frac{m_1 m_2}{r^2}.
```
To turn “proportional to” into “equals,” nature supplies a constant $G$ (measured by Cavendish). Thus,
```math
F = G\,\frac{m_1 m_2}{r^2}.
```
Notice this expression is perfectly symmetric in $m_1$ and $m_2$. That symmetry is the mathematical echo of the physical fact: each pulls the other with the same magnitude.

### 3) Apply to Earth and Moon
Let $M_E$ be Earth’s mass and $M_M$ be Moon’s mass. The force on the Moon due to Earth is
```math
F_{E\;\text{on}\;M} = G\,\frac{M_E M_M}{r^2}.
```
The force on the Earth due to the Moon is
```math
F_{M\;\text{on}\;E} = G\,\frac{M_M M_E}{r^2}.
```
These are the same number. So the ratio is
```math
\frac{F_{E\;\text{on}\;M}}{F_{M\;\text{on}\;E}} = 1.
```

Therefore, the gravitational pull of Earth on Moon and of Moon on Earth have equal magnitude.

- Given: Moon’s mass is 1% of Earth’s mass ($M_M = 0.01 M_E$).
- That affects accelerations, not force:
  - Same force on both, but $a = F/m$, so
    ```math
    \frac{a_{\text{Moon}}}{a_{\text{Earth}}} = \frac{M_E}{M_M} \approx 100.
    ```
  - The Moon accelerates about 100 times more than Earth, which is why Earth only “wobbles” slightly while the Moon orbits.

## Final answer
Option 1: 1 : 1

## Multiple perspectives (to deepen understanding)

- Momentum/center-of-mass argument:
  - In an isolated Earth–Moon system, if the forces weren’t equal and opposite, the center of mass would accelerate without any external push. That contradicts momentum conservation. Thus, forces must be equal in magnitude.

- Field viewpoint:
  - Earth creates a gravitational field $g_E = G M_E / r^2$ at the Moon; force on Moon is $M_M g_E$.
  - Moon creates a field $g_M = G M_M / r^2$ at the Earth; force on Earth is $M_E g_M$.
  - Both give $F = G M_E M_M / r^2$.

## Conceptual follow-up questions
1. If the Moon had half its current mass, how would the force magnitudes compare? Would they still be equal? What would change instead?
2. If the Earth–Moon distance doubled, what happens to the force on each? By what factor?
3. If two identical stars orbit each other, how do their forces and accelerations compare?
4. Why don’t the equal and opposite forces “cancel out” to make zero motion?

## Application questions
- How does the equal-force principle explain the location of the Earth–Moon barycenter (the point they both orbit around)?
- In binary star systems, how does mass ratio determine wobble amplitude used to detect exoplanets?
- How do equal gravitational forces but different accelerations affect tidal forces and ocean tides on Earth?

## Common misconceptions and how to avoid them
- “The heavier object pulls harder.” Reality: Forces are equal; accelerations differ. Remember $F$ is the same, but $a = F/m$.
- “Action and reaction cancel.” They act on different bodies; they can’t cancel each other’s effect on the same object.
- “Only the smaller object orbits.” Both orbit their common center of mass; the heavier one just moves less.

## Extension challenges
1. Using $M_M = 0.01 M_E$, estimate how far from Earth’s center the barycenter lies as a fraction of the Earth–Moon separation. Hint: $r_E = \dfrac{M_M}{M_E + M_M}\,R$.
2. Derive the acceleration ratio $a_{\text{Moon}}/a_{\text{Earth}}$ from the equal-force idea alone, without using any gravitational formula.
3. For a hypothetical planet 5 times Earth’s mass and at the same Earth–Moon distance, compare the force and acceleration of the Moon.

## Reflective insight
The essence: Interactions are mutual, and nature guards momentum. Gravity doesn’t pick favorites; it links masses symmetrically. Equal forces with different accelerations is the signature of that symmetry. Understand that, and you can reason about any two-body interaction—planets, stars, or skaters on ice—with confidence.