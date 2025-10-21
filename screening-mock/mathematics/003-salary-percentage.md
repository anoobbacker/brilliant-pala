## Question

The salary of an officer has been increased by 50%. By what percent must the new salary be reduced to restore the original salary?

**Options:**
- A) 44 4/9 %
- B) 33 1/3 %
- C) 22 2/3 %
- D) 11 1/3 %

## Goal
Find the percent decrease needed to bring a salary back to its original value after it was increased by 50%.

Options:  
A) 44 4/9 % B) 33 1/3 % C) 22 2/3 % D) 11 1/3 %

---

## Intuition from everyday life
- If a jacket’s price increases by 50%, it becomes 1.5 times the original. To get back, you don’t “undo” it by 50%, because 50% of the new (bigger) price is larger in absolute amount. You need a smaller percent of the new amount.
- Think of stretching a rubber band by 50% (1.5×). To return to the original length, you must multiply by the reciprocal of 1.5, which is 2/3. That’s not “minus 50%,” it’s “keep two-thirds,” i.e., remove one-third.

---

## Build from first principles

### Step 1: Use a neutral symbol for the original salary
Let the original salary be $S$. Percentages are ratios, so the exact number doesn’t matter; using $S$ keeps us general.

### Step 2: Understand “increase by 50%”
“Increase by 50%” means add half of $S$:
```math
\text{New salary} = S + 0.5S = 1.5S
```

### Step 3: Define what “reduce by r%” means
Reducing the new salary by $r\%$ means we keep $(1 - r/100)$ of it:
```math
\text{Restored salary} = 1.5S \times \left(1 - \frac{r}{100}\right)
```
We want to return to the original $S$, so set this equal to $S$:
```math
1.5S \left(1 - \frac{r}{100}\right) = S
```

### Step 4: Solve for the required reduction r
Divide both sides by $S$ (since $S \neq 0$), then by $1.5$:
```math
1 - \frac{r}{100} = \frac{1}{1.5} = \frac{2}{3}
```
So,
```math
\frac{r}{100} = 1 - \frac{2}{3} = \frac{1}{3}
\Rightarrow r = \frac{1}{3}\times 100\% = 33\frac{1}{3}\%
```

Therefore, the new salary must be reduced by 33 1/3% to restore the original.

Answer: B) 33 1/3 %

---

## Quick numerical check (sanity test)
Pick a concrete number to see the logic:
- Start with 100 (simple unit).
- Increase by 50% → 150.
- How much percent to drop from 150 to return to 100?
  - Drop needed = 50.
  - As a percent of the current 150: $50/150 = 1/3 = 33\frac{1}{3}\%$.
Consistent with the derivation.

---

## Visual/ratio perspective
- Increase by 50% = multiply by 1.5.
- To undo, multiply by its reciprocal, $1/1.5 = 2/3$.
- Multiplying by $2/3$ means “keep two-thirds,” i.e., “remove one-third” = 33 1/3%.

---

## Generalization (derived, not memorized)
If something is increased by $p\%$, the factor is $(1 + p/100)$. To get back, multiply by $(1 - r/100)$ so the product returns to 1:
```math
(1 + \frac{p}{100})(1 - \frac{r}{100}) = 1
```
Solve for $r$:
```math
1 - \frac{r}{100} = \frac{1}{1 + p/100}
\Rightarrow \frac{r}{100} = 1 - \frac{1}{1 + p/100}
= \frac{p/100}{1 + p/100}
= \frac{p}{100 + p}
```
So the required reduction is:
```math
r\% = \frac{p}{100 + p}\times 100\%
```
For $p=50$, $r\% = \frac{50}{150}\times 100\% = 33\frac{1}{3}\%$.

---

## Why this makes sense (units and proportionality)
- Percent is dimensionless (a ratio). Changes multiply, not add.
- Going up by $+50\%$ then down by $-50\%$ doesn’t cancel, because the second 50% is of a larger base. Multiplication captures this asymmetry.

---

## Conceptual follow-up questions
1. If a price increases by 25%, by what percent should it be reduced to return to the original? (Use the general result.)
2. If a value decreases by 20%, what percent increase is needed to get back to the original?
3. Is there any nonzero percent $p$ such that “increase by $p\%$ then decrease by $p\%$” returns you to the start?

## Application questions
- Stocks: If a stock rises 50% one day and falls the next day by the number you found, does it end where it started?
- Sales and taxes: A shop marks up an item by 40% and then offers a percent discount to return to the pre-markup price. What must that discount be?
- Engineering tolerances: A machine stretches a material by a fixed percent; to restore the original dimension, what contraction percent is required?

## Common misconceptions and traps
- “Additive trap”: Thinking +50% and −50% cancel. They don’t, because the base changed after the first change.
- “Wrong base”: Computing the reduction relative to the original instead of the new amount.
- “Rounding too early”: Rounding intermediate steps heavily can produce wrong final percents; keep fractions (like 2/3) until the end.

## Extension challenges
- After a +20% change followed by −20%, what is the net percent change? Explain using multiplication.
- If a quantity is multiplied by 1.5, what single percent change brings it back? Generalize to any factor $k$.
- Design a real experiment: Take a piece of elastic, mark its original length, stretch by 50%, then relax it to 2/3 of the stretched length. Verify it returns to the original mark.

## Reflective insight
The essence: Percent changes are multiplicative transformations. To “undo” a change, you multiply by the reciprocal factor, not subtract the same percent. Once you see percent changes as scale factors (like 1.5 and 2/3), problems like this become simple ratio questions rather than memorized tricks.

Final answer: B) 33 1/3 %