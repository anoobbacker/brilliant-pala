# Question
 Two bodies of mass 1 kg and 4 kg possess equal momentum. The ratio of their kinetic energies is:
- A) 4 : 1
- B) 1 : 4
- C) 2 : 1
- D) 1 : 2

---
# Answer

## Big Idea
Momentum tells you “how hard something is to stop” ($p = mv$). Kinetic energy measures “how much work it can do because of motion” ($K$). If two objects have the same momentum, the lighter one must move faster. Because energy grows with the square of speed, the lighter object ends up having more kinetic energy.

We’ll derive this from first principles (not by memorizing formulas).

---

## Derivation 1: From Newton’s laws and Work (first principles)
1. Work done by a force is the force times distance moved in its direction:
   ```math
   W=\int F\,ds
   ```
2. Newton’s second law: $F = ma$. Also, $a=\frac{dv}{dt}$ and $v=\frac{ds}{dt}$.
3. Substitute into the work integral:
   ```math
   W=\int m\frac{dv}{dt}\,ds=\int m\frac{dv}{dt}\,v\,dt=\int m v\,dv=\frac{1}{2} m v^2
   ```
   This work becomes the kinetic energy:
   ```math
   K=\frac{1}{2} m v^2
   ```

Now connect kinetic energy to momentum. Momentum is $p=mv$, so $v=\frac{p}{m}$. Substitute into $K$:
```math
K=\frac{1}{2} m\left(\frac{p}{m}\right)^2=\frac{p^2}{2m}
```
Key result: For fixed momentum $p$, kinetic energy is inversely proportional to mass:
```math
K\propto \frac{1}{m}\quad \text{(if } p \text{ is the same)}
```

So for masses $m_1=1$ and $m_2=4$ with equal $p$:
```math
\frac{K_1}{K_2}=\frac{p^2/(2m_1)}{p^2/(2m_2)}=\frac{m_2}{m_1}=\frac{4}{1}=4:1
```

Answer: A) 4 : 1.

---

## Derivation 2: Directly from $dK = v\,dp$ (clean momentum-energy link)
- Work-energy idea at an instant: $dK = F\,dx$.
- Use $F=\frac{dp}{dt}$ and $dx = v\,dt$:
  ```math
  dK = \frac{dp}{dt}\,v\,dt = v\,dp
  ```
- With constant mass, $v = \frac{p}{m}$, so:
  ```math
  K = \int_0^{p} v\,dp' = \int_0^{p} \frac{p'}{m}\,dp' = \frac{p^2}{2m}
  ```
Same conclusion: at fixed $p$, $K \propto \frac{1}{m}$ → ratio 4:1.

---

## Dimensional and Proportional Reasoning (unit check)
- Momentum units: $[p]=\mathrm{kg\cdot m/s}$.
- Energy units: $[K]=\mathrm{kg\cdot m^2/s^2}$.
- The only way to build energy from $p$ and $m$ is $p^2/m$:
  ```math
  \frac{[p]^2}{[m]}=\frac{(\mathrm{kg^2\cdot m^2/s^2})}{\mathrm{kg}}=\mathrm{kg\cdot m^2/s^2}
  ```
So $K$ must be proportional to $p^2/m$; the ratio for equal $p$ depends only on the inverse of mass → 4:1.

---

## Intuitive Picture (spring test)
Imagine pushing each cart (1 kg and 4 kg) so both have the same momentum, then letting them hit the same spring:
- Spring compression depends on kinetic energy (more energy → more compression).
- The 1 kg cart must move 4× faster than the 4 kg cart to have the same momentum.
- Because energy grows with speed squared, the faster (lighter) cart stores more energy in the spring.
- Measured compression would be 2× larger for the lighter cart (since compression ∝ sqrt(energy)), consistent with 4× energy.

---

## Quick Numerical Sanity Check
Let the common momentum be $p=4\,\mathrm{kg\cdot m/s}$.
- 1 kg mass: $v=4\,\mathrm{m/s}$, $K=\frac{1}{2}\cdot 1\cdot 4^2=8\,\mathrm{J}$.
- 4 kg mass: $v=1\,\mathrm{m/s}$, $K=\frac{1}{2}\cdot 4\cdot 1^2=2\,\mathrm{J}$.
Ratio $8:2 = 4:1$.

Final answer: A) 4 : 1.

---

## 1) Conceptual Follow-up Questions
- If two bodies have equal kinetic energy, how do their momenta compare? (Hint: from $K=\frac{p^2}{2m}$, $p=\sqrt{2mK}$ → $p \propto \sqrt{m}$.)
- If the masses are $m$ and $4m$ with equal momentum, what is the speed ratio? (Answer: $v \propto 1/m$ → speeds are $4:1$.)
- If momentum doubles, how does kinetic energy change for the same mass? (Answer: quadruples, since $K \propto p^2$.)

---

## 2) Real-life Applications
- Firearm recoil: Bullet and gun have equal and opposite momentum. The gun’s mass is large, so its kinetic energy is much smaller than the bullet’s—why recoil energy feels less than bullet’s damaging energy.      
- Car safety: For equal momentum collisions, lighter vehicles can carry more kinetic energy, influencing crash energy management and crumple zone design.
- Rocket exhaust: Exhaust gases and rocket have opposite momenta; energy distribution skews toward the fast, light exhaust.

---

## 3) Common Misconceptions and Traps
- “Equal momentum means equal kinetic energy.” False: $K \propto p^2/m$, so mass matters inversely.
- Mixing up ratios: For equal $p$, $K_1/K_2 = m_2/m_1$, not $m_1/m_2$.
- Confusing “same speed” with “same momentum”: Same speed means same kinetic energy only if masses are equal; otherwise, momentum differs.

---

## 4) Extension Challenges
- Given two carts with equal kinetic energy, derive the ratio of their momenta and verify using a spring compression experiment (compression ∝ sqrt(K)).
- For a fixed kinetic energy budget, which choice gives larger momentum transfer: a heavy slow object or a light fast one? Quantify using $p=\sqrt{2mK}$.
- Explore energy-momentum in 2D: Two pucks with equal momentum magnitudes move at different angles and hit the same wall—compare their kinetic energies and impulse directions.
- Advanced thought: How would the relation change at speeds close to light? (Relativistic momentum and energy.)

---

## 5) Reflective Insight (the deep “why”)
Momentum measures motion’s “quantity” (linked to push duration needed to stop it), while kinetic energy measures motion’s “ability to do work.” For the same momentum, making an object lighter forces it to move faster; squaring this higher speed dramatically boosts energy. That’s why $K$ ends up inversely tied to mass when momentum is fixed. Understanding which quantity is held constant (momentum vs energy) is the key to predicting how mass and speed trade off in real systems.

Answer: A) 4 : 1