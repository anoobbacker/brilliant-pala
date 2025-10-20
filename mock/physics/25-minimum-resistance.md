# Question
A student has 10 resistors of resistance 'r' each. The minimum resistance made by him from given resistors is:  
1) r / 10  
2) 10 r  
3) r / 100
4) r / 5

## Build the idea from real life

Question to start: If you want to make it as easy as possible for water to flow from one tank to another, what helps more?
- Making the pipe longer (series) — that adds more friction.
- Or giving the water more parallel pipes (parallel) — more lanes for flow.

Electric current behaves similarly. A resistor is like a “narrow pipe” for electrons. More resistors in series make the path longer (harder), while more in parallel make more lanes (easier).

---

## Reconstruct the rules (from first principles)

We’ll use two basic ideas:
- Ohm’s law: current responds to voltage like V = I R.
- Conservation: in series, the same current flows; in parallel, currents split and add.

### Series (one path, resistors end-to-end)
Same current I flows through each; voltages add:
```math
V_\text{total} = I(R_1 + R_2 + \dots) \implies R_\text{eq} = R_1 + R_2 + \dots
```
So series always increases resistance.

### Parallel (many paths, both ends tied together)
Same voltage V across each; currents add:
```math
I_\text{total} = I_1 + I_2 + \dots
= \frac{V}{R_1} + \frac{V}{R_2} + \dots
= V\left(\frac{1}{R_1} + \frac{1}{R_2} + \dots\right).
```
So
```math
\frac{1}{R_\text{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots
```
For N identical resistors of resistance r in parallel:
```math
\frac{1}{R_\text{eq}} = \frac{N}{r} \quad \Rightarrow \quad R_\text{eq} = \frac{r}{N}.
```

Text sketch of “all parallel”:
- Two big rails (top and bottom) are the terminals.
- Each resistor is a rung connecting the rails.
- More rungs = more lanes for current.

---

## What arrangement gives the absolute minimum?

Use all 10 resistors as separate parallel branches. That maximizes the total “conductance” (ease of flow), thus minimizes resistance.

A neat check: Suppose you tried mixing series and parallel by making m parallel branches, each branch having k resistors in series (so km = 10). Each branch has resistance k r, and m such branches in parallel give:
```math
R_\text{eq} = \frac{k r}{m} = \frac{k r}{10/k} = \frac{k^2}{10}\, r.
```
This is smallest when k = 1 (the smallest possible), i.e., no series at all. That gives:
```math
R_\text{min} = \frac{r}{10}.
```
Any series anywhere only makes it bigger.

So among the options, the minimum is r/10.

Answer: 1) r / 10

---

## Experimental view (how you’d verify)
- Take 10 identical resistors and connect both ends of every resistor to the same two nodes (all-parallel).
- Measure with an ohmmeter: it should read one-tenth of a single resistor’s value.
- If you instead put any two in series, the reading goes up.

---

## Intuitive checks
- r/100 would mean “as easy as 100 resistors in parallel.” But you only have 10.
- 10 r is the maximum (all in series), not the minimum.
- r/5 is what you’d get if you did 5 parallel branches of 2r each (pairs in series), which is larger than r/10.

---

> ### 🧠 Quick Exam Tips
> - To minimize resistance with identical resistors: put all in parallel → R_min = r/N.
> - To maximize resistance: put all in series → R_max = N r.
> - Mixing series inside parallel branches increases resistance compared to pure parallel.

---

## Misconception clinic
- “Maybe a clever bridge (like Wheatstone) could go below r/10.” No. Any series portion increases path resistance. The maximum conductance you can get is by placing every resistor directly across the same two nodes (pure parallel).
- “Do I have to use all resistors?” For minimum resistance, using more in parallel always helps, so yes—use all of them in parallel.

---

## Quick practice
1) With 12 resistors of r each, what is the minimum possible resistance?
- Answer: r/12.

2) With 6 resistors of r each, arranged as 3 branches of 2 in series per branch:
- Each branch = 2r; 3 in parallel → R_eq = (2r)/3.

---

> ### 🌱 Reflective essence
> Nature rewards parallelism: more independent paths reduce resistance—in circuits, traffic, data networks, and even teamwork. More lanes, shorter waits.