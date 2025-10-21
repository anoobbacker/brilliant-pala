## Question

In figure, $D$ and $E$ are the mid-points of sides $A B$ and $A C$ respectively of $\triangle A B C$, if $\angle E D B=K^{\circ}$, then the value of $K$ is

Diagram:
```
           A ( 60° )
          /\
         /  \
        /    \
       /      \
    D +--5 cm--+ E
     /          \
    /            \
   /              \
B /________________\ C (50°)
```

## Key idea in one line
Because D and E are midpoints, DE is parallel to BC. So the angle at D between DE and DB equals the angle at B between BC and BA. Therefore, K = ∠ABC.

## Step-by-step, from first principles

### 1) Build an everyday picture
- Imagine triangle ABC as a sheet of paper.
- Mark the halfway point D along AB and the halfway point E along AC.
- Connect D to E. Intuitively, the little segment DE “looks” like a miniature version of BC, sitting halfway up the triangle.

This is the “mid-segment” idea: the line joining midpoints of two sides of a triangle behaves like a shrunken, parallel copy of the third side.

### 2) Reconstruct the midpoint theorem (no memorizing)
We want to show DE ∥ BC from scratch.

- Facts we know:
  - D is the midpoint of AB, so AD = DB.
  - E is the midpoint of AC, so AE = EC.
  - The angle at A is common to triangles ADE and ABC.

- Compare triangles ADE and ABC:
  - AD/AB = 1/2 (since D is midpoint),
  - AE/AC = 1/2 (since E is midpoint),
  - ∠DAE is the same as ∠BAC (they are literally the same angle at A).

So the two triangles have two pairs of sides in the same ratio with the included angle equal. That’s enough to say the triangles are similar (same shape, different size) by SAS similarity with scale 1:2.

In similar triangles, corresponding sides are parallel (they point in the same direction).
- Side DE in the small triangle corresponds to side BC in the big triangle.
- Therefore:
```math
DE \parallel BC.
```

This is the midpoint theorem, but we just derived it logically from similarity.

### 3) Transfer the angle using parallel lines
We are asked for ∠EDB, which is the angle at D formed by DE and DB.

- Since DE ∥ BC, the direction of DE matches the direction of BC.
- DB lies along BA (because D is on AB).
- Therefore, the angle between DE and DB equals the angle between BC and BA.

But the angle between BC and BA is precisely ∠CBA, which is the angle at B in triangle ABC (commonly written as ∠ABC).

So:
```math
\angle EDB = \angle CBA = \angle ABC.
```

Therefore:
```math
K = \angle ABC.
```

If your diagram labels ∠ABC numerically (say 50°), then K = 50°. The value of K is exactly “the angle at B” in the original triangle.

---

## Multiple ways to see it (flexible thinking)

- Intuitive/experimental (dynamic geometry):
  - Draw any triangle ABC in a geometry app.
  - Mark midpoints D (on AB) and E (on AC), draw DE.
  - Measure ∠EDB and ∠ABC. Drag the vertices around: the two measurements always match. This invariance hints at parallelism.

- Coordinate/Vector reasoning (analytical):
  - Place A at the origin, let B be vector b and C be vector c.
  - Then D = b/2 and E = c/2 (midpoints).
  - Vector DE = E − D = (c/2 − b/2) = (1/2)(c − b), which is a scalar multiple of BC = c − b.
  - So DE is parallel to BC, and the same angle transfer argument gives ∠EDB = ∠ABC.

---

## Final answer
```math
K = \angle ABC.
```
(Read the value of ∠ABC from your figure; K equals that.)

---

## 1) Conceptual follow-up questions
- If F is the midpoint of BC, what can you say about the triangle formed by D, E, and F compared to triangle ABC?
- If DE ∥ BC, what can you say about ∠AED and ∠ACB? Why?
- If you pick any other point M on AB (not the midpoint), is ME parallel to BC? Under what condition would it be?

## 2) Real-life applications
- In civil engineering, mid-segment concepts help in creating scaled, parallel members in trusses to balance forces and simplify analysis.
- In computer graphics, constructing parallel segments via midpoint operations is used in mesh simplification and shape modeling.

## 3) Common misconceptions and traps
- Mistake: Thinking DE is “approximately” parallel to BC only in isosceles triangles. Reality: it is exactly parallel in any triangle when D and E are true midpoints.
- Mistake: Assuming ∠EDB equals ∠ABC only when the triangle is symmetric. The equality holds for all triangles due to parallel lines.
- Trap: Mixing up angle positions: ∠CBA is the angle at B between CB and BA, not between AB and AC.

## 4) Extension challenges
- Prove that the length DE is exactly half of BC using similarity (not just parallelism).
- Show that the perimeter of triangle ADE is exactly half the perimeter of triangle ABC minus AB (careful reasoning needed).
- Given any triangle ABC, find a point P such that the segment through P parallel to BC cuts AB and AC at their midpoints. Is P unique?

## 5) Reflective insight
The essence here is structural similarity: selecting midpoints creates a smaller, self-similar copy nested inside the original triangle. Parallelism is not a coincidence; it is the geometric fingerprint of similarity. Once you spot the similarity, angle equalities flow naturally via parallel lines, making local angles (like ∠EDB) simply re-labeled versions of the original triangle’s angles (like ∠ABC). This mindset—looking for hidden similarity and invariance—lets you solve many geometry problems with clarity and confidence.