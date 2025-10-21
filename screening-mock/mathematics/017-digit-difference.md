## Question

The difference between a two-digit number and the number obtained by interchanging its digits is $27$. What is the difference between the two digits of the number?

## Solution — building from first principles

### 1) Start with an everyday model: place value
- A two-digit number like 41 is not “4 next to 1.” It means “4 tens plus 1 one.”
- So 41 = 4×10 + 1. If you swap the digits, you get 14 = 1×10 + 4.

This “tens-and-ones” idea is the engine of the whole problem.

### 2) Represent any two-digit number using digits
- Let the tens digit be $a$ and the ones digit be $b$.
- The original number is $10a + b$ (because $a$ tens = $10a$, plus $b$ ones).
- The interchanged number is $10b + a$.

### 3) What does swapping do, cause-and-effect?
- The digit $a$ moves from the tens place (worth $10a$) to the ones place (worth $a$). It loses $10a - a = 9a$ in value.
- The digit $b$ moves from the ones place (worth $b$) to the tens place (worth $10b$). It gains $10b - b = 9b$ in value.
- So the total change when you go from $10a + b$ to $10b + a$ is “gain $9b$ and lose $9a$,” i.e., a net change of $9(b - a)$.
- Therefore, the difference between the two numbers must be a multiple of 9.

Let’s write that difference explicitly:

```math
(10a + b) - (10b + a) = 9(a - b)
```

The sign depends on which digit is bigger, but the size (magnitude) is

```math
|10a + b - (10b + a)| = |9(a - b)| = 9|a - b|.
```

### 4) Use the given fact: the difference is 27
We’re told the difference is 27, i.e.,

```math
9|a - b| = 27.
```

Divide both sides by 9:

```math
|a - b| = 3.
```

This means the two digits differ by 3.

### 5) Quick reality check with examples
- 41 and 14: 41 − 14 = 27, digits differ by 3.
- 30 and 03 (i.e., 3): 30 − 3 = 27, digits differ by 3.
- 52 and 25: 52 − 25 = 27, digits differ by 3.

Everything fits the rule we derived.

### Final answer
```math
\text{Difference between the two digits} = 3.
```

---

## Multiple ways of seeing it

- Intuitive swap effect: Moving a digit from tens to ones changes its value by 9 times that digit (because 10 − 1 = 9). So the overall difference is “9 × (difference between digits).”
- Algebraic derivation: $|10a + b - (10b + a)| = 9|a - b|$.
- Experimental pattern: Try pairs whose digits differ by 1, 2, 3, … and notice differences of 9, 18, 27, … respectively.

---

## 1) Conceptual follow-up questions
- If the difference after swapping is 18, what must the difference between the digits be? Why?
- Could the difference after swapping ever be 20? Explain using place value.
- If two digits are the same, what is the difference after swapping? Why must that be true?

## 2) Application questions (real-world links)
- Barcodes and error checking often use mod 9 or mod 10 ideas. Explain how the fact “swap difference is a multiple of 9” hints at why digit sums mod 9 are useful for catching certain errors.
- On a digital counter (like an odometer), how does swapping digits compare to increasing by 9 repeatedly? What invariants (unchanged properties) can you identify?

## 3) Common misconceptions and how to avoid them
- Mistake: Thinking “swapping digits changes the number by the difference of the digits.” Reality: it changes by 9 × (difference of digits), because tens are worth 10 ones, not 1.
- Ignoring absolute value: You don’t know which digit is larger; use $|a - b|$ to get a positive difference between digits.
- Forgetting place value: Writing the number as “$a+b$” instead of “$10a + b$” loses the tens contribution and leads to wrong results.

## 4) Extension challenges
- Generalize to any base $B$: Show that swapping digits in base $B$ changes the number by $(B - 1)(a - b)$. Verify that for base 10, $B - 1 = 9$.
- Three-digit twist: For number $100a + 10b + c$, what is the change if you reverse it to $100c + 10b + a$? When is the difference a multiple of 99? Why 99?
- Constraint puzzle: Find all two-digit numbers whose reverse differs by 27. List them and explain the pattern.

## 5) Reflective insight — the deep “why”
The heart of the problem is place value: a digit in the tens place is worth 10 times what it’s worth in the ones place. Swapping moves each digit between values that differ by exactly a factor of 9 (because 10 − 1 = 9). That’s why the swap difference is always a multiple of 9 and why the difference between digits is simply the total difference divided by 9. When you truly “see” place value, problems like this become predictable and simple.