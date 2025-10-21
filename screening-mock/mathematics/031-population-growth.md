## Question

The population of a town increases by $5 \%$
annually. If its population in the end of the year 2020 was 120000 . What will
be the population of the town in the end of the year 2023

**Options:**

1. $1,30,125$
2. $1,38,915$
3. $1,34,315$
4. $1,38,1750$

## Understand the situation in everyday terms

- Imagine a town where each year, the number of people grows by 5% of whatever the current population is.
- “5% of the current” means the amount added each year is not fixed; it depends on how many people are already there. More people → bigger 5% → faster growth later. This is growth-on-growth, also called compounding.

## Build the logic from first principles

### Step 1: What does “increase by 5%” do in one year?
- If the population at the start of a year is P, then “increase by 5%” means you add 0.05P to P.
- So the new population after one year is:

```math
\text{New} = \text{Old} + 0.05 \times \text{Old} = (1 + 0.05)\times \text{Old} = 1.05 \times \text{Old}
```

- Notice 5% is a pure ratio (dimensionless). That’s why multiplying by 1.05 makes sense regardless of units (people, rupees, etc.).

### Step 2: Turn that into a year-by-year rule
- Let P2020 be the population at the end of 2020. Then each year:

```math
P_{\text{next year}} = 1.05 \times P_{\text{this year}}
```

This is a causal, recursive rule: next amount depends on current amount.

### Step 3: Apply it for each year up to 2023
- We are given: end of 2020 → P2020 = 120000.
- End of 2021:

```math
P_{2021} = 1.05 \times 120000 = 126000
```

- End of 2022:

```math
P_{2022} = 1.05 \times 126000 = 132300
```

- End of 2023:

```math
P_{2023} = 1.05 \times 132300 = 138915
```

So the population at the end of 2023 is 138,915.

### Step 4: Same result via compact reasoning (derived, not memorized)
- Repeating “multiply by 1.05” three times is the same as multiplying once by $(1.05)^3$:

```math
P_{2023} = (1.05)^3 \times 120000
```

- To keep arithmetic exact, convert 1.05 to a fraction: $1.05 = \tfrac{21}{20}$:

```math
P_{2023} = 120000 \left(\frac{21}{20}\right)^3
= 120000 \cdot \frac{9261}{8000}
= \left(\frac{120000}{8000}\right) \cdot 9261
= 15 \cdot 9261
= 138915
```

### Step 5: Quick mental estimate to check
- Three years at 5% is a bit more than a simple 15% increase because of compounding.
- 15% of 120,000 = 18,000, so a no-compound estimate would be 138,000.
- Compounding adds a little extra: $(1.05)^3 - 1 = 0.157625 \approx 15.7625\%$.
- Extra over 15% is about 0.7625% of 120,000 ≈ 915. Total ≈ 138,915. Matches exactly.

## Final answer
- Population at the end of 2023: 138,915
- Correct option: 2) 1,38,915

---

## Conceptual follow-up questions
1. If the population decreased by 5% each year instead, what multiplier would you use each year? After 3 years, what would the population be?
2. If the rate changed each year (e.g., +5%, +3%, +4%), how would you compute the final population?
3. If the population at the end of 2023 was known and the 2020 population unknown, how would you work backward?

## Application questions
- Banking: If you deposit ₹120,000 at 5% annual interest, what is the balance after 3 years? Why is this the same math?
- Biology: A bacterial colony grows by 5% per hour. What’s the population after 3 hours if you start with 120,000 cells?
- Economics: If inflation is 5% per year, how does the cost of an item change over 3 years?

## Common misconceptions and reasoning traps
- Treating it as simple addition: Adding 15% to 120,000 to get 138,000 ignores growth on growth. Always multiply by (1 + rate) each period.
- Miscounting periods: End of 2020 to end of 2023 is 3 growth steps (2021, 2022, 2023), not 4.
- Mixing bases: “5% of what?” It’s always 5% of the current year’s population, not the original (unless explicitly stated).

## Extension challenges
- Variable rate: Start with 120,000. Apply +4%, +6%, then −2% over three years. What is the final population?
- Solve for time: How many years n does it take for 120,000 to become at least 160,000 at 5% annually? (Hint: find n such that $(1.05)^n \ge 160000/120000$.)
- Solve for rate: If 120,000 becomes 138,915 in 3 years, derive the annual rate r from $(1+r)^3 = 138915/120000$.
- Spreadsheet experiment: Create a column that multiplies by 1.05 each row and observe the curvature of the growth graph.

## Reflective insight
The essence of compounding is feedback: the change in each step depends on the current size. That single idea—“next = current × (1 + rate)”—cascades into exponential behavior. Once you see that compounding is repeated proportional change, you can handle any variant confidently: growth, decay, variable rates, or reverse calculations.