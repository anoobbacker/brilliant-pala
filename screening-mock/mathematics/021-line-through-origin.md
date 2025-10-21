## Question

Equation of a line passing through origin is

**Options:**

1. $x+y=1$
2. $x=2 y-4$
3. $x+y=0$
4. $y=x-1$

## Understand the question from first principles

What does it mean for a “line to pass through the origin”?  
- A graph is just a collection of points that obey a rule (an equation).  
- The origin is the special point with coordinates $(0,0)$.  
- So a line “passes through the origin” exactly when the point $(0,0)$ satisfies the line’s equation.

Think of the equation like a membership test: you plug in a point’s coordinates. If the statement becomes true, that point is on the line.

## Method 1: Direct plug-in test (most fundamental)

Test the point $(x,y)=(0,0)$ in each equation:

1) $x + y = 1$
```math
0 + 0 = 1 \quad \Rightarrow \quad 0 = 1 \quad \text{(false)}
```

2) $x = 2y - 4$
```math
0 = 2(0) - 4 \quad \Rightarrow \quad 0 = -4 \quad \text{(false)}
```

3) $x + y = 0$
```math
0 + 0 = 0 \quad \Rightarrow \quad \text{true}
```

4) $y = x - 1$
```math
0 = 0 - 1 \quad \Rightarrow \quad 0 = -1 \quad \text{(false)}
```

Only option 3 is true at $(0,0)$.  
Answer: Option 3. $x + y = 0$.

## Method 2: Intercepts logic (visual/graph intuition)

- The x-intercept is where $y=0$.  
- The y-intercept is where $x=0$.  
- A line through the origin must have both intercepts at 0.

Check quickly:
- $x+y=1$: when $y=0$, $x=1$ (x-intercept 1). Not at 0 → not through origin.  
- $x=2y-4$: when $y=0$, $x=-4$; when $x=0$, $y=2$ → misses origin.  
- $x+y=0$: when $y=0$, $x=0$; when $x=0$, $y=0$ → passes origin.  
- $y=x-1$: when $x=0$, $y=-1$ → not through origin.

## Method 3: Rebuilding the slope form from scratch

Why does a straight line look like $y=mx+c$?

- A straight line means a constant “rate of change”: for each equal step in $x$, $y$ changes by the same amount.  
- That constant ratio is the slope $m$:
```math
\frac{\Delta y}{\Delta x} = m \quad \text{(constant for a straight line)}
```
- Starting from where the line meets the y-axis, call that value $c$ at $x=0$.  
- After moving $x$ units horizontally, the change in $y$ is $mx$.  
- So total $y$ becomes:
```math
y = mx + c
```

If the line passes through the origin, then at $x=0$, $y=0$, so:
```math
0 = m\cdot 0 + c \quad \Rightarrow \quad c=0 \quad \Rightarrow \quad y = mx
```
This is the family of all lines through the origin.  
Option 3 can be rewritten as $y=-x$, which is of the form $y=mx$ with $m=-1$ → it passes through the origin.

(Equivalently, moving all terms to one side gives $ax + by + c = 0$. Passing through $(0,0)$ forces $c=0$, so lines through the origin look like $ax + by = 0$. For option 3, $a=1$, $b=1$.)

## Final Answer
Option 3: $x + y = 0$

---

## Conceptual follow-up questions
- If a line passes through the origin, what must its y-intercept be? Why?
- Which of these passes through the origin: $3x-2y=0$, $2x-5y=7$, $y=\tfrac{3}{2}x$, $x=5$?
- True or false: All lines through the origin can be written as $y=mx$. What about vertical lines like $x=0$?
- If a line through the origin has slope $m$, what is the angle it makes with the positive x-axis? (Hint: connect slope to tangent of the angle.)

## Application questions (real-world)
- In physics, Hooke’s law is $F=kx$. Why does this graph pass through the origin, and what does that mean about zero force and zero extension?
- Ohm’s law is $V=IR$. Why does the $V$–$I$ graph for an ideal resistor pass through the origin, and what would a nonzero intercept mean (e.g., a diode’s threshold)?
- In economics, if cost is $C = kq$ for quantity $q$, what does passing through the origin say about fixed costs?

## Common misconceptions and reasoning traps
- Mistake: “If an equation looks simple, it must pass through the origin.”  
  Fix: Always substitute $(0,0)$. If it doesn’t satisfy the equation, it’s not on the line.
- Confusing slope with intercept: Thinking $y=x-1$ passes through origin because “slope is 1.”  
  Fix: Slope tells steepness, not where it crosses axes. Intercept decides if it hits the origin.
- Forgetting vertical lines: Believing all lines through the origin are $y=mx$.  
  Fix: The y-axis $x=0$ also passes through the origin; it’s just not expressible as $y=mx$ with a finite $m$.

## Extension challenges
- Show that a line passes through the origin if and only if its equation has no constant term when written as $ax + by + c = 0$ (i.e., $c=0$).
- Parameter form: Describe all points on a line through the origin in the direction of a vector $(a,b)$ as $(x,y) = t(a,b)$ for real $t$. Convert this to an equation in $x$ and $y$ (you’ll get $bx - ay = 0$ up to scaling).
- Given two lines through the origin, $y=m_1x$ and $y=m_2x$, derive a formula for the angle between them using pure geometry or similar triangles.
- Experiment idea: On graph paper, draw any line through the origin. Measure rise/run between several point pairs; verify the ratio is constant. Why does this confirm straightness?

## Reflective insight
At its core, a graph is a set of points that make an equation true. “Passing through the origin” means the equation honors the special case $x=0$, $y=0$. For straight lines, “straight” means constant rate of change, giving $y=mx+c$. The origin constraint forces $c=0$, leaving pure proportionality $y=mx$. This is why so many fundamental relationships in science that start at “nothing gives nothing” (zero input → zero output) are straight lines through the origin.