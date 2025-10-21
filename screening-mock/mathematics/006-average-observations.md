## Question

If the average of 20 observations is 58, and the average of 18 observations is 56, the measure of opposite angles are:

**Options:**
- A) 158, 22
- B) 160, 20
- C) 50, 71
- D) 59, 71
- E) None of these

## Rebuilding the idea from first principles

Note: The phrase “measure of opposite angles” doesn’t fit a question about averages. I’ll treat this as a classic data/average problem: two observations were removed from a set, causing the average to change. We’ll solve from first principles and then check which option (if any) matches. Spoiler: the only thing we can know for sure is the sum (or average) of the two removed observations.

### 1) Start with an everyday picture (fair-share idea)
- Imagine 20 jars with stones. Saying “the average is 58” means if we redistributed stones so every jar had the same number, each would hold 58 stones.
- “Average × number of items = total amount” is just “rate × count = total,” like speed × time = distance.

So:
```math
\text{Total from 20 observations} = 20 \times 58 = 1160.
```

Now, suppose we remove 2 jars (2 observations). What remains is a group of 18 jars with a new average of 56:
```math
\text{Total from remaining 18} = 18 \times 56 = 1008.
```

### 2) What did we remove?
The stones that disappeared are exactly the difference between the old total and the new total:
```math
\text{Sum of the 2 removed observations} = 1160 - 1008 = 152.
```
- That means the two removed observations together add up to 152.
- Their own average is therefore:
```math
\text{Average of the removed two} = \frac{152}{2} = 76.
```

### 3) What can and cannot be known
- From the data, we can know the sum (152) and the average (76) of the two removed observations.
- But we cannot know the two individual values uniquely without more information (like their difference). Many pairs add to 152: (76, 76), (60, 92), (70, 82), etc.

### 4) Check the options
- A) 158 + 22 = 180
- B) 160 + 20 = 180
- C) 50 + 71 = 121
- D) 59 + 71 = 130

None add to 152. So none of these pairs can be the two removed observations.

Answer: E) None of these.

### 5) Why the averaging logic works (cause → effect)
- Average is a “fair share.” Multiply by count to get the total.
- Removing two items removes their sum from the total.
- New total = old total − (sum of removed). Rearranging reveals the sum of the removed items.

### 6) A quick balance (center-of-mass) view
Think of 58 as the “balance point.” The 18 remaining items sit at 56 (which is 2 below 58). To keep the original average at 58, the two removed must be above 58 enough to compensate:
```math
18 \times (56 - 58) + 2 \times (x - 58) = 0
\Rightarrow -36 + 2(x - 58) = 0
\Rightarrow 2x - 116 = 36
\Rightarrow 2x = 152 \Rightarrow x = 76.
```
So the pair’s average is 76, consistent with the total-sum method.

### 7) Dimensional check
- Average has units “value per observation.”
- Multiplying by “observations” gives “value,” which matches the total. So equations are dimensionally consistent.

---

## Final Answer
E) None of these

Because the two removed observations must sum to 152 (average 76), and none of the listed pairs do.

---

## Conceptual follow-up questions
1. If the average of 30 numbers is 40 and after removing 5 numbers the new average is 36, what is the sum and average of the removed 5 numbers?
2. If removing two numbers changes the average from 70 to 69, what is the average of the two removed numbers?
3. If you know the sum of removed numbers but not their individual values, what extra information would make the pair unique (e.g., their difference, product, or one of the values)?

## Application questions
- Quality control: A factory samples 100 bolts with an average mass. After discarding a few outliers, the new average shifts. How do you estimate the total mass of the discarded bolts?
- Sports analytics: A player’s average over a season changes after two poor performances are excluded. How can you compute the combined contribution of those two games?

## Common misconceptions and reasoning traps
- Thinking you can determine each of the two removed values uniquely. You cannot—only their sum (and average) is fixed without extra info.
- Confusing “change in average” with “average of the removed items.” It’s not 58 − 56 = 2; instead, the removed two have average 76, found via totals.
- Being distracted by the phrase “opposite angles” (likely a typo). Don’t import unrelated rules (like summing to 180 degrees) into a data problem.

## Extension challenges
- If removing k numbers lowers the average by d from A to A − d, express the average of the k removed numbers in terms of A, d, and k. Then test it with numbers.
- Suppose you know the sum and product of the two removed numbers. Can you find the numbers uniquely? Connect to quadratic equations.
- Design two different sets of 20 observations (with the same average) such that removing the same two observations leads to different new averages. Explain why this is possible or not.

## Reflective insight (the deep “why”)
The heart of average problems is conservation of total. Average is just total spread evenly. When data changes (adding/removing items), the only thing that moves the average is how much total you added or took away. Multiply “average × count” to get the total, compare totals before and after, and the rest follows—no memorized tricks needed.