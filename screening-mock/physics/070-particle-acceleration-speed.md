# Question
A particle is initially at rest, it is subjected to a linear acceleration ' $a$ ', as shown in the figure. The maximum speed attained by the particle in $\mathrm{m} / \mathrm{s}$ is

```
     a (m/s²)
     ^              
     |              
10 --+*\            
     |  \           
     |   \          
     |    \         
     |     \        
     |      \       
     |       \     
     |        \    
     |         \   
     |          \  
     +-----------\--------------------> time (s)
     0            11
```

---
# Answer
## Quick visual solution
- Picture the acceleration graph as a ramp: starts high at 10 and slides linearly down to 0 by 11 s.
- Each 1-second strip under this curve adds a “chunk” of speed. All chunks stacked make a triangle. That triangle’s area is the total speed gained.
- A straight ramp has a perfectly even “rise-and-fall,” so its average height is halfway between top and bottom: halfway between 10 and 0 is 5.
- So it’s as if you had a flat strip of height 5 that lasts the whole 11 s. Stacking 11 equal strips of height 5 gives a speed gain of 5 × 11 = 55.
- Acceleration never goes negative before 11 s, so speed keeps climbing until then. That’s the maximum.

Answer: 55 m/s

## Creative twists
- Reading the graph as speed vs time and doing 10 × 11 = 110 (forgetting it’s acceleration, and the shape is a triangle, not a rectangle).
- Missing that a straight ramp averages to the midpoint height (5 here).
- Thinking speed keeps increasing after acceleration hits zero. With zero push, speed stops changing—so the top speed is exactly at 11 s.
- If the line dipped below the axis later, the top speed would occur where the curve crosses zero (area stops growing and starts shrinking).
- Same idea in real life: a tap’s flow fading steadily while filling a bucket—the total water added equals the “area under the flow-time graph.” A steady half-strength flow for the whole time gives the same fill as a linearly fading flow.

## Idea in one line
Speed grows when acceleration is positive and shrinks when it’s negative. The graph shows acceleration starting at 10 and decreasing linearly to 0 at 11 s, so the speed is largest exactly when the acceleration hits zero. That maximum speed equals the area under the acceleration–time graph up to 11 s (a triangle).

## Start from everyday thinking
- Think of velocity as “how much water is already in a tank.”
- Think of acceleration as the “flow rate” of water into the tank.
  - If the flow rate is positive, the water level (speed) rises.
  - If the flow rate later becomes negative, water drains and the level drops.
- The total water added is “flow rate × time.” If the flow rate changes with time, you add up little rectangles: area under the flow-rate vs time graph.

So: change in velocity = area under the acceleration–time graph.

## From first principles: why “area under a–t graph = change in velocity”
- Definitions:
  - Velocity is rate of change of position: $v = \frac{\Delta x}{\Delta t}$ (in the small-time limit).
  - Acceleration is rate of change of velocity: $a = \frac{\Delta v}{\Delta t}$ (in the small-time limit).
- Over a tiny interval $\Delta t$, velocity changes by approximately:

```math
  \Delta v \approx a(t)\,\Delta t
  ```
- Add these tiny changes from $t=0$ to $t=T$:

```math
  \Delta v \approx \sum a(t)\,\Delta t
  ```
- In the limit of very small slices, this sum becomes the area (integral):

```math
  v(T) - v(0) = \int_{0}^{T} a(t)\,dt
  ```
- Unit check (dimensional analysis):
  - Acceleration: m/s²; time: s; product: (m/s²)·s = m/s, which is a change in velocity. Good.

## Read the given graph
- At $t=0$, $a = 10$ m/s².
- Acceleration decreases linearly to $a=0$ at $t=11$ s.
- After that, if the line continued below the axis, $a$ would be negative (deceleration), so the speed would start to decrease.
- Therefore, the maximum speed happens exactly when $a$ crosses zero, i.e., at $t=11$ s.

## Compute the maximum speed (graphical/area method)
From $t=0$ to $t=11$ s, the acceleration–time graph is a right triangle with:
- Height = 10 m/s²
- Base = 11 s

Area of triangle = 1/2 × base × height:
```math
v_{\max} = \Delta v = \frac{1}{2}\times 11 \times 10 = 55\ \text{m/s}
```
- Interpretation: starting from rest, the particle speeds up to 55 m/s by the time $a$ falls to zero.

## Two more ways to see it (reconstructed, not memorized)

### 1) Average-acceleration reasoning (since it’s linear)
- For a straight-line change from 10 to 0, the average acceleration over 0–11 s is the midpoint: $(10 + 0)/2 = 5$ m/s².
- Change in velocity = average acceleration × time:

```math
  \Delta v = (5\ \text{m/s}^2)\times (11\ \text{s}) = 55\ \text{m/s}
  ```

### 2) Algebraic accumulation (integral as sum)
First write the linear function for $a(t)$:
- Slope = fall/rise in time = $-10/11$ m/s³.
- So:

```math
  a(t) = 10 - \frac{10}{11}t
  ```
Integrate from 0 to 11 s:
```math
v(11) - v(0) = \int_{0}^{11}\left(10 - \frac{10}{11}t\right)dt
= \left[10t - \frac{10}{22}t^2\right]_{0}^{11}
= 110 - \frac{10}{22}\cdot 121
= 110 - 55
= 55\ \text{m/s}
```

## Final answer
```math
\boxed{55\ \text{m/s}}
```

---

## Conceptual follow-up questions
1. If the acceleration became negative after 11 s (continuing the same straight line), what would happen to the speed? When would it be largest? Why?
2. If the graph were a straight line from 10 m/s² at $t=0$ to −10 m/s² at $t=20$ s, at what time would the speed be maximum?
3. If the particle didn’t start from rest but from 5 m/s, how would that change the result? How would you incorporate it in the area method?

## Application questions
- Engineering braking systems: Why does the maximum speed of a car under a “fade-out” throttle (gradually reducing engine force) occur just when net acceleration drops to zero?
- Rocket burns: If thrust decreases linearly as fuel pressure drops, how would you estimate the rocket’s burnout speed from the thrust-time graph?
- Sports biomechanics: In a sprint, if the runner’s acceleration falls roughly linearly after the start, why is the top speed reached when their forward acceleration becomes zero?

## Common misconceptions and reasoning traps
- “Speed is highest where acceleration is highest.” Not necessarily. High acceleration early only starts the build-up; the speed keeps increasing as long as acceleration stays positive. The maximum speed occurs when positive acceleration runs out and turns negative (i.e., at $a=0$).
- “Area under any graph is meaningless.” It depends on axes. Area under a–t has units m/s, which is velocity change. Always check units to see what an area represents.
- “If acceleration goes to zero, speed must be zero.” Zero acceleration means speed is not changing at that instant; it does not mean the speed is zero. It could be any value.

## Extension challenges
- Suppose the acceleration decreases quadratically: $a(t) = 10\left(1 - (t/11)^2\right)$ for $0 \le t \le 11$. Compute the maximum speed by integrating and compare with the linear case.
- You are given noisy experimental acceleration data as a table. How would you estimate the maximum speed numerically (e.g., using the trapezium rule)? Discuss error sources.
- Design an acceleration profile that achieves the same maximum speed in 11 s but minimizes peak acceleration (use a “cap” on $a$). What shape might the a–t graph have?

## Reflective insight
The essence: velocity is the accumulation of acceleration over time. Graphically, this is “area under the curve.” Maxima in accumulated quantities occur where the rate switches sign—from adding to subtracting. That’s why the top speed appears exactly when acceleration crosses zero, and why carefully reading units and slopes on graphs can solve physics problems without memorized formulas.
