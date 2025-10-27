# Question
A body of mass 5 kg is thrown vertically up with a kinetic energy of 490 J . The height at which KE of the body becomes half of original value is

**Options:**

1. 2.5 m
2. 10 m
3. 7.5 m
4. 5 m

# Answer
## Quick visual solution
- Picture energy moving: at launch it’s all “motion energy.” As the body rises, that energy pours into “height energy.” Gravity pulls with nearly the same strength the whole way up, so height gained grows in straight step with energy spent.
- “Half the motion energy left” means “half the starting energy has been spent lifting.” So you must be halfway up the total rise the object will ever reach.
- The full 490 units of motion energy would carry a 5 kg mass to about 10 meters at the top. Halfway up is therefore 5 meters.

Answer: 5 m (Option 4)

## Creative twists
- Thinking “half the energy” means “half the speed” or “half the time.” Energy drains into height steadily with height, not with time or speed.
- Forgetting gravity’s pull is essentially constant here, so height gained is directly in step with energy spent.
- Trying to compute speeds; you only need the idea that halfway energy loss means halfway in height.
- Roller coaster: from the top, halfway down in height means half the potential energy has turned into motion energy.
- Car coasting uphill: when it has lost half its initial “oomph,” it has climbed halfway to the point where it would just stop.
- Engineering: An elevator lifting a fixed load—energy used is directly proportional to the floors climbed; half the energy buys half the floors.

## Solve it from first principles

### 1) Physical picture (everyday intuition)
- Throw a ball straight up: it slows down as it climbs. Why? Gravity pulls downward, doing negative work on the ball.
- “Where did the motion go?” It’s converted into “height energy” (gravitational potential). Think of gravity as charging a fixed “energy toll” per meter climbed.

We’ll quantify that toll and then ask: at what height has exactly half of the original kinetic energy been paid?

Assume no air resistance so energy isn’t lost as heat.

### 2) Reconstruct the energy relations (no memorized shortcuts)

#### Work changes kinetic energy (Work–Energy idea)
- A constant force $F$ acting over a displacement $s$ does work $W = F s$.
- Work is the mechanism that changes motion. If you push an object and it speeds up, your work increased its kinetic energy (KE).

We can show why KE depends on $v^2$:
- Start from Newton: $F = m a$ with constant $F$.
- If the object starts from rest and moves a distance $s$ to reach speed $v$, then
  - Use the chain between acceleration and distance: $a = \frac{dv}{dt}$ and $v = \frac{ds}{dt}$, so

```math
    a = \frac{dv}{dt} = \frac{dv}{ds}\frac{ds}{dt} = v \frac{dv}{ds}.
    ```
  - Plug into $F = m a$:

```math
    F = m\, v \frac{dv}{ds} \quad \Rightarrow \quad F\, ds = m v\, dv.
    ```
  - Integrate from start (rest, $v=0$) to some speed $v$ over distance $0$ to $s$:

```math
    \int_0^s F\, ds = \int_0^v m v\, dv
    \Rightarrow F s = \frac{1}{2} m v^2.
    ```
- The left side is the work done by the net force. So the change in kinetic energy is

```math
  \Delta K = \frac{1}{2} m v^2.
  ```
That’s why $K = \tfrac{1}{2} m v^2$.

#### Gravitational potential “toll” near Earth
- Near Earth’s surface, gravity is approximately constant: weight $= mg$ downward.
- If you slowly lift a mass $m$ by height $h$ at constant speed, your upward force is $mg$, so the work you do is $W_{\text{you}} = mg\,h$.
- Gravity does negative work $W_g = -mg\,h$ over the same rise.
- This energy $mg h$ is stored as gravitational potential energy difference:

```math
  \Delta U = +mg h.
  ```
Dimensional check: $mg h$ has units N·m = J (joules), as energy should.

#### Energy bookkeeping when thrown up
- When the ball rises by height $h$, gravity removes kinetic energy equal to $mg h$:

```math
  K(h) = K(0) - mg h.
  ```

### 3) Apply to the problem
Given:
- Mass $m = 5$ kg
- Initial KE $K(0) = 490$ J
- We want the height $h$ where KE becomes half: $K(h) = 245$ J

Use the energy balance:
```math
K(h) = K(0) - mg h
\Rightarrow 245 = 490 - (5)(9.8)\, h.
```
Solve:
```math
(5)(9.8) h = 245
\Rightarrow 49 h = 245
\Rightarrow h = \frac{245}{49} = 5\ \text{m}.
```

- Units: J/N = m, consistent.

Answer: 5 m → Option 4.

### 4) Quick alternative (derived kinematics)
- From the earlier derivation, $K \propto v^2$, so “half KE” means $v^2$ halves.
- For constant downward acceleration $-g$, one can derive

```math
  v^2 = u^2 + 2 a s
  ```
  by the same chain-rule step: $a = v\, dv/ds$. With $a = -g$ and upward displacement $h$:

```math
  v^2 = u^2 - 2 g h.
  ```
- Half KE ⇒ $v^2 = \tfrac{1}{2} u^2$. Then

```math
  \tfrac{1}{2} u^2 = u^2 - 2 g h \Rightarrow h = \frac{u^2}{4 g}.
  ```
- Find $u^2$ from initial KE: $490 = \tfrac{1}{2} m u^2 \Rightarrow u^2 = \frac{2 \cdot 490}{5} = 196$.
- Hence

```math
  h = \frac{196}{4 \cdot 9.8} = \frac{196}{39.2} = 5\ \text{m}.
  ```

### 5) Sanity check
- The maximum height occurs when all KE converts to PE:

```math
  h_{\max} = \frac{K(0)}{mg} = \frac{490}{49} = 10\ \text{m}.
  ```
- Half KE lost corresponds to half of this height: 5 m. This matches our result.

---

## Final Answer
5 m

---

## Conceptual follow-up questions
1. If the mass were 10 kg with the same initial KE of 490 J, would the height for half-KE be the same? Why? (Hint: both KE loss and the gravitational “toll” depend on $m$.)
2. On the Moon ($g \approx 1.6$ m/s²), how would the height for half-KE change? Predict before calculating.
3. If instead the speed halves (not KE), at what height would that happen? Compare to the half-KE height and explain using $K \propto v^2$.
4. If air resistance is significant, would the half-KE height be greater or smaller than 5 m? Why?
5. Generalize: if we want the KE to drop to a fraction $k$ of its original value ($0<k<1$), show that

```math
   h = (1 - k)\,\frac{K(0)}{mg}.
   ```

## Application questions
- Roller coasters: How do engineers use the idea “gravity charges a fixed energy toll per meter” to set the minimum height of the first hill?
- Regenerative braking: In electric cars, how does converting KE into stored energy parallel converting KE into gravitational potential energy when going uphill?
- Hydroelectric dams: Why does the energy available per kilogram of water depend linearly on the drop height ($mgh$)?

## Common misconceptions and reasoning traps
- “Half speed means half energy.” False: energy scales with $v^2$. Half speed gives one-quarter KE.
- “Potential energy is an absolute number.” It’s only differences that matter; we chose zero at ground level implicitly.
- “Mass cancels everywhere.” Not always. Here, the height depends on $K(0)/(mg)$. If $K(0)$ is fixed (not speed), mass matters; if initial speed is fixed, mass cancels.
- “Gravity always does positive work upwards.” Gravity does negative work when the object moves against it; sign matters in energy bookkeeping.

## Extension challenges
- Variable gravity: Derive the height for half-KE if $g$ changed with altitude (e.g., in a tall shaft where $g(h)$ is slightly smaller at the top). How would you approximate the effect with calculus?
- Sloped motion: A block slides up a frictionless incline at angle $\theta$. Show the distance along the slope to half-KE depends only on $K(0)$, $m$, $g$, and $\theta$ through $h = (1-k)\,K(0)/(mg)$ and $s = h/\sin\theta$.
- Experimental design: Using a motion sensor, measure how KE decreases with height for a tossed ball and test $K(h) = K(0) - mgh$.

## Reflective insight
The essence: Forces transfer energy by doing work, and gravity near Earth charges a constant energy “toll” per meter: $mg$ joules per meter. Because KE is proportional to $v^2$, energy accounting becomes a simple, powerful tool: changes in height directly map to changes in KE. Once you see “force × distance” as the bridge between motion and stored energy, a huge class of problems becomes intuitive—no need to memorize; just track who does work and where the energy goes.
