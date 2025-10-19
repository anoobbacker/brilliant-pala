# Question
A bullet of mass 10g moving with velocity 100m/s strikes a mud wall and comes to rest after penetrating through 5m. The force offered by the mud wall is

A) 10N B)  20N C)  25N D)  40N

# Answer

Find the (average) force the mud wall exerts on a 10 g bullet moving at 100 m/s that comes to rest after penetrating 5 m.

---

## Given, with units made consistent
- Mass: $m = 10\ \text{g} = 0.01\ \text{kg}$
- Initial speed: $u = 100\ \text{m/s}$
- Final speed: $v = 0$
- Penetration distance: $s = 5\ \text{m}$

We’ll assume the force from the mud is roughly constant over the 5 m, or we’re being asked for the average force. Gravity is negligible over the very short stopping time compared to the much larger resistive force.

---

## Intuition first: Energy “budget” picture
- The bullet starts with kinetic energy. To stop, that energy must be “spent” doing work against the mud.
- Work done by the mud force over distance $s$ equals the loss of kinetic energy.
- Bigger starting speed or mass → more energy to dump → larger force needed if stopping distance is fixed.
- Bigger stopping distance → more room to spread out the energy dump → smaller force.

This is exactly how airbags and crumple zones work: increase stopping distance/time to reduce force.

---

## Approach 1 (from first principles): Work–energy via Newton’s law
Start with Newton’s second law and relate acceleration to change in speed over distance.

1) Newton’s second law:
$$
F = m a
$$

2) Chain rule to connect acceleration to position:
$$
a = \frac{dv}{dt} = \frac{dv}{dx}\frac{dx}{dt} = v\frac{dv}{dx}
$$

3) Multiply both sides of $F = m a$ by $dx$:
$$
F\,dx = m\,v\,dv
$$

4) Integrate from the entry point to the stop point:
- Position: $x=0$ to $x=s$
- Speed: $v=u$ down to $v=0$
$$
\int_0^s F\,dx = \int_u^0 m\,v\,dv
$$

If $F$ is approximately constant (or we interpret the left as average force times distance), then:
$$
F\,s = m\left[\frac{v^2}{2}\right]_u^0 = -\frac{1}{2}m u^2
$$
The negative sign indicates the force opposes motion; its magnitude is:
$$
F = \frac{\frac{1}{2} m u^2}{s}
$$

5) Plug in numbers:
$$
F = \frac{\tfrac{1}{2}\cdot 0.01 \cdot (100)^2}{5}
  = \frac{0.5 \cdot 0.01 \cdot 10000}{5}
  = \frac{50}{5}
  = 10\ \text{N}
$$

Answer: 10 N (Option A)

---

## Check by dimensional analysis
Formula used: $F = \frac{\tfrac{1}{2} m u^2}{s}$

Units:
- $m u^2$ → $(\text{kg})(\text{m}^2/\text{s}^2)$ = Joule (J)
- Divide by $s$ (m): J/m = $(\text{kg}\cdot\text{m}^2/\text{s}^2)/\text{m} = \text{kg}\cdot\text{m}/\text{s}^2 = \text{N}$
Units check out.

---

## Approach 2 (equally first-principles): Kinematics + Newton’s law
If the resistive force is constant, the deceleration $a$ is constant. Then the motion over distance $s$ obeys:
$$
v^2 = u^2 + 2 a s
$$
Derivation sketch: use $a = v\,dv/dx$ and integrate with $a$ constant.

Since $v=0$ at the end:
$$
0 = u^2 + 2 a s \Rightarrow a = -\frac{u^2}{2s}
$$
Then the force magnitude is:
$$
F = m|a| = m\frac{u^2}{2s} = \frac{\tfrac{1}{2} m u^2}{s} = 10\ \text{N}
$$
Same result.

---

## Reality check
- The bullet’s weight is $mg \approx 0.01 \times 9.8 \approx 0.098\ \text{N}$, much smaller than 10 N. So ignoring gravity during the brief stop was reasonable.
- Proportional reasoning: If the mud were twice as thick (10 m), the average force would halve to 5 N. If the speed doubled, the force would quadruple.

---

## Final Answer
- Force offered by the mud wall: 10 N
- Correct option: A

---

## Conceptual follow-up questions
1) If the penetration distance were 2.5 m instead of 5 m, what would the force be? Why?
2) If the mass were doubled but speed the same, how would the force change?
3) If the bullet had the same kinetic energy but took twice the distance to stop, what happens to the force?
4) What if the resistive force isn’t constant? How would you interpret the 10 N then?

---

## Application questions
- Airbags and crumple zones: How does increasing stopping distance in a car crash reduce force on passengers?
- Sports helmets: How do foam layers manage energy to lower forces on the head?
- Material testing: Given penetration depth and impact speed, how can engineers estimate average resistive stress of soils or soft materials?

---

## Common misconceptions and reasoning traps
- Confusing force with energy: The mud doesn’t “absorb 50 J” and “exert 50 N” interchangeably. Work (energy transfer) depends on both force and distance: $W = F s$.
- Forgetting unit consistency: Not converting 10 g to 0.01 kg leads to a 100× error.
- Overemphasizing gravity: In high-speed impacts with short times/distances, impact forces dwarf weight.
- Assuming time matters directly here: You don’t need time to compute average force if you have energy and distance.

---

## Extension challenges
1) Variable force model: Suppose resistive force scales with speed, $F = k v$. Using $a = v\,dv/dx$, solve for penetration distance and compare with the constant-force case.
2) Layered target: Bullet passes 1 m of water, then 4 m of mud. If water offers twice the average force of mud, find the total work split and discuss resulting distances if the order is reversed.
3) Energy vs impulse: If the bullet stops in time $t$, show the average force also equals change in momentum divided by $t$, and connect that to the energy-over-distance result.

---

## Reflective insight
The essence: Stopping an object is about converting kinetic energy into other forms by doing work over a distance. For a given energy, the force you feel is inversely tied to how much “space” you give the system to slow down. That’s why spreading out the stopping over more distance (or time) is the universal strategy to reduce forces—whether in airbags, landing cushions, or shock absorbers.