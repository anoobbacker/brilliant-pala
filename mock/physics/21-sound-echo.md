# Question
The minimum distance between the source of sound and the obstacle for an echo to take place is (speed of sound is $340$ m/s).

## Echo distance — built from first principles

### Start with a real-life question
Have you ever clapped near a wall and noticed you only hear an echo when you’re far enough away? Why is that?

Your ears blend sounds that arrive very close together in time. If the reflected sound comes back too quickly, your brain merges it with the original sound and you hear just one “clap.” Experiments show your ear needs about 0.1 s (a tenth of a second) gap to hear a separate echo. This is called the persistence of hearing.

---

### Build the physics model
Picture this:
- You clap at point S (source).
- Sound travels to a wall (obstacle) a distance d away.
- It reflects and comes back the same distance d to you.

So the sound’s round trip distance is 2d.

Text sketch:
S (you) —— d ——> Wall —— d ——> back to S

Time taken for the echo to return:
- Time = distance / speed = (2d) / v

For an echo to be heard as a separate sound:
- The return time must be at least 0.1 s.

So we set:
```math
\text{Echo condition:}\quad \frac{2d}{v} \ge 0.1
```

Solve for d:
```math
d \ge \frac{v \times 0.1}{2}
```

With v = 340 m/s:
```math
d_{\min} = \frac{340 \times 0.1}{2} = \frac{34}{2} = 17\ \text{m}
```

Answer: 17 m

---

### Intuition and checks
- Dimensional check: speed (m/s) × time (s) gives meters — good.
- Proportional logic: Faster sound → needs a larger distance to create the same 0.1 s delay. So on a hot day (slightly higher speed of sound), the minimum distance is slightly larger.

---

> ### 🧠 Quick Exam Tips
> - Use round-trip time: t = 2d/v, not d/v.
> - Echo needs at least 0.1 s delay.
> - Handy shortcut: d_min = v/20 (since 0.1/2 = 1/20). For v = 340 m/s → 340/20 = 17 m.

---

## Multiple lenses

### Analytical view
- Requirement: 2d/v ≥ 0.1 → d ≥ v/20.
- For any medium, just plug in its speed of sound.

### Experimental view
- Stand near a wall, clap, walk backward slowly.
- Notice the exact moment you start to hear a separate “second clap” — that’s when 2d/v ≈ 0.1 s.

### Intuitive view
- If you’re too close, the reflection returns too fast and blends with the original sound.
- Doubling the speed of sound doubles the needed distance (same 0.1 s delay).

---

## Misconception clinic
- Many students think: “Distance = speed × time = 340 × 0.1 = 34 m.” But actually, 34 m is the round-trip distance. You must split by 2. Correct answer: 17 m.
- A common mistake is ignoring the ear’s 0.1 s threshold and assuming any reflection is an echo. Not true — timing matters, not just reflection.
- Some think louder sounds create echoes at shorter distances. Loudness doesn’t change the ear’s timing threshold.

---

## Application nuggets
- Auditorium design: absorb sound and shape walls to avoid strong reflections returning after ~0.1 s, which cause audible echoes.
- Sonar/radar use exactly this “round-trip time” idea to measure distances.

---

## Practice questions
1) If the speed of sound is 343 m/s (warmer air), what is d_min?
   - d_min = 343/20 ≈ 17.15 m.

2) In water, v ≈ 1500 m/s. What is d_min for an echo?
   - d_min = 1500/20 = 75 m.

3) You hear an echo 0.5 s after a shout in air (340 m/s). How far is the wall?
   - d = v × t / 2 = 340 × 0.5 / 2 = 85 m.

4) If your brain could separate sounds at 0.07 s instead of 0.1 s (more sensitive), with v = 340 m/s:
   - d_min = 340 × 0.07 / 2 = 11.9 m.

---

> “Reflective essence”
> Nature often hides answers in round trips. Whether it’s echoes, sonar, or radar, measure the time there and back — and the distance quietly reveals itself.