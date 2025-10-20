# Question
A particle is taken to a height equal to the Earth’s radius, R, above the Earth’s surface. What is the acceleration due to gravity at that height?

Options:
- A) 19.6 m/s²
- B) 2.45 m/s²
- C) 9.8 m/s²
- D) 4.9 m/s²

# Answer

## Build-from-first-principles reasoning

### 1) What “gravitational strength” means
- The acceleration due to gravity at a distance r from Earth’s center is the “gravitational field” $g(r)$ experienced by a unit mass.
- Physically: if you place a small mass m at distance r, the Earth pulls it inward; the acceleration is $g(r)$.

---

### 2) Why gravity weakens with distance (geometric/flux intuition)
- Imagine gravity as “influence lines” or field lines spreading out from Earth uniformly in all directions.
- As you move away from Earth, the same total number of lines must spread across the surface of a bigger sphere centered on Earth.
- The area of a sphere of radius r is $4\pi r^2$. So the “density” of field lines (and hence the field strength) must scale as $1/r^2$.
- Therefore, $g(r) \propto 1/r^2$.

This is the same inverse-square pattern seen in light intensity from a bulb: double the distance → brightness becomes one-quarter.

---

### 3) From proportionality to equation (introducing the constant G)
Experimentally (Cavendish experiment and planetary motion analysis) we find the exact law:
```math
g(r) = \frac{GM}{r^2}
```
- M is Earth’s mass.
- G is the universal gravitational constant.

Dimensional check:
- [G] = L^3/(M·T^2)
- Multiply by M → L^3/T^2
- Divide by r^2 (L^2) → L/T^2, which matches acceleration.

---

### 4) Use a ratio to avoid unknowns
Let $R$ be Earth’s radius and $g_0$ be gravity at Earth’s surface:
```math
g_0 = \frac{GM}{R^2} \approx 9.8\ \text{m/s}^2
```
At height $h = R$ above the surface, the distance from Earth’s center is:
```math
r = R + h = R + R = 2R
```
So
```math
g(2R) = \frac{GM}{(2R)^2} = \frac{GM}{4R^2} = \frac{1}{4}\cdot \frac{GM}{R^2} = \frac{g_0}{4}
```
Numerically:
```math
g(2R) = \frac{9.8}{4} = 2.45\ \text{m/s}^2
```

Answer: B) 2.45 m/s²

---

## Multiple approaches (to strengthen understanding)

### A) Proportional reasoning only
- Gravity ∝ 1/r².
- Double the distance from Earth’s center (R to 2R) → gravity becomes one-quarter.

### B) Analytical formula
- Use $g(r) = GM/r^2$ and $g_0 = GM/R^2$.
- Take ratio: $g(2R)/g_0 = (R^2)/(2R)^2 = 1/4$.

### C) Real-world check (satellites)
- At about 6400 km above the surface (roughly R), gravity is not zero; it’s still 2.45 m/s².
- This is why satellites in high orbits still “fall” around Earth—they are in continuous free-fall, just moving sideways fast enough to miss Earth.

---

## Final Answer
B) 2.45 m/s²

---

## Conceptual follow-up questions
1) If you go to a height where your distance from Earth’s center is 3R, what is $g$ there in terms of $g_0$?  
2) If $g$ at some height is one-ninth of $g_0$, what is your distance from Earth’s center (in units of R)?  
3) If Earth’s radius doubled but mass stayed the same, how would surface gravity change?

---

## Application questions
1) GPS satellites orbit at about 20,000 km above Earth’s surface. Estimate the gravitational acceleration they experience, using the $1/r^2$ law.  
2) Why do astronauts in the International Space Station feel weightless even though $g$ there is still close to 9 m/s²? Explain using free-fall and orbits.  
3) How would engineers use the $1/r^2$ dependence to plan fuel requirements for missions to geostationary orbit vs low Earth orbit?

---

## Common misconceptions and reasoning traps
- “Gravity is zero in space.” False: even at large altitudes, gravity is significant; it just decreases with distance as $1/r^2$.  
- “Use $g \propto 1/h^2$ with h = height above surface.” Wrong reference: the correct distance is from the center, $r = R + h$.  
- “Gravity decreases linearly with height.” Not outside Earth. The linear approximation applies only for small height changes relative to R (and different reasoning inside Earth).

---

## Extension challenges
1) Derive the orbital speed at r = 2R from $g(r)$ by equating centripetal acceleration $v^2/r$ to $g(r)$.  
2) For another planet with mass 8M and radius 2R, compare its surface gravity to Earth’s using $g \propto M/R^2$.  
3) Suppose Earth were twice as dense but with the same radius. How would $g_0$ change? Connect to $M = \rho \cdot \frac{4}{3}\pi R^3$.  
4) Use energy: compare gravitational potential energies at R and 2R, and relate the slope of potential vs r to the magnitude of $g$.

---

## Reflective insight
The essence: gravity’s strength is governed by geometric spreading from a central source—what matters is how the same “influence” distributes over expanding spherical surfaces. That simple 1/r² geometry, combined with mass as the source strength, explains why doubling distance quarters gravity. Once you see the geometry, you can predict gravity anywhere without memorization: think “distance from center” and “inverse-square.”