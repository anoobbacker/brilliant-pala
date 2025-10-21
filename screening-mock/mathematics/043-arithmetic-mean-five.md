## Question

Arithmetic mean of $15,17,19,21,23$ is

## Build-up from first principles

### 1) What is an “average,” really?
- Imagine 5 buckets holding 15, 17, 19, 21, and 23 liters of water.
- The “average” is the water level you’d get if you could pour water between buckets until all buckets end up with the same amount, without spilling or adding any water.
- Why this makes sense: the total water is conserved. If, after equalizing, each of the 5 buckets has A liters, then the total must be 5A. But the total is also the sum of the original amounts. So A must be the “fair share.”

This conservation idea is the root of the average formula.

### 2) Equalization by pairing (intuitive construction)
- Pair the smallest with the largest: 15 with 23. If you pour 4 from 23 into 15, both become 19.
- Pair the next smallest with the next largest: 17 with 21. Pour 2 from 21 into 17, both become 19.
- The middle number is already 19.
- We’ve equalized all five buckets to 19 without changing the total. Therefore, the average must be 19.

This works because the numbers are symmetrically placed around 19.

### 3) Deriving the formula from conservation (analytical)
From the conservation idea:
- Let A be the average. After equalizing, total = 5A.
- But total is also the sum of the original numbers.

Compute the sum:
```math
15 + 17 + 19 + 21 + 23 = 95
```
So:
```math
5A = 95 \;\;\Rightarrow\;\; A = \frac{95}{5} = 19
```

### 4) Symmetry/center-of-mass viewpoint
- Place equal weights at positions 15, 17, 19, 21, 23 on a number line.
- The balance point (center of mass) is the average. Since the points are equally spaced around 19, the torques cancel: (-4)+(-2)+0+(+2)+(+4)=0 about 19.
- So the balancing point is exactly 19.

### 5) Sanity and unit checks
- The average must lie between the smallest and largest values: between 15 and 23. Indeed, 19 lies in this range.
- Because the list is symmetric, the average should be right at the center—again 19.
- Units: if each number were “units,” the sum is in “units,” dividing by a count (5) keeps it in “units.” Consistent.

## Final answer
```math
\text{Arithmetic mean} = 19
```

---

## Conceptual follow-up questions
- If you raise only the last number from 23 to 28, how much does the average change? Explain without recomputing the whole sum.
- If the list were 14, 16, 18, 20 (even count), where would the average lie and why?
- Why must the average always be between the minimum and maximum values?

## Application questions
- Center of mass: If five equal metal beads are glued at positions 15, 17, 19, 21, 23 cm on a ruler, where should you place a pivot to balance it? Why is that the average?
- Load balancing: Five servers handle 15, 17, 19, 21, 23 tasks. How many tasks should each handle after perfect balancing? How would you move tasks to achieve it?

## Common misconceptions and reasoning traps
- Confusing average with median: here they’re the same (19) due to symmetry, but not always.
- Dividing by the wrong count: always divide by the number of values (here, 5), not by the largest value or the range.
- Thinking the average must be one of the original numbers: not necessarily; it just lies between min and max.

## Extension challenges
- Prove from first principles that for any arithmetic progression with an odd number of terms, the average equals the middle term.
- If one value increases by Δ, show that the average increases by Δ divided by the number of values. Use conservation reasoning.
- Weighted average: If 15 occurs twice, 17 once, 23 twice, what is the average? Derive the weighted-average formula from the conservation idea.

## Reflective insight
The essence of “average” is conservation and balance: it’s the unique value that, if every entry were replaced by it, preserves the total. Whether you pour water between buckets, balance masses on a ruler, or redistribute tasks among servers, the average is the equalized level that keeps the sum unchanged. Understanding this lets you recompute or adjust averages quickly and confidently in any new situation.