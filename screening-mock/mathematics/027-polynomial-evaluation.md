## Question

If
$\mathrm{P}(\mathrm{x})=\mathrm{x}^2-\mathrm{x}+1$ then
$\frac{\mathrm{P}(2)-\mathrm{P}(-2)}{\mathrm{P}(1)-\mathrm{P}(-1)}=$

**Options:**

1. 0
2. 2
3. 4
4. 5

## Solve it from first principles (mirror-thinking and simple arithmetic)

### 1) Start with an everyday picture
Think of the x-axis as a straight road. The points x and −x are like two houses equally far from the origin but on opposite sides. If a function P(x) gives a “height” above the road, then:
- Even parts (like x² and constants) look the same from both houses (symmetry in a mirror).
- Odd parts (like x) flip sign across the mirror.

So when you compare P(x) and P(−x), only the odd part causes a difference. That’s the key idea.

Our function is:
```math
P(x) = x^2 - x + 1
```
- x² is even: x² = (−x)²
- 1 is even: 1 = 1 for any x
- −x is odd: −(−x) = +x (it changes sign)

So the difference P(x) − P(−x) will be caused only by the odd part (−x).

---

### 2) Direct computation (arithmetic approach)

Compute each value carefully.

- For x = 2:
  ```math
  P(2) = 2^2 - 2 + 1 = 4 - 2 + 1 = 3
  ```
- For x = −2:
  ```math
  P(-2) = (-2)^2 - (-2) + 1 = 4 + 2 + 1 = 7
  ```
- Difference in the numerator:
  ```math
  P(2) - P(-2) = 3 - 7 = -4
  ```

- For x = 1:
  ```math
  P(1) = 1^2 - 1 + 1 = 1
  ```
- For x = −1:
  ```math
  P(-1) = (-1)^2 - (-1) + 1 = 1 + 1 + 1 = 3
  ```
- Difference in the denominator:
  ```math
  P(1) - P(-1) = 1 - 3 = -2
  ```

Now the ratio:
```math
\frac{P(2) - P(-2)}{P(1) - P(-1)} = \frac{-4}{-2} = 2
```

---

### 3) Why this happens (symmetry approach)

Let’s analyze P(x) − P(−x) using the even/odd idea:

```math
P(x) = x^2 - x + 1,\quad P(-x) = x^2 + x + 1
```

Subtract:
```math
P(x) - P(-x) = (x^2 - x + 1) - (x^2 + x + 1) = -2x
```

- Notice how the even parts x² and 1 cancel out exactly.
- Only the odd part (−x) contributes, and it doubles in size (because we subtract a flipped sign), giving −2x.

So:
```math
P(2) - P(-2) = -2(2) = -4,\quad P(1) - P(-1) = -2(1) = -2
```
Hence the ratio:
```math
\frac{-4}{-2} = 2
```

This shows the deep reason: the ratio ends up being 2 because the “odd-part difference” scales linearly with x.

---

### 4) Final answer
Option 2: 2

---

## Extra insight: a quick generalization
For any quadratic P(x) = ax² + bx + c:
```math
P(x) - P(-x) = (ax^2 + bx + c) - (ax^2 - bx + c) = 2bx
```
So:
```math
\frac{P(2) - P(-2)}{P(1) - P(-1)} = \frac{2b \cdot 2}{2b \cdot 1} = 2
```
(as long as b ≠ 0; if b = 0, there’s no odd part and the denominator is 0, so the ratio is undefined).

Our polynomial has a = 1, b = −1, c = 1, which fits this pattern.

---

## 1) Conceptual follow-up questions
- If a function has only even powers (like x², x⁴, or a constant), what is P(x) − P(−x)? Why?
- If a function has only odd powers (like x, x³), what is P(x) + P(−x)? Why?
- For Q(x) = 3x³ − 5x, compute Q(a) − Q(−a) and simplify. What pattern do you notice?
- For which polynomials will the ratio (P(2) − P(−2)) / (P(1) − P(−1)) always equal 2?

## 2) Applications to real life and science
- Signal processing: Any signal can be split into an even part (symmetric) and an odd part (antisymmetric). Comparing s(t) and s(−t) isolates the odd component—useful in filtering and communications.
- Physics: Many laws are symmetric under reversal (even), but some effects (like certain torques or magnetic forces) change sign (odd) when direction flips. Measuring differences at +x and −x can reveal these “odd” effects.
- Engineering: In sensor calibration, taking readings at +x and −x and subtracting cancels symmetric biases (even parts), isolating the directional error (odd part).

## 3) Common misconceptions and traps
- Thinking x² changes sign when x becomes negative. It doesn’t; (−x)² = x².
- Dropping the negative when substituting x → −x into linear terms; −(−x) = +x.
- Forgetting that constants are even and stay the same at ±x.
- Dividing by zero: if the denominator P(1) − P(−1) = 0, the ratio is undefined (this happens if there’s no odd part).

## 4) Extension challenges
- Prove: For any polynomial P(x), P(x) − P(−x) contains only the odd-power terms, each doubled.
- Find all polynomials P such that (P(2) − P(−2)) / (P(1) − P(−1)) = 2. Hint: the odd part must be proportional to x (no x³, x⁵, … terms).
- Explore: For R(x) = x³ − x, compute (R(2) − R(−2)) / (R(1) − R(−1)). Is it still 2? Why or why not?
- Generalize: For which functions f and numbers k does (f(k) − f(−k)) / (f(1) − f(−1)) equal k? What structure must f have?

## 5) Reflective insight — the essence
The difference P(x) − P(−x) is a “mirror test” that reveals only the odd part of a function. Even parts are invisible to this test because they look identical in the mirror. In this problem, that odd part is linear in x, so the difference scales directly with x, making the ratio between the “2” case and the “1” case equal to 2. Understanding this symmetry lets you solve quickly and confidently—even for more complex functions—by seeing which parts survive a mirror flip.