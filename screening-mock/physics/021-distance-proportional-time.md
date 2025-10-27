# Question
The distance travelled by a body is directly proportional to time. Then the force acting on body will be:  
1) 1 N  
2) 0 N  
3) 9.8 N  
4) 98 N

---
# Answer
## Quick visual reasoning
- Picture a time-lapse: every tick of the clock, the body covers equal chunks of distance. The distance–time plot would be a straight line with steady slant.
- Equal distance each tick means a steady pace — no speeding up, no slowing down.
- A net push would make each later chunk longer (or shorter); the line would bend.
- Since there’s no bend, there’s no overall push changing the motion.

Answer: 2) 0 N

## Creative twists
- Mixing “no force” with “no net force”: pushes can exist but balance out, giving zero overall effect.
- Grabbing familiar-looking numbers (like weights of objects) even though nothing here changes pace.
- Thinking “constant speed” always means “no force” even when turning; in a curve the direction changes, so there is a net force. Here we’re reading it as straight, steady motion.
- Cruise control on a highway: engine push matches air and tire drag, so distance ticks up evenly — net force zero.
- Elevator gliding smoothly: cable pull balances weight; floors pass at equal intervals — net force zero.

## Start with a real-world feel
Question to you: If your car’s odometer increases by the same amount every second, what does that say about your driving?
Answer: You’re cruising at a constant speed.

“Distance is directly proportional to time” means: double the time → double the distance; triple the time → triple the distance. That’s exactly what “constant speed” feels like.

---

## Build from first principles

Let distance be s and time be t. “Directly proportional” means:
```math
s = k\,t \quad \text{for some constant } k
```
- Velocity is “how fast distance changes,” so:
```math
v = \frac{ds}{dt} = k \quad \Rightarrow \quad \text{velocity is constant}
```
- Acceleration is “how fast velocity changes,” so:
```math
a = \frac{dv}{dt} = 0
```
Newton’s second law connects force and acceleration:
```math
F_\text{net} = m\,a = m \times 0 = 0
```
So the net force on the body is zero.

Pick: 2) 0 N

---

## Why this makes sense (intuition chain)

- Constant distance-per-time → constant speed.
- No change in speed (and if direction is straight) → no acceleration.
- No acceleration → no net force needed to keep it moving (inertia).
- Forces are only needed to change motion, not to sustain steady motion.

Visual aid (mentally imagine):
- A straight line on an s–t graph. Its slope is constant (that slope is the speed).
- If slope is constant, the v–t graph is a flat line.
- A flat v–t line has zero slope, so acceleration is zero.

---

## Experimental view

On an air track (very low friction), a glider pushed once keeps moving at nearly constant speed without further push. The measured net force is ~0, matching the math.

---

## Dimensional and logical check

- Options like 9.8 N or 98 N need a mass to make sense (they’re typical weights: 1 kg × g or 10 kg × g).
- The question gives no mass. The only mass-independent option that fits constant velocity is 0 N.

---

## Small but important caveat

If the path curves (like uniform circular motion), distance can still be proportional to time (constant speed), yet direction changes, so acceleration isn’t zero and a force acts toward the center. But the question usually assumes straight-line motion unless stated otherwise. With the given options, 0 N is the intended answer.

---

> ### 🧠 Quick Exam Tips
> - Distance ∝ time → constant speed.
> - Constant speed in a straight line → zero acceleration → zero net force.
> - Force changes motion; it doesn’t sustain steady motion.

---

## Misconception clinic

- Many students think “moving object needs a force to keep moving.” But actually, only a change in motion (speed or direction) needs net force. No change → no net force.
- Confusing weight with net force: 9.8 N is the weight of a 1 kg mass on Earth, not the horizontal net force here.
- Forgetting direction: constant speed with changing direction still means acceleration exists. Here we assume straight-line motion.

---

## Quick practice

1) A cyclist moves at constant speed in a straight line. What is the net horizontal force?
- Answer: 0 N (air resistance and friction are balanced by the cyclist’s driving force).

2) A stone on a string moves in a horizontal circle at constant speed. Is the net force zero?
- Answer: Not zero. There is inward (centripetal) force; speed is constant but direction changes.

---

## Reflective essence

> Physics separates “motion” from “change of motion.” Nature doesn’t charge you force to keep moving; it charges you force to change. That one idea— inertia—unlocks a lot of fast thinking in mechanics.