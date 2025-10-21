## Question

Find the cost of erecting a fence around a square field whose area is 9 hectares if fencing costs 3.50/- per metre:

**Options:**
- A) 4200/-
- B) 4300/-
- C) 4400/-
- D) 4500/-

## Fence Cost — From First Principles

### Big picture
- A fence runs around the outside edge of the field. So the cost depends on the total length of the boundary — the perimeter — not the area.
- We’re given area (in hectares) and must find the perimeter of a square with that area, then multiply by the cost per metre.

### Step 1: What is a hectare?
Imagine a 100 m by 100 m square patch of land. Farmers use this as a standard chunk called a “hectare.”

```math
1\ \text{hectare} = 100\ \text{m} \times 100\ \text{m} = 10{,}000\ \text{m}^2
```

So for 9 hectares:
```math
A = 9\ \text{ha} = 9 \times 10{,}000\ \text{m}^2 = 90{,}000\ \text{m}^2
```

Dimensional check: area is in m² — good.

### Step 2: From area to side length (square logic from first principles)
- Visualize covering the square field with 1 m by 1 m tiles.
- If there are $s$ tiles along one side, then there are $s$ rows of $s$ tiles. So the total number of tiles (the area) is $s \times s = s^2$.

Thus, for a square:
```math
\text{Area} = s^2 \quad \Rightarrow \quad s = \sqrt{\text{Area}}
```
Units check: $\sqrt{\text{m}^2} = \text{m}$, so side length comes out in metres.

For our field:
```math
s = \sqrt{90{,}000\ \text{m}^2} = \sqrt{9 \times 10{,}000}\ \text{m} = \sqrt{9}\times \sqrt{10{,}000}\ \text{m} = 3 \times 100\ \text{m} = 300\ \text{m}
```

Quick intuition: 9 times the area means side becomes 3 times as long (because area scales with the square of side).

### Step 3: From side to perimeter
Perimeter means the distance all the way around. A square has 4 equal sides:
```math
P = 4s = 4 \times 300\ \text{m} = 1200\ \text{m}
```

### Step 4: From perimeter to cost
Cost = (length to fence) × (cost per metre):
```math
\text{Cost} = P \times 3.50\ \text{per m} = 1200 \times 3.50
```
Compute cleanly:
```math
1200 \times 3.50 = 12 \times 3.5 \times 100 = 42 \times 100 = 4200
```

### Final answer
- Cost = 4200/- 
- Correct option: A) 4200/-

---

## Multiple Ways to See It (flexible thinking)
- Scaling method: A 1-hectare square has side 100 m. If area becomes 9 times larger, side becomes 3 times larger ⇒ side = 300 m ⇒ perimeter = 1200 m ⇒ same cost as above.
- Experimental mindset: If you walked around the field with a measuring wheel, you’d measure 1200 m. Multiplying by the rate per metre directly gives the total cost. The area only helps us deduce that perimeter.

---

## Conceptual Follow-up Questions
1. If the area were 16 hectares at the same rate, what would the cost be?
2. If the rate increases by 20%, how does the total cost change for the same field?
3. If the field had the same area but was a rectangle 2:1 (length:breadth), would the cost be higher, lower, or the same as the square? Why?
4. If you only fence three sides (one side borders a river), what is the new cost?
5. If the area doubles, by what factor does the cost change? (Hint: side scales with the square root of area.)

---

## Application Questions (real-world connections)
- Urban design: For a park of fixed area, which shape minimizes fencing cost? How does the square compare to a circle for material savings?
- Agriculture: If a farmer wants to enclose a 9-hectare field but build two gates (each 4 m wide) that don’t need fencing, what is the cost now?
- Conservation: For wildlife reserves with fixed habitat area, discuss how shape choice affects fencing costs and animal movement.

---

## Common Misconceptions and Traps
- Mixing area and perimeter: Using area × rate instead of perimeter × rate. Cost depends on boundary length.
- Hectare confusion: Forgetting that 1 ha = 10,000 m², not 1000 m².
- Skipping the square root: For a square, side is √(area), not area/4 or other shortcuts.
- Unit slips: Not keeping track that area is m², perimeter is m, and rate is per metre.

How to avoid: Always do a unit (dimensional) check. If you multiply by a rate “per metre,” you must have metres, not square metres.

---

## Extension Challenges
- Design challenge: For the same 9-hectare area, compare fencing cost for a circle vs a square. Which is cheaper and by how much? (Circle has minimal perimeter for a given area.)
- Scaling insight: If you scale a square’s side by k, the area scales by k² but the perimeter scales by k. Explain why costs tied to area (like seeding) and costs tied to perimeter (like fencing) behave differently as fields grow.
- Mixed-units: If fencing is priced at 10 per foot, convert carefully and recompute the cost for the 9-hectare square.

---

## Reflective Insight (the essence)
Perimeter vs area are different “kinds” of size: perimeter is about boundary length (1D), area is about surface coverage (2D). For a square, area tells you side by taking a square root because squaring builds area from side length in two directions. Once you see this, many problems become straightforward: get side from area (√), get perimeter from side (×4), then apply the real-world rate (per metre). Understanding these dimensional relationships is the key that unlocks any similar problem.