# Question
A cube of side 0.2 m rests on the floor, as
shown. Given that the cube has a mass of 100 kg , the pressure exerted by the
cube on the floor is ____ . (Take $\mathrm{g}=10 \mathrm{~N}
\mathrm{~kg}^{-1}$ )

```
        +---------+
       /         /|
      /         / |
     +---------+  |
     | 100kg   |  |
     |         |  +
     |         | /
     +---------+
        0.2 m
```

**Options:**

1. $15000 \mathrm{Nm}^{-2}$
2. $25000 \mathrm{Nm}^{-2}$
3. $22500 \mathrm{Nm}^{-2}$
4. $12500 \mathrm{Nm}^{-2}$

## Problem restatement (in everyday terms)
You place a heavy cube on the floor. How “hard” does it press on the floor? Intuitively:
- A heavier object presses harder.
- A larger contact area spreads the push out, so each bit of floor feels less.

That “how hard per unit area” is what physics calls pressure.

Given:
- Cube side: 0.2 m (so it sits on a square face)
- Mass: 100 kg
- Gravitational field: g = 10 N/kg
- Find the pressure the cube exerts on the floor.

## Build from first principles

### 1) What is pressure, and why is it defined as force per area?
Imagine dividing the floor under the cube into many tiny equal squares. The cube’s push (its weight) must be shared among these squares. If you double the number of squares (double the area), each gets half as much push. That’s a direct proportionality: more area → less push per square.

So we define pressure P as the “push per area.” If a small patch of area ΔA feels a push ΔF, and the distribution is uniform, then ΔF ∝ ΔA. The constant of proportionality is P:

```math
\Delta F = P\,\Delta A \quad\Rightarrow\quad F = P\,A \quad\Rightarrow\quad P = \frac{F}{A}
```

Units check: N divided by m² gives N/m², also called pascals (Pa).

Mental model: Snowshoes vs stiletto heels — same person (same force), but larger area spreads the force, reducing pressure.

---

### 2) What force is the cube applying? (Its weight from gravity)
The gravitational field g tells how much force each kilogram feels.

- g = 10 N/kg means “each kg weighs 10 N here.”
- The cube’s weight W = m × g.

```math
W = mg = (100\ \text{kg})(10\ \text{N/kg}) = 1000\ \text{N}
```

Units: kg × (N/kg) = N. Good.

---

### 3) What is the contact area?
The cube sits on one square face of side 0.2 m. Area of a square is side²:

```math
A = (0.2\ \text{m})^2 = 0.04\ \text{m}^2
```

---

### 4) Compute the pressure
Use the first-principles relation P = F/A with F = W:

```math
P = \frac{W}{A} = \frac{1000\ \text{N}}{0.04\ \text{m}^2} = 25{,}000\ \text{N/m}^2
```

This is 25,000 Pa (25 kPa).

Answer choice: 2) 25000 Nm⁻².

---

## Why this makes sense (quick intuition + unit check)
- If the cube had the same weight but a larger base, P would decrease (spread out more).
- If the cube had the same base but more mass, P would increase (more push).
- Units: N/m² is exactly pressure. Everything is consistent.

Bonus sanity check: 25,000 Pa is about a quarter of atmospheric pressure (~101,325 Pa). Floors can easily handle that.

---

## Multiple perspectives

### Analytical (what we did)
- Define pressure from how force distributes over area.
- Compute weight from g.
- Divide by area.

### Proportional reasoning
- Pressure ∝ mass/area, because P = mg/A and g is fixed.
- Halving side length quarters the area and thus quadruples pressure.
- Doubling mass doubles pressure.

### Experimental thought-experiment
- Place pressure-sensitive film under the cube. The total force reading (sum over pixels) equals the weight (≈1000 N), and the uniform distribution over A gives the average pressure ≈ 25 kPa.

---

## Final answer
25000 Nm⁻²  (Option 2)

---

## 1) Conceptual follow-up questions
- If the cube were turned to rest on a smaller face (impossible for a perfect cube but imagine a rectangular block), how would pressure change? Why?
- In an elevator accelerating upward at 2 m/s², what happens to pressure? Hint: effective weight becomes m(g + a).
- On the Moon (g ≈ 1.6 N/kg), how does pressure compare to Earth’s?
- If the floor is soft and deforms, increasing the contact area, what happens to pressure?
- If the cube rests on an edge or point, does pressure go to infinity? What stops it in reality?

---

## 2) Application questions (real-world links)
- Why do snowshoes prevent sinking into snow? How would you estimate the required shoe area for a given body mass?
- Why do wide tires reduce soil compaction in agriculture?
- How do building foundations (footings) use large areas to keep ground pressure safe?
- Compare the pressure under a high-heel tip to that under an elephant’s foot for the same total weight per leg.

---

## 3) Common misconceptions and reasoning traps
- Confusing mass and weight: Mass is in kg (how much stuff), weight is in N (force due to gravity). Use W = mg.
- Thinking atmospheric pressure must be added to the answer: Here, we’re asked for the pressure due to the cube on the floor (contact pressure), not absolute pressure including the atmosphere.
- Using the wrong area: Only the contact face matters, not the total surface area of the cube.
- Unit slips: Forgetting that N/kg × kg = N, and N/m² = Pa.

---

## 4) Extension challenges
- If instead of mass you were given the cube’s density ρ and side s, show that resting on a face gives:
  
  ```math
  m = \rho s^3,\quad A = s^2 \quad\Rightarrow\quad P = \frac{mg}{A} = \rho g s
  ```
  
  Insight: For same material, pressure scales linearly with size.
- On an inclined plane of angle θ (still resting on a face), the normal force is W cosθ. Find the pressure:
  
  ```math
  P = \frac{W\cos\theta}{A} = \frac{mg\cos\theta}{A}
  ```
- What minimum face area is needed so that pressure does not exceed 10⁵ Pa (about 1 atm) for this 100 kg mass?
  
  ```math
  A_{\min} = \frac{mg}{10^5} = \frac{1000}{10^5} = 0.01\ \text{m}^2 \quad\Rightarrow\quad \text{side} = 0.1\ \text{m}
  ```

---

## 5) Reflective insight — the essence
Pressure is concentration of force. It answers, “How intensely is force applied at a surface?” The deeper idea is distribution: the same total push can be gentle or severe depending on the area over which it is spread. Once you see pressure as “force density over area,” almost everything follows: snowshoes, tires, foundations, even fluid pressure. The core relation P = F/A isn’t a memorized formula; it’s a definition born from how force shares itself across space. Understanding that lets you generalize confidently to new contexts.