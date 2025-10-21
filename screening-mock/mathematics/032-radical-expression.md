## Question

Value of
$\frac{1}{\sqrt{32}-\sqrt{18}}+\frac{1}{\sqrt{98}-\sqrt{72}}$ is

**Options:**

1. $\sqrt{2}$
2. $\frac{1}{\sqrt{2}}$
3. $\frac{1}{2 \sqrt{2}}$
4. $2 \sqrt{2}$

## Intuition First: What does a square root mean?
- If a square has area A (in square units), its side length is √A (in length units).
- If you scale the area by a factor of 16, the side scales by 4 (because side^2 = area → side = √area).
- If you scale the area by a factor of 2, the side scales by √2.

This is why numbers like √2 appear when comparing diagonals of squares, paper sizes (A4 to A3), etc. We’ll use this “area-to-side-length” logic to simplify the square roots.

## Rebuilding the key property: √(ab) = √a · √b (for a,b ≥ 0)
- Think of a rectangle with area ab = (area a) × (area b). If one side is √a and we stretch it by √b, the new side is √a·√b, and the area becomes (√a·√b)^2 = ab.
- Since both √(ab) and √a·√b are the positive lengths whose squares equal ab, they must be equal.

We’ll use this to pull perfect square factors out of square roots.

## Step-by-step simplification
Break each radicand into a perfect square times something simple:
- 32 = 16·2, 18 = 9·2, 98 = 49·2, 72 = 36·2

So:
```math
\sqrt{32}=\sqrt{16\cdot 2}=4\sqrt{2}
```
```math
\sqrt{18}=\sqrt{9\cdot 2}=3\sqrt{2}
```
```math
\sqrt{98}=\sqrt{49\cdot 2}=7\sqrt{2}
```
```math
\sqrt{72}=\sqrt{36\cdot 2}=6\sqrt{2}
```

Now look at each denominator:
```math
\sqrt{32}-\sqrt{18}=4\sqrt{2}-3\sqrt{2}=\sqrt{2}
```
```math
\sqrt{98}-\sqrt{72}=7\sqrt{2}-6\sqrt{2}=\sqrt{2}
```

So each fraction becomes:
```math
\frac{1}{\sqrt{32}-\sqrt{18}}=\frac{1}{\sqrt{2}},\quad \frac{1}{\sqrt{98}-\sqrt{72}}=\frac{1}{\sqrt{2}}
```

Add them:
```math
\frac{1}{\sqrt{2}}+\frac{1}{\sqrt{2}}=\frac{2}{\sqrt{2}}
```

And simplify:
- Note that 2 = √2·√2, so 2/√2 = √2.
- Or “rationalize” by multiplying top and bottom by √2:
```math
\frac{2}{\sqrt{2}}\cdot\frac{\sqrt{2}}{\sqrt{2}}=\frac{2\sqrt{2}}{2}=\sqrt{2}
```

## Answer
```math
\sqrt{2}
```
So the correct option is 1. √2.

---

## A second (equally first-principled) approach: Conjugates
Why does this work? Because (a−b)(a+b)=a^2−b^2 removes the roots.

For the first term:
```math
\frac{1}{\sqrt{32}-\sqrt{18}}=\frac{\sqrt{32}+\sqrt{18}}{(\sqrt{32}-\sqrt{18})(\sqrt{32}+\sqrt{18})}=\frac{\sqrt{32}+\sqrt{18}}{32-18}=\frac{\sqrt{32}+\sqrt{18}}{14}
```
Now simplify the roots:
```math
\frac{4\sqrt{2}+3\sqrt{2}}{14}=\frac{7\sqrt{2}}{14}=\frac{\sqrt{2}}{2}=\frac{1}{\sqrt{2}}
```
The second term gives the same. Sum = √2.

This confirms the result from a different angle.

---

## Quick numerical “experiment” (sanity check)
- √32 ≈ 5.657, √18 ≈ 4.243 → denominator ≈ 1.414 → its reciprocal ≈ 0.7071
- √98 ≈ 9.899, √72 ≈ 8.485 → denominator ≈ 1.414 → its reciprocal ≈ 0.7071
- Sum ≈ 1.414 ≈ √2

---

## Conceptual follow-up questions
1. If you see 1/(√(50)−√(8)), can you factor out √2 first? What does it become?
2. For which numbers a,b of the form a=k·2 and b=m·2 does √a−√b collapse to a single multiple of √2?
3. Why is √(a)−√(b) not equal to √(a−b)? Give a counterexample.
4. If A and B are areas of two squares, what does √A−√B represent geometrically?

## Application questions
- Why do paper sizes (A0, A1, A2, …) use a √2 aspect ratio? How does doubling area lead to multiplying side lengths by √2?
- The diagonal of a square is s√2 if the side is s. How does this relate to the idea that scaling area by 2 scales lengths by √2?

## Common misconceptions and traps
- Mistake: Thinking √(a−b)=√a−√b. Not true; test a=9, b=4: √5 ≠ 3−2.
- Skipping the step of extracting perfect squares from under the root. Always break numbers like 32, 18, 98, 72 into (perfect square)×(rest).
- Forgetting that rationalizing with conjugates eliminates roots because (a−b)(a+b)=a^2−b^2.

## Extension challenges
1. Generalize: Evaluate
```math
\frac{1}{\sqrt{2n^2}-\sqrt{2m^2}}
```
in simplest form. When does it simplify nicely?
2. Evaluate and simplify:
```math
\frac{1}{\sqrt{a} - \sqrt{b}} + \frac{1}{\sqrt{a} + \sqrt{b}}
```
using conjugates; what cancels?
3. Show that for positive x,y:
```math
\frac{1}{\sqrt{x}-\sqrt{y}}=\frac{\sqrt{x}+\sqrt{y}}{x-y}
```
and discuss when this is useful.

## Reflective insight
The essence: Square roots convert areas into lengths. Factoring perfect squares “pulls out” clean length multipliers, exposing shared factors like √2. Conjugates then exploit the difference-of-squares structure to remove radicals cleanly. Whenever you see roots in denominators, look for shared factors and consider conjugates—these two ideas turn messy expressions into something simple and meaningful.