## Question

The difference between the compound interest and the simple interest for 2 years at 8% per annum on a certain sum of money is 160. Find the sum:

**Options:**
- A) 18,750/-
- B) 18,700/-
- C) 18,850/-
- D) 18,050/-

## Big idea in plain words
- Simple interest (SI) is like a fixed rent: every year you pay/earn the same amount based only on the original sum.
- Compound interest (CI) is like stacking blocks: each new block is built both on the original sum and on the blocks already added—so interest itself starts earning interest.
- Over 2 years, the only extra amount CI has over SI is the “interest-on-interest” that appears in the second year.

We’re told:
- Time = 2 years
- Rate = 8% per annum
- Difference between CI and SI in 2 years = 160
- Find the principal (original sum)

## Rebuild from first principles

### 1) Track what happens year by year
Imagine you deposit a principal P rupees at 8% per year.

- Year 1:
  - SI interest = 8% of P = 0.08P
  - CI interest (so far) = also 0.08P (first year is the same for both)

- Year 2:
  - SI: still 8% of the original P = 0.08P (simple interest never grows)
  - CI: 8% of the new total amount after Year 1, which is P + 0.08P = 1.08P
      
    So second-year CI interest = 8% of 1.08P = 0.08 × 1.08P = 0.0864P

Now compare the total interest over 2 years:
- SI total = 0.08P + 0.08P = 0.16P
- CI total = 0.08P + 0.0864P = 0.1664P

So the difference (CI − SI) over 2 years is:
```math
\text{Difference} = 0.1664P - 0.16P = 0.0064P = P \times (0.08)^2
```
Why does a square appear? Because the “interest-on-interest” in the second year is “8% of 8% of P,” i.e., 0.08 × 0.08 × P = 0.0064P.

### 2) Use the given difference to solve for P
We’re told the difference is 160:
```math
0.0064P = 160
\Rightarrow P = \frac{160}{0.0064} = 25{,}000
```

### 3) Quick check by recomputing both interests
- SI for 2 years: 25,000 × 0.08 × 2 = 4,000
- CI for 2 years: 25,000 × [(1.08)^2 − 1] = 25,000 × (1.1664 − 1) = 25,000 × 0.1664 = 4,160
- Difference: 4,160 − 4,000 = 160 ✔

### 4) Dimensional sanity check
- Rate is “per year” (dimension 1/year); over 2 years, SI uses r×t (dimensionless) times P (money) → money.
- In CI, (1 + r)^2 is a dimensionless multiplier; subtract 1 gives a dimensionless fraction of P → money.
- The difference 0.0064P has units of money, consistent with 160 rupees.

## Answer
- The principal (sum) is 25,000 rupees.
- Note: None of the provided options match this correct value. This suggests a likely misprint in the options.

## Multiple ways to see it

### A) Intuitive “interest-on-interest” view
- First year: both SI and CI add 8% of P.
- Second year: SI adds 8% of P again; CI adds 8% of P plus 8% of last year’s interest (which was 8% of P).
- Extra amount under CI = 8% of (8% of P) = 0.08 × 0.08 × P = 0.0064P → set equal to 160.

### B) Growth-multiplier view (reconstructing, not memorizing)
- Each year at 8%, your money grows by a factor of 1.08.
- Over 2 years, total growth factor = 1.08 × 1.08 = (1.08)^2.
- CI over 2 years = P[(1.08)^2 − 1] = P(2×0.08 + 0.08^2) = P(0.16 + 0.0064).
- SI over 2 years = P × 2 × 0.08 = 0.16P.
- Difference = P × 0.0064.

### C) “Per-rupee experiment”
- If you invested 1 rupee:
  - SI in 2 years = 0.16 rupees
  - CI in 2 years = 0.1664 rupees
  - Difference per rupee = 0.0064 rupees
- To get a difference of 160 rupees, scale up by a factor of 160 ÷ 0.0064 = 25,000.

---

## 1) Conceptual follow-up questions
- If the time were 3 years instead of 2, would the CI − SI difference still be P × r^2? What extra terms would appear and why?
- For very small rates (say 1%), is the difference between CI and SI small or large? Explain using the idea of “interest-on-interest.”
- If the difference between CI and SI doubles, does the principal double, assuming rate and time are fixed? Why (proportionality)?
- If the rate is halved, how does the difference change for 2 years? (Hint: difference ∝ r^2.)

## 2) Applications to real life
- Credit cards and loans: Compounding causes balances to grow faster than simple interest—design payment strategies to minimize “interest-on-interest.”
- Savings and investments: Long-term investing benefits from compounding—small consistent returns can grow significantly.
- Population growth and epidemics: Multiplicative growth (similar to compounding) explains why early control matters.
- Engineering reliability: Compound probabilities (like repeated failure chances) can be approximated with similar multiplicative reasoning.

## 3) Common misconceptions and traps
- Mixing percent and decimal: Using 8 instead of 0.08 inflates answers by 100×. Always convert 8% → 0.08.
- Assuming CI − SI after 2 years is 2 × something: The extra is NOT 2rP; it’s r^2P because it’s “percent of a percent.”
- Forgetting compounding frequency: If compounding is half-yearly or quarterly, the difference changes. Here we assumed annual compounding.
- Thinking SI grows each year: In SI, yearly interest stays constant; only CI grows year to year.

## 4) Extension challenges
- If the rate is 8% compounded half-yearly (i.e., 4% every 6 months) for 2 years, find the new difference between CI and SI.
- For 3 years at rate r, derive CI − SI from first principles. Identify the “interest-on-interest” pieces year by year.
- If P grows with inflation (say 5% per year) while earning 8% CI, what is the real (inflation-adjusted) growth after 2 years?
- Given CI − SI and time = 2 years, derive a formula for the rate r in terms of P and the difference. What happens if r is unknown but small?

## 5) Reflective insight — the essence
Compounding is multiplicative growth: each step builds on the whole built so far. The gap between CI and SI is the pure signature of that multiplicative effect—the “interest-on-interest.” For 2 years, that effect appears exactly once, so the difference is r^2P. Once you see this as a story of how money “stacking” changes over time, you can reconstruct any formula by tracking how many layers of “percent-on-percent” appear.