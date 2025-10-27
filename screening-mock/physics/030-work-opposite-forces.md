# Question
A body is under the action of two equal and opposite forces, each of 3N. The body is displaced by 3m. The work done is  
1) +9 J  
2) 0  
3) -9 J  
4) 18 J

---
# Answer
## Quick visual answer
- Picture a tug-of-war: the object is in the middle, pulled equally from both sides with the same strength.
- It slides 3 m to the right. The right pull helps the motion; the left pull resists it by the same amount over the same distance.
- Energy given by one side is exactly taken away by the other, like equal deposits and withdrawals.
- So the pair, together, transfer no net energy.

Answer: 0 (Option 2)

## Creative twists
- Adding the two “efforts” as 9 + 9 = 18. But one helps and one opposes; they cancel.
- Thinking “if it moved, work can’t be zero.” It can—motion may continue from earlier push; with balanced pulls, no net energy change.
- Forgetting direction: work depends on whether a force aids or resists the motion.

- Car cruising at steady speed: engine push and air drag pull are equal and opposite; over any distance, engine’s positive work is canceled by drag’s negative work—net zero.
- Walking with two people pulling you equally from front and back: even if you glide forward, front friend adds energy while the back friend removes the same amount.

## Start with a real picture

Imagine two friends pulling you on a skateboard from opposite sides with equal strength: one pulls forward with 3 N, the other pulls backward with 3 N. You roll 3 m forward (maybe you already had some speed). Who gives you energy overall?

- The forward friend is helping your motion (adds energy).
- The backward friend is resisting your motion (removes the same amount of energy).

Energy added and removed cancel out. That’s the heart of this problem.

---

## Build from first principles

### What is “work” really?
Work is energy transferred by a force when it has a component along the displacement. If the force helps the motion, work is positive; if it opposes, work is negative.

Mathematically,
```math
W = \vec F \cdot \vec s = F\,s\,\cos\theta
```
- θ is the angle between the force and the displacement.
- Units: N·m = Joule (J).

### Apply to this situation
Two forces act on the same body:
- Force 1: +3 N in the direction of motion → θ = 0°, so cosθ = 1
- Force 2: −3 N opposite to motion → θ = 180°, so cosθ = −1
- Displacement s = 3 m

Work by each:
```math
W_1 = (+3)\times 3 \times \cos 0^\circ = +9\ \text{J}
```
```math
W_2 = (3)\times 3 \times \cos 180^\circ = -9\ \text{J}
```

Total work (sum of works) is:
```math
W_{\text{total}} = W_1 + W_2 = +9\ \text{J} + (-9\ \text{J}) = 0
```

Another way: the net force is zero (3 N − 3 N = 0), so net work by these forces equals work by the resultant force:
```math
W_{\text{net}} = \vec F_{\text{net}} \cdot \vec s = \vec 0 \cdot \vec s = 0
```

Therefore, the correct answer is:
- Option 2) 0

---

## Why this makes sense (energy viewpoint)
If the net force is zero, these forces don’t change the kinetic energy of the body. One force gives +9 J, the other takes −9 J, so the body’s kinetic energy from these two forces doesn’t change. 

---

## Experimental view
Put a cart on a low-friction track. Attach two spring scales on opposite sides, each pulling with 3 N. Let the cart glide 3 m. One person does +9 J of work; the other does −9 J. The cart’s speed stays the same overall (ignoring friction). Net energy from the pair: zero.

---

## Intuitive checks
- If we doubled the displacement to 6 m, each force does ±18 J, still summing to 0.
- If the displacement were perpendicular to both forces, cos 90° = 0, so each does 0 work, and total is still 0.

---

> ### 🧠 Quick Exam Tips
> - Work cares about direction: W = F s cosθ.
> - For several forces, add their works (or use resultant force): W_total = (F_net)·s.
> - Equal and opposite collinear forces doing work over the same displacement give equal and opposite energies → net 0 J.
> - “Object moves” does not automatically mean “net work ≠ 0.”

---

## Conceptual follow-ups
- What if the forces weren’t equal? Then F_net ≠ 0 and W_net = F_net s cosθ would be non-zero.
- What if the forces are equal but not collinear (forming a couple)? Then net force is 0, but they can cause rotation and do rotational work. Translational work is still 0, but rotational kinetic energy can change. This problem doesn’t specify a couple, so we assume collinear forces.

---

## Real-world connection
- Elevator moving at constant speed: tension equals weight. Over some rise, tension does positive work, gravity does equal negative work → net work 0 → speed unchanged.

---

## Misconception clinic
- “Any displacement means positive work.” Not true. Work depends on alignment. Opposing forces can do negative work.
- “Work is just F × s.” Missing the cosθ makes you miss signs and perpendicular cases.
- “Net force zero means no work by any force.” Individual forces can still do non-zero work; they just cancel in total.

---

## Practice questions
1) A box slides 4 m to the right. Two horizontal forces act: 5 N right and 2 N left. What is the net work?
2) A 3 N force acts upward while the object moves 3 m horizontally. How much work does this force do?
3) Two students pull a sled in opposite directions with 10 N each; the sled moves 2 m north. What is the total work by the pair?
4) A block is pulled 5 m by a 6 N force at 60° to the direction of motion. What is the work done by the force?

Answers:
1) W = (5 − 2) × 4 = 12 J
2) W = 3 × 3 × cos 90° = 0 J
3) W = (10 − 10) × 2 = 0 J
4) W = 6 × 5 × cos 60° = 15 J

---

> ### Reflective essence
> Energy bookkeeping is about alignment and balance. Forces can fight and still do work individually, yet the universe only cares about the sum. Direction turns arithmetic into meaning.