## Question

If $x^2 - 3x - 4$ divides $p(x)$ completely, then the corresponding factors are:

**Options:**
- A) $(x - 4)(x + 1)$
- B) $(x - 4)(x - 1)$
- C) $(x + 4)(x - 1)$
- D) $(x + 4)(x + 1)$
- E) None of these

## Big idea (from everyday thinking)
Factoring a polynomial is like breaking a complex shape into simpler “building blocks.” For numbers, 12 = 3×4. For areas, a rectangle’s area = length × width. For a quadratic like x^2 − 3x − 4, we try to express it as the product of two simpler linear pieces, like (x + something)(x + something), because multiplying these “lengths” will rebuild the area (the polynomial).

## What does “divides completely” mean?
If x^2 − 3x − 4 divides p(x) completely, it means p(x) contains x^2 − 3x − 4 as a factor with no remainder. So the “corresponding factors” must be the linear pieces that multiply to x^2 − 3x − 4.

So our task is: factor x^2 − 3x − 4 into two linear factors.

## Deriving the factor form from first principles
Start with the most general way two linear expressions multiply:
```math
(x + m)(x + n) = x(x + n) + m(x + n) = x^2 + nx + mx + mn = x^2 + (m + n)x + mn.
```
This is just the distributive law twice—no memorized formula, just expanding and regrouping.

To match x^2 − 3x − 4, we require:
```math
m + n = -3
mn = -4
```

Now, which two numbers multiply to −4 and add to −3? Test integer pairs with product −4:
- 1 and −4 → sum = −3 (works!)
- −1 and 4 → sum = 3 (no)
- 2 and −2 → sum = 0 (no)

So m = 1 and n = −4 (or swapped). Therefore,
```math
x^2 - 3x - 4 = (x + 1)(x - 4) = (x - 4)(x + 1).
```

Hence, the corresponding factors are (x − 4) and (x + 1).

Answer: A) (x − 4)(x + 1)

---

## Alternative first-principles approach: “roots” via completing the square
If a polynomial equals zero at some x-values (called roots), then it must factor as (x − root1)(x − root2). Let’s find those values without any memorized formulas.

Solve x^2 − 3x − 4 = 0 by completing the square:
```math
x^2 - 3x = 4
x^2 - 3x + \left(\frac{3}{2}\right)^2 = 4 + \left(\frac{3}{2}\right)^2
\left(x - \frac{3}{2}\right)^2 = \frac{25}{4}
x - \frac{3}{2} = \pm \frac{5}{2}
x = \frac{3 \pm 5}{2} \Rightarrow x = 4 \text{ or } x = -1.
```
So the factors are (x − 4) and (x + 1). This independently confirms Option A.

---

## Why this connects to divisibility
- If p(4) = 0, then x − 4 is a factor of p(x). Why? Because if p(x) = (x − 4)q(x), substituting x = 4 makes the first factor zero, so the whole product is zero (zero-product idea).
- Similarly, p(−1) = 0 implies x + 1 is a factor.
- Since x^2 − 3x − 4 = (x − 4)(x + 1), any polynomial divisible by x^2 − 3x − 4 must contain both factors.

---

## Final choice
- A) (x − 4)(x + 1) ✓
- B) (x − 4)(x − 1) ✗ gives x^2 − 5x + 4
- C) (x + 4)(x − 1) ✗ gives x^2 + 3x − 4
- D) (x + 4)(x + 1) ✗ gives x^2 + 5x + 4
- E) None of these ✗

Answer: A

---

## Conceptual follow-up questions
1. If x^2 + bx + c factors as (x + m)(x + n), why must m + n = b and mn = c? Re-derive using the distributive law.
2. If a quadratic has roots r and s, explain why it must equal k(x − r)(x − s) for some constant k.
3. What happens if no real m, n satisfy m + n = b and mn = c? What does that say about the graph y = x^2 + bx + c?

## Application questions
- Engineering: A quadratic resonance curve often factors into two linear terms in frequency. How does identifying roots help predict frequencies that nullify vibration?
- Computer graphics: Collision detection uses solving quadratic equations for time-of-impact. Why is factoring helpful to find when contact begins and ends?

## Common misconceptions and reasoning traps
- Trap: Thinking the signs inside factors match the signs of b and c directly. Fix: Always use m + n = b and mn = c; test pairs logically.
- Trap: Assuming every quadratic factors nicely over integers. Fix: If no integer pair fits mn = c and m + n = b, try completing the square or quadratic formula to find irrational/complex roots.
- Trap: Mixing up (x − a)(x − b) = x^2 − (a + b)x + ab. Fix: Re-expand to check; the sign in front of x depends on the sum of the roots.

## Extension challenges
1. Factor x^2 + 2x − 15 by reconstructing m + n and mn, then verify by expansion.
2. For kx^2 − 3x − 4, find the factorization in terms of k using completing the square or root method.
3. If a quadratic has one root at 5 and axis of symmetry at x = 3, find the other root and the factorization.

## Reflective insight
The essence: Factoring quadratics is just reversing the distributive law. The coefficients tell a story: the x-term coefficient is the sum of the numbers in the linear factors, and the constant is their product. Whether you approach it by matching sums/products or by finding roots via completing the square, you’re uncovering the same structure: a quadratic is a stretched and shifted version of (x − r)(x − s). Once you see that skeleton, unfamiliar versions become manageable.