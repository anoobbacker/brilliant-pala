# Question
The power of a lens having focal length $20$ cm is

# Answer 
## Quick visual solution
- Think of a 1-meter ruler. A focal length of 20 cm means the focus is one 20-cm step from the lens.
- How many 20-cm steps fit into 1 meter? Five steps.
- Power is just “how many such focal-length steps fit in a meter.” So the strength is 5.
- Sign: converging (convex) lenses have positive strength; diverging (concave) have negative.

Answer: +5 diopters (if converging). If it’s a diverging lens, −5 diopters.

### Creative twists
- Forgetting that the count is per meter, not per centimeter.
- Missing the sign: positive for converging, negative for diverging.
- Miscounting 20-cm chunks in a meter (it’s 5, not 20).
- Halve the focal length, and twice as many chunks fit in a meter → double the power. Double the focal length → half the power.
- Reading glasses: if you comfortably focus at about 50 cm, that’s two 50-cm chunks per meter → roughly 2 diopters.
- Cameras and the eye: stronger lenses (shorter focal lengths) bend light more sharply to focus closer, just like packing more short “chunks” into a meter.

### Start with intuition
Think of eyeglasses. “Stronger” glasses bend light more sharply to focus it sooner. So a stronger lens brings parallel light to focus at a shorter distance.

That focus distance is called the focal length. Short focal length = stronger bending.

The “power” of a lens is just a neat way to measure this strength directly.

---

## Build from first principles

### What is focal length?
- Send in parallel rays (like sunlight).
- A converging lens brings them to a point — the focal point — at distance f from the lens.
- A shorter f means the lens bends rays more sharply.

### Why define power as 1/f?
We want a number that:
- Gets bigger when the lens is “stronger” (smaller f).
- Adds simply when you stack lenses (two lenses in contact act like one lens whose “strengths” add).

Defining power P as inverse focal length does exactly that, with f in meters:
```math
P = \frac{1}{f} \quad \text{(with f in meters)}
```
Unit: diopter (D), which is just m⁻¹.

- Converging (convex) lens: f > 0 → P > 0
- Diverging (concave) lens: f < 0 → P < 0

Dimensional check: P has units 1/m, matching diopters.

---

## Compute for f = 20 cm

Convert to meters:
```math
f = 20\ \text{cm} = 0.20\ \text{m}
```
Now,
```math
P = \frac{1}{0.20} = 5\ \text{D}
```
- If it’s a converging (convex) lens: +5 D
- If it’s a diverging (concave) lens: −5 D (but that would require f = −20 cm)

Since the question just says “focal length 20 cm” (usually taken as positive unless stated), the answer is:
- Power = +5 diopters.

---

### Visual aid (mental sketch)
Imagine parallel rays entering a convex lens; they meet at a point 20 cm behind the lens. That “20 cm” is the focal length f, and its inverse in meters gives the power.

---

> ### 🧠 Quick Exam Tips
> - Always convert f to meters before using P = 1/f.
> - Positive f (convex) → positive power; negative f (concave) → negative power.
> - Lenses in contact: powers add (P_total = P1 + P2).

---

## Conceptual follow-ups
- What if you halve the focal length from 20 cm to 10 cm? Power doubles from +5 D to +10 D. Stronger bending.
- Why is “inverse length” natural here? Because focusing strength scales with how quickly rays are brought together — a geometric effect that’s proportional to 1/f.

## Experimental view
Shine a parallel beam (e.g., from a distant source) through the lens and find where it sharply focuses. Measure that distance as f. A lensmeter would read about +5.00 D for this lens.

## Misconception clinic
- Many students think they can use f in cm in P = 1/f. But P is in m⁻¹. Using cm gives the wrong number. Always convert.
- A common mistake is ignoring the sign. Convex lenses have positive f and P; concave lenses have negative f and P.

## Mini practice
1) A lens has f = −50 cm. What’s its power?
- f = −0.50 m → P = −2.0 D

2) A lens has power −4 D. What is its focal length?
- f = 1/P = −0.25 m = −25 cm

---

> ### 🌱 Reflective essence
> When nature’s “strength” grows as size shrinks, the right measure often turns out to be an inverse: 1/length, 1/time, or 1/mass. Power of a lens is one of those elegant inverses that makes combining effects simple and thinking clearer.

Final answer: +5 diopters (assuming a converging lens).