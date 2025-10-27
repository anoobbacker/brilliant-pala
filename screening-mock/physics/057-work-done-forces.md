# Question
Total work done by all the forces on a body is equal to

**Options:**

1. Change in potential energy
2. Change in mechanical energy
3. Change in kinetic energy
4. -(Change in potential energy)

---
# Answer
## Why (visual)
- Picture a skateboarder. Add up every push and pull along their path—friends pushing, gravity on a slope, friction, air drag. The combined effect decides only one thing: how their speed changes.
- Faster or slower is the “motion-energy” of the skateboarder. That’s kinetic energy. So the total push-along-the-motion changes kinetic energy.

## Why not the others
- Change in potential energy: That’s the “height/spring” store. Only certain forces (like gravity or a spring) swap this with motion-energy. But “all forces” includes friction and engines too, so it’s not just potential.
- Negative change in potential energy: That matches the work of those special forces alone (like gravity), not all forces.
- Change in mechanical energy (kinetic + potential): This shifts mainly when non-conservative forces (like friction) act. But the total of all forces directly shows up as a change in speed—kinetic—not the sum.

Answer - 3. Change in kinetic energy

## Creative twists
- Seeing “all forces” and thinking “all energies,” picking mechanical energy.
- Thinking gravity’s role (height change) always tells the whole story, ignoring friction or engines.
- Forgetting sideways forces (like a tight turn) don’t speed you up—they just steer, so no change in kinetic energy from them.
- Car braking: All resisting forces together slow the car; the motion-energy drops—kinetic changes.
- Roller coaster: With no friction, gravity’s push trades height for speed, but the total push still shows up as speed change.
- Rocket thrust in space: No height change, yet thrust changes speed—kinetic shifts directly.

## Build-up from first principles (for deep understanding)

### 1) Everyday observation: what actually changes when you push?
- If you push a skateboard in the direction it’s moving, it speeds up.
- If you push sideways (like pulling in a circle), it changes direction but not speed.
- So, only the part of your push along the motion changes how fast it goes. That “speed-changing push over a distance” is what we call work.

This motivates:
- Work measures how much a force changes the motion by acting along the motion.

### 2) What is “work” and why this definition?
- When a small step of motion is along a tiny displacement vector d𝐬, the only effective part of force 𝐅 is its component along d𝐬.
- So the infinitesimal work is 𝐅·d𝐬 (dot product picks the along-the-motion part).
- Total work along a path is the accumulation (integral) of those tiny contributions:
  
```math
W = \int \mathbf{F} \cdot d\mathbf{s}
```

- If 𝐅 is perpendicular to motion (like ideal circular motion with centripetal force), 𝐅·d𝐬 = 0, so no speed change. That matches experience.

### 3) From Newton’s 2nd law to the Work–Kinetic Energy Theorem
We start only with definitions and Newton’s second law.

- Newton’s 2nd law: net force causes acceleration
```math
\mathbf{F}_{\text{net}} = m \mathbf{a}
```
- Velocity is rate of change of position: 𝐯 = d𝐬/dt.
- Acceleration is rate of change of velocity: 𝐚 = d𝐯/dt.

Now take the dot product of both sides with velocity 𝐯:
```math
\mathbf{F}_{\text{net}} \cdot \mathbf{v} = m \mathbf{a} \cdot \mathbf{v}
```

But there’s a key identity: the time derivative of speed-squared.
- Since $v^2 = \mathbf{v} \cdot \mathbf{v}$,
```math
\frac{d}{dt}\left(\tfrac{1}{2} m v^2\right) = m \mathbf{v} \cdot \frac{d\mathbf{v}}{dt} = m \mathbf{a} \cdot \mathbf{v}
```
So,
```math
\mathbf{F}_{\text{net}} \cdot \mathbf{v} = \frac{d}{dt}\left(\tfrac{1}{2} m v^2\right)
```

Integrate from time $t_1$ to $t_2$:
```math
\int_{t_1}^{t_2} \mathbf{F}_{\text{net}} \cdot \mathbf{v}\, dt
= \int_{t_1}^{t_2} \frac{d}{dt}\left(\tfrac{1}{2} m v^2\right) dt
= \tfrac{1}{2} m v_2^2 - \tfrac{1}{2} m v_1^2
```

But $\mathbf{v}\, dt = d\mathbf{s}$, so the left side is the total (net) work:
```math
W_{\text{net}} = \int \mathbf{F}_{\text{net}} \cdot d\mathbf{s} = \Delta\left(\tfrac{1}{2} m v^2\right) = \Delta K
```
This is the Work–Kinetic Energy Theorem, derived from Newton’s law.

Conclusion: Total work done by all forces equals change in kinetic energy.

### 4) Alternative derivation (distance-based intuition)
Sometimes it’s clearer to relate acceleration to how speed changes with distance.

- Chain rule: $a = \frac{dv}{dt} = \frac{dv}{ds}\frac{ds}{dt} = v \frac{dv}{ds}$.
- Newton: $F_{\text{net}} = ma = m v \frac{dv}{ds}$.
- Multiply both sides by $ds$:
```math
F_{\text{net}}\, ds = m v\, dv
```
- Integrate from start to end:
```math
\int F_{\text{net}}\, ds = \int m v\, dv \quad \Rightarrow \quad W_{\text{net}} = \tfrac{1}{2} m v_2^2 - \tfrac{1}{2} m v_1^2 = \Delta K
```

Same result, but via distance instead of time.

### 5) Units check (dimensional analysis)
- Work: newton·meter = (kg·m/s²)·m = kg·m²/s² = joule.
- Kinetic energy: $(1/2) m v^2$ = kg·(m/s)² = kg·m²/s² = joule.
- The units match, reinforcing the relationship.

### 6) So what about potential and mechanical energy?
- For conservative forces (like gravity, ideal springs), we can define potential energy U such that:
```math
W_{\text{conservative}} = -\,\Delta U
```
- Total work by all forces:
```math
W_{\text{all}} = W_{\text{conservative}} + W_{\text{non-conservative}} = \Delta K
```
- Rearranging:
```math
W_{\text{non-conservative}} = \Delta K + \Delta U = \Delta (K + U) = \Delta E_{\text{mechanical}}
```

Key distinctions:
- Total (net) work by all forces → change in kinetic energy (Option 3).
- Work by conservative forces alone → negative change in potential energy (Option 4).
- Work by non-conservative forces alone → change in mechanical energy (Option 2).

This also clarifies why Option 1 is not correct for “all forces.”

---

## Quick numerical intuition
Throw a ball straight up. From release to the highest point:
- Forces acting: only gravity (downward).
- It slows to zero at the top: ΔK is negative.
- Gravity does negative work during ascent; that equals the decrease in kinetic energy.
- Meanwhile U increases by exactly the kinetic energy lost, consistent with $W_g = -\Delta U$.

---

## Final choice
- Correct option: 3) Change in kinetic energy.

---

## Conceptual follow-up questions
1) If a force is always perpendicular to velocity (like ideal centripetal force), what is the net work and what happens to speed? Why?  
2) A block slides on a rough surface and slows down. Which forces do positive/negative work? How does ΔK compare to W_friction?  
3) If total work is zero over a motion, must all forces be zero? Give a counterexample.  
4) Can kinetic energy change without mechanical energy changing? Under what conditions?

## Applications to real life and engineering
- Braking systems: Brake pads do negative work on wheels; the lost K becomes thermal energy. Designing brakes means managing that energy flow safely.  
- Elevators: Motors do work against gravity to increase gravitational potential energy; regenerative braking can recover energy on descent.  
- Roller coasters: Track does (almost) no work if normal force is perpendicular; gravity swaps K and U; friction drains mechanical energy.  
- Batteries and electric motors: Electric forces do work on charges; that becomes mechanical work on shafts in motors.

## Common misconceptions and reasoning traps
- “Total work equals change in mechanical energy.” Not in general. Only non-conservative work equals Δ(mechanical). Total work equals ΔK.  
- “Any force does work if it’s non-zero.” Only the component along displacement does work; perpendicular forces change direction, not speed.  
- “If ΔK = 0, no forces acted.” False. Forces can act but do zero net work (e.g., uniform circular motion).  
- “Potential energy belongs to the object alone.” Potential is a property of a system (object + field), and only defined for conservative forces.

## Extension challenges
- Derive the work–kinetic theorem for a particle moving on a curved path under a magnetic force. Explain why magnetic forces do no work and what changes instead.  
- For a spring–mass with friction, show step-by-step that the decrease in mechanical energy equals the thermal energy generated by friction.  
- Use energy bar charts to compare different processes (free fall, ramp with friction, spring launch). Predict speeds and check with kinematics.

## Reflective insight: the deep “why”
Forces change motion, but only the part of a force that “pushes along the path” changes speed. Adding up that along-the-path influence over distance gives work. Newton’s law translates that accumulated push into a precise change in “motion content,” which we recognize as kinetic energy. That is why, at the most basic level, total work by all forces equals the change in kinetic energy. Understanding this cause-effect chain lets you navigate any energy problem with confidence.