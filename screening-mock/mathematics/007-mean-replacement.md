## Question

The mean of 100 observations is 60. If one observation (50) is replaced by 120, the resulting mean will be:

**Options:**
- A) 60.7
- B) 60.5
- C) 60.6
- D) 60.8
- E) None of these

## Mean After Replacement — Derived from First Principles

### Everyday intuition: equal sharing
Imagine 100 friends put their pocket money into one pot to share equally. The average (mean) money per person is simply:
- Add up all the money,
- Divide by how many people.

If one friend replaces Rs. 50 with Rs. 120, the pot gains Rs. 70. Spread across 100 friends, each person’s fair share rises by Rs. 70/100 = Rs. 0.70. That’s the new mean.

### Step 1: What does “mean” actually mean?
By definition, mean is “equal share”:
```math
\text{mean} = \frac{\text{total sum of values}}{\text{number of values}}
```
Units check (dimensional analysis):
- If values are in marks (or rupees), totals are in marks.
- Dividing by a count (dimensionless) keeps the unit as marks — consistent.

### Step 2: Reconstruct the original total from the mean
We’re told:
- Number of observations, $n = 100$
- Original mean, $\bar{x} = 60$

So total sum $S$ must be:
```math
S = \bar{x} \times n = 60 \times 100 = 6000
```

### Step 3: Understand the effect of replacing one observation
One observation 50 is replaced by 120. The total changes by the difference:
```math
\Delta = 120 - 50 = 70
```
So the new total becomes:
```math
S' = S + \Delta = 6000 + 70 = 6070
```

### Step 4: Compute the new mean from first principles
Use the definition again:
```math
\bar{x}' = \frac{S'}{n} = \frac{6070}{100} = 60.7
```

### Why this makes sense (cause-effect check)
- We replaced a smaller number (50) with a larger one (120) → mean must increase.
- The increase to the total is 70, spread across 100 observations → increase per observation is $70/100 = 0.7$.
- Hence new mean = $60 + 0.7 = 60.7$.

### General principle (derived, not memorized)
Starting from the definition:
```math
\bar{x}' = \frac{S + (a_{\text{new}} - a_{\text{old}})}{n}
= \frac{S}{n} + \frac{a_{\text{new}} - a_{\text{old}}}{n}
= \bar{x} + \frac{a_{\text{new}} - a_{\text{old}}}{n}
```
Here, $a_{\text{old}} = 50$, $a_{\text{new}} = 120$, $n=100$ → $\bar{x}' = 60 + 70/100 = 60.7$.

### Multiple ways to see it
- Balance-point model: The mean is like the balance point of 100 equal masses on a number line. Raising one mass by 70 shifts the center by 70/100.
- Small-scale experiment: If 4 numbers average 6 (total 24), replacing a 5 with 12 adds 7; new total 31; new mean 31/4 = 7.75 = 6 + 7/4. Same logic scales to 100.

### Final Answer
- 60.7 → Option A

---

## 1) Conceptual follow-up questions
- If you replace a value by a larger one, will the mean always increase? By how much, in terms of $n$ and the difference?
- If the number of observations doubled to 200 but the same replacement happened once, how would the change in mean compare? Why?
- What happens to the mean if you add the same constant $c$ to every observation? Explain from the “total sum” perspective.
- If two replacements are made: 40 → 70 and 90 → 60, what happens to the mean? Predict using net change.

## 2) Application questions
- In a class of 50 students, one extra-credit project raises a single student’s score by 20 marks. By how much does the class average increase? How does this inform grading policies?
- In manufacturing, one defective batch is reworked to add 300 units to total output across 10,000 items. What is the impact on average output per item?
- National income statistics: If one company’s revenue is corrected upward by $5$ billion among 1,000 companies, how much does average revenue change? What does this tell us about the sensitivity of averages?

## 3) Common misconceptions and traps
- Confusing difference with average change: The total increases by 70, but the average increases by 70 divided by the number of observations (here, 100), not by 70.
- Forgetting the count doesn’t change: Replacing a value doesn’t change $n$; it changes the total.
- Unit mismatch: Average has the same unit as the observations; dividing by $n$ preserves units.
- Overgeneralizing: Thinking the mean changes by the same amount as the replaced value’s change, regardless of $n$.

## 4) Extension challenges
- Derive a formula for the new mean after multiple replacements and show it equals old mean plus (sum of all changes)/$n$.
- Compare mean vs median under replacement: If you replace a very small value by a very large one, which statistic is more sensitive? Why?
- Weighted average scenario: If one observation has weight $w$ (counts $w$ times), how does replacing it change the overall mean?
- Error correction: A dataset’s mean was computed as 75 for $n=200$, but later two entries 30 and 45 were found to be 70 and 65. Find the corrected mean without recomputing everything.

## 5) Reflective insight — the essence
The mean is the “equal-share” or “center-of-balance” of a dataset. Any change to a single value changes the total first; only then does the average respond by spreading that total change evenly across all $n$ items. That’s why the mean’s change is the total change divided by how many items share it. Once you internalize “mean = total per item,” you can adjust averages mentally in seconds, even for large datasets.