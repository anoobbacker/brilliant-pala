## Question

$100^{100}$ is divided by $50^{50}$ then the
quotient is

**Options:**

1. $50^{50}$
2. $50^{100}$
3. $200^{50}$
4. $400^{50}$

## Big idea (everyday start)
Think of an exponent as “how many copies of the same factor are multiplied together.” For example, $100^{100}$ means 100 multiplied by itself 100 times. Dividing by $50^{50}$ means we cancel out 50 copies of 50 from the product if they are present.

Also notice: 100 is just “twice 50.” That simple ratio (2:1) will guide the whole simplification.

## Step-by-step derivation from first principles

### 1) Rewrite 100 in terms of 50
Because 100 = 2 × 50, we can rewrite each 100 as (2 × 50). So:
```math
100^{100} = (2 \times 50)^{100}
```
What does this mean? It means we have 100 copies of (2 × 50) multiplied together:
```math
(2 \times 50)\times(2 \times 50)\times\cdots\times(2 \times 50) \quad \text{(100 times)}
```
By the idea of grouping and rearranging (multiplication is associative and commutative), we can collect all the 2’s together and all the 50’s together:
```math
(2 \times 50)^{100} = 2^{100}\times 50^{100}
```
This is why the rule (ab)^n = a^n b^n works: it’s just regrouping identical factors.

### 2) Now divide by $50^{50}$
We have:
```math
\frac{100^{100}}{50^{50}} = \frac{2^{100}\,50^{100}}{50^{50}}
```
Dividing by $50^{50}$ cancels 50 of the 100 copies of 50 in the numerator:
```math
\frac{50^{100}}{50^{50}} = 50^{100-50} = 50^{50}
```
So the expression becomes:
```math
\frac{100^{100}}{50^{50}} = 2^{100}\times 50^{50}
```
Why is $a^m/a^n = a^{m-n}$? Because you cancel common factors: $a^m$ has m copies of a; dividing by $a^n$ removes n of them, leaving $m-n$ copies.

### 3) Combine the remaining factors into a single neat power
We have $2^{100}\times 50^{50}$. Notice that $2^{100}$ is 100 twos. Pair them into 50 groups of $(2 \times 2)=4$:
```math
2^{100} = (2^2)^{50} = 4^{50}
```
So now:
```math
2^{100}\times 50^{50} = 4^{50}\times 50^{50}
```
When two terms have the same exponent, multiplying them corresponds to multiplying their bases first, then raising to that exponent:
```math
a^n \times b^n = (ab)^n
```
Reason: you have n copies of a and n copies of b; pair each a with one b to make n copies of ab. Thus:
```math
4^{50}\times 50^{50} = (4\times 50)^{50} = 200^{50}
```

### Final answer
```math
\frac{100^{100}}{50^{50}} = 200^{50}
```
So the correct option is 3) $200^{50}$.

## A second, equally “from-first-principles” path
Group the 100 copies of 100 into two equal blocks of 50:
```math
100^{100} = (100^{2})^{50}
```
Why? Because $(a^2)^{50} = a^{2\times 50} = a^{100}$ (you’re making 50 groups, each group contributes two a’s, total 100 a’s).

Then
```math
\frac{100^{100}}{50^{50}} = \frac{(100^2)^{50}}{50^{50}} = \left(\frac{100^2}{50}\right)^{50}
```
Reason: with the same exponent in numerator and denominator, $(A^{50})/(B^{50}) = (A/B)^{50}$ — you’re dividing each of the 50 corresponding factors.

Compute the base:
```math
\frac{100^2}{50} = \frac{10000}{50} = 200
```
Hence:
```math
\left(\frac{100^2}{50}\right)^{50} = 200^{50}
```
Same result.

## Quick intuition check
- Since 100 is double 50, and you have many copies, you should expect a result involving a power of 2 times something. The neat regrouping leads to $(200)^{50}$, which is consistent with “fifty times” of combining a factor 4 with a 50 to make 200.

---

## Conceptual follow-up questions
1. If $a = 2b$, simplify $\dfrac{a^{10}}{b^{5}}$ using the same reasoning.  
2. Which is larger: $100^{100}$ or $200^{50}$? Explain without a calculator.  
3. If $x = 5y$, evaluate $\dfrac{x^{6}}{y^{3}}$ in terms of y only, then as a single power.  
4. Why does $(ab)^n = a^n b^n$ make sense from the viewpoint of repeated multiplication?

## Application questions (real-world connections)
- In image scaling, doubling each dimension multiplies area by 4. If you scale a square photo by a factor of 2 fifty times in one direction and combine with 50 factors of the original size, what total scale results? Connect this to turning $4^{50}\cdot 50^{50}$ into $(200)^{50}$.
- In computing, powers of 2 are everywhere. If a storage unit doubles in size (factor 2) a hundred times, and you then group those upgrades into 50 larger “package units” each combined with a base unit of size 50, what is the combined size? Interpret this as $2^{100}\cdot 50^{50}$ becoming $(200)^{50}$.

## Common misconceptions and how to avoid them
- Trap: Thinking $100^{100}/50^{50} = (100/50)^{100} = 2^{100}$.  
  Why it’s wrong: You changed the exponents inconsistently. The denominator had only 50 copies, not 100. Correct regrouping gives $(100^{2}/50)^{50}$ or $2^{100}\cdot 50^{50}$, not $2^{100}$.
- Trap: Trying to add or subtract exponents across different bases, like $100^{100}/50^{50} = (100/50)^{100-50}$.  
  Why it’s wrong: Exponent subtraction $a^{m}/a^{n} = a^{m-n}$ only works for the same base a.
- Trap: Cancelling 50 with 100 inside the exponents (treating them like fractions) without understanding the meaning of exponents.  
  Fix: Always translate exponents to “how many identical factors,” then cancel factors logically.

## Extension challenges
- Generalize: If $a = kb$, simplify $\dfrac{a^{n}}{b^{m}}$ as a single power when possible. Explore cases for $n\ge m$ and $n<m$.
- Evaluate and express as a single base:
  - $\dfrac{27^{10}}{9^{5}}$  
  - $\dfrac{12^{8}}{3^{8}}$  
  - $\dfrac{50^{75}}{100^{25}}$
- Prove from first principles that:
  - $(ab)^n = a^n b^n$  
  - $\dfrac{a^m}{a^n} = a^{m-n}$ for integers $m\ge n$  
  - $(a^p)^q = a^{pq}$
  Do it by expanding as repeated multiplication and regrouping, not by quoting formulas.

## Reflective insight (the essence)
Exponents are just organized counting of repeated multiplication. The “laws of exponents” are not magic rules; they’re consequences of regrouping and cancelling identical factors. When you’re stuck, return to first principles: write out what the exponent means (how many copies), pair or cancel factors carefully, and reassemble. This mindset lets you confidently handle even unfamiliar expressions—like turning $100^{100}/50^{50}$ into the clean single power $200^{50}$.