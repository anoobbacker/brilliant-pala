# Question
The correct set of co-efficients $x$, $y$, $z$ and $w$ for the balanced chemical equation  
$x\text{NH}_3(g) + y\text{O}_2(g) \rightarrow z\text{NO}(g) + w\text{H}_2\text{O}(g)$ is  
   1) $x = 4;\ y = 6;\ z = 4;\ w = 7$  
   2) $x = 5;\ y = 4;\ z = 5;\ w = 6$  
   3) $x = 4;\ y = 5;\ z = 4;\ w = 6$  
   4) $x = 4;\ y = 6;\ z = 4;\ w = 5$

---
# Answer

## Start with a real-world picture

Question: If you “burn” ammonia (NH3) in oxygen, what happens to the atoms?

Think Lego. Each NH3 has:
- 1 nitrogen (N)
- 3 hydrogens (H)

Each O2 has:
- 2 oxygens (O)

On the right, we want:
- Nitric oxide (NO): 1 N + 1 O
- Water (H2O): 2 H + 1 O

Balancing means: we can rearrange the Lego blocks, but we can’t create or destroy any blocks (atoms). So the number of each atom type must be equal on both sides.

---

## Build it from first principles (not from a memorized formula)

Let the coefficients be x, y, z, w:

```math
x\,\text{NH}_3 + y\,\text{O}_2 \rightarrow z\,\text{NO} + w\,\text{H}_2\text{O}
```

Count each element:

1) Nitrogen:
```math
\text{Left: } x \quad\text{Right: } z \quad\Rightarrow\quad x = z
```

2) Hydrogen:
```math
\text{Left: } 3x \quad\text{Right: } 2w \quad\Rightarrow\quad 3x = 2w \ \Rightarrow\ w = \frac{3x}{2}
```
This tells us x must be even for w to be a whole number.

3) Oxygen:
```math
\text{Left: } 2y \quad\text{Right: } z + w \quad\Rightarrow\quad 2y = z + w
```
Using z = x and w = 3x/2:
```math
2y = x + \frac{3x}{2} = \frac{5x}{2} \quad\Rightarrow\quad y = \frac{5x}{4}
```
For y to be an integer, x must be a multiple of 4. Choose the smallest: x = 4.

Then:
```math
x = 4,\quad z = 4,\quad w = \frac{3(4)}{2} = 6,\quad y = \frac{5(4)}{4} = 5
```

Balanced equation:

```math
4\text{NH}_3 + 5\text{O}_2 \rightarrow 4\text{NO} + 6\text{H}_2\text{O}
```

So the correct option is 3) x = 4; y = 5; z = 4; w = 6.

---

## Fast elimination using smart checks

- Oxygen parity trick: O2 gives oxygen in pairs, so the total O atoms on the right (z + w) must be even. Check options:
  - 1) z + w = 4 + 7 = 11 (odd) → impossible
  - 2) 5 + 6 = 11 (odd) → impossible
  - 4) 4 + 5 = 9 (odd) → impossible
  - 3) 4 + 6 = 10 (even) → only possible one

- Hydrogen check: 3x hydrogens must go into water (2 per H2O), so w = 1.5x. If x = 4 → w = 6 (fits option 3). If x = 5 → w = 7.5 (not an integer; rules out option 2).

---

## Visual aid (imagine the atoms)

- Picture 4 NH3 molecules: total H = 12, N = 4.
- To use all 12 H, you need 6 H2O (each uses 2 H).
- The 4 N become 4 NO.
- Now count O needed on the right: 4 (from NO) + 6 (from H2O) = 10 O atoms → that’s 5 O2 molecules.

---

## Analytical view (compact)

From conservation:
```math
\begin{aligned}
\text{N: } & x = z \\
\text{H: } & 3x = 2w \Rightarrow w = \frac{3x}{2} \\
\text{O: } & 2y = z + w = x + \frac{3x}{2} = \frac{5x}{2} \Rightarrow y = \frac{5x}{4}
\end{aligned}
```
Smallest integer solution: x = 4 → (x, y, z, w) = (4, 5, 4, 6).

---

## Experimental view

In industry (Ostwald process), NH3 is oxidized over a platinum-rhodium catalyst:
- Ammonia + oxygen → nitric oxide + water (releases heat).
- NO quickly turns to brown NO2 in air. Our equation captures the primary step.

---

## Intuitive checks

- Doubling all coefficients keeps the balance valid. We always report the simplest whole-number ratio.
- Mass conservation check (optional): both sides have equal total mass; the balanced equation enforces that.

---

> ### 🧠 Quick Exam Tips
> - Start with the element that appears in the fewest compounds (here N), then H, then O.
> - Use w = 1.5x for NH3→H2O balancing; choose x even.
> - Oxygen parity: since O2 has pairs, z + w must be even.
> - Never change subscripts (the chemical identity); only change coefficients.

---

## Conceptual follow-ups

- What if NH3 burns to N2 and H2O instead?
  - Try balancing: x NH3 + y O2 → z N2 + w H2O. You’ll get different coefficients.
- What if the product were NO2 instead of NO?
  - Balance NH3 + O2 → NO2 + H2O and compare oxygen demand.

---

## Real-world application

This reaction is the first step in making nitric acid (fertilizers, explosives, dyes). Efficient catalysts and correct oxygen ratios are vital to maximize NO yield.

---

## Misconception clinic

- Many students think they can “fix” balance by altering subscripts (like H2O to H3O). But subscripts change the substance. Only adjust the big numbers in front (coefficients).
- A common mistake is balancing atoms on one side only, then forgetting to re-check others. Always loop back and re-count all elements.
- Students sometimes ignore parity: if O2 is the only oxygen source, the total oxygen atoms on the product side must be even.

---

## Extension challenges

- Math link: Treat balancing as solving a system of linear equations. The solution vector gives the smallest integer ratio.
- Engineering link: Consider how catalysts lower activation energy and control selectivity (NH3 → NO vs complete oxidation to N2).

---

## Practice questions

1) Balance: NH3 + O2 → N2 + H2O. What are the simplest coefficients?
2) Balance: NH3 + O2 → NO2 + H2O.
3) Quick check: In a proposed balance of a reaction where O2 is the only O-source, the sum of oxygen atoms on the right is odd. What must be wrong?
4) If you doubled the coefficient of NH3 in the correct equation, what happens to the others?

---

> “The timeless pattern: Nature conserves counts. Whether it’s atoms, charge, or momentum, balance comes from respecting what cannot be created or destroyed—only rearranged.”