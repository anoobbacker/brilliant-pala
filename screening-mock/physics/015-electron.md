# Question
An electron has a circular path of radius $0.01$ m  in a perpendicular magnetic induction $10^{-2}$ T.  Find the speed of the electron:

Options:  
A) $1.76 \times 10^6$ m/s  
B) $1.76 \times 10^5$ m/s  
C) $1.76$ m/s  
D) none

---
# Answer
## Visual and Physical Intuition
- Picture the electron like a tiny charged bead sliding sideways into a magnetic field.
- A magnetic field doesn’t push forward or backward (it does no work); it only deflects the direction of motion, creating a circular path.
- If the sideways “bend” at every instant is just right, the path closes into a circle. That means the magnetic force acts as the centripetal force.

## Creative twists
- Thinking “stronger magnetic field means faster electron.” The field doesn’t speed it up; it only bends the path. Faster just means a larger circle in the same field.
- Mixing up “bigger speed, smaller circle.” That would be true if the inward pull didn’t grow with speed, but the magnetic shove does grow with speed, so the circle grows with speed here.
- Ignoring that electrons are extremely light, so their charge-per-mass is huge. That’s why modest fields can bend them a lot unless they’re moving very fast.
- Mass spectrometers and old CRT TVs use this same idea: beam radius scales with speed (or with voltage accelerating the electron). Engineers steer beams by changing the field or the speed.
- In nature, charged particles spiraling along Earth’s magnetic field lines (auroras) follow the same “sideways shove makes a circle” logic. Adjust the speed or the field, and the spiral radius changes in lockstep.

---

## Deriving the Speed from First Principles

### 1) Why circular motion needs centripetal force
- For uniform circular motion, the velocity’s direction changes continuously, even if its magnitude stays the same.
- The necessary inward (centripetal) acceleration must scale up when:
  - Speed increases (more turn per time),
  - Radius decreases (tighter turn).
- Dimensional analysis: the only combination with units of acceleration (m/s²) from speed v (m/s) and radius r (m) is v²/r. So:

```math
  a_{\text{centripetal}} = \frac{v^2}{r}
```
- The required inward force is:

```math
  F_{\text{centripetal}} = m \frac{v^2}{r}
```

### 2) Magnetic force on a moving charge (perpendicular case)
- Experiments show a magnetic field exerts a force on a moving charge:
  - Proportional to charge q,
  - Proportional to speed v,
  - Proportional to magnetic field strength B,
  - Perpendicular to both v and B, so it changes direction, not speed.
- When v ⟂ B, the magnitude is:

```math
  F_{\text{mag}} = q v B
```

### 3) Set magnetic force = centripetal force
For a circular path caused by the magnetic field:
```math
q v B = m \frac{v^2}{r}
```
Solve for v (cancel one v from both sides):
```math
v = \frac{q B r}{m}
```

This shows:
- v is directly proportional to B (stronger field bends tighter unless speed is higher),
- v is directly proportional to r (bigger circle needs higher speed for same B),
- v is proportional to q/m (lighter and more highly charged particles go faster for the same orbit).

### 4) Dimensional check
- Tesla (T) = kg/(C·s). Then:

```math
  \frac{q B r}{m} \sim \frac{C \cdot \frac{kg}{C \cdot s} \cdot m}{kg} = \frac{m}{s}
```
  Correct units for speed.

---

## Numerical Evaluation

Constants:
- Electron charge: e = 1.602 × 10⁻¹⁹ C
- Electron mass: mₑ = 9.11 × 10⁻³¹ kg
- Magnetic field: B = 1.00 × 10⁻² T
- Radius: r = 1.00 × 10⁻² m

Compute using v = (qBr)/m:
```math
v = \frac{(1.602 \times 10^{-19}\ \text{C})(1.00 \times 10^{-2}\ \text{T})(1.00 \times 10^{-2}\ \text{m})}{9.11 \times 10^{-31}\ \text{kg}}
```
Group powers of ten and numbers:
```math
v \approx \frac{1.602 \times 10^{-23}}{9.11 \times 10^{-31}}
= \left(\frac{1.602}{9.11}\right) \times 10^{8}
\approx 0.176 \times 10^{8}
= 1.76 \times 10^{7}\ \text{m/s}
```

- This is about 5.9% of the speed of light (non-relativistic, so our classical formula is valid).

Answer: 1.76 × 10⁷ m/s → not listed in the options ⇒ D) none.

---

## Alternative Perspective (Same Physics, Different Lens)

- Angular (cyclotron) frequency: the circular motion implies v = ωr.
- From force balance qvB = m v²/r, divide both sides by v r: qB/m = v/r = ω.

```math
  \omega = \frac{qB}{m}, \qquad v = \omega r = \frac{q B}{m} r
```
- Frequency f = ω/(2π) = qB/(2πm), then v = 2π r f.
- Plugging in gives the same v ≈ 1.76 × 10⁷ m/s.

Real-world link: This is exactly how cyclotrons and mass spectrometers measure q/m or control particle speeds.

---

## Why the Options Don’t Match

- Our physics and units check out.
- Both r and B are 10⁻², so their product is 10⁻⁴; multiplying by e/m ≈ 1.76 × 10¹¹ gives ≈ 1.76 × 10⁷ m/s.
- None of A, B, or C is close. So D) none is the correct choice.

---

## Conceptual Follow-up Questions

1. If we doubled the magnetic field while keeping the radius the same, how would the speed change?
2. If the particle had the same speed and magnetic field but twice the radius, what would that imply about its mass or charge?
3. What happens if the velocity is not exactly perpendicular to the magnetic field?
4. Does a magnetic field do work on the electron? Why or why not?

---

## Application Questions

1. Mass spectrometers use curved paths in magnetic fields to separate ions. Explain how measuring radius at a known B and v lets you find the mass-to-charge ratio m/q.
2. In a cyclotron, the frequency depends only on q/m and B, not on the radius. Why is that helpful for accelerating particles to high energies?
3. The aurora is caused by charged particles spiraling along Earth’s magnetic field lines. How does v = (qBr)/m help you estimate the curvature scale of their paths?

---

## Common Misconceptions and Traps

- Mixing units: forgetting to convert cm to m or gauss to tesla. Here both r and B are in SI, which is required.
- Thinking magnetic fields change speed: they don’t. The force is perpendicular to v, so it redirects but does not speed up or slow down.
- Using wrong mass: electron mass is 9.11 × 10⁻³¹ kg, not the proton’s mass (~1836 times larger).
- Forgetting v must be perpendicular to B for F = qvB to be the full magnitude; otherwise use F = qvB sinθ.
- Arithmetic slip with powers of ten: notice B × r = 10⁻² × 10⁻² = 10⁻⁴ before multiplying by e/m.

---

## Extension Challenges

1. Derive the time period T of the circular motion and show it is independent of speed and radius for non-relativistic motion. Then compute T and f for this electron.
2. Consider relativistic speeds: if v becomes a significant fraction of c, how does the increased relativistic mass (inertia) change the radius for the same B?
3. Suppose an ion with unknown charge q and mass m enters the same field and traces a radius of 2 cm at the same speed. What can you infer about q/m compared to the electron?
4. Design a lab: Given a Helmholtz coil to create a known B and a way to measure the radius of an electron beam, outline a procedure to estimate e/m.

---

## Reflective Insight: The Essence

Magnetic fields don’t inject energy into a charged particle; they steer it. That steering becomes a perfect circle when the sideways magnetic push exactly supplies the inward (centripetal) force needed for the turn. From this simple balance, v = (qBr)/m falls out naturally. The beauty is in its proportionality: bigger fields or bigger circles require higher speeds; lighter or more highly charged particles are more easily “bent” and thus must move faster for the same circle. This single idea underlies cyclotrons, mass spectrometers, and even space physics, letting us read nature’s “fingerprints” of charge, mass, and motion from curved tracks.

Final answer: v ≈ 1.76 × 10⁷ m/s → D) none.
