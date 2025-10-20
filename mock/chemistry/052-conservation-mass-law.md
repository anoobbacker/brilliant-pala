## Question
Law of conservation of mass is valid for which of the following?
i) Reactions involving oxidation
ii) Nuclear reactions
iii) Endothermic reactions

**Options:**

1. i and iii
2. i and ii
3. ii and iii
4. ii only

## Answer: Option 1 — i and iii

- i) Oxidation reactions: Yes (valid)
- ii) Nuclear reactions: No (mass alone is not conserved)
- iii) Endothermic reactions: Yes (valid for ordinary chemical reactions)

---

## Build-up from first principles

### 1) Everyday intuition: Lego blocks and rearrangements
- If you make a car out of Lego bricks and then rebuild it into a house, the number of bricks stays the same. You didn’t create or destroy bricks—you rearranged them.
- Chemical reactions are like that: atoms are the “bricks.” In ordinary chemical reactions, atoms rearrange into new groupings, but no atom disappears or pops into existence.

### 2) What “conservation of mass” really means in chemistry
- Mass is “how much stuff” there is. If the “stuff” (atoms) isn’t created or destroyed, and each atom has a fixed mass, then the total mass shouldn’t change just because we reshuffled the atoms.
- Let’s express that logic precisely. Suppose we count atoms of each element a (H, O, Fe, etc.). If the number of atoms of each element is the same before and after the reaction (which is what a correctly balanced equation enforces), then:

```math
\text{Total mass} = \sum_{\text{elements } a} (N_a \times m_a)
```

- Here, $N_a$ is the number of atoms of element $a$, and $m_a$ is the mass of one atom of $a$.
- In ordinary chemical reactions, $N_a$ for each element stays the same (atoms are only rearranged), so the total mass stays the same.

### 3) Experimental backbone: sealing the system
- Lavoisier showed this by sealing reactants in a closed container, letting them react, and weighing before and after—the mass was the same.
- Important: the system must be closed. If oxygen from the air joins in (like rusting iron in open air), the iron’s mass appears to increase, but that’s just because you didn’t include the oxygen’s mass at the start. Include all reactants, and the mass balances.

---

## Now, analyze each case in the question

### i) Oxidation reactions
- Oxidation means “combining with oxygen” (e.g., iron rusting, magnesium burning).
- This is a chemical rearrangement: the atoms of Fe and O are regrouped into iron oxide. No atoms are created or destroyed.
- In a closed system:
  - Before: mass(Fe) + mass(O2)
  - After: mass(iron oxide)
  - Because the same atoms are present, total mass is conserved.
- So, conservation of mass holds for oxidation reactions.

### ii) Nuclear reactions
- Nuclear reactions change the nucleus itself (protons and neutrons rearrange; sometimes a neutron turns into a proton or vice versa), and significant energy is released or absorbed due to changes in nuclear binding energy.
- Here, “mass alone” is not conserved. Instead, what’s conserved is mass-energy as a combined quantity.
- Why? Energy itself has inertia—energy “weighs.” The precise link is:

```math
E = mc^2
```

- Dimensional check: energy (J) = mass (kg) × (m/s)^2; so $m = E/c^2$ has units of kg—consistent.
- In nuclear reactions, the energy released is large enough that the corresponding “mass change” $E/c^2$ is measurable. The sum of the masses of products can be less than that of the reactants; the “missing mass” appears as released energy.
- Therefore, the simple law “mass is conserved” does not hold in nuclear reactions; only mass-energy is conserved.

### iii) Endothermic reactions
- Endothermic = absorbs energy (heat). But it’s still an ordinary chemical reaction—atoms just rearrange differently and the products have higher chemical potential energy.
- From the “atoms as Lego” logic, the count of each type of atom is unchanged, so the chemical mass is conserved to extremely high precision.
- Subtlety (good to know): If we include Einstein’s insight, the absorbed energy slightly increases the system’s mass by $m = E/c^2$. For a typical chemical energy like 100 kJ:

```math
m = \frac{E}{c^2} \approx \frac{10^5 \text{ J}}{9\times 10^{16} \text{ m}^2/\text{s}^2} \approx 1.1\times 10^{-12} \text{ kg}
```

- That’s about a nanogram—far too small to matter in school-level chemistry. So, for ordinary chemical reactions (endothermic or exothermic), we treat mass as conserved.

---

## Conclusion
- Valid for oxidation (i) and endothermic reactions (iii).
- Not valid for nuclear reactions (ii) if you track mass alone; only mass-energy is conserved there.
- Correct option: 1) i and iii.

---

## Multiple approaches to understand this

### Analytical (theoretical) approach
- Chemical reactions conserve the count of each atom type; masses add. Therefore, total mass remains the same.

```math
\sum_a N_a m_a \text{ (before)} = \sum_a N_a m_a \text{ (after)}
```

### Experimental approach
- Perform reactions in a sealed container and weigh before and after. The measured mass stays constant for chemical reactions, confirming the theory.

---

## Conceptual follow-up questions
1. If you burn magnesium in open air and weigh only the strip before and the ash after, why does the mass increase? What changes if you include the air in the “system”?
2. In an exothermic chemical reaction that releases 200 kJ of heat, what is the approximate decrease in the system’s mass due to $E=mc^2$? Would a lab balance detect it?
3. Why do we need the idea of a “closed system” when stating conservation laws?

---

## Application questions
1. How do engineers ensure mass balance in industrial reactors where gases flow in and out? What measurements are critical?
2. In battery charging (endothermic overall at the cell level), the battery stores energy. Does its mass change in principle? By how much for 100 kJ stored?
3. Why is mass change in nuclear reactors and stars non-negligible, and how does that connect to the huge energy outputs observed?

---

## Common misconceptions and reasoning traps
- Mistake: “Rusting increases mass, so mass isn’t conserved.”  
  Fix: You ignored the oxygen mass from air. Consider the entire closed system.
- Mistake: “Endothermic reactions break conservation of mass because energy is absorbed.”  
  Fix: Energy absorption doesn’t create or destroy atoms. In chemistry, mass is effectively conserved; the $E/c^2$ mass change is far below measurement limits.
- Mistake: “Mass is always conserved.”  
  Fix: In nuclear reactions, mass alone is not conserved—mass-energy is. The mass defect corresponds to released/absorbed energy.

---

## Extension challenges
1. Estimate the mass difference when a 5 kWh battery is fully charged, using $E=mc^2$. Is this detectable with a microbalance?
2. Show with sample numbers that the mass of a helium nucleus is less than the sum of masses of 2 protons and 2 neutrons, and relate the difference to binding energy.
3. Design a classroom experiment to verify mass conservation for a reaction producing a gas (e.g., vinegar + baking soda) using a sealed setup.

---

## Reflective insight: the deep “why”
At the chemical scale, reactions are rearrangements of enduring building blocks—atoms. Because the number of each type of atom stays constant, and mass is additive over these atoms, the total mass doesn’t change. At the nuclear scale, the “bricks” themselves can change and their binding energy matters; energy and mass are two faces of the same conserved quantity. So, “conservation of mass” is an excellent approximation for chemistry, and “conservation of mass-energy” is the deeper principle that unifies both chemistry and nuclear physics.