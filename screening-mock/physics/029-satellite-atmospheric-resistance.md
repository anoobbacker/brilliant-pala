# Question
When a satellite in a circular orbit around the earth enters the atmospheric region, it encounters small resistance to its motion. Then:  
1) Gravitational force on satellite decreases  
2) Its kinetic energy decreases  
3) Its period of revolution around the earth increases  
4) Its kinetic energy increases

---
# Answer
## Quick visual reasoning
- Picture the coin-donation funnel: as the coin rubs against the walls (like air drag), it spirals inward and spins faster.
- Drag steals energy, so the satellite can’t stay high; it sinks closer to Earth.
- Closer in, gravity tugs harder and the path is tighter, so the satellite must whip around faster to keep curving instead of plunging straight down.
- The loop is smaller and the satellite moves faster, so each lap takes less time.
- Although drag removes total energy, dropping lower converts height into speed, so the satellite’s speed — and thus its kinetic energy — ends up higher in the new, lower orbit.

## What that means for the options
- 1) Gravitational force on satellite decreases → False. Closer means a stronger pull.
- 2) Its kinetic energy decreases → False. In a lower orbit it moves faster, so kinetic energy is higher.
- 3) Its period of revolution increases → False. Smaller, faster loop means shorter time per lap.
- 4) Its kinetic energy increases → True.

## Answer
Only 4

## Creative twists
- “Drag slows you, so kinetic energy must drop.” Trap: in orbits, falling inward speeds you up more than the drag slows you, ending with a faster, lower orbit.
- “Bigger pull should slow it.” Trap: stronger pull closer to Earth accelerates the satellite along its path, tightening and quickening the orbit.
- “Shorter path means longer time.” Trap: the path shrinks but speed rises even more, so the lap time shrinks.
- Coin-in-a-funnel or water spiraling into a drain: friction makes it spiral inward and spin faster — same logic.
- Spacecraft deorbiting: skims atmosphere, loses height, orbits faster, period drops before reentry.
- Planetary rings: inner ring particles circle faster than outer ones — the closer, the quicker.

### Start with a picture in your head
Imagine whirling a ball on a string above your head. If the string gets shorter, what must you do to keep the ball moving in a circle? You have to swing it faster. Why? Because at a smaller radius the inward pull must be stronger, and that requires a higher speed.

A satellite with a tiny air drag is like that ball: drag slowly “steals” energy so the orbit shrinks (radius gets smaller). Once the satellite is closer to Earth, gravity is stronger and the circular speed required is higher.

---

## Rebuild from first principles

### Step 1: What keeps a satellite in a circular path?
Gravity provides the inward (centripetal) force:
```math
\frac{G M m}{r^2} = \frac{m v^2}{r}
```
So the circular speed is
```math
v^2 = \frac{G M}{r} \quad \Rightarrow \quad v = \sqrt{\frac{G M}{r}}
```
Smaller r ⇒ larger v. This is the key pattern.

### Step 2: Kinetic energy in a circular orbit
```math
K = \frac{1}{2} m v^2 = \frac{1}{2} m \cdot \frac{G M}{r} = \frac{G M m}{2 r}
```
Smaller r ⇒ larger K.

Total mechanical energy for a circular orbit (useful for intuition):
```math
E_\text{total} = K + U = \frac{G M m}{2 r} - \frac{G M m}{r} = - \frac{G M m}{2 r}
```
As r decreases, E_total becomes more negative (energy is lost), even though K increases.

### Step 3: Period of revolution
```math
T = \frac{2 \pi r}{v} = 2 \pi \sqrt{\frac{r^3}{G M}}
```
Smaller r ⇒ smaller T (shorter period).

### Step 4: Gravitational force size
```math
F_g = \frac{G M m}{r^2}
```
Smaller r ⇒ larger F_g.

---

## What does air resistance actually do?
- Drag does negative work on the satellite, removing mechanical energy.
- With less energy, the orbit can’t stay at the same radius; it spirals inward.
- Closer to Earth, gravity is stronger, so the required circular speed is higher, making the satellite’s kinetic energy larger in its new, lower circular orbit.
- The orbital period becomes shorter.

Small nuance: the instant drag acts, speed momentarily drops. Then the path becomes elliptical and the satellite falls to a lower altitude where it ends up moving faster in the new (lower) circular orbit. Exam questions are asking about this overall effect.

---

## Evaluate each statement

1) Gravitational force on satellite decreases
- False. As r decreases, F_g ∝ 1/r^2 increases.

2) Its kinetic energy decreases
- False. In the new lower circular orbit, K = GMm/(2r) is larger.

3) Its period of revolution increases
- False. T = 2π√(r^3/GM) decreases with r.

4) Its kinetic energy increases
- True.

Correct choice: 4 only.

---

## Visual aid (mental sketch)
- Draw Earth with two circular orbits: a higher one (initial) and a slightly lower one (after drag).
- Arrows:
  - Tangential drag opposite motion.
  - Gravity pointing inward.
- Labels:
  - Lower orbit: larger v, larger K, stronger gravity, shorter period.

---

> ### 🧠 Quick Exam Tips
> - For circular orbits: v ∝ r^(-1/2), K ∝ r^(-1), T ∝ r^(3/2), F_g ∝ r^(-2).
> - Losing orbital energy (due to drag) → orbit shrinks → speed up → period down.
> - Counterintuitive but true: in bound orbits, losing energy can make you move faster.

---

## Deep learning layer

### Conceptual follow-ups
- What if the atmosphere suddenly vanished after the satellite dipped lower? It would keep the new faster, lower circular orbit (until other perturbations act).
- What if instead of drag, a rocket briefly speeds the satellite up at the same altitude? It goes to a higher, slower orbit (opposite effect).

### Experimental view
- The ISS at ~400 km altitude moves at ~7.66 km/s with a period of ~92 minutes. If it drops lower, it speeds up slightly and the period gets shorter. That’s why it needs periodic “reboosts” to counter drag.

### Misconception clinic
- Many students think “friction always makes things slower.” In straight-line motion, yes. In orbits, drag lowers the orbit so the required circular speed is higher, making the satellite end up moving faster.
- A common mistake is assuming gravity “weakens” as a satellite drops because “it’s losing energy.” Actually, gravity gets stronger when you’re closer: F_g ∝ 1/r^2.
- Thinking period must increase if speed drops: in orbits, both radius and speed change. The dominating effect for period is T ∝ r^(3/2): smaller r means shorter T.

### Extension challenge
- Link to Kepler’s third law: T^2 ∝ r^3 arises naturally from centripetal balance and Newton’s law of gravitation.
- Cross-discipline pattern: Systems with central forces often have counterintuitive energy-speed relations—use energy diagrams to reason about them.

### Interactive practice
1) If r becomes half, by what factor does v change?
   Answer: v ∝ r^(-1/2) ⇒ v increases by √2.

2) If a satellite’s orbital period drops by 10%, what happens qualitatively to its radius?
   Answer: It decreases (since T ∝ r^(3/2)); roughly r scales like T^(2/3), so r decreases by about 6–7%.

3) In a lower circular orbit, which increases more strongly with decreasing r: gravity or kinetic energy?
   Answer: Gravity ∝ 1/r^2 grows faster than K ∝ 1/r.

> ### ✨ Reflective essence
> In orbit, “lower” means “faster.” Losing energy draws you deeper into the gravitational well where the required circular speed is higher. Nature trades height for speed. Understanding that trade—rather than memorizing formulas—makes orbital questions feel obvious.