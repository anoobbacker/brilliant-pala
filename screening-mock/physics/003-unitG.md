# Question
Unit of G is
 A) Nm2kg-2 B)  Nmkg-2 C) Nkg2m-2 D) Nkg-2m-2

# Answer
## Start with an everyday picture
Imagine gravity like light from a bulb. As you move away, the light spreads over a bigger sphere — its “strength” thins out with distance squared (because the area of a sphere is 4πr^2). Gravity’s pull behaves similarly: it weakens as 1/r^2.

### Quick visual reasoning
- The pull between two objects strengthens if either object is heavier — so “two masses” are involved.
- The pull fades as they’re separated because the influence spreads over a ballooning bubble around them; when the bubble’s radius doubles, its skin area grows fourfold — a “distance effect” happening twice.
- To turn “two masses together, weakened by distance twice” into a push you can feel (a force), the constant must carry:
  - the force label N,
  - two meters on top to undo the double spread,
  - and “per kilogram” twice to undo the two masses.

So its unit is N m^2 per kg^2 → Option A) Nm2kg-2.

Answer: A

### Creative twists
- Mixing up where meters go: thinking meters belong below because “farther means weaker.” Remember: the weakening comes from distance; G needs meters above to cancel that.
- Forgetting there are two masses, not one; you need “per kilogram” twice.
- Confusing G (universal link between mass and pull) with local gravity strength near Earth; they’re different ideas and have different units.
- The same “spreading over a growing bubble” logic appears in light brightness and sound from a point source — both fade with distance twice. Any constant that converts “source × receiver” with this spread into an effect must carry two lengths on top and two “per source” factors below.


### Build the law from scratch
- More mass means stronger pull: force should be proportional to m1 and m2.
- Farther apart means weaker pull: proportional to 1/r^2.

So the force between two masses must follow:
```math
F \propto \frac{m_1 m_2}{r^2}
```
To turn “proportional to” into “equals,” we introduce a constant G that sets the overall strength:
```math
F = G \frac{m_1 m_2}{r^2}
```

### Derive the unit of G (dimensional reasoning)
Rearrange:
```math
G = \frac{F\, r^2}{m_1 m_2}
```
Now replace each symbol with its unit:
- F in newtons (N)
- r in meters (m)
- m1, m2 in kilograms (kg)

So the unit of G is:
```math
[G] = \text{N} \cdot \text{m}^2 \cdot \text{kg}^{-2}
```
Which matches option A) Nm2kg-2.

Cross-check in base units:
```math
\text{N} = \text{kg} \cdot \text{m} \cdot \text{s}^{-2}
\Rightarrow [G] = \text{m}^3 \cdot \text{kg}^{-1} \cdot \text{s}^{-2}
```
Consistent.

Answer: A) Nm2kg-2

---

## Multiple Lenses

### Analytical view
Because distance appears squared in the denominator, r^2 goes to the numerator for G’s units. Two masses in the numerator go to kg^-2.

### Experimental view
In a Cavendish torsion balance experiment, tiny twists measure the weak gravitational attraction and allow calculation of G — its unit must convert those measured quantities into newtons consistently.

### Intuitive view
- Double one mass → force doubles → G’s unit must reduce one factor of kg.
- Double distance → force quarters → G’s unit must supply m^2 to counter the r^2 in the denominator.

---

> ### 🧠 Quick Exam Tips
> - Don’t confuse G (universal constant) with g (acceleration due to gravity).
> - Units: G → N m^2 kg^-2; g → m s^-2 (or N kg^-1).
> - Dimension of G: M^-1 L^3 T^-2.

---

## Misconception Clinic
- Many students think G is unitless. But it must carry units to balance F = G m1 m2 / r^2.
- A common mistake is choosing Nm kg^-2 (missing one m). Remember: because r^2 is in the denominator, G needs m^2 to cancel it.
- Don’t mix G and g: g is about Earth’s local gravity; G is universal and appears in the law itself.

---

## Quick Practice
1) If the distance between two masses doubles, by what factor does the gravitational force change?  
2) What are the SI base units of G?  
3) By analogy, what are the units of the electrostatic constant k in Coulomb’s law?

Answers:
1) It becomes 1/4.  
2) m^3 kg^-1 s^-2.  
3) N m^2 C^-2.

---

> “Constants like G set the scale; the exponents (like r^2) reveal the geometry. Understand the shape, and the units fall into place.”