## Question

The sum of the squares of two consecutive positive integers is 545. Then the integers are:

**Options:**
- A) 15, 16
- B) 16, 17
- C) 21, 17
- D) 6, 12
- E) None of these

## Solve from first principles (no memorized formulas)

### 1) Start with a picture in your mind
- Imagine two square tiles whose sides are consecutive whole numbers: one is n by n, the other is (n+1) by (n+1).
- The total area of both tiles is 545 square units.
- Areas of squares come from side × side. So, the total area is:
  - area of the smaller square: n²
  - area of the larger square: (n+1)²

So we translate the sentence into an equation:
```math
n^2 + (n+1)^2 = 545
```

Why squares? Because “square of an integer” literally came from the area of a square with that integer as side length—this is a natural, visual meaning.

Also, a quick “sanity check”: one of the consecutive integers is even and the other is odd, so their squares are even and odd respectively, and even + odd = odd. The sum 545 is odd, so that fits.

---

### 2) Expand step-by-step, using structure (not memorized tricks)
We open up the expression (n+1)² by thinking of it as (n+1)(n+1): that’s the area of a square n×n with an extra “L-shaped” border of thickness 1, plus one extra 1×1 corner.

So:
```math
(n+1)^2 = n^2 + 2n + 1
```
Substitute back:
```math
n^2 + (n^2 + 2n + 1) = 545
2n^2 + 2n + 1 = 545
```
Move everything to one side so we can “see” the structure we need to solve:
```math
2n^2 + 2n - 544 = 0
```
Divide by 2 to simplify:
```math
n^2 + n - 272 = 0
```

---

### 3) Solve by completing the square (derive it logically)
We want to turn the left side into a perfect square because perfect squares are easy to “unsquare” by taking square roots.

Notice how n² + n is close to a square. If you take (n + 1/2)² and expand it:
```math
(n + \tfrac{1}{2})^2 = n^2 + n + \tfrac{1}{4}
```
So n² + n becomes a perfect square if we add 1/4. Let’s do that to both sides to keep the balance:
```math
n^2 + n - 272 = 0
n^2 + n = 272
n^2 + n + \tfrac{1}{4} = 272 + \tfrac{1}{4}
(n + \tfrac{1}{2})^2 = 272.25
```
Note 272.25 = 1089/4, and 1089 = 33² (since 30² = 900, 35² = 1225, and 33² = 1089).
So:
```math
(n + \tfrac{1}{2})^2 = \frac{1089}{4} = \left(\frac{33}{2}\right)^2
```
Taking square roots (both positive and negative are possible for the number inside the square):
```math
n + \tfrac{1}{2} = \pm \tfrac{33}{2}
```
Solve both:
```math
n = -\tfrac{1}{2} + \tfrac{33}{2} = \tfrac{32}{2} = 16
n = -\tfrac{1}{2} - \tfrac{33}{2} = -\tfrac{34}{2} = -17
```
We need positive integers (as stated), so take n = 16. The consecutive numbers are 16 and 17.

Check:
```math
16^2 + 17^2 = 256 + 289 = 545
```
Perfect.

Answer: 16, 17 → Option B.

---

## Multiple ways to see it (build flexible thinking)

### A) Quick estimation (engineering intuition)
- If the two numbers are close, pretend both are roughly x. Then 2x² ≈ 545 → x² ≈ 272.5 → x ≈ 16.5.
- So the pair is likely around 16 and 17. This narrows the search instantly, then verify exactly.

### B) Symmetry trick
Start from:
```math
n^2 + (n+1)^2 = 2n^2 + 2n + 1 = 2(n^2 + n) + 1
```
Complete the square inside:
```math
n^2 + n = (n + \tfrac{1}{2})^2 - \tfrac{1}{4}
```
So:
```math
2(n^2 + n) + 1 = 2\left((n + \tfrac{1}{2})^2 - \tfrac{1}{4}\right) + 1 = 2(n + \tfrac{1}{2})^2 + \tfrac{1}{2}
```
Set equal to 545:
```math
2(n + \tfrac{1}{2})^2 + \tfrac{1}{2} = 545
2(n + \tfrac{1}{2})^2 = 544.5
(n + \tfrac{1}{2})^2 = 272.25 = 16.5^2
```
Same conclusion: n + 1/2 = ±16.5 → n = 16 or -17 → choose 16.

### C) Option check (verification, not primary method)
- 15,16 → 225 + 256 = 481 (too small)
- 16,17 → 256 + 289 = 545 (exact)
- 21,17 → 441 + 289 = 730 (too big)
- 6,12 → 36 + 144 = 180 (too small)

---

## Final Answer
- Integers: 16 and 17
- Option: B

---

## 1) Conceptual follow-up questions
- If the sum of squares of two consecutive integers is odd, must one be even and one odd? Why?
- If the sum were 546 instead of 545, could two consecutive integers work? Explain using parity (odd/even) logic.
- What if the numbers were consecutive even integers instead (like 2k and 2k+2)? How would the equation change?
- If the sum of squares is S, show that S − 1/2 must equal 2(n + 1/2)². What does this say about the “shape” of possible S values?

---

## 2) Applications to real-world thinking
- Signal processing: Energy in a signal often involves sums of squares (like power = sum of squared amplitudes). Estimating nearby values (like we did with x ≈ 16.5) is crucial in engineering for quick checks.
- Geometry and design: Completing the square is literally “adding a small piece” to make a perfect square—think of cutting and rearranging materials to form clean shapes.
- Data science: Least squares methods minimize sums of squares. Understanding how squares behave (and completing the square) gives geometric intuition for optimization.

---

## 3) Common misconceptions and how to avoid them
- Mistake: Forgetting both positive and negative roots when taking square roots. Fix: Always write ± and then use context (positive integers here) to decide.
- Mistake: Expanding (n+1)² as n² + 1. Fix: Remember the middle term 2n comes from the two side rectangles in the geometric picture.
- Mistake: Jumping to the quadratic formula without understanding. Fix: Complete the square to see the structure—this teaches where the formula comes from.

---

## 4) Extension challenges
- Generalize: Find all integers n such that n² + (n+1)² = S has an integer solution. What condition must S satisfy?
- Explore: Solve n² + (n+k)² = S for a fixed k (not just k=1). Complete the square and analyze when integer solutions exist.
- Number theory twist: Prove that the sum of squares of two consecutive integers is always odd.
- Inverse problem: If n² + (n+1)² = m² (a perfect square), find all integer solutions (a Diophantine equation).

---

## 5) Reflective insight — the essence
This problem is about recognizing structure. Two consecutive squares naturally combine into a tidy form when you “center” them at the halfway point n + 1/2. Completing the square is just a precise way to express symmetry: move to the center, then measure the squared distance from that center. Once you see that, the path to the solution becomes simple, logical, and memorable.