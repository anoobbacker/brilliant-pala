## Question

If 5 is the remainder when $3x^2 + mx - 2$ is divided by $x + 2$, then $m$ is:

**Options:**
- A) 5
- B) 15
- C) –5
- D) 2
- E) 3

## Understand the situation from everyday logic

- Think of dividing candies into packs of size (x + 2). You’ll get some full packs (the quotient) and a small leftover (the remainder).
- In algebra, when you divide any polynomial P(x) by a linear divisor like x + 2, the remainder must be a constant number (because any leftover can’t still depend on x if the divisor is first-degree).

This idea is captured by the structure:
```math
P(x) = (x + 2)\,Q(x) + r
```
- Q(x) is the quotient (another polynomial).
- r is the remainder (a constant, since degree of remainder < degree of divisor).

Now ask: What happens if we choose x = –2? Then x + 2 = 0, so the big product disappears:
```math
P(-2) = (0)\cdot Q(-2) + r = r
```
So, the remainder when you divide by x + 2 is exactly P(–2). This is the Remainder Theorem, derived from first principles (no memorization).

## Apply it to the given polynomial

Given:
```math
P(x) = 3x^2 + mx - 2
```
If the remainder when dividing by x + 2 is 5, then:
```math
P(-2) = 5
```
Compute P(–2):
```math
P(-2) = 3(-2)^2 + m(-2) - 2 = 3(4) - 2m - 2 = 12 - 2m - 2 = 10 - 2m
```
Set equal to 5:
```math
10 - 2m = 5
-2m = -5
m = \frac{5}{2} = 2.5
```

## Answer
m = 5/2 = 2.5

## Important note about the options
None of the listed options (A: 5, B: 15, C: –5, D: 2, E: 3) equals 2.5. So the correct value of m is not among the given choices. This suggests a likely typo in the problem or options. For reference:
- If m = 2, the remainder would be 6.
- If m = 3, the remainder would be 4.
- If m = 5, the remainder would be 0 (exactly divisible).

## A second, fully “from scratch” method (no theorem)
Assume the quotient is linear: Q(x) = Ax + B (since dividing a quadratic by a linear gives a linear quotient). Then:
```math
3x^2 + mx - 2 = (x + 2)(Ax + B) + r
```
Expand:
```math
(x + 2)(Ax + B) = Ax^2 + (2A + B)x + 2B
```
Match coefficients with 3x^2 + mx − 2:
- x^2 term: A = 3
- x term: 2A + B = m ⇒ 6 + B = m ⇒ B = m − 6
- constant term: 2B + r = −2 ⇒ 2(m − 6) + r = −2 ⇒ r = 10 − 2m

Given remainder r = 5:
```math
10 - 2m = 5 \Rightarrow m = \frac{5}{2}
```
Same result.

---

## 1) Conceptual follow-up questions
- Why must the remainder be constant when dividing by a linear polynomial like x + 2?
- If the divisor were quadratic (say x^2 + 1), what shape could the remainder have?
- If P(−2) = 0, what does that say about x + 2 and the factorization of P(x)?
- How would you explain the idea P(−2) = remainder to someone using just the “plug in and zero-out” argument?

## 2) Applications to real life and modern tech
- Digital communications (CRCs): Computers use polynomial long division over bits (mod 2 arithmetic). The remainder is the “checksum” that detects errors in transmission. Why is a remainder a good error detector?
- Control systems: Evaluating polynomials at particular inputs tests system behavior at critical points (like poles/zeros). How does P(a) = 0 signify a special “cancellation” point?

## 3) Common misconceptions and traps
- Trap: Thinking the remainder depends on x when dividing by a linear divisor. Fix: Degree of remainder < degree of divisor; hence for linear divisors, the remainder is a constant.
- Trap: Plugging x = 2 instead of x = −2 for x + 2. Fix: Always set divisor to zero: x + 2 = 0 ⇒ x = −2.
- Trap: Forgetting to distribute minus signs: 3(−2)^2 is 12, not −12.

## 4) Extension challenges
- If 3x^2 + mx − 2 leaves remainder 0 when divided by x + 2 and remainder 4 when divided by x − 1, find m. (Hint: use P(−2) = 0 and P(1) = 4.)
- Find m so that x + 2 is a factor and the other factor also has integer coefficients.
- For P(x) = ax^2 + bx + c, derive the general expression for the remainder upon division by x + h in terms of a, b, c, h.

## 5) Reflective insight
The heart of the idea: Division by x + 2 creates a “zero switch” at x = −2. Choosing x = −2 shuts off the whole divisible part, revealing the hidden leftover in one clean evaluation. That’s why P(−2) equals the remainder. This “zeroing trick” underlies many powerful theorems in algebra: plug in the root of the divisor, and you isolate the remainder. Understanding this mechanism makes the Remainder and Factor Theorems feel inevitable, not magical.