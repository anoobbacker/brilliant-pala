# Question
Calculate the resistance of an electric bulb which allows a $10$ A current when connected to a $220$ V power source.

---
# Answer
## Quick visual reasoning
- Imagine electricity like water: voltage is push, current is flow, resistance is how tight the pipe is.
- Here, a push of 220 makes a flow of 10.
- Tightness is “push needed per one unit of flow.”
- So if 220 push gives 10 flow, then each 1 flow needs 220 divided into 10 equal parts → 22 push per flow.
- That “push per flow” is the resistance.

Answer: 22 ohms

## Creative twists
- Mixing up multiply vs divide: resistance isn’t push times flow; it’s how much push per unit flow.
- Thinking more current means more resistance: for the same push, more flow means it’s less tight, not more.
- Forgetting the check: 22 push per flow × 10 flows = 220 push, which matches the source.
- Water faucet: If a certain pressure gives a certain stream, the “stiffness” of the faucet opening is the pressure per stream—same idea.
- Air through a straw: Big push with small airflow means a tight straw (high resistance); same push with big airflow means a wide straw (low resistance).
- Wires in gadgets: Thicker wire (wider pipe) lowers tightness, so for the same push you get more flow—engineers use this to prevent overheating.

## Start with a real picture
Imagine electricity like water in a pipe.
- Voltage (V) is like the pressure pushing water.
- Current (I) is the flow rate of water.
- Resistance (R) is how narrow/rough the pipe is — it resists the flow.

Question: If you know the push (220 V) and the flow that results (10 A), how “narrow” is the path? That “narrowness” is the resistance.

---

## Build the relation from first principles
For many materials (at a fixed temperature), pushing twice as hard doubles the flow. That “linear response” is summarized by Ohm’s law:
```math
V \propto I \quad \Rightarrow \quad V = I R
```
Rearranging to find resistance:
```math
R = \frac{V}{I}
```
Unit check by dimensional reasoning:
```math
\frac{\text{volt}}{\text{ampere}} = \text{ohm} \; (\Omega)
```

---

## Calculate
```math
R = \frac{220\ \text{V}}{10\ \text{A}} = 22\ \Omega
```

Answer: The bulb’s resistance is 22 Ω.

---

## Quick consistency check (optional but powerful)
Power should match both ways:
- Using P = VI: P = 220 × 10 = 2200 W
- Using P = I²R: P = (10)² × 22 = 100 × 22 = 2200 W
Consistent — good sign our reasoning is coherent.

---

## Multiple lenses
- Intuitive view: Big push (voltage) causing a sizeable flow (current) through a moderate “narrowness” (resistance). 220 V producing 10 A means the filament isn’t extremely resistive.
- Analytical view: Direct substitution in R = V/I.
- Experimental view: In a lab, you’d connect the bulb to 220 V, measure current with an ammeter, and compute R from V/I at that operating point.

Note: Real incandescent bulbs aren’t perfectly “Ohmic” across all temperatures — their resistance changes as the filament heats up. But at a given operating point, we can still use V/I to define the instantaneous resistance.

---

> ### 🧠 Quick Exam Tips
> - Ohm’s law form triangle: V on top, I and R at the bottom — R = V/I, I = V/R, V = IR.
> - Always check units: V/A = Ω.
> - Fast power cross-check: P = VI = I²R = V²/R should agree.

---

## Conceptual follow-ups
- What if the voltage were halved to 110 V (and R stayed 22 Ω)? Then I = V/R = 110/22 = 5 A.
- If the bulb heats up and R increases, what happens to I for the same V? Current decreases.

## Misconception clinic
- Many students think resistance is a fixed property like mass. Actually, for metals, resistance rises with temperature (hot filament → higher R).
- Another mistake: Mixing formulas randomly. Decide what’s asked (R) and use the direct relation (R = V/I) before jumping to power formulas.

## Practice questions
1) A device draws 2 A at 12 V. What is its resistance?  
2) If a 44 Ω resistor is connected to 220 V, what current flows?  
3) A bulb has 22 Ω resistance at 220 V. What is its power?

Answers (quick): 1) 6 Ω, 2) 5 A, 3) 2200 W.

---

> ### Reflective essence
> Nature often follows “push vs. response.” Ohm’s law is one example: push (voltage) causes response (current), moderated by a property of the medium (resistance). Understanding the push–response–resistance triad unlocks many systems, from circuits to fluids to traffic flow.