## Question

The distance between two points $(0,-1)$ and $(x, 3)$ is 5 . Find positive value of $x$

## Intuition from everyday life

Imagine a city laid out in a square grid. You start at a point A with coordinates (0, −1). You want to end at a point B somewhere on the horizontal line where y = 3, so B = (x, 3). That means:
- You go horizontally by x units (right if x > 0, left if x < 0).
- You go vertically up by 4 units (from −1 to 3).

If you tie a string from A to B, its length is the straight-line distance between the points. We’re told this string is 5 units long. We need to find the positive x that makes this true.

## Building the math from first principles

### Step 1: Translate the coordinates into a right triangle
- Horizontal change: Δx = x − 0 = x
- Vertical change: Δy = 3 − (−1) = 4

These form the legs of a right triangle. The distance d between the points is the hypotenuse.

### Step 2: Why the hypotenuse relates to the squares of the legs (reconstructing Pythagoras)
For any right triangle with legs a and b and hypotenuse c, here’s a quick “area rearrangement” argument:

- Make a large square of side (a + b). Its area is (a + b)^2.
- Fit four copies of the right triangle inside, leaving a central tilted square of side c.
- The total area is also the sum of the four triangles plus the central square:
  - Area of 1 triangle = (1/2)ab, so 4 triangles have area 2ab.
  - Central square area = c^2.
- Equate both expressions for the same big square’s area:
  
```math
(a + b)^2 = 4 \cdot \frac{1}{2} ab + c^2 \quad \Rightarrow \quad a^2 + 2ab + b^2 = 2ab + c^2
```

Subtract 2ab:

```math
c^2 = a^2 + b^2
```

This shows why the square of the diagonal equals the sum of the squares of the sides.

### Step 3: Apply it to our triangle
Here, a = |Δx| = |x| and b = |Δy| = 4, and the distance d = 5. Squaring keeps signs from mattering:

```math
d^2 = (\Delta x)^2 + (\Delta y)^2 \quad \Rightarrow \quad 5^2 = x^2 + 4^2
```

So:

```math
25 = x^2 + 16 \quad \Rightarrow \quad x^2 = 9 \quad \Rightarrow \quad x = \pm 3
```

We’re asked for the positive value, so:

```math
x = 3
```

### Step 4: Dimensional/units sanity check
- Distances have units of length (say, meters or units).
- Squared distances have units of length^2.
- Left side: 25 (units^2). Right side: x^2 (units^2) + 16 (units^2). Units match—this is consistent.

### Step 5: Geometric (locus) viewpoint
“All points at distance 5 from (0, −1)” form a circle centered at (0, −1) with radius 5. Its equation comes from the same distance idea:

```math
(x - 0)^2 + (y + 1)^2 = 5^2
```

Intersect this circle with the horizontal line y = 3:

```math
x^2 + (3 + 1)^2 = 25 \Rightarrow x^2 + 16 = 25 \Rightarrow x^2 = 9 \Rightarrow x = \pm 3
```

Again, the positive solution is x = 3.

### Step 6: Vector viewpoint (another angle)
The displacement vector from A to B is ⟨x − 0, 3 − (−1)⟩ = ⟨x, 4⟩. Its length d satisfies

```math
d^2 = x^2 + 4^2
```

Setting d = 5 gives the same result.

## Final answer

```math
\boxed{x = 3}
```

---

## 1) Conceptual follow-up questions

- If the distance between (0, −1) and (x, 3) were 13 instead of 5, what would x be? Explain the steps.
- Why are there two solutions (x = ±3) before we choose the positive one? What symmetry in the picture causes this?
- If the two points were (a, b) and (c, d), how would you reconstruct the distance formula from first principles?
- How would this change in 3D for points (x1, y1, z1) and (x2, y2, z2)? Derive the 3D version using the same triangle logic twice.

## 2) Application questions

- Architecture: A ladder of length 5 m must reach a window 4 m above the ground. How far from the wall should the base be? What if the window is 4.5 m high—can the same ladder reach?
- GPS/Robotics: A robot moves x meters east and 4 meters north. Its straight-line displacement is 5 meters. Find x. How would sensor noise affect your estimate of x?
- Networking: In a data center, a cable runs diagonally between racks separated by x meters horizontally and 4 meters vertically in layout. What cable length is needed and why do we square lengths when combining?

## 3) Common misconceptions and reasoning traps

- Mixing up distance and coordinate difference: Forgetting that Δy = 3 − (−1) = 4, not 2.
- Ignoring squares: Thinking 5 = x + 4 rather than 5^2 = x^2 + 4^2—lengths add in a straight line, not across perpendicular directions; the squares add.
- Dropping the ±: Solving x^2 = 9 but only writing x = 3. Both ±3 solve the equation; then apply the “positive x” condition.
- Units mismatch: Writing 25 = x + 16 (units vs units^2). Always check units: squared distance equals sum of squared components.

## 4) Extension challenges

- Generalize: For points (h, k) and (x, 3), with distance r, derive an equation for x in terms of h, k, r.
- Uncertainty: If the vertical coordinate 3 is measured with ±0.2 error, estimate the resulting uncertainty in x when the distance is exactly 5. (Hint: use differentials or compare (3±0.2) numerically.)
- Optimization: Among all points on the line y = 3, which is closest to (0, −1)? Show that this point is (0, 3) and explain geometrically why.
- Non-Euclidean twist: If you measured “city-block distance” (|Δx| + |Δy|) instead of straight-line distance, what x would make the distance 5? Compare with the Euclidean answer.

## 5) Reflective insight

At the heart of this problem is the idea that perpendicular directions are independent. Moving east and moving north don’t interfere with each other, so the “combined effect” of these independent moves shows up through the sum of their squares—captured by the Pythagorean relationship. That’s why the straight-line distance comes from squaring, adding, and then square-rooting. This principle scales to vectors, energy, and even statistics: independent contributions add in squares. Understanding that “why” lets you rebuild the formulas any time, from first principles.