## Question

Sum of 15 terms of the series $1+3+5+7+$ $\_\_\_\_$ is

## Big idea (start from everyday observation)
- Imagine building a square floor with square tiles:
  - 1 tile makes a 1×1 square.
  - To grow to a 2×2 square, you add a border of 3 tiles.
  - To grow to a 3×3 square, you add a border of 5 tiles.
- Each time you go from an n×n square to an (n+1)×(n+1) square, you must add a “ring” of tiles around the edges. That ring always has an odd number of tiles: 3, 5, 7, etc.
- So “adding odd numbers” is exactly the same as “building bigger and bigger squares.”

This gives a powerful pattern: the sum of the first n odd numbers makes an n×n square.

## Visual/Geometric Derivation (first principles)
- Start with 1 = 1×1 (a 1×1 square).
- Add 3 to get 4 = 2×2.
- Add 5 to get 9 = 3×3.
- Add 7 to get 16 = 4×4.
- Continue…

So after adding the first n odd numbers, the total is n². Why? Because each new odd number adds exactly the tiles needed to go from n² to (n+1)².

We can express the “ring” idea algebraically as the difference of consecutive squares:
```math
(k+1)^2 - k^2 = 2k + 1
```
Notice 2k + 1 is an odd number. Now sum both sides from k = 0 to n − 1:
```math
\sum_{k=0}^{n-1} \big[(k+1)^2 - k^2\big] = \sum_{k=0}^{n-1} (2k + 1)
```
The left telescopes (everything cancels except the ends):
```math
n^2 - 0^2 = \sum_{k=0}^{n-1} (2k + 1)
```
So:
```math
\sum_{k=1}^{n} \text{(odd numbers)} = n^2
```

## Apply to 15 terms
The first 15 odd numbers are 1, 3, 5, …, 29. Therefore:
```math
\text{Sum of first 15 odd numbers} = 15^2 = 225
```
Quick mental check:
```math
15^2 = (10 + 5)^2 = 10^2 + 2\cdot10\cdot5 + 5^2 = 100 + 100 + 25 = 225
```

## Alternative Derivation (Arithmetic-series reasoning from scratch)
1. Recognize this is an arithmetic sequence: start a = 1, common difference d = 2.
2. List n terms forward and backward, then add term-by-term:

Forward:
```math
S_n = (1) + (3) + (5) + \dots + (2n-1)
```
Backward:
```math
S_n = (2n-1) + (2n-3) + \dots + (1)
```
Add vertically:
```math
2S_n = (1 + 2n-1) + (3 + 2n-3) + \dots + (2n-1 + 1)
```
Each pair equals 2n, and there are n pairs:
```math
2S_n = n \cdot (2n) \quad \Rightarrow \quad S_n = n^2
```
For n = 15:
```math
S_{15} = 15^2 = 225
```

## Intuition and “units”
- Think of each odd number as “number-of-tiles” added.
- Adding increasing odd numbers (2k−1) is like stacking “border rings” around a square: borders grow linearly with k, but the total area grows quadratically (k²). That’s why the sum becomes a square number.

## Final Answer
```math
\boxed{225}
```

---

## Conceptual Follow-up Questions
1. If the sum of the first n odd numbers is 400, what is n? (Hint: n² = 400.)
2. What is the sum of the first n even numbers? Explain from first principles (think pairs or rectangles).
3. Without adding, what is the 15th odd number? Why? (Hint: a + (n−1)d.)
4. What is the sum of the odd numbers from the 6th to the 15th term? How can you avoid re-adding from the start?

## Application Questions
- Pixel grids: If a camera sensor grows from n×n to (n+1)×(n+1) pixels, how many new pixels were added? Why does this relate to an odd number?
- Stadium seating: If each successive ring of seats increases by a fixed “thickness,” why does total seating look quadratic in the number of rings?
- Robotics: A robot paints concentric square borders. If border k needs 2k−1 units of paint, how much paint for the first n borders? Why is it n²?

## Common Misconceptions and Traps
- “Average = (first + last)/2 always.” Only true for equally spaced (arithmetic) sequences. Odd numbers are equally spaced by 2, so it works here—but not for arbitrary sequences.
- Confusing “15 terms” with “numbers up to 15.” The 15th odd number is 29, not 15.
- Forgetting the last term formula: last term = a + (n−1)d; here 1 + 14×2 = 29.
- Thinking growth is linear: adding odd numbers leads to quadratic growth because each step adds a linearly growing amount.

## Extension Challenges
1. General sum of an arithmetic sequence, derived by pairing:
   ```math
   S_n = \frac{n}{2}\big[2a + (n - 1)d\big]
   ```
   Apply it to a = 1, d = 2 to recover n².
2. Show that:
   ```math
   \sum_{k=1}^{n} (2k - 1) = n^2
   \quad\text{and}\quad
   \sum_{k=1}^{n} (2k) = n(n + 1)
   ```
   Explain both geometrically (squares vs rectangles).
3. Telescoping proof variant: Use
   ```math
   2k - 1 = k^2 - (k - 1)^2
   ```
   and sum from k = 1 to n.
4. Design thinking: If you want the total number of tiles to grow like a cube (n³), what kind of “layer” sizes would you need to add each step? Explore the idea of discrete integration.

## Reflective Insight (the deep “why”)
Adding odd numbers builds perfect squares because each new odd number is exactly the extra “border” needed to grow one square into the next. In algebra, that’s the identity (k+1)² − k² = 2k + 1. In geometry, it’s a ring of tiles. In thinking terms, it reveals a universal pattern: sums of linearly growing steps create quadratic totals. Once you see this, many sequences become intuitive rather than memorized.