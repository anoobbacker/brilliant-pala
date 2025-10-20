## Question
The sum of smallest whole number co-efficients $x, y$ and $z$ in the balanced equation $\mathrm{xH}_{2(\mathrm{~g})}+\mathrm{yO}_{2(\mathrm{~g})} \longrightarrow \mathrm{ZH}_2 \mathrm{O}_{(\ell)}$ is .......

## Understanding the problem from first principles

Think of molecules like LEGO pieces: when you build something new, you don’t make pieces vanish or appear from nowhere—you just rearrange them. Chemistry is similar. When hydrogen gas and oxygen gas react to form liquid water, the atoms are simply rearranged. No atom is lost or created. This is the law of conservation of mass, supported by countless experiments (Lavoisier’s sealed-flask experiments showed total mass stays constant during reactions).

So, to balance a chemical equation, we are doing careful “atom bookkeeping.” The coefficients (x, y, z) tell us how many molecules of each substance take part so that the number of each type of atom is the same before and after.

We’re asked to find the smallest whole numbers x, y, z in:
```math
x\,\mathrm{H}_{2(g)} + y\,\mathrm{O}_{2(g)} \longrightarrow z\,\mathrm{H_2O}_{(\ell)}
```

Key facts (built from basic structure):
- A molecule of H2 has 2 hydrogen atoms.
- A molecule of O2 has 2 oxygen atoms.
- A molecule of H2O has 2 hydrogens and 1 oxygen.
- Coefficients (x, y, z) multiply the numbers of molecules, i.e., they scale the atom counts.

## Set up conservation equations

Let’s count hydrogen and oxygen atoms on both sides.

- Hydrogen atoms:
  Left side has 2 per H2, and there are x of them → total hydrogen = 2x.
  Right side has 2 per H2O, and there are z of them → total hydrogen = 2z.
  Conservation demands:
  ```math
  2x = 2z \quad \Rightarrow \quad x = z
  ```

- Oxygen atoms:
  Left side has 2 per O2, and there are y of them → total oxygen = 2y.
  Right side has 1 per H2O, and there are z of them → total oxygen = z.
  Conservation demands:
  ```math
  2y = z
  ```

Now solve the pair:
- From 2y = z, we see z must be even. Let z = 2k.
- Then y = k.
- From x = z, we get x = 2k.

To get the smallest whole numbers, choose the smallest positive integer k = 1:
```math
x = 2,\quad y = 1,\quad z = 2
```

So the balanced equation is:
```math
2\,\mathrm{H}_{2(g)} + 1\,\mathrm{O}_{2(g)} \longrightarrow 2\,\mathrm{H_2O}_{(\ell)}
```

The sum x + y + z = 2 + 1 + 2 = 5.

## Why these are the “smallest” coefficients

Our equations gave x = 2k, y = k, z = 2k. Any k = 2, 3, … would simply scale all coefficients up, describing the same reaction in a larger quantity. Chemistry convention uses the least whole-number ratio—so k = 1 is minimal.

## Cross-checks (different lenses for the same truth)

- Mass check (experimental thinking):
  - Left: 2 mol H2 (2×2 g = 4 g) + 1 mol O2 (32 g) = 36 g
  - Right: 2 mol H2O (2×18 g = 36 g)
  Mass is conserved → consistent.

- Volume ratio check (gas reasoning at same T and P):
  By Avogadro’s law, equal moles of gases occupy equal volumes. Coefficients become volume ratios:
  2 volumes H2 + 1 volume O2 → 2 volumes steam. Matches the coefficients.

- Fraction method (alternate balancing strategy):
  Start with:
  ```math
  \mathrm{H_2} + \tfrac{1}{2}\mathrm{O_2} \to \mathrm{H_2O}
  ```
  Multiply entire equation by 2 to clear the fraction:
  ```math
  2\mathrm{H_2} + 1\mathrm{O_2} \to 2\mathrm{H_2O}
  ```

## Final answer
Sum of smallest whole-number coefficients x + y + z = 5.

---

## 1) Conceptual follow-up questions

- If you started with 3 molecules of O2, how many H2 molecules are needed for complete reaction, and how many H2O form?
- Why must z be even in this reaction?
- Can you balance: N2 + H2 → NH3 by the same method? What are the smallest coefficients and why?
- If you mistakenly wrote H + O2 → H2O, what goes wrong in terms of atom counting and the nature of real molecules?

## 2) Application questions

- Rocket engines often burn liquid hydrogen with liquid oxygen. Why is the mixture ratio near 2:1 by molecules (or 1:8 by mass)? How does exact balancing affect efficiency and temperature?
- In a hydrogen fuel cell, why is the stoichiometric (balanced) ratio critical for maximum electrical output and minimal leftover reactants?
- In firefighting, why does removing oxygen stop combustion? Connect to the idea of required stoichiometric oxygen.

## 3) Common misconceptions and reasoning traps

- Forgetting that oxygen is O2, not O. This doubles the oxygen count on the left.
- Changing subscripts instead of coefficients (e.g., writing H2O2). Subscripts change the substance; coefficients change the count of molecules.
- Thinking fractional coefficients are “wrong.” They’re fine intermediate steps; just clear fractions at the end.
- Ignoring the “smallest” condition. 4:2:4 is balanced but not minimal; reduce to 2:1:2.

## 4) Extension challenges

- Balance and find sum of coefficients:
  - C3H8 + O2 → CO2 + H2O
  - Fe + O2 → Fe2O3
- Given 10 L of O2 at the same T and P, how many liters of H2 are needed to completely react? How many liters of steam form?
- Limiting reagent twist: If you have 5 mol H2 and 3 mol O2, which runs out first, and how much water forms?

## 5) Reflective insight

At its core, balancing equations is solving a set of simple conservation laws—linear equations that ensure each element’s atoms are the same before and after. The “coefficients” are just the smallest whole-number solution to these conservation constraints. See every balancing problem as atom bookkeeping guided by conservation, not memorization. Once you set up the element-by-element equalities, the correct coefficients reveal themselves.