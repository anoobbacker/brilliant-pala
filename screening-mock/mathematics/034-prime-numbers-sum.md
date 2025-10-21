## Question

Sum of smallest and largest two digit prime
numbers is

**Options:**

1. 103
2. 105
3. 108
4. 106

## Understand the task in plain language
Think of whole numbers like Lego blocks. Some blocks can be split into smaller identical blocks (like 12 = 3 × 4), while others cannot be split evenly except as 1 × itself. The “unsplittable” ones are primes.

The question asks: among all two-digit primes (from 10 to 99), take the smallest one and the largest one, and add them. What do you get?

## Step 1: What is a prime—first principles
- A number is prime if it has exactly two positive divisors: 1 and itself.
- A number is composite if it can be expressed as a product of two smaller natural numbers (not 1 times itself).

Why this definition? Because we want “building blocks” of all numbers—like atoms in chemistry. Every whole number can be built from primes by multiplication in one unique way (Fundamental Theorem of Arithmetic).

## Step 2: How to test if a number is prime (logic, not memorization)
If a number n can be factored, it must be n = a × b for some integers a and b. Without loss of generality, let a ≥ b. Then b × b ≤ a × b = n, so b ≤ √n. This means:
- If n has any factor at all (besides 1 and n), at least one factor is ≤ √n.
- So to check if n is prime, you only need to test divisibility by numbers up to √n.

```math
\text{If } n = a b \text{ with } a \ge b \Rightarrow b^2 \le ab = n \Rightarrow b \le \sqrt{n}.
```

This saves work and explains “why” we can stop at √n.

## Step 3: Find the smallest two-digit prime
Two-digit numbers start at 10.

- 10: even, so 10 = 2 × 5 (composite).
- 11: check divisors up to √11. Since √11 ≈ 3.31, only test 2 and 3.
  - 11 ÷ 2 is not whole (11 is odd).
  - 11 ÷ 3 is not whole (3 × 3 = 9, 3 × 4 = 12).
  - So 11 has no factors other than 1 and 11 → 11 is prime.

Therefore, the smallest two-digit prime is 11.

## Step 4: Find the largest two-digit prime
Two-digit numbers end at 99. Work downwards and eliminate obvious composites using simple logic:
- 99: divisible by 3 (sum of digits 9+9=18, and 18 is divisible by 3), so composite.
  Why does “sum of digits” work for 3? Because 10 ≡ 1 (mod 3), so powers of 10 are ≡ 1, and a number’s value mod 3 equals the sum of its digits mod 3.
  ```math
  10 \equiv 1 \pmod{3} \Rightarrow 10^k \equiv 1 \Rightarrow \sum d_k 10^k \equiv \sum d_k \pmod{3}.
  ```
- 98: even, so divisible by 2 → composite.
- 97: test primes up to √97. Since √97 ≈ 9.85, test 2, 3, 5, 7 only.
  - Not divisible by 2 (odd).
  - Not divisible by 3 (9+7=16, not a multiple of 3).
  - Not divisible by 5 (doesn’t end in 0 or 5).
  - Not divisible by 7 (7×13=91, 7×14=98; no exact hit).
  - Therefore 97 has no factors ≤ √97 → 97 is prime.

So the largest two-digit prime is 97.

## Step 5: Add them
```math
\text{Sum} = 11 + 97 = 108
```

Answer: 108. Option 3.

---

## Multiple viewpoints (why this conclusion is robust)
- Analytical: Stopping at √n is guaranteed because any factor pair straddles √n.
- Pattern-based filters: Any prime greater than 5 must end with 1, 3, 7, or 9 (to avoid factors 2 and 5). This quickly rules out many candidates.
- Experimental (sieve idea): If you cross out multiples of 2, 3, 5, and 7 under 100, the largest remaining un-crossed number is 97.

---

## 1) Conceptual follow-up questions
- Why can’t any prime (other than 2) be even? Why can’t any prime (other than 5) end with 5?
- Explain in your own words why checking divisors only up to √n is sufficient.
- What is the smallest and largest two-digit composite number? What is their sum?
- Is 91 prime? Reason it out without a calculator.
- If you were told the sum of two primes is 108, what pairs of two-digit primes could make that sum?

## 2) Applications to real life and modern science
- Cryptography (RSA): Large primes are used to build “locks” that are easy to make (multiply two large primes) but hard to break (factor the product). Two-digit primes are toy examples; real systems use hundreds of digits.
- Error checking: Divisibility rules (like for 3 and 9) help design quick checksum tests in barcodes and ID numbers.
- Computer science: Efficient primality tests (e.g., Miller–Rabin) allow fast checking of huge numbers without full factorization.

## 3) Common misconceptions and traps
- “1 is prime.” False. A prime must have exactly two distinct positive divisors (1 and itself).
- “You must test all numbers up to n.” Unnecessary. Only test up to √n.
- “Ends with 1, 3, 7, 9 means prime.” Not sufficient—many composites end with those digits (e.g., 91 = 7×13).
- Misusing digit-sum rules: The sum-of-digits test works for divisibility by 3 and 9, not for 7 or 11.

## 4) Extension challenges
- Prove there are infinitely many primes using Euclid’s idea: multiply a list of primes and add 1.
- Find the smallest and largest three-digit primes and their sum. Outline your testing plan before computing.
- Design a quick human-friendly method to find the largest prime less than 200 without listing all primes.
- In base-12 (duodecimal), rethink the “last digit” tests for divisibility by 2 and 3. How do prime-ending digits change?

## 5) Reflective insight — the deep “why”
Primality is about indivisibility. Factor pairs come in “below √n” and “above √n” partners; this symmetry is why the √n boundary is the natural stopping point. Once you internalize factor-pair symmetry and simple divisibility filters (2, 3, 5, 7), you can reason about primes confidently—even in unfamiliar settings.

Final answer: 108 (Option 3).