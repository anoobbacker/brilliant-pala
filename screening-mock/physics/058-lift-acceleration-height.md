## Question
A lift starts from rest. Its acceleration is plotted against time in the following graph. When it comes to rest, its height in meter above its starting point is

```
        a (m/s^2)
        ^
      4 |--------|
        |        |
        |        |
(s) ----+--------+-----------+-------------+---> t
        0        4           8             12 
        |                    |             |
        |                    |             |
 -4 ----+---v----|-----------|-------------|        
            4           8                 12
```

**Options:**

1. 64
2. 128
3. 32
4. 164

## Understand the story the graph is telling

- Think of riding a lift (elevator). A smooth ride feels like this:
  1) It speeds up from rest (you feel heavier),  
  2) Then moves at steady speed (you feel normal),  
  3) Then slows to a stop (you feel lighter).

- The acceleration–time graph shows exactly that:
  - From 0 to 4 s: acceleration is +4 m/s² (speeding up upward).
  - From 4 to 8 s: acceleration is 0 (coasting at constant speed).
  - From 8 to 12 s: acceleration is −4 m/s² (slowing down to rest).

This is the only interpretation that also matches “starts from rest” and “comes to rest at the end.”

## First principles: how acceleration builds velocity, and velocity builds distance

- Acceleration tells you how quickly velocity changes. Over a small time Δt:
  - Change in velocity ≈ a × Δt
  - Units check: (m/s²) × (s) = m/s, which is velocity.

- Velocity tells you how quickly position changes. Over a small time Δt:
  - Change in position ≈ v × Δt
  - Units check: (m/s) × (s) = m, which is distance.

So:
- Area under the acceleration–time graph gives change in velocity.
- Area under the velocity–time graph gives displacement (height gained here).

We’ll build velocity first (from acceleration), then distance (from velocity).

## Step 1: Build the velocity from the acceleration graph (area under a–t)

Start: v(0) = 0 (lift starts from rest).

1) From t = 0 to 4 s, a = +4 m/s²
```math
\Delta v_{0\to4} = a \times \Delta t = 4 \times 4 = 16 \ \text{m/s}
```
So v(4) = 16 m/s (upward).

2) From t = 4 to 8 s, a = 0
```math
\Delta v_{4\to8} = 0 \times 4 = 0
```
So v(8) = 16 m/s (still).

3) From t = 8 to 12 s, a = −4 m/s²
```math
\Delta v_{8\to12} = (-4) \times 4 = -16 \ \text{m/s}
```
So v(12) = 16 + (−16) = 0 m/s, i.e., it comes to rest.

Mental picture of v–t:
- Ramps up linearly from 0 to 16 m/s (0–4 s),
- Stays flat at 16 m/s (4–8 s),
- Ramps down linearly from 16 to 0 (8–12 s).

## Step 2: Build the displacement from the velocity graph (area under v–t)

Displacement = total area under the v–t graph.

1) 0–4 s: v rises linearly 0 → 16 m/s
- Average v = (0 + 16)/2 = 8 m/s
- Time = 4 s
```math
s_{0\to4} = \text{avg }v \times \Delta t = 8 \times 4 = 32 \ \text{m}
```

2) 4–8 s: v = 16 m/s constant
```math
s_{4\to8} = 16 \times 4 = 64 \ \text{m}
```

3) 8–12 s: v drops linearly 16 → 0 m/s
- Average v = (16 + 0)/2 = 8 m/s
- Time = 4 s
```math
s_{8\to12} = 8 \times 4 = 32 \ \text{m}
```

Total height gained:
```math
s_{\text{total}} = 32 + 64 + 32 = 128 \ \text{m}
```

## Check with dimensional reasoning and symmetry
- The speeding-up and slowing-down phases are symmetric (same |a| and duration), so they contribute equal distances (32 m each), with a flat middle segment adding the most (64 m). Sum = 128 m, consistent.
- Units: area under v–t is (m/s)×s = m. Good.

## Answer
128 meters above the starting point.

Correct option: 2

---

## Conceptual follow-up questions
1) If the middle segment (a = 0) lasted 6 s instead of 4 s, how much higher would the lift go?  
2) If the final deceleration were −8 m/s² but lasted only 2 s, would the lift still come to rest at 12 s? Why or why not?  
3) If the lift had a = +3 m/s² for 4 s, 0 for 4 s, and then a = −3 m/s² for 4 s, what would be the final speed? What would change about the total height?

## Application questions
- Elevators use “acceleration–cruise–deceleration” profiles to balance comfort and speed. Why does reducing peak acceleration reduce both jerk felt by passengers and mechanical wear?  
- High-speed trains and electric cars also shape acceleration profiles. How would energy usage and passenger comfort trade off if you changed the length of the cruising segment?

## Common misconceptions and traps
- Confusing acceleration with velocity: A flat a–t segment at zero is not “rest” — it means constant velocity, not zero velocity.  
- Ignoring signs: Negative acceleration here slows upward motion; it doesn’t mean downward motion unless the velocity actually crosses zero.  
- Using formulas without context: Plugging s = ut + 1/2 at² everywhere fails in the middle segment (a = 0) and the last segment (different a and different u). Always piecewise-analyze.

## Extension challenges
- Derive the same result by integrating explicitly: v(t) from a(t), then s(t) = ∫ v(t) dt over each interval.  
- Suppose the acceleration ramps smoothly (no sharp corners): a(t) is triangular (jerk-limited profile). Sketch v(t) and estimate the displacement. How does it compare to the boxy (constant a) case?  
- If the lift’s maximum allowed acceleration is 4 m/s² and maximum allowed jerk is 1 m/s³, design a time-minimizing a(t) that starts and ends at rest and reaches a cruising speed without exceeding limits.

## Reflective insight
At its core, motion is about stacking rates on top of rates:
- Acceleration accumulates into velocity (area under a–t),
- Velocity accumulates into position (area under v–t).
Graphs make this tangible: areas tell you “how much change piled up.” Once you see motion this way, you can handle any piecewise profile — not by memorizing formulas, but by reasoning from the shapes and the units.