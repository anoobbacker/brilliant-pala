# Question
A body floats with $ \frac{1}{3} $ of its volume outside water and $ \frac{3}{4} $ of its volume outside another liquid.  

Then the density of the liquid is:

Options:  
A) $ \frac{3}{8} \text{ g/cm}^3 $  
B) $ \frac{8}{3} \text{ g/cm}^3 $  
C) $ \frac{9}{4} \text{ g/cm}^3 $  
D) $ \frac{4}{9} \text{ g/cm}^3 $

---
# Answer
## Visual solution (no formulas)

- Picture the object cut into 3 equal “volume slices.”
  - In water, 1 slice sticks out, 2 slices are under.
  - Floating means the 2 submerged water-slices balance the whole object (all 3 object-slices).
  - So one object-slice is as heavy as 2/3 of a water-slice → the object is “2/3 as heavy as water” (density = 2/3 of water).

- Now cut the same object into 4 equal “volume slices.”
  - In the other liquid, 3 slices stick out, only 1 slice is under.
  - That single submerged slice of liquid must hold up all 4 object-slices.
  - So one liquid-slice is as heavy as 4 object-slices → the liquid is 4 times the object.

- Chain them: liquid is 4 times the object, and the object is 2/3 of water.
  - So liquid = 4 × (2/3 of water) = 8/3 of water.
  - Since water is 1 g/cm³, the liquid is 8/3 g/cm³.

Answer: B) 8/3 g/cm³

Heavier liquid needs less of itself pushed aside to hold the same object up, so the object floats higher (more outside). Going from 2/3 under (water) to only 1/4 under (other liquid) means the other liquid is much heavier than water—specifically by a factor of 8/3.


### Creative twists
- Thinking “heavier liquid makes it sink more.” It’s the opposite: heavier liquid supports more with less displacement, so the object rides higher.
- Comparing volumes instead of weights: it’s the weight of the displaced liquid that balances the object, not just the amount of space.
- Only 1/4 submerged means the liquid must be very dense. 8/3 ≈ 2.67 is much denser than water — makes sense.
- In water it floats mostly submerged (2/3 in), so the object is lighter than water — consistent with “2/3 of water.”
- People float higher in the Dead Sea (denser water → less of you sinks).
- A block floats very high in mercury (very dense), just like the 1/4 submerged case.
- Mixing up “outside” and “submerged.” Here: 1/3 outside → 2/3 submerged; 3/4 outside → 1/4 submerged.
- Thinking the fraction outside directly gives the density. It’s the submerged fraction that tells the story.
- If an iceberg shows 10% above water, you can eyeball its density as “90% of water.” Same slicing idea solves it instantly.
- Count how many equal “slices” are under the surface. Fewer slices needed → liquid is heavier per slice. Here: 2 slices in water vs 1 slice in the other liquid leads straight to 8/3.
- Ships ride higher in salty seawater than in a river: same ship, less hull under the surface in the heavier liquid.
- Hot-air balloons: in denser cold air, they need less heated volume to lift the same basket—same “less displacement needed” idea.
- Design check: If a prototype floats deeper in a tank than in the ocean, you’ve verified the ocean water is denser—no formulas needed, just how much hull shows above the surface.

## First Principles: Why floating happens (Archimedes from scratch)
Imagine the fluid’s pressure increases with depth because fluid at lower levels supports more weight. The pressure at depth h in a fluid is proportional to the depth and the fluid’s density:
```math
P = \rho_{\text{fluid}} g h
```
- Units check: [ρ] = kg/m³, [g] = m/s², [h] = m → [P] = kg/(m·s²) = N/m² (Pascal). Good.

Now consider a submerged object. Pressure on the bottom (deeper) is higher than on the top (shallower). Adding up these pressure forces over the whole surface gives a net upward force. A simple way to “see” this: 

- Replace the submerged part of the object by an imaginary block of fluid of the same shape and size.
- That block was originally in static equilibrium, so the surrounding fluid pushed it up exactly enough to balance its weight.
- Therefore, when you swap the block for the object, the surrounding fluid still exerts the same upward force.
- That upward force must equal the weight of the displaced fluid.

This is Archimedes’ principle derived logically:
```math
F_{\text{buoyant}} = \rho_{\text{fluid}}\, g\, V_{\text{submerged}}
```
For a floating object (not sinking or rising), forces balance:
```math
\text{Upthrust} = \text{Weight of object}
\quad\Rightarrow\quad
\rho_{\text{fluid}}\, g\, V_{\text{sub}} = \rho_{\text{object}}\, g\, V_{\text{total}}
```
Cancel g and define the fraction submerged f = V_sub / V_total:
```math
f = \frac{V_{\text{sub}}}{V_{\text{total}}} = \frac{\rho_{\text{object}}}{\rho_{\text{fluid}}}
```
This is a powerful proportional statement: the denser the object compared to the fluid, the larger the fraction submerged.

---

## Apply to the two cases
1) In water:
- 1/3 outside → 2/3 submerged → f_water = 2/3.
- Take density of water as 1 g/cm³ (standard for these problems).
```math
\frac{2}{3} = \frac{\rho_{\text{object}}}{\rho_{\text{water}}} \Rightarrow \rho_{\text{object}} = \frac{2}{3} \times 1 = \frac{2}{3}\ \text{g/cm}^3
```

2) In the other liquid:
- 3/4 outside → 1/4 submerged → f_liquid = 1/4.
```math
\frac{1}{4} = \frac{\rho_{\text{object}}}{\rho_{\text{liquid}}}
\Rightarrow
\rho_{\text{liquid}} = \frac{\rho_{\text{object}}}{1/4} = \frac{2}{3} \times 4 = \frac{8}{3}\ \text{g/cm}^3
```

Answer: 8/3 g/cm³ → Option B.

---

## Quick proportional shortcut (same logic, fewer steps)
From f = ρ_object / ρ_fluid:
```math
\frac{\rho_{\text{liquid}}}{\rho_{\text{water}}}
= \frac{\rho_{\text{object}}/f_{\text{liquid}}}{\rho_{\text{object}}/f_{\text{water}}}
= \frac{f_{\text{water}}}{f_{\text{liquid}}}
= \frac{2/3}{1/4}
= \frac{8}{3}
```
Since ρ_water = 1 g/cm³, ρ_liquid = 8/3 g/cm³.

---

## Physical intuition and sanity checks
- In denser liquids, objects float higher (smaller submerged fraction) because the same weight can be supported by displacing a smaller volume: each cubic centimeter of a denser liquid “weighs” more.
- Here, the body is 2/3 submerged in water but only 1/4 submerged in the other liquid. That means the other liquid must be much denser than water. 8/3 ≈ 2.67 g/cm³ fits this intuition.

---

## Experimental perspective (how you’d measure this)
- Float the object in a liquid and mark the fluid level on the object.
- Use an overflow can: gently submerge the object to the marked level and collect displaced liquid; measure its mass (with a balance).
- The displaced mass equals the object’s mass when it floats (balance of forces). Repeat for a second liquid: less displaced volume for a denser liquid confirms the theory.
- Build a hydrometer: a calibrated float that directly reads fluid density from how deep it sinks. This problem is essentially a hydrometer reading in two fluids.

---

## Dimensional check of the key equation
```math
[\rho g V] = \left[\frac{\text{kg}}{\text{m}^3}\right]\left[\frac{\text{m}}{\text{s}^2}\right]\left[\text{m}^3\right] = \left[\frac{\text{kg}\cdot \text{m}}{\text{s}^2}\right] = [\text{N}]
```
Matches force units, so the buoyant force expression is dimensionally consistent.

---

## Final Answer
- Density of the liquid = 8/3 g/cm³
- Option B

---

## Conceptual Follow-up Questions
1) If the same body floats in a third liquid with 1/5 of its volume submerged, is that liquid denser or less dense than the previous one? By what factor compared to water?
2) What happens to the fraction submerged if we take the same object to the Moon (lower g)? Explain using the equations.
3) An iceberg has density ~0.92 g/cm³. What fraction of it is above seawater (ρ ≈ 1.03 g/cm³)? Compare to freshwater.

---

## Application Questions (Real-world links)
- Hydrometer design: How do brewers or battery technicians use floating devices to estimate sugar concentration or acid density? Derive the scale marks based on f = ρ_object / ρ_fluid.
- Submarine ballast: Explain how changing the average density of a submarine (by pumping water in/out) controls the submerged fraction and depth.
- Environmental science: Oil spills float on water. Given typical densities (oil ~0.8–0.9 g/cm³), predict the visible thickness and behavior on waves.

---

## Common Misconceptions and Traps
- Mixing “outside” with “submerged”: 1/3 outside means 2/3 submerged, not 1/3.
- Thinking “bigger objects float better”: Floating depends on density, not size. A big ship floats because its average density (hull + air) is less than water.
- Forgetting units: Always state density with units (g/cm³ or kg/m³). Here, using ρ_water = 1 g/cm³ is crucial for clean numbers.
- Believing gravity changes the fraction submerged: In the floating equation, g cancels out. So the fraction submerged is independent of g (though absolute forces change).

---

## Extension Challenges
- Suppose the object absorbs some liquid and its density increases slightly over time. Model how the fraction submerged changes with time if ρ_object(t) = ρ0 + kt.
- For an irregularly shaped object with a nonuniform density, explain how orientation affects floating depth and stability (center of buoyancy vs center of mass).
- Design a two-fluid column (e.g., oil over saltwater). Predict how deep the same object sinks and whether it will sit at the interface. Derive the condition for “interfacial floating.”

---

## Reflective Insight (the deep “why”)
Floating isn’t magic—it’s pressure bookkeeping. Fluids push more at greater depth. When those pushes are integrated over the surface of an object, the net upward force equals the weight of the fluid you had to “make space for” to put the object there. That’s why a denser fluid needs less displaced volume to balance the same weight, so objects ride higher. Remember this chain:
- Pressure grows with depth → net upward force appears.
- Net upward force equals weight of displaced fluid.
- For floating, upthrust equals weight → fraction submerged equals density ratio.
Hold onto this logic, and you can navigate any buoyancy problem with confidence.