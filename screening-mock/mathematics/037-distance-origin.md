## Question

The square of the distance of origin from the point $\mathrm{P}(3,-2)$ is

## Intuition from everyday life
- Imagine standing at the origin on a grid-like city map.
- To reach P(3, −2), you move:
  - 3 steps to the right (east),
  - 2 steps down (south).
- The straight-line path (what a bird would fly) is the distance OP. This forms a right triangle with legs 3 and 2, and the straight-line OP is the slanted side (hypotenuse).

---

## Why perpendicular moves combine via “sum of squares”
We need to relate the straight-line length (hypotenuse) to the two perpendicular moves.

### Reconstructing the Pythagorean relation (from areas)
Take any right triangle with legs a and b, hypotenuse c. Arrange four identical triangles to make a big square in two ways:
- Big square side is (a + b), so its area is (a + b)².
- Inside, the four triangles (each area 1/2 ab) surround a small central square of side c, so total area is 4(1/2 ab) + c².

Equate the two expressions:
```math
(a + b)^2 = 4\left(\tfrac{1}{2}ab\right) + c^2
a^2 + 2ab + b^2 = 2ab + c^2
c^2 = a^2 + b^2
```
This shows why the square of the straight-line distance equals the sum of the squares of the perpendicular legs.

---

## Apply to O(0, 0) → P(3, −2)
- Horizontal difference: 3 − 0 = 3
- Vertical difference: −2 − 0 = −2 (length is 2; sign only tells direction)
- Let a = 3, b = 2. Then the square of the distance is:
```math
OP^2 = a^2 + b^2 = 3^2 + 2^2 = 9 + 4 = 13
```

Answer: 13 (in units²).  
If you wanted the distance itself, it would be √13 units.

---

## Dimensional and logical checks
- Distances have units of length (L); squares of distances have units L². Our result 13 is in units², consistent with “square of the distance.”
- The negative y doesn’t change length because squaring removes sign (length is always non-negative).

---

## Alternative viewpoints
- Vector view: The displacement vector is ⟨3, −2⟩. Its length squared is the dot product with itself: 3·3 + (−2)·(−2) = 13. This matches the geometric result.
- Experimental check: Draw a 3-by-2 right triangle on graph paper and measure the hypotenuse (~3.606). Squaring ≈ 13.

---

## Final result
```math
\boxed{13}
```

---

## Conceptual follow-up questions
1. If P is (−3, −2), does OP² change? Why or why not?
2. For Q(x, y), what is OQ² in terms of x and y? Can you justify it geometrically?
3. If R is (3, 4), what are OR² and OR? Why is this a “Pythagorean triple”?
4. How would OP² change if the units on the x-axis and y-axis weren’t the same (e.g., x in meters, y in centimeters)?

---

## Applications
- GPS and mapping: Computing shortest paths in a flat region uses this sum-of-squares idea.
- Physics: Speed squared v² = vx² + vy² when motion has perpendicular components.
- Engineering: Diagonal bracing lengths in frames; precise CNC machine moves along x and y to reach a diagonal endpoint.

---

## Common misconceptions and how to avoid them
- Forgetting to square the negative: (−2)² = 4, not −4.
- Mixing the distance with its square: OP² = 13; OP = √13. Know which one the question asks.
- Using “city-block” distance (|x| + |y|) instead of straight-line distance. That’s a different metric (Manhattan distance).

---

## Extension challenges
- 3D generalization: For S(x, y, z), show OS² = x² + y² + z². Why do three perpendicular components still add in squares?
- Weighted axes: If one axis is stretched (say y is measured in 2 meters per grid unit), how does the formula change?
- Non-Euclidean twist: On Earth’s curved surface, straight lines are arcs (geodesics). How would you approximate small distances with the Euclidean formula, and when does it break down?

---

## Reflective insight
Perpendicular directions don’t “interfere”; their contributions to straight-line length accumulate through areas, not simple addition. That’s why distances in a flat world combine in quadrature: the square of the whole equals the sum of the squares of the independent perpendicular parts. Understanding this “sum of squares” principle helps in geometry, physics, data science (norms), and beyond.