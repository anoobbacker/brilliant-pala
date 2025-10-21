## Question

Let $P Q R S$ be a rectangle such that $P Q+Q R+R S=28$ and $P T=10$, where $T$ is mid point of $Q R$. Then the area of the trapezium PTRS in the figure is

Diagram:
```
S +--------------------------------------+ R
  |                                      | 
  |                                      | 
  |                                      | 
  |                                      | 
  |                                 /    | T
  |                 10         /         | 
  |                       /              | 
  |                  /                   | 
  |             /                        | 
  |        /                             | 
P +--------------------------------------+ Q

```

**Options:**

1. 56
2. 96
3. 68
4. 72

## Big-picture idea

Imagine a rectangle made from cardboard. You mark the midpoint T on the right edge, then connect the top-left corner P to T. You’re asked for the area of the shape made by P → T → R → S → back to P. That shape is a trapezium (a trapezoid): two opposite sides are parallel (the left side PS and the right half TR).

We’ll:
- Name the rectangle’s side lengths as unknowns and translate the given words into equations.
- Use a right-triangle idea (Pythagoras) to connect those unknowns logically.
- Find the rectangle’s area without solving for the individual sides directly.
- Derive the trapezium’s area from first principles by dissecting shapes.

Everything will follow from simple geometry you can visualize with paper cutting.

---

## 1) Name what we don’t know

Let the rectangle have:
- Width PQ = a
- Height QR = b

Opposite sides of a rectangle are equal, so RS = a and PS = b.

Given:
- PQ + QR + RS = a + b + a = 2a + b = 28
- T is the midpoint of QR, so QT = TR = b/2
- PT = 10

So we already have one equation:
```math
2a + b = 28  \quad (1)
```

---

## 2) How does PT relate to a and b?

Think of moving from P to T in two “L-shaped” steps:
- Move horizontally from P to Q: distance a
- Move vertically from Q down to T: distance b/2

The straight path PT is the hypotenuse of a right triangle with legs a and b/2. By the Pythagorean relationship (which itself comes from comparing areas of squares built on the sides of a right triangle):

```math
PT^2 = a^2 + \left(\frac{b}{2}\right)^2
```

But PT = 10, so:
```math
a^2 + \frac{b^2}{4} = 100  \quad (2)
```

Multiply (2) by 4 to clear the fraction:
```math
4a^2 + b^2 = 400  \quad (3)
```

---

## 3) Extract the product ab without solving for a or b

Why the product ab? Because area of the rectangle is ab, and the trapezium’s area (as we’ll see) is a simple fraction of that.

From (1), square both sides:
```math
(2a + b)^2 = 28^2
```
Expand:
```math
4a^2 + 4ab + b^2 = 784  \quad (4)
```

Now subtract (3) from (4):
```math
(4a^2 + 4ab + b^2) - (4a^2 + b^2) = 784 - 400
```
So:
```math
4ab = 384 \;\;\Rightarrow\;\; ab = 96
```

Dimensional check: a and b are lengths, so ab is an area. The numbers 784 and 400 came from squaring lengths, so everything is dimensionally consistent.

---

## 4) Area of trapezium PTRS from first principles

We need the area of trapezium PTRS. There are two clean “from-first-principles” ways:

### A. Subtract a triangle from the rectangle
- Whole rectangle area = ab
- Triangle PQT: base PQ = a, height QT = b/2, and angle at Q is right because rectangle sides are perpendicular.
  The area of a right triangle is half the area of the rectangle that would be formed### A. Subtract a triangle from the rectangle (continued)
A triangle’s area can be understood by “halving a rectangle”: if you draw a right triangle inside a rectangle whose sides are the triangle’s legs, the diagonal cuts the rectangle into two equal triangles.

- Rectangle formed by base PQ = a and height QT = b/2 has area a·(b/2).
- So triangle PQT has area half of that:
```math
[\triangle PQT] = \frac{1}{2}\cdot a\cdot \frac{b}{2} = \frac{ab}{4}
```

Therefore,
```math
[\text{trapezium } PTRS] = [\text{rectangle } PQRS] - [\triangle PQT] = ab - \frac{ab}{4} = \frac{3ab}{4}
```

We already found ab = 96, so
```math
[\text{trapezium } PTRS] = \frac{3}{4}\cdot 96 = 72
```

### B. Or, derive the trapezium area formula from first principles
In trapezium PTRS:
- The parallel sides are PS = b and TR = b/2 (both vertical).
- The distance between them is the horizontal width a.

You can get the trapezium area by “cut-and-paste”: cut the small right triangle at the top-right and slide it to the top-left; the shape becomes a rectangle whose one side is the average of the two parallel sides and the other side is the distance between them.

So,
```math
[\text{trapezium}] = \frac{(\text{parallel side 1}) + (\text{parallel side 2})}{2} \times (\text{distance})
= \frac{b + \frac{b}{2}}{2} \times a = \frac{3b}{4}\, a = \frac{3ab}{4}
```
Again, with ab = 96, the area is 72.

---

## 5) Quick numerical check (optional but reassuring)
From earlier:
```math
2a + b = 28,\quad a^2 + \frac{b^2}{4} = 100
```
We solved without finding a and b individually. If you do solve:
- From a^2 + (b^2)/4 = 100 ⇒ 4a^2 + b^2 = 400
- From 2a + b = 28 ⇒ b = 28 − 2a
- Substitute and simplify ⇒ a^2 − 14a + 48 = 0 ⇒ a = 6 or 8
- Then b = 16 or 12

Check PT:
- If (a, b) = (6, 16): PT^2 = 6^2 + 8^2 = 100 ⇒ PT = 10
- If (a, b) = (8, 12): PT^2 = 8^2 + 6^2 = 100 ⇒ PT = 10

In both cases, ab = 96 and the trapezium area 3ab/4 = 72.

---

## Final answer
72  (Option 4)

---

## 1) Conceptual follow-up questions
- Why did the midpoint matter? Show that because T is the midpoint, QT = b/2, which made 4a^2 + b^2 cancel nicely when combined with (2a + b)^2. What if T were not the midpoint?
- If we only knew PT = 10 and the perimeter condition 2a + b = 28, could the area of the trapezium be different? Explain why it still comes out fixed at 72.
- How would the area change if T divided QR in the ratio t:1−t from the top (so QT = t b)? Predict the fraction of the rectangle included and verify.
- Is there more than one rectangle with these conditions? If so, why does the trapezium area not depend on which one you pick?
- Without coordinates, can you argue purely by area dissection that [PTRS] = [PQRS] − [PQT] and that [PQT] = ab/4 because T is the midpoint?

---

## 2) Applications to real-world and modern problems
- Manufacturing/laser cutting: If you cut off triangle PQT from a rectangular sheet (with the cut going to the midpoint of a side), the remaining area is always 3/4 of the rectangle—useful for material estimates.
- Robotics path planning: The straight-line reach PT to the midpoint is constrained by a and b. Combining a linear constraint (2a + b fixed) with a Pythagorean reach constraint models trade-offs in machine design.
- Display design: Two screens with different aspect ratios (6×16 vs 8×12) can satisfy the same diagonal condition and “partial frame” area—helpful in UI layout where area fractions matter more than aspect ratios.
- Civil engineering: A ramp or brace from a corner to the midpoint determines constraints on dimensions for stability, while preserving certain area fractions for usable space.

---

## 3) Common misconceptions and reasoning traps
- Treating PT as a + b/2 instead of using Pythagoras. The straight path is not the sum of legs; it is the hypotenuse: square-and-add, then square root.
- Forgetting RS = PQ in a rectangle. This leads to misusing PQ + QR + RS as a + b + b.
- Using the trapezium area formula without understanding it. Always be able to re-derive it via cut-and-paste to a rectangle with width equal to the average of parallel sides.
- Assuming a and b are uniquely determined. There are two solutions (6,16) and (8,12), yet the area asked is invariant.
- Dropping units and dimensional sense. 2a + b is length, but (2a + b)^2 and 4a^2 + b^2 are areas; subtracting them yields an area (4ab), not a length.

---

## 4) Extension challenges
- General divider position: Let T be at a fraction t of the way down from Q (so QT = t b). Show that
  - Triangle PQT has area (1/2)·a·(t b) = (t/2)ab.
  - Trapezium PTRS area = ab − (t/2)ab = (1 − t/2)ab.
- Does ab remain uniquely determined if T isn’t the midpoint? Given 2a + b = C and PT = p with QT = t b, show that eliminating to get ab works cleanly only when t = 1/2 (midpoint), which makes the b^2 terms cancel. Explain why this midpoint symmetry is special.
- Prove purely geometrically (without coordinates) that when T is the midpoint, the removed triangle has exactly one quarter of the rectangle’s area.
- Algebraic insight: From the given conditions, show that a satisfies a^2 − 14a + 48 = 0 and discuss how the two roots correspond to swapping (a, b/2) in the Pythagorean pair.

---

## 5) Reflective insight (the deep “why”)
Two powerful ideas made this easy:
- Target the right invariant: We didn’t need a and b separately—only their product ab (the rectangle’s area). Combining a linear constraint (2a + b) with a Pythagorean constraint makes the squares cancel in a way that reveals ab directly when T is the midpoint.
- Structure reveals simplicity: The trapezium’s area is just the rectangle minus a triangle that is exactly one quarter of it because the cut goes to a midpoint. Midpoint symmetry turns a messy-looking problem into a clean fraction (3/4) of the rectangle’s area.

Once you see these structural invariants and symmetric cuts, you can handle many unfamiliar problems by asking: What combination is truly determined? What cancels nicely? How can I dissect the shape into simpler parts?