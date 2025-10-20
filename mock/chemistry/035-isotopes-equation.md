# Question
$^{x}_{y}\mathrm{A}$ and $^{p}_{q}\mathrm{B}$ are isotopes. Which equation among the following is correct regarding the isotopes?  
   1) $(x^2 + q^2)(y^2 + q^2) = 0$  
   2) $(x^2 + p^2)(y^2 + q^2) = 0$  
   3) $(x^2 - q^2)(y^2 - p^2) = 0$  
   4) $(x^2 - p^2)(y^2 - q^2) = 0$

---
# Answer

## Problem Sense-Making: What does “isotope” really mean?

Start with a simple picture: imagine two bottles with the same label (same brand), but one has a bit more water inside. The label tells you the identity; the amount inside tells you the weight.

- In atoms, the “label” is the number of protons. It decides the element.
- The “amount” (weight) is protons + neutrons.

Now decode the symbols:
- In the notation `^x_y A`, 
  - y = number of protons (atomic number, the identity label),
  - x = number of protons + neutrons (mass number, the weight).
- Similarly, `^p_q B` has q = protons, p = mass number.

Isotopes = same element = same number of protons. That means:
- Same atomic number: y = q.
- Usually different mass number: x ≠ p (that’s what makes them different isotopes of the same element).

---

## From first principles to the right equation

“Isotopes” only guarantees y = q. So:

```math
y = q \quad \Rightarrow \quad y^2 - q^2 = 0.
```

This alone is enough to kill any product that contains the factor (y^2 − q^2), because multiplying by zero gives zero:

```math
(x^2 - p^2)(y^2 - q^2) = (x^2 - p^2)\cdot 0 = 0.
```

Among the choices, only option 4 matches this:

4) (x^2 − p^2)(y^2 − q^2) = 0

So the correct answer is option 4.

---

## Quick check: Why the others fail

- 1) (x^2 + q^2)(y^2 + q^2) = 0
- 2) (x^2 + p^2)(y^2 + q^2) = 0

Sums of squares are never zero unless each term is zero. That would force x = q = 0 or p = q = 0, which is not what “isotopes” says.

- 3) (x^2 − q^2)(y^2 − p^2) = 0

This would require either x = q or y = p. That mixes “mass number of one” with “atomic number of the other,” which has nothing to do with isotopes.

---

## Answer

Option 4: (x^2 − p^2)(y^2 − q^2) = 0

---

## Visual/Intuitive Aid (in words)

- Think: “Same label, different fill.” 
- Label = atomic number (protons) → same for isotopes → y = q.
- Fill = mass number (protons + neutrons) → can differ → x and p can be different.

---

## 🧠 Quick Exam Tips
- Isotopes: same Z (atomic number, protons), different A (mass number).
- Notation: in ^A_Z X, A is mass number, Z is atomic number.
- If two nuclides are isotopes: Z1 = Z2 → y = q → y^2 − q^2 = 0.

---

## Conceptual Follow-ups

- What if they were isobars? Then mass numbers are equal: x = p, so x^2 − p^2 = 0.
- What if they were isotones? Same neutrons: (x − y) = (p − q).
- What stays similar for isotopes? Chemical behavior (same electrons for neutral atoms). What differs? Mass-dependent properties and nuclear stability.

---

## Application Glimpses
- Radiocarbon dating uses isotopes of carbon (C-14 vs C-12).
- Medical imaging uses isotopes like I-131.
- Nuclear power relies on isotopes like U-235 vs U-238.

---

## Misconception Clinic
- Many students think “isotopes” means “same mass.” Actually, it’s “same atomic number,” and usually different mass.
- A common mistake is confusing “isotopes” with “isobars.” Isobars have the same mass number (A), not the same atomic number (Z).
- Another trap: mixing symbols. Remember: top number (A) = mass number; bottom number (Z) = atomic number.

---

## Extension Challenges
- Derive a neutron-count condition for isotopes: neutrons = A − Z. Show that isotopes have different A but the same Z, so different neutron counts.
- Connect to periodic chemistry: Explain why chlorine’s average atomic mass (~35.5) reflects natural isotope abundance (Cl-35 and Cl-37).

---

## Interactive Practice Questions

1) If ^x_y E and ^p_q F are isobars, which equation must hold?
   - A) (x^2 − p^2) = 0
   - B) (y^2 − q^2) = 0
   - C) (x − y) = (p − q)
   - Correct: A

2) If ^x_y E and ^p_q F are isotones, which relation holds?
   - A) x = p
   - B) y = q
   - C) x − y = p − q
   - Correct: C

3) For isotopes, which of these is always true?
   - A) x = p
   - B) y = q
   - C) x − y = p + q
   - Correct: B

---

> Reflective Essence
> Nature often hides identity in what stays the same (protons) and variety in what can change (neutrons). Spot the invariant first—once you find the “label,” the rest of the math usually falls into place.