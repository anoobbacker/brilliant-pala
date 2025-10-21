## Question

If $\mathrm{x}+\frac{1}{\mathrm{x}}=5$ then
$\mathrm{x}^2+\frac{1}{\mathrm{x}^2}=$

**Options:**

1. 26
2. 23
3. 27
4. 32

## Think-it-through solution (from first principles)

### What are we given and what do we want?
- Given: $x + \frac{1}{x} = 5$ (so $x \ne 0$ because division by zero is undefined).
- Want: $x^2 + \frac{1}{x^2}$.

Notice the target has squares. A natural way to produce squares is to square something we already know. Since we know $x + \frac{1}{x}$, let’s square that.

### Why squaring helps (visual, “area of a big square” idea)
Imagine a big square whose side length is the sum of two lengths: $x$ and $\frac{1}{x}$. The area of the big square is the square of that sum:

```math
(x + \tfrac{1}{x})^2
```

You can cut that big square into:
- one square of area $x^2$,
- one square of area $\left(\frac{1}{x}\right)^2 = \frac{1}{x^2}$,
- two identical rectangles each of area $x \cdot \frac{1}{x} = 1$.

So the total area (which equals the square of the side) is:

```math
(x + \tfrac{1}{x})^2 = x^2 + \frac{1}{x^2} + 2 \cdot \left(x \cdot \frac{1}{x}\right)
= x^2 + \frac{1}{x^2} + 2
```

This is not memorizing a formula; it’s just adding areas of pieces.

### Now use the given number
We know $x + \frac{1}{x} = 5$. Square both sides:

```math
(x + \tfrac{1}{x})^2 = 5^2 = 25
```

But from the area reasoning:

```math
(x + \tfrac{1}{x})^2 = x^2 + \frac{1}{x^2} + 2
```

Equate them and solve for the target:

```math
x^2 + \frac{1}{x^2} + 2 = 25
\Rightarrow x^2 + \frac{1}{x^2} = 25 - 2 = 23
```

Answer: 23 → Option 2.

---

## Quick logical cross-check (optional)
From $x + \frac{1}{x} = 5$, multiply both sides by $x$:

```math
x^2 + 1 = 5x \Rightarrow x^2 - 5x + 1 = 0
```

Solving gives $x = \frac{5 \pm \sqrt{21}}{2}$. For either value, $x^2 + \frac{1}{x^2}$ must be the same because the expression is symmetric under $x \leftrightarrow \frac{1}{x}$. Using the identity we derived, it’s 23.

---

## Conceptual follow-up questions
1. If $x + \frac{1}{x} = k$, what is $x^2 + \frac{1}{x^2}$ in terms of $k$? Derive it using the same area/squaring idea.
2. If $x + \frac{1}{x} = 5$, what is $x^3 + \frac{1}{x^3}$? Hint: cube $(x + \frac{1}{x})$ and carefully group terms, or multiply $(x + \frac{1}{x})(x^2 + \frac{1}{x^2})$ and subtract appropriate terms.
3. For which real values of $k$ does $x + \frac{1}{x} = k$ have real solutions? Reason using the graph of $y = x + \frac{1}{x}$ or by AM-GM.

## Applications to real-world thinking
- Reciprocal pairs appear in science and engineering: frequency and period ($f$ and $T=1/f$), resistance and conductance ($R$ and $G=1/R$), focal length and power of a lens. Symmetric expressions like $x + \frac{1}{x}$ often simplify when squared because cross-terms become constants (here, 2).
- Designing formulas that produce “the squares you want plus a small, controllable extra” is a common engineering trick. We squared to get $x^2 + \frac{1}{x^2}$ plus a simple constant we could handle.

## Common misconceptions and traps
- Forgetting the cross term: $(a+b)^2$ isn’t $a^2 + b^2$; it includes $2ab$. Here that’s exactly what gives the neat constant 2.
- Treating $x$ as zero: not allowed because $1/x$ is undefined.
- Dimensional mismatch: You can only add $x$ and $1/x$ if they’re pure numbers (dimensionless). In physics, you’d avoid adding quantities with different units.

## Extension challenges
- Given $x + \frac{1}{x} = 5$, compute $x^4 + \frac{1}{x^4}$ without finding $x$. Hint: square $x^2 + \frac{1}{x^2}$ and adjust.
- Prove by induction that if $x + \frac{1}{x} = k$, then $x^n + \frac{1}{x^n}$ can be expressed using a recurrence: $S_n = k S_{n-1} - S_{n-2}$ with $S_0=2$, $S_1=k$.
- Explore the graph of $y = x + \frac{1}{x}$ for $x>0$ and $x<0$, and explain why $|y| \ge 2$. Connect this to the range of possible $k$.

## Reflective insight
The essence here is structural thinking: choose an operation that naturally manufactures the pieces you want. Because we wanted $x^2$ and $\frac{1}{x^2}$, squaring $x + \frac{1}{x}$ was the minimal move that produces them, and the “extra” cross-term simplified to a constant. This habit—engineering the right operation to reveal structure—is the key to confidently tackling unfamiliar algebraic problems.