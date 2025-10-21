## Question

How many balls, each of radius $1$ cm, can be made from a solid sphere of lead of radius $8$ cm?

## Big idea in everyday terms
Imagine you have a big lump of lead shaped like a sphere (a ball) with radius 8 cm. You melt it and pour the liquid lead into molds to make many smaller balls, each with radius 1 cm. How many small balls can you make?

When you melt and recast the same material:
- The stuff (mass) is conserved — nothing magically disappears or appears.
- For the same material, mass is proportional to volume. So this question is really: How many times does the small ball’s volume fit into the big ball’s volume?

So the heart of the problem is comparing volumes of two spheres with different radii.

## Step 1: What is conserved?
- Lead is the same material before and after. So density (mass per volume) stays the same.
- Let ρ be the density. Then mass = ρ × volume.
- If we make N small balls, the total mass must match:

```math
\text{Mass of big sphere} = N \times \text{Mass of one small sphere}
```

Because density is the same on both sides, it cancels:

```math
\rho \, V_{\text{big}} = N \, \rho \, V_{\text{small}} \quad \Rightarrow \quad N = \frac{V_{\text{big}}}{V_{\text{small}}}
```

So we only need the ratio of volumes.

## Step 2: How does a sphere’s volume depend on its radius? (from first principles)
We won’t start by quoting the formula. Instead, let’s reason it out.

- Volume is measured in cubic centimeters (cm³). Radius is in centimeters (cm).
- If the volume of a sphere depends only on its radius r (and the “shape” is fixed), the only way to turn a length (r) into a volume (cm³) is to cube it. So the volume must be “some constant × r³”.

This is dimensional analysis logic: to get cm³ from cm, you need r³. But let’s also give a geometric reason:

- Imagine “blowing up” a ball so every linear size is multiplied by a factor k (like zooming a 3D model).
- Each length multiplies by k, each area by k², and each volume by k³.
- So if V(r) is the volume at radius r, then scaling the radius to kr scales the volume to k³V(r). This functional rule forces the form V(r) = C r³ for some constant C (the same for all spheres).

We don’t even need to know what C is, because it will cancel when we take a ratio.

So write:

```math
V(r) = C \, r^3
```

## Step 3: Compare the two spheres
Let r_big = 8 cm and r_small = 1 cm.

```math
N = \frac{V(8)}{V(1)} = \frac{C \cdot 8^3}{C \cdot 1^3} = 8^3 = 512
```

So you can make 512 balls of radius 1 cm.

## Quick reality check (optional)
If you do know the standard formula V = (4/3)πr³, the ratio still becomes (8³)/(1³) = 512. The constant (4/3)π cancels, exactly as our reasoning predicted.

## Final answer
512 balls.

---

## Conceptual follow-up questions
1. If the big sphere had radius 10 cm and the small balls still had radius 1 cm, what would the number be? Why?
2. If the small balls had radius 2 cm, how many could you make from the same 8 cm sphere? Explain using the r³ scaling.
3. If you doubled the radius of a ball, by what factor does its volume change? Its surface area? Why are these different?
4. Suppose 5% of the lead is lost during melting. How would you adjust the calculation?

## Application questions
- Engineering: Ball bearings are made by casting spheres. If a foundry switches from making 5 mm radius bearings to 4 mm radius, how does total output (number of balls) change for the same amount of steel?
- Planetary science: If a moon’s radius is 3 times smaller than Earth’s, estimate its volume and mass (assuming same average density). What fraction of Earth’s mass does it have?
- Medicine: Microbeads used in drug delivery are tiny spheres. If bead radius is halved, how many more beads can you make from the same material?

## Common misconceptions and reasoning traps
- Mixing up radius and diameter: If diameter is doubled, radius is also doubled—so volume increases by 2³ = 8, not 2.
- Using area scaling for a volume problem: Areas scale as r², but we need volume, which scales as r³.
- Thinking density matters here: Density cancels because it’s the same material. It would matter only if materials changed.
- Forgetting conservation: Cutting without melting wastes material; our answer assumes you melt and recast with no loss.

## Extension challenges
- If you tried to carve spheres out of the big solid without melting, what’s the maximum number of 1 cm radius spheres you could extract, considering packing inefficiency? (Hint: sphere packing in a volume tops out around 74%.)
- Derive V ∝ r³ by approximating a sphere as many tiny cubes, then showing that scaling each length by k multiplies the number of cubes by k³.
- Use water displacement: Design an experiment to measure the big sphere’s volume and a small sphere’s volume by water rise, and compute N from your measurements.

## Reflective insight
The essence here is scaling and conservation. When shape stays the same and you scale its size, volume grows with the cube of the length scale. Because mass is conserved and density is constant, counting how many small shapes fit into a big one reduces to a pure ratio of r³. This “constants-cancel” mindset lets you solve many problems without memorizing formulas—by focusing on dimensions, similarity, and what’s physically conserved.