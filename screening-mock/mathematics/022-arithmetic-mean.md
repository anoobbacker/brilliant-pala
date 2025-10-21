## Question

If the arithmetic mean of $5,7,9, x$ is 9 , then the value of $x$ is

**Options:**

1. 11
2. 15
3. 18
4. 16

## Solve from First Principles (IGCSE-friendly)

### 1) Everyday intuition: equal sharing
Think of the four numbers 5, 7, 9, and x as four piles of cubes.  
Saying “the arithmetic mean is 9” means: if we redistribute cubes so every pile is equal, each pile would have 9 cubes.

- So the total number of cubes must be “number of piles × cubes per pile”.

```math
\text{Total} = \text{count} \times \text{mean} = 4 \times 9 = 36
```

We already have three piles: 5, 7, and 9. Their total is:

```math
5 + 7 + 9 = 21
```

For the grand total to be 36, the last pile x must make up the difference:

```math
x = 36 - 21 = 15
```

So, x = 15.  
Correct option: 2

---

### 2) Why this works (causality and structure)
- The mean is “equal sharing.” If each of 4 items should end up at 9, the total must be 4 × 9.
- We already know part of the total (21), so the missing piece must be whatever completes the full total (36).
- This is just conservation: total before and after equalizing is the same.

---

### 3) Quick check
```math
\frac{5 + 7 + 9 + 15}{4} = \frac{36}{4} = 9
```
Works perfectly.

---

### 4) Alternative mental model: deviations from the mean
Imagine the target level is 9. Measure how far each known number is from 9:
- 5 is 4 below 9 → deviation −4
- 7 is 2 below 9 → deviation −2
- 9 is exactly at 9 → deviation 0

Total deficit so far is −6. To balance to zero overall, x must be +6 above 9:
```math
x = 9 + 6 = 15
```
Same answer, different lens.

---

### 5) Dimensional and proportional reasoning
- “Mean” has the same “dimension” as the numbers (plain numbers here), so Total = Count × Mean is dimensionally consistent.
- If you raise one number by k, the mean rises by k/4 (because there are 4 numbers). Here the three numbers are together 6 below the target, so the last number must compensate with +6.

---

## Final Answer
15  (Option 2)

---

## Conceptual Follow-up Questions
1) If the mean of 6, 10, x is 9, what is x?  
2) If the mean of 5, 7, 9, x is 10 instead, what must x be?  
3) If you increase one of the four numbers by 12, by how much does the mean increase? Why?

---

## Application Questions (real-life connections)
- You have three test scores: 70, 75, 80. What score do you need on the fourth test to average 85?  
- A chef mixes three batches of soup with salt concentrations 2%, 3%, and 4%. What concentration must the fourth batch have to get an overall 3.5%?

---

## Common Misconceptions and Traps
- Forgetting to multiply the mean by the count to get the total (thinking 9 is the total instead of 36).
- Dividing the total of known numbers by the total count (e.g., taking 21/4) and calling that x.
- Using the wrong count (3 instead of 4), especially when one value is unknown.
- Arithmetic slip: 5 + 7 + 9 = 21 (not 20 or 22).

How to avoid: Always write
```math
\text{Total} = \text{count} \times \text{mean},\quad \text{Known sum} + x = \text{Total}
```
and compute step by step.

---

## Extension Challenges
- If the mean of five numbers is 12 and four of them are 8, 10, 13, 15, find the fifth.  
- Two more numbers are added to 5, 7, 9, x so that the new mean is still 9. What can you say about the sum of the two new numbers?  
- Weighted mean: If x counts twice as much as the others (like a final exam), and the mean is still 9, how does that change the equation?

---

## Reflective Insight (the deep “why”)
The arithmetic mean is the “equal-share level.” It’s governed by a conservation idea: the total amount stays the same whether unevenly distributed or perfectly equalized. That’s why the master equation is
```math
\text{Total} = \text{count} \times \text{mean}.
```
Once you see the mean as equal sharing and totals as conserved, problems with unknown entries become simple balancing acts.