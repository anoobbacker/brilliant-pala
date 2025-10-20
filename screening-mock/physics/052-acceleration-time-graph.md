## Question
Acceleration time graph of a particle moving along a straight line is as shown in figure. Initial velocity of the particle is $10 \mathrm{~m} / \mathrm{s}$. The velocity of the particle at $5^{\text {th}}$ second is

![A diagram of a line AI-generated content may be...](https://d3e4y8hquds3ek.cloudfront.net/institute/brilliantpalaelearn/questions/8cf74b78dce14b1a810a89ce1bed8e1c.png)

**Options:**

1. [ ] $15 \mathrm{~m} / \mathrm{s}$
2. [ ] $10 \mathrm{~m} / \mathrm{s}$
3. [✓] $25 \mathrm{~m} / \mathrm{s}$
4. [ ] $30 \mathrm{~m} / \mathrm{s}$

## Understand the situation (from everyday intuition)
- Think of the accelerator in a car. Pressing it changes how quickly your speed increases — that “how quickly” is called acceleration.
- If acceleration is high for some time, your speed goes up a lot. If acceleration is zero, your speed stays the same. If acceleration is negative (braking), your speed goes down.

The graph you’re given shows how acceleration changes with time. Your job is to use that to find the speed at t = 5 s, knowing the initial speed was 10 m/s.

From the figure:
- The acceleration starts at 6 m/s² at t = 0 s.
- It decreases in a straight line to 0 m/s² at t = 5 s.
- So the a–t graph is a right triangle with base 5 s and height 6 m/s².

## Build the physics from first principles
### What does “acceleration” do to velocity?
- Acceleration is the rate at which velocity changes:
  
  ```math
  a = \frac{dv}{dt}
  ```

- Rearranged for a tiny time slice dt:
  
  ```math
  dv = a \, dt
  ```

- To get the total change in velocity from t = 0 to t = 5 s, add up (integrate) all these tiny contributions:
  
  ```math
  \Delta v = \int_{0}^{5} a(t) \, dt
  ```

- Graphically, this integral is just the area under the acceleration–time (a–t) graph between 0 and 5 s.

So: Change in velocity = area under the a–t graph.

### Read the graph and find the area
- The graph is a triangle with:
  - Base = 5 s
  - Height = 6 m/s²
- Area of a triangle = 1/2 × base × height:
  
  ```math
  \text{Area} = \frac{1}{2} \times 5 \times 6 = 15 \ \text{(m/s)}
  ```

- Units check: (m/s²) × s = m/s, which matches “change in velocity.”

This area is the total increase in velocity over 5 s.

### Find the velocity at 5 s
- Initial velocity v₀ = 10 m/s
- Increase Δv = 15 m/s
- Therefore:
  
  ```math
  v(5\ \text{s}) = v_0 + \Delta v = 10 + 15 = 25 \ \text{m/s}
  ```

Answer: 25 m/s

## Why the “triangle area” method is valid (another angle)
Because the line is straight from 6 to 0, the acceleration changes uniformly. The average acceleration over 0–5 s is just the midpoint of 6 and 0:

```math
a_{\text{avg}} = \frac{6 + 0}{2} = 3 \ \text{m/s}^2
```

Change in velocity = average acceleration × time:

```math
\Delta v = a_{\text{avg}} \cdot \Delta t = 3 \times 5 = 15 \ \text{m/s}
```

Same result.

## Final result
- Velocity at t = 5 s = 25 m/s

---

## Conceptual follow-up questions
1. If the acceleration line dipped below the time axis (negative) between 3–5 s, how would that affect the final velocity? Why?
2. If the initial velocity were 0 m/s, what would the final velocity be? How does that change your area reasoning?
3. If the acceleration were constant at 3 m/s² for 5 s, would you get the same final velocity? Explain using area.
4. What if the graph were curved (not straight)? How would you still use the area idea to get Δv?

## Application questions
- Car design: Braking systems aim to control deceleration (negative acceleration) smoothly. Why might engineers prefer a linearly changing deceleration rather than an abrupt one?
- Rockets: Thrust (force) changes with time as fuel burns. Since acceleration = force/mass, how would an a–t graph help estimate a rocket’s velocity gain during a burn?

## Common misconceptions and traps
- Confusing acceleration with velocity: A high acceleration doesn’t mean high speed instantly. It means speed is increasing quickly. You still need time and area to get actual speed change.
- Using v = u + at blindly: That only works if acceleration is constant. Here it changes with time — we used the area (integral) instead.
- Misreading “at 5th second”: Some problems say “in the 5th second,” which refers to the interval 4–5 s. “At 5 s” means the exact moment t = 5 s. Be precise.

## Extension challenges
1. Equation approach: Write the acceleration as a function a(t) for 0 ≤ t ≤ 5 s (it’s a straight line from 6 to 0). Integrate to find v(t) for any time t in this interval.
2. Displacement: First find v(t) (from the previous step), then integrate v(t) from 0 to 5 s to get how far the particle traveled in 5 s.
3. Reverse problem: Suppose you know v(5 s) must be 25 m/s starting from 10 m/s, and you’re allowed only a straight-line a–t graph from t = 0 to 5 s that ends at a(5) = 0. Find the required a(0). Show that area reasoning fixes this uniquely.

## Reflective insight
At the heart of this problem is a powerful idea: “Area under a rate curve equals total accumulated change.” Acceleration is the rate of change of velocity. So the area under the a–t graph isn’t just a shape — it is literally the velocity you’ve gained. This one insight generalizes everywhere: area under a speed–time graph gives distance; area under a power–time graph gives energy; area under a probability density gives probability. When in doubt, think “rate × time = accumulation,” and read the area.