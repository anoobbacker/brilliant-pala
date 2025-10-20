## Question
Which of the following pair have same unit?

**Options:**

1. Velocity and momentum
2. Force and power
3. Work and energy
4. Work and power

## Answer with first-principles reasoning
Correct option: 3. Work and energy

### Start from base ideas and build up units
In physics we reduce complex ideas to a few “base quantities” we can measure directly:
- Length (metre, m)
- Mass (kilogram, kg)
- Time (second, s)

Everything else is built from these.

### 1) Velocity — how fast position changes
Everyday idea: If you travel 100 m in 10 s, you’re moving 10 m per second. So velocity is “distance per time.”

```math
\text{velocity} = \frac{\text{distance}}{\text{time}} \quad\Rightarrow\quad [v] = \frac{\text{m}}{\text{s}}
```

Unit: m/s

### 2) Force — what causes acceleration
Observation: A push makes an object speed up, slow down, or change direction. The stronger the push, the bigger the acceleration for the same mass. The heavier the object, the smaller the acceleration for the same push. This cause-effect is captured by:

```math
\text{force} \propto \text{mass} \times \text{acceleration}
```

We define the Newton (N) so that 1 N gives a 1 kg mass an acceleration of 1 m/s²:
```math
[F] = [m][a] = \text{kg}\cdot\frac{\text{m}}{\text{s}^2} = \text{N}
```

Unit: N = kg·m/s²

### 3) Momentum — “quantity of motion”
Think stopping a moving cart: the heavier and/or faster it is, the harder it is to stop. Experimentally, if a constant force F acts for time t on a mass m starting from rest:
- Acceleration a = F/m
- Velocity after time t: v = at = (F/m)t

Rearrange:
```math
F t = m v
```
The left side (force × time) is the impulse you apply; it equals the change in motion on the right. This suggests defining momentum p as the “thing” that changes when you give an impulse:

```math
p = m v \quad\Rightarrow\quad [p] = \text{kg}\cdot\frac{\text{m}}{\text{s}}
```

Unit: kg·m/s

### 4) Work — energy transferred by a force through a distance
If you push with force F and the object moves through distance s in the direction of the push, you’ve transferred energy. Double the force or double the distance, and you double the transfer. This linear cause-effect leads to:

```math
W = F s \quad\Rightarrow\quad [W] = \text{N}\cdot\text{m} = \left(\text{kg}\cdot\frac{\text{m}}{\text{s}^2}\right)\cdot\text{m} = \text{kg}\cdot\frac{\text{m}^2}{\text{s}^2}
```

Unit: Joule (J) = N·m = kg·m²/s²

### 5) Energy — the capacity to do work
By definition, energy is the ability to do work. So they must share the same unit:

```math
[E] = [W] = \text{J} = \text{kg}\cdot\frac{\text{m}^2}{\text{s}^2}
```

### 6) Power — how fast work is done
Power is the rate of energy transfer. If you do the same work in less time, you need more power:

```math
P = \frac{W}{t} \quad\Rightarrow\quad [P] = \frac{\text{J}}{\text{s}} = \frac{\text{kg}\cdot\text{m}^2/\text{s}^2}{\text{s}} = \text{kg}\cdot\frac{\text{m}^2}{\text{s}^3}
```

Unit: Watt (W) = J/s

### Compare each option by units
- 1) Velocity (m/s) vs Momentum (kg·m/s): not the same.
- 2) Force (kg·m/s²) vs Power (kg·m²/s³): not the same.
- 3) Work vs Energy: both Joules (kg·m²/s²): same.
- 4) Work (J) vs Power (J/s): not the same.

Therefore, Option 3 is correct.

---

## Quick real-world anchors
- Speedometer: m/s (velocity).
- Airbags reduce force by increasing stopping time t for the same momentum change p (since Ft = Δp).
- Lifting a bag: doing work against gravity transfers energy; both measured in Joules.
- Light bulb rating (Watt): how fast it uses energy (Joules per second).

---

## 1) Conceptual follow-up questions
- If momentum changes only when there is an impulse, what units must impulse have? Show that it matches momentum’s units.
- A 60 W device uses 60 J each second. How long does it take to use 180 J?
- If two quantities share the same units, are they necessarily the same kind of thing? Explain using work vs torque (both N·m) but one is energy (scalar) and the other is a rotational effect (vector-like).
- If you double an object’s speed, how does its momentum change? Its kinetic energy? Why are these different?

## 2) Application questions
- Car safety: Why do crumple zones help reduce injury in a crash given the relation Ft = Δp?
- Elevator motor: If lifting a 100 kg load at constant speed of 0.5 m/s, estimate the required power. Hint: power ≈ force × speed; force here is weight.
- Renewable energy: A wind turbine’s power depends on air mass flow and velocity. Using dimensional thinking, argue why power scales with v³ of wind speed.

## 3) Common misconceptions and traps
- Confusing W (Watt) with W (symbol for Work). They are different: Work uses unit Joule; Watt is J/s.
- Thinking “same unit means same quantity.” Not always. Example: Work (energy, scalar) and torque (rotational effect) both use N·m but represent different physical ideas.
- Mixing up velocity and momentum because both involve m and s in the denominator. Momentum also includes mass.
- Believing force depends on speed directly. For a given mass, force causes acceleration; the relationship with speed depends on how long the force acts.

## 4) Extension challenges
- Show by experiment design how to measure momentum without a speedometer: use a known spring force over a measured compression time and apply impulse-momentum.
- Derive that kinetic energy must scale with v² using only: (a) doubling distance under constant force doubles work done, and (b) constant acceleration kinematics.
- Prove that power can be written as P = Fv for motion in the direction of the force, and check units to confirm.
- Explore why torque and work share units yet differ physically: one relates to rotation (moment arm), the other to energy transfer along displacement.

## 5) Reflective insight — the deep “why”
Units reveal the structure of cause and effect. Velocity compares change of position to time; force links mass to acceleration; momentum is the “motion budget” changed by impulse; work is how a force through distance transfers energy; power is how quickly that transfer happens. Because energy is defined by the capacity to do work, they naturally share the same unit. When you understand the chain from definitions to dimensions, you can reconstruct formulas confidently, even in unfamiliar problems.