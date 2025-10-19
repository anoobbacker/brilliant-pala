# Question
A bus starts from town A and reaches town B with speed $40$ km/h. It returns to town A with speed $60$ km/h.  The average velocity of the bus is

## What are we really asking?

Imagine you walk from your house to the park and then come back home. Where are you now compared to where you started? Exactly where you began — your “change in position” is zero.

That idea is the heart of average velocity.

- Average velocity = how fast your position changes, including direction.
- Average speed = how fast your distance adds up (ignores direction).

The problem asks for average velocity.

---

## Build it from first principles

### Step 1: Define average velocity
Average velocity is total displacement divided by total time.

$$
\text{Average velocity} = \frac{\text{Total displacement}}{\text{Total time}}

$$

- Displacement means “straight-line change in position from start to finish,” with direction.

### Step 2: Apply it to this trip
- The bus starts at A, goes to B, and returns to A.
- Start and end point are the same, so total displacement = 0.

Let the A-to-B distance be D (we don’t even need its value).

Total time T is the sum of the two legs:
- Time A → B: D/40 hours
- Time B → A: D/60 hours

$$
T = \frac{D}{40} + \frac{D}{60}
  = D\left(\frac{1}{40} + \frac{1}{60}\right)
  = D\left(\frac{3+2}{120}\right)
  = \frac{D}{24} \text{ hours}

$$

Now average velocity:
$$
\overline{v} = \frac{\text{Total displacement}}{\text{Total time}} 
             = \frac{0}{T} 
             = 0
$$

So the average velocity of the bus over the entire round trip is 0 km/h (vector).

---

## Quick reality check (dimensional and intuitive)

- Units: displacement (km) / time (h) → km/h. Zero divided by anything is still zero km/h.
- Intuition: Ended where it started, so on average its position didn’t change.

---

## Important: Many exams actually mean average speed

If they intended “average speed” (common in such problems), then:

- Total distance = 2D
- Total time = D/24
$$
\text{Average speed} 
= \frac{2D}{D/24}
= 48 \ \text{km/h}
$$
This is the harmonic mean of 40 and 60, not the simple average.

---

> ### 🧠 Quick Exam Tips
> - Average velocity = displacement/time. Round trip → displacement = 0 → average velocity = 0.
> - Average speed over equal distances uses the harmonic mean: 2v₁v₂/(v₁+v₂).
> - Don’t confuse “velocity” (direction matters) with “speed” (no direction).

---

## Multiple lenses

- Intuitive view: Ending where you started = no net movement overall.
- Analytical view: Use displacement/time for velocity; distance/time for speed.
- Experimental view: GPS from A back to A shows zero net change in coordinates, even if you moved a lot in between.

---

## Conceptual follow-ups

- What if the bus stops midway back and doesn’t reach A? Then displacement ≠ 0, so average velocity ≠ 0.
- If both speeds were the same (say 50 and 50), then:
  - Average velocity for the round trip is still 0.
  - Average speed would be 50 km/h.

---

## Misconception clinic

- Many students think: “Average velocity is the average of 40 and 60, so 50.” But velocity uses displacement, not path distance; for a round trip, it’s 0.
- A common mistake is: “If speeds differ, average speed is the simple average.” Not true when distances are equal; use the harmonic mean (48 km/h here).
- “Different route back changes the result.” It doesn’t change displacement; start and end points still coincide, so average velocity remains 0.

---

## Extension challenges

- Math link: The harmonic mean appears whenever you combine rates over equal chunks of the “thing being measured” (here, equal distances).
- Engineering link: In traffic flow or network data rates, overall throughput often depends on harmonic means, not arithmetic means.

---

## Interactive practice

1) A cyclist goes 30 km out and returns 30 km back. Outward speed 20 km/h, return speed 30 km/h.
   - Average velocity for the whole trip?
   - Average speed?

2) A runner goes 400 m around a track and finishes where they started in 80 s.
   - Average velocity?
   - Average speed?

3) If a car drives 100 km east, then 100 km west but stops 20 km short of the start, is average velocity zero? Why or why not?

---

> ### Reflective essence
> Nature cares about where you end up, not just what path you took. Velocity measures change of position; speed measures effort along the path. Knowing which “change” you’re tracking is the key to choosing the right average.