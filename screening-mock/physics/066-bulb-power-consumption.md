## Question
A bulb rated $200 \mathrm{~V}, 100 \mathrm{~W}$ is connected to a potential difference of 100 V . The power consumed by the bulb in watt will be

---
# Answer
Find the power consumed by a bulb rated “200 V, 100 W” when it is connected to a 100 V supply — using first principles and clear cause-effect reasoning.

## Quick visual reasoning
- Picture the bulb as a fixed-width water pipe. Voltage is the “push” and current is the “flow.”
- At 200 V, it’s designed to use 100 W.
- If you halve the push to 100 V, the flow through the same “pipe” also halves (same thickness, same material).
- Power is like “push × flow.” Half the push and half the flow → the turning effect (power) becomes one-quarter.
- One-quarter of 100 W is 25 W.

## Final answer
25 W

## Creative twists
- Thinking “half the voltage gives half the power.” That ignores that both push and flow drop together, making it a quarter.
- Forgetting we’re treating the bulb like a fixed resistor here. Real filaments cool at lower voltage and change resistance, but exam-style reasoning keeps the “pipe width” fixed.
- Mixing up ratings: 200 V, 100 W is the designed operating point, not what always happens.
- Dimmer switch via a lower voltage: like lowering a waterfall’s height—each bucket of water has less energy and fewer buckets pass per second, so the wheel turns much more gently.
- Electric heater on a lower supply warms much slower for the same reason: both the “push” and the “flow” drop, making heat production about a quarter.
- In engineering, step-down transformers dim incandescent bulbs steeply because of this double reduction effect.

---

## Step 1: Decode what “200 V, 100 W” means
- Everyday idea: A bulb is like a narrow pipe for electrons. “Voltage” is like water pressure pushing charges; “current” is the flow rate; “resistance” is how narrow the pipe is.
- The label “200 V, 100 W” tells us:
  - If you push with 200 V, the bulb converts electrical energy into heat and light at 100 joules every second (that’s 100 W).
  - So at 200 V, the bulb is using 100 W. This fixes the bulb’s electrical “narrowness” (its resistance).

---

## Step 2: Build the power relation from first principles
- Start from energy per charge:
  - A voltage $V$ means each coulomb (C) of charge gains $V$ joules (J). Energy gained by charge $Q$ is $E = VQ$.
- If charges flow at a rate of $I$ coulombs per second (that’s current), then in 1 second, $Q = I \times 1$ flows.
- Power is energy per second, so:
  

```math
  P = \frac{\text{energy}}{\text{time}} = \frac{VQ}{t} = V\frac{Q}{t} = VI
  ```

- That’s the root idea: power equals voltage times current.

---

## Step 3: Introduce resistance and relate V, I, and R
- For many metal conductors (like a bulb filament at a given temperature), doubling the push (V) doubles the flow (I). This proportionality is captured by Ohm’s Law:
  

```math
  V = IR
  ```

  where $R$ is resistance (how hard it is for charge to flow).

- Combine with $P = VI$ to get two useful power forms:
  

```math
  P = VI = I(IR) = I^2R
  ```
  
  and
  

```math
  P = VI = V\left(\frac{V}{R}\right) = \frac{V^2}{R}
  ```

- These weren’t memorized; they follow directly from the meaning of voltage, current, and resistance.

- Unit (dimensional) check for $R = V^2/P$:
  - Watt = V·A, so $V^2/W = V^2/(V\cdot A) = V/A = \Omega$. Good.

---

## Step 4: Find the bulb’s resistance from its rating
At its rated condition (200 V gives 100 W), use $P = V^2/R$ to extract $R$:

```math
R = \frac{V^2}{P} = \frac{(200)^2}{100} = \frac{40000}{100} = 400\ \Omega
```

So the bulb’s hot operating resistance is 400 Ω at its rated condition.

---

## Step 5: Apply a 100 V supply and compute new power
Keep $R$ the same in our ideal model (the standard assumption in school physics unless told otherwise), and use $P = V^2/R$:

```math
P' = \frac{(100)^2}{400} = \frac{10000}{400} = 25\ \text{W}
```

Alternate path (same physics):
- Current at 100 V: $I' = V'/R = 100/400 = 0.25$ A
- Power: $P' = V'I' = 100 \times 0.25 = 25$ W

So the bulb consumes 25 W at 100 V.

---

## Step 6: Intuition and scaling
- From $P = V^2/R$ (with fixed $R$), power scales with the square of voltage.
- Halving the voltage (from 200 V to 100 V) reduces power to one quarter:
  

```math
  P' = P \left(\frac{V'}{V}\right)^2 = 100\ \text{W} \times \left(\frac{100}{200}\right)^2 = 100 \times \frac{1}{4} = 25\ \text{W}
  ```

---

## Step 7: Real-world nuance (what engineers notice)
- A tungsten filament’s resistance increases a lot when it gets hot. At 100 V it runs cooler, so its actual resistance would be lower than 400 Ω. That would make the real power slightly more than 25 W. However:
  - IGCSE-style problems assume constant resistance at the rated value.
  - Under that assumption, 25 W is the correct answer.

Answer: 25 W

---

## Multiple approaches
- Analytical (derived): Use $P=VI$ and $V=IR$ to get $P=V^2/R$; compute $R$ from rating; recompute at new $V$.
- Scaling intuition: If $R$ is constant, $P \propto V^2$. Halving $V$ quarters $P$.
- Experimental: Use a variable DC supply, set 100 V, measure current with an ammeter, compute $P = VI$. You’d likely measure a power slightly above 25 W due to temperature-dependent resistance.

---

## Conceptual follow-up questions
1. If the same bulb is connected to 300 V (don’t try this!), what power would the constant-R model predict? What would happen physically?
2. Two identical 200 V, 100 W bulbs are connected in series to 200 V. What is the power in each? In parallel?
3. If the supply is 200 V but you place a resistor in series so the bulb sees only 100 V, how much power is wasted in the resistor vs used by the bulb?
4. Why does an incandescent bulb draw a very large current the instant it’s switched on?
5. If a bulb is rated 120 V, 60 W, what is its resistance at the rated condition? What power at 240 V (idealized constant-R)?

---

## Application questions (engineering and science)
- Dimming lights: Why do old-school dimmers use voltage control (triac/phase-cut) to reduce $V$ and thus $P$ roughly with $V^2$? How do modern LED drivers differ?
- Power grids: Why is high voltage used for transmission? Link to $P=VI$ and reducing current to cut $I^2R$ losses in lines.
- Thermal design: How does filament temperature affect resistance and lifetime? Why does lower voltage greatly extend bulb life?
- Safety fuses: How does the inrush current of a cold filament affect fuse selection?

---

## Common misconceptions and reasoning traps
- “Power halves when voltage halves.” Trap: That’s true only if current stays the same. For a resistor, $P$ follows $V^2/R$; halving $V$ quarters $P$.
- “Resistance is always constant.” Metals change resistance with temperature; incandescent bulbs are very non-ohmic during warm-up.
- “Watt rating is how much the bulb always uses.” No—the watt rating is at the specified voltage. Change the voltage, and the power changes.
- “Higher wattage bulb is always brighter at any voltage.” Brightness depends on actual operating power and the bulb’s efficiency at temperature.

---

## Extension challenges
- Derive how small changes in voltage affect power using calculus: if $P \propto V^2$, then $\frac{\Delta P}{P} \approx 2 \frac{\Delta V}{V}$ for small changes.
- Model a filament with temperature-dependent resistance: assume $R(T)=R_0(1+\alpha\Delta T)$ and radiative cooling $P \approx \sigma \epsilon A T^4$; estimate how resistance and power shift at 0.5× rated voltage.
- Design a safe series resistor to run a 200 V, 100 W bulb from a 240 V supply at full power; compute resistor value and its power dissipation.
- Compare incandescent vs LED: For equal luminous output, estimate electrical power and discuss why LEDs need constant-current drivers rather than simple voltage sources.

---

## Reflective insight (the deep “why”)
Electrical power is the rate at which energy is moved. Voltage tells you “how much energy per charge,” and current tells you “how many charges per second.” Multiply them (VI), and you get energy per second. Resistance links voltage and current by how hard the material makes it for charges to move. From these simple cause-effect ideas, all the working formulas—$P=VI$, $P=I^2R$, $P=V^2/R$—fall out naturally. Once you truly see that structure, problems like this become quick sanity checks rather than memorization exercises.
