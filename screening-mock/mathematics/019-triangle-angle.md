## Question

In $\triangle ABC$, if $\angle A : \angle B : \angle C = 2 : 3 : 5$, then the angle at $B$ is:

## Goal and Given
- We are told the angles of triangle ABC are in the ratio 2 : 3 : 5.
- We want angle B.

To use the ratio, we first need to know the total sum of the three interior angles of any triangle. Rather than “remembering” it’s 180°, let’s rebuild that from everyday thinking.

## Rebuilding the key fact (sum of angles in a triangle) from first principles

### A street-corner (turning) model
Imagine you are riding a bike along the sides of a triangular block (triangle ABC), always turning the same way (say, right turns) at each corner to follow the next side. Two simple observations:

1) A full spin is 360°.
   - If you start facing east and come back to the same place facing east, you have turned a total of 360° overall.

2) The turn you make at a corner relates to the interior angle there.
   - If you continued straight, you’d make a straight angle, which is half a full spin: 180°. An interior angle inside the triangle “uses up” part of that 180°.
   - So, the external turn you make at a corner = 180° − (interior angle at that corner).

If the interior angles are A, B, C, then your three turns are (180° − A), (180° − B), (180° − C). Since you end up facing your original direction after going around once, the total turn is 360°:

```math
(180^\circ - A) + (180^\circ - B) + (180^\circ - C) = 360^\circ.
```

Add the left side:

```math
540^\circ - (A + B + C) = 360^\circ.
```

Rearrange to isolate A + B + C:

```math
A + B + C = 540^\circ - 360^\circ = 180^\circ.
```

That’s the triangle angle sum — derived by pure turning logic.

- Dimensional check: degrees are units of rotation; ratios like 2:3:5 are unitless. Summing three angles gives an angle (degrees). Everything is consistent.

### (Optional) Hands-on experiment
Cut out a paper triangle and rip off its three corners. Place the three tips together along a straight edge. They fit exactly into a straight line — which is 180°. This is an experimental confirmation.

## Using the ratio 2 : 3 : 5
A ratio like 2 : 3 : 5 means the three angles are made of equal “chunks” where:
- A has 2 chunks,
- B has 3 chunks,
- C has 5 chunks.

Total chunks = 2 + 3 + 5 = 10 chunks. These 10 chunks must add to 180°, so each chunk is:

```math
\text{1 chunk} = \frac{180^\circ}{10} = 18^\circ.
```

Therefore:
- A = 2 × 18° = 36°
- B = 3 × 18° = 54°
- C = 5 × 18° = 90°

So the angle at B is:

```math
B = 54^\circ.
```

Quick sense check: 36° + 54° + 90° = 180°. Also, the largest ratio (5) gives 90°, which makes the triangle right-angled at C — consistent and reasonable.

## Multiple ways to see why triangle angles sum to 180°

- Parallel-line logic (analytical):
  Draw a line through a vertex parallel to the opposite side. The two other angles of the triangle appear as alternate interior angles on this line. They line up with the third angle to form a straight line (180°).

- Turning-angle logic (intuitive/dynamical):
  The “walk around the triangle” argument above uses only the idea that a full turn is 360° and a straight angle is 180°.

- Experimental (empirical):
  Paper tear-and-fit method.

All three perspectives lead to the same 180° result, strengthening confidence.

## Final Answer
- Angle at B = 54°.

---

## Conceptual follow-up questions
1) If the angles were in the ratio 1 : 1 : 2, what are the three angles? Why is this type of triangle special?
2) Suppose one angle is 90°. If the other two are in the ratio 2 : 3, what are they?
3) If A : B : C = k : k : k (all equal), what must each angle be? What triangle is this?

## Application questions
- Surveying and GPS: Why do triangulation methods rely on triangle angle sums being 180° on flat terrain? What changes when measuring over large distances on Earth’s curved surface?
- Engineering frames: In truss bridges, small triangular units are used for rigidity. How does knowing exact angle splits (like ratios) help in ensuring load paths and stability?

## Common misconceptions and reasoning traps
- Confusing interior and exterior angles: Exterior angles around a polygon sum to 360°, but the interior angles of a triangle sum to 180°. Don’t mix them up.
- Treating ratios as angle differences: 2 : 3 : 5 doesn’t mean “A is 2°, B is 3°, C is 5° more.” It means they are proportional parts of a whole.
- Forgetting the whole must be 180°: Always tie the ratio back to the known total (here, the triangle’s 180°).
- Units slippage: Ratios are unitless; the resulting angles must be in degrees (or radians if specified). Keep track of units.

## Extension challenges
1) Generalize to polygons: Derive (from first principles) that an n-gon’s interior angle sum is (n−2)×180° by dividing it into triangles from one vertex.
2) Curved geometry: On a sphere, the triangle’s interior angles sum to more than 180°. Construct a triangle on a globe with three right angles (each 90°). Why does this not contradict our flat-plane result?
3) Variable ratios: If A : B : C = 2 : x : (8−x) and the triangle remains valid, what are the possible values of x? Which x makes the triangle right-angled at B?

## Reflective insight (the deep “why”)
Angles in a triangle sum to 180° because, in flat (Euclidean) space, going around a closed shape returns you to your original direction after a full 360° turn, and each corner’s turn is exactly what’s “left over” from a straight 180° after accounting for the interior angle. This connects geometry to motion (turning) and shows that the 180° result is not a memorized fact but a consequence of how directions change in a flat world. On curved surfaces, direction accumulates differently, so the sum changes — revealing that angle sums encode the geometry of the space itself.

Answer: 54°.