## Question

Volume of the sphere of diameter 'd' is

**Options:**

1. $\frac{4}{3} \pi d^3$
2. $\frac{1}{3} \pi d^3$
3. $\frac{1}{4} \pi d^3$
4. $\frac{1}{6} \pi d^3$

## Big idea: Build volume by stacking slices
Think of volume like filling a shape with ultra-thin “pancake” slices and adding their areas up. If two solids have equal cross-sectional area at every height, they must have the same volume (Cavalieri’s principle). This “stacking” idea will guide everything.

We’ll:
1) Reconstruct volumes of cylinder and cone by slicing.
2) Compare a sphere to a cylinder and a “double cone” using slice-by-slice equality.
3) Convert the final result from radius r to diameter d.

---

## Step 1: Area of a circle (quick reconstruction)
Cut a circle into many equal pizza slices and rearrange them alternately (tips up/down). As the slices get thinner, the shape approaches a rectangle:
- Height ≈ radius r
- Base ≈ half the circumference = (1/2)(2πr) = πr

So the area A becomes base × height:
```math
A_{\text{circle}} = \pi r^2
```
This isn’t memorized—it's a rearrangement argument: circumference spreads out along one side, radius along the other.

---

## Step 2: Volume of a cylinder = base area × height
Stack identical circular slices of area A_base through a height h. Because every slice is the same:
```math
V_{\text{cylinder}} = A_{\text{base}} \cdot h = \pi r^2 \, h
```
This is just “same area × how many layers.”

---

## Step 3: Volume of a cone (why the 1/3 appears)
A cone of height h and base radius r narrows linearly from the base to the tip.

- At a distance x from the tip, similar triangles give the local radius:
  r(x) = (r/h) x
- The slice there is a circle of area:
  A(x) = π [r(x)]^2 = π### Step 3 (continued): Volume of a cone (why the 1/3 appears)
- At a distance x from the tip, similar triangles give r(x) = (r/h) x.
- The cross-sectional area there is:
```math
A(x) = \pi [r(x)]^2 = \pi \left(\frac{r}{h}\right)^2 x^2 = \pi \frac{r^2}{h^2} x^2
```
- Stack these thin slices (thickness dx) from x=0 to x=h:
```math
V_{\text{cone}} = \int_{0}^{h} A(x)\,dx = \int_{0}^{h} \pi \frac{r^2}{h^2} x^2 \, dx
= \pi \frac{r^2}{h^2} \cdot \frac{h^3}{3} = \frac{1}{3} \pi r^2 h
```
Intuition for the 1/3: the slice area grows like x^2 (slow at first, fast later). The “average” of x^2 from 0 to h is h^2/3, so the average cross-section is one-third of the base area, making the volume one-third of “base area × height.”

Experimental check: If you have a cone and a cylinder with the same base and height, you can actually fill the cone with water and pour it into the cylinder. It takes three full cones to fill the cylinder. That’s the 1/3 in action.

---

## Step 4: Sphere volume by slice-by-slice comparison (Archimedes’ idea)
Place a sphere of radius r inside a cylinder of radius r and height 2r (just fitting). Consider a horizontal slice at distance x from the center (−r ≤ x ≤ r).

- Sphere slice radius: by Pythagoras, the radius is √(r^2 − x^2), so its area is:
```math
A_{\text{sphere}}(x) = \pi (r^2 - x^2)
```
- Cylinder slice area is constant:
```math
A_{\text{cyl}}(x) = \pi r^2
```
- Now compare with a “double cone” (two identical cones back-to-back, apex at the center, reaching top and bottom of the cylinder). At height x, the radius grows linearly with |x|, so its slice area is:
```math
A_{\text{double-cone}}(x) = \pi x^2
```
Subtracting:
```math
A_{\text{cyl}}(x) - A_{\text{double-cone}}(x) = \pi r^2 - \pi x^2 = \pi (r^2 - x^2) = A_{\text{sphere}}(x)
```
So, at every height, the sphere and “cylinder minus double cone” have equal slice areas. By Cavalieri’s principle, they have equal volumes:
```math
V_{\text{sphere}} = V_{\text{cylinder}} - V_{\text{double-cone}}
```
Compute each part:
- Cylinder: base area × height = πr^2 × 2r = 2π r^3
- Double cone: two cones, each (1/3)πr^2 × r, so total = (2/3)π r^3

Therefore:
```math
V_{\text{sphere}} = 2\pi r^3 - \frac{2}{3}\pi r^3 = \frac{4}{3}\pi r^3
```

---

## Step 5: Convert from radius r to diameter d
Diameter and radius are related by r = d/2. Substitute into the sphere volume:
```math
V = \frac{4}{3}\pi \left(\frac{d}{2}\right)^3 = \frac{4}{3}\pi \frac{d^3}{8} = \frac{1}{6}\pi d^3
```

## Final answer
- Option 4: $\frac{1}{6}\pi d^3$

---

## Sanity checks
- Units: Volume must scale like length^3. Right-hand side has $d^3$, correct.
- Scaling: If you double the diameter, volume should multiply by 8 (since volume ∝ size^3). The formula gives $V \propto d^3$, so yes, it becomes 8 times larger.
- Ratio to cylinder: A sphere of radius r fits in a cylinder of radius r and height 2r. Cylinder volume is $2\pi r^3$. Sphere volume is $(4/3)\pi r^3$, which is exactly 2/3 of the cylinder—matching Archimedes’ famous result.

---

## Alternative derivation (direct slicing with calculus)
Slice the sphere into discs along the x-axis from −r to r:
```math
V = \int_{-r}^{r} \pi (r^2 - x^2)\,dx
= \pi \left[ r^2 x - \frac{x^3}{3} \right]_{-r}^{r}
= \pi \left( 2r^3 - \frac{2r^3}{3} \right)
= \frac{4}{3}\pi r^3
```
This directly sums the areas of circular slices.

---

## 1) Conceptual follow-up questions
- If the diameter triples, by what factor does the volume change? Why?
- A sphere is inscribed in a cylinder (same r and height 2r). What fraction of the cylinder’s volume is empty space?
- If two solids have the same cross-sectional area at every height, must they have the same volume? Explain with the sphere vs. cylinder-minus-cone example.
- You know $V_{\text{cone}} = \frac{1}{3} \pi r^2 h$. Using only similarity and stacking, explain why the “1/3” arises (think: average of $x^2$).

## 2) Application questions (real-world)
- Ball bearings: If a bearing ball’s diameter increases by 10%, about how much does its volume (and thus mass) change? What does that mean for inertia and load?
- Planetary science: If Earth’s diameter is about 12,742 km, estimate its volume treating it as a sphere. How does a 1% error in diameter measurement affect volume estimates?
- Medicine: Microbubbles used in ultrasound imaging are roughly spherical. If you halve the diameter, how many bubbles do you need to keep the same total gas volume?

## 3) Common misconceptions and traps
- Mixing radius and diameter: Plugging d into $V = \frac{4}{3}\pi r^3$ without halving gives the wrong factor. Always convert r = d/2 first.
- Thinking volume ∝ diameter (linear) or ∝ area (square): Volume scales with the cube of size. Doubling d → 8× volume.
- Forgetting the 2/3 cylinder relation: Sphere is 2/3 of its circumscribed cylinder (r, 2r). This is a powerful check.

## 4) Extension challenges
- Derive the sphere’s surface area from its volume by differentiation: $S = \frac{dV}{dr} = 4\pi r^2$. Explain why “a thin shell of thickness dr has volume ≈ surface area × dr.”
- Design experiment: Verify $V_{\text{cone}} = \frac{1}{3}\pi r^2 h$ by water transfer into a same-base, same-height cylinder. Discuss measurement errors.
- Generalize slicing: For a solid whose slice area is $A(x) = kx^2$ from 0 to h, show $V = \frac{k h^3}{3}$. Connect this to the cone case.
- Optimization: For a fixed surface area, which 3D shape encloses the maximum volume? Build intuition using scaling and curvature (hint: sphere).

## 5) Reflective insight (the deep “why”)
Volume is “area accumulated through a thickness.” When a shape grows linearly in one direction (like a cone from tip), its cross-sectional area grows as the square of that distance, and averaging a square over a range naturally introduces a 1/3 factor. For the sphere, a brilliant comparison—matching each horizontal slice to “cylinder minus double cone”—lets us bypass difficult calculations yet still capture the exact result. The essence is matching like with like, slice by slice, and trusting that volume is the sum of these slices. Once this principle is clear, unfamiliar volume problems become approachable and logical, not memorized.