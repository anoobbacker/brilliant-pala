# Question
Two cars A and B simultaneously start a race. Velocity 'v' of the car A varies with time 't' according to the graph shown in the figure. It acquires a velocity 50 m/s five seconds before t = 100 s and thereafter moves with this speed. Car B runs together with car A till both acquire a velocity 20 m/s; after this, car B moves with zero acceleration for one second and then follows velocity-time profile identical to that of A with a delay of one second. In this way, car B acquires the velocity 50 m/s one second after A acquires it. How much more distance Δs (as in meter) does the car A cover in the first 100 s as compared to the car B?

Graph:
The graph is a **velocity-time graph** showing how the velocity of car A changes over time. It starts at **0 m/s** at **t = 0 s**. and increases. The curve is not smooth in the sense of being gradual or uniform; instead, it shows changing acceleration — likely increasing rapidly at first and then tapering off as it approaches 50 m/s. The velocity reaches **50 m/s** at **t = 95 s**. From **t = 95 s to t = 100 s**, the velocity remains constant at **50 m/s**, forming a horizontal line.

```log
v/(m/s)
  |
50+ - - - - - - - - - - - - - - - - - - - - - - - -
  |           . . . . . . . . . . . .|
  |        .                         |
  |      .                           |
  |     .                            |
  |    .                             |
  |   .                              |
  |  .                               |
  | .                                |
  |.                                 |
 0+----------------------------------+-------------> t/s
  0                                100
```

1) Δs = 20 m  
2) Δs = 30 m  
3) Δs < 30 m  
4) Insufficient information

## Big Idea: Distance is “area under the speed graph”

Imagine two runners on a track:
- Car A speeds up smoothly and reaches 50 m/s by 95 s, then stays at 50 m/s.
- Car B copies A at first, then takes a 1-second “breather” at 20 m/s, and after that runs exactly like A but always 1 second behind.

Key physical meaning:
- Distance covered = the area under the velocity–time graph.
- So “who went farther?” becomes “whose graph encloses more area?”

---

## Translate the story into a clean picture

- Let t20 be the time when A’s speed first reaches 20 m/s.
- From 0 to t20: B copies A exactly (same area).
- From t20 to t20 + 1 s: B holds constant speed 20 m/s (zero acceleration means constant speed).
- After t20 + 1 s: B follows the same v–t profile as A, but delayed by 1 s. In symbols, for these times, v_B(t) = v_A(t − 1).

Because A is already at 50 m/s from 95 s to 100 s, we know A’s speed in the last second: it’s a flat 50 m/s.

---

## Analytical view: Let’s do the area accounting

Let S_A(T) and S_B(T) be distances of A and B up to time T.

- For B up to 100 s, split time into the three parts described above:
  1) 0 → t20: area equals A’s area there.
  2) t20 → t20 + 1: area = 20 × 1 = 20 m.
  3) t20 + 1 → 100: since v_B(t) = v_A(t − 1), a 1-second shift in time turns this area into A’s area from t = t20 to t = 99.

So:
```math
S_B(100) \;=\; \int_0^{t_{20}} v_A(t)\,dt \;+\; 20 \;+\; \int_{t_{20}}^{99} v_A(u)\,du
\;=\; \int_0^{99} v_A(t)\,dt \;+\; 20.
```

A’s distance is just:
```math
S_A(100) \;=\; \int_0^{100} v_A(t)\,dt.
```

Therefore the difference is:
```math
\Delta s \;=\; S_A(100) - S_B(100)
\;=\; \int_{99}^{100} v_A(t)\,dt \;-\; 20.
```

Now use the given graph fact: v_A(t) = 50 m/s for 95 s ≤ t ≤ 100 s.
So the last 1-second area for A is simply:
```math
\int_{99}^{100} v_A(t)\,dt \;=\; 50 \times 1 \;=\; 50\;\text{m}.
```

Thus:
```math
\Delta s \;=\; 50 - 20 \;=\; 30\;\text{m}.
```

Answer: 2) Δs = 30 m.

---

## Why this works (intuitive view)

- After B’s 1-second pause at 20 m/s, B is always 1 second behind A.
- So by t = 100 s, B is “missing” whatever A did in the last 1 second (from 99 to 100 s).
- Replace that “missing” slice with what B did during its 1-second pause: a flat 20 m.
- Difference = A’s last 1-second area − 20 m = 50 − 20 = 30 m.

Dimensional check: velocity × time = distance. 50 m/s × 1 s = 50 m; 20 m/s × 1 s = 20 m. Difference 30 m. Units and magnitudes make sense.

---

## Experimental view

If you had GPS speed data for both cars:
- Compute the area (distance) numerically.
- You’d see B’s curve overlaps A’s except for a 1-second flat segment at 20 m/s, and then the whole curve is shifted by 1 second.
- The net difference is exactly the last 1-second area of A minus that flat 20 m strip.

---

> ### 🧠 Quick Exam Tips
> - Distance under a v–t graph is area. Area tricks (cut, shift, and paste) can avoid calculus.
> - A time delay of 1 s turns an integral from [a, b] into [a−1, b−1].
> - Zero acceleration means constant velocity (flat line).
> - You don’t need A’s full curve. Only A’s average speed in the last 1 s matters here.

---

## Misconception Clinic
- Many students think you must know when A first hits 20 m/s (t20). But actually it cancels out when you shift the areas.
- A common mistake is mixing “zero acceleration” with “zero velocity.” Zero acceleration means the speed stays what it is at that instant (here, 20 m/s), not that it drops to zero.
- Another trap: worrying about the exact shape of A’s acceleration. The time-shift property makes the result depend only on A’s last 1-second speed.

---

## Conceptual follow-ups
- What if A wasn’t flat at the end? Then Δs would be “A’s average speed from 99 to 100 s minus 20,” still the same formula.
- If B had paused for 2 seconds at 20 m/s and then followed with a 2-second delay, the difference at 100 s would be A’s last 2-second area minus 2 × 20.

---

## Interactive Practice
1) If A’s final speed (from 95 to 100 s) were 40 m/s instead of 50 m/s, what would Δs be?
Hint: Use the same formula: Δs = A’s last-1-second area − 20.

2) If B paused 1 s at 25 m/s instead of 20 m/s (everything else the same), what would Δs be?
Hint: Replace “20” with “25” in the difference.

3) Generalize: If B pauses for τ seconds at speed v_p and then follows A with a τ-second delay, show that
```math
\Delta s = \int_{100-\tau}^{100} v_A(t)\,dt - \tau\, v_p.
```

---

> ### 🌱 Reflective Essence
> Time shifts don’t change shapes; they move them. When you compare motions, align shapes in your mind and subtract what’s common. What remains is the true cause of the difference.