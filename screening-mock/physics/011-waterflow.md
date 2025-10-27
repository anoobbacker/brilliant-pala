# Question
The water flows through three holes made at different heights of a vessel. The pressure is maximum at:

Options:  
A) the topmost hole  
B) the middle hole  
C) the lowermost hole  
D) is same at all holes

---
# Answer
## Intuitive solution
- Picture the water above each hole as a stack of heavy blocks pressing on that spot.
- The deeper the hole, the taller the stack of water above it, so the stronger the push.
- Bottom hole has the most water above → strongest push → highest pressure.

Answer: C) the lowermost hole

## Creative twists
- Thinking “same water, same pressure everywhere”: not true—deeper layers carry the weight of all the water above, so they push harder on the walls.
- Top hole: shortest water stack above → weakest push.
- Middle: more than top, less than bottom.
- “Same at all holes” would only be true if all were at the same depth (they’re not).
- Which hole is hardest to plug with your finger? The bottom one.
- When you dive, your ears feel more squeeze deeper down.
- Dams are thicker at the bottom because the push there is stronger.
- Don’t confuse “which jet lands farthest” with “which has most pressure.” The middle hole can sometimes shoot farthest because it has a good mix of push and fall time, but the bottom still has the greatest pressure.
- “All holes open to air so pressure is the same” is wrong: inside the water, the deeper spot feels more squeeze before meeting the air.
- Air works the same way: more air above you at sea level than on a mountain → stronger push at lower altitude.
- In a pool, a small cut in a liner near the bottom leaks harder than one near the top.
- Mental picture: three doors holding back a stack of water. The lowest door supports the tallest stack, so it’s pushed the hardest. Hence, pressure is greatest at the lowest hole.

## Why this is true — derive from first principles

### 1) Build the idea from a force balance (no memorized formulas)
- Imagine the water is almost at rest inside the large tank (the holes are small). Take a thin horizontal “slice” of water of thickness $dz$ at depth $z$ (measured upward), with area $A$.
- Forces acting:
  - Upward force from pressure on the bottom face: $P(z)\,A$
  - Downward force from pressure on the top face: $P(z+dz)\,A$
  - Downward weight of the slice: $\rho g A\,dz$ (density $\rho$, gravity $g$)

For static equilibrium (no acceleration):
```math
\text{Upward} - \text{Downward} - \text{Weight} = 0 \\
P(z)A - P(z+dz)A - \rho g A\,dz = 0
```
Divide by $A$ and rearrange:
```math
P(z) - P(z+dz) = \rho g\,dz \quad \Rightarrow \quad \frac{dP}{dz} = -\rho g
```

Integrate from the free surface (where $P = P_\text{atm}$) down a depth $h$:
```math
P(h) = P_\text{atm} + \rho g h
```

- This is hydrostatic pressure: it depends only on depth below the free surface, not on the shape of the container.
- Therefore, the deeper the hole, the higher the pressure inside the tank at that hole. The lowermost hole is deepest → maximum pressure.

Dimensional check: $[\rho g h] = (kg/m^3)(m/s^2)(m) = kg/(m\,s^2) = N/m^2 = Pa$.

---

### 2) Visual and intuitive model
- Think of the water above as a tall stack. More stack above means more weight pressing down → more pressure at the bottom.
- Real-world analogy: Dams are thicker at the bottom because water pressure increases with depth.

---

### 3) But what about the water coming out?
Here’s a subtle point that often confuses people:
- Just outside the hole, the water jet is exposed to air, so its pressure is atmospheric at every hole.
- The reason the lower jet shoots out faster is not because its exit pressure is higher; it’s because more of the gravitational potential energy (from greater depth) is converted into kinetic energy.

Use Bernoulli between the free surface and just outside the hole:
```math
P_\text{atm} + 0 + \rho g z_\text{surface} = P_\text{atm} + \tfrac{1}{2}\rho v^2 + \rho g z_\text{hole}
```
Simplify:
```math
\tfrac{1}{2}\rho v^2 = \rho g (z_\text{surface} - z_\text{hole}) = \rho g h
\quad \Rightarrow \quad v = \sqrt{2gh}
```
- Deeper hole → larger $h$ → larger $v$.
- Exit pressure (in the free jet) is the same (atmospheric) for all holes, but exit speed differs.

So:
- Inside the tank at the hole: pressure increases with depth → maximum at the lowermost hole.
- In the jet outside: pressure equals atmospheric → same at all holes.

The question typically refers to the pressure at the hole inside the vessel, hence option C.

---

## Multiple ways to see it

### Analytical (Statics)
- Derived $P = P_\text{atm} + \rho g h$ from force balance on a fluid slice.

Answer: C) The lowermost hole

### Energy/Bernoulli
- Converts hydrostatic head $\rho g h$ into kinetic energy: $v = \sqrt{2gh}$.
- Explains why deeper holes give faster jets, even though jet pressure is atmospheric.

### Experimental (Try it!)
- Poke three holes at different heights in a plastic bottle.
- Fill with water. Observe:
  - Lower hole jet shoots farther (higher speed).
  - If you momentarily cap the hole exit and stick a small pressure sensor or your finger, you feel more push at the lower hole (more pressure).

---

## Real-world connections
- Dams and submarine hulls must withstand higher pressure at depth.
- Deep-sea creatures and submersibles experience intense hydrostatic pressure.
- Blood pressure in tall animals (like giraffes) is higher at their feet than at their heart due to hydrostatic effects.

---

## Final takeaway for this question
- Pressure inside an open tank at a given depth is $P_\text{atm} + \rho g h$.
- Greater depth → greater pressure.
- Therefore, maximum pressure is at the lowermost hole.

Answer: C) The lowermost hole

---

## Conceptual follow-up questions
1. If the tank were sealed and pressurized at the top to $P_\text{top} > P_\text{atm}$, what would be the pressure at a hole at depth $h$? What happens to the jet speed?
2. If the liquid were oil with density $\rho_\text{oil} < \rho_\text{water}$, how would the pressure at a given depth compare to water?
3. Two differently shaped containers have holes at the same depth from the free surface. Do they have the same pressure at those holes? Why?
4. If the outside of the hole opened into a chamber at pressure $P_\text{ext}$ (not atmospheric), how would the jet speed change?

---

## Application questions
- Why are observation windows in deep-sea submersibles smaller and thicker than in shallow vehicles?
- How do engineers decide the thickness gradient of a dam from top to bottom?
- In drip irrigation, how do designers ensure uniform flow rate along pipes laid over uneven terrain, where hydrostatic head varies?

---

## Common misconceptions and traps
- “Faster flow means higher pressure.” Actually, along a streamline in steady flow, higher speed corresponds to lower static pressure (Bernoulli). Jets speed up by converting pressure/height energy into kinetic energy.
- “All holes have the same pressure because they’re open to air.” Inside the tank, pressures differ by depth; the jet outside is at atmospheric pressure.
- “Container shape changes pressure at depth.” Hydrostatic pressure depends only on depth and fluid density (and any gas pressure above), not on container shape.

How to avoid them:
- Always specify where the pressure is being measured (inside the fluid vs in the free jet).
- Use the relation $P = P_\text{top} + \rho g h$ for hydrostatics inside, and Bernoulli to connect height to jet speed.

---

## Extension challenges
1. Derive the horizontal range of the jet from a hole at height $y$ above the ground when the water level is at height $H$ above the ground. For which hole height is the range maximal?
2. If the tank drains and the water level drops with time, derive how the jet speed changes with time (use Torricelli’s law and volume continuity).
3. Consider a tank with two immiscible fluids (oil on top of water). What is the pressure at a hole at depth $h$ below the oil-water interface?
4. Explore non-uniform gravity (e.g., in a centrifuge). How does “effective gravity” change the hydrostatic pressure distribution?

---

## Reflective insight — the deep “why”
Hydrostatic pressure is simply the weight of fluid above you distributed over area. More depth means more weight above, giving more push. When water escapes, that stored “height energy” (pressure head) transforms into motion (kinetic energy). Keep track of where you measure pressure (inside vs in the free jet) and whether energy is tied up as height/pressure or has been converted into speed. This lens will guide you through any fluid problem, from leaking bottles to ocean engineering.