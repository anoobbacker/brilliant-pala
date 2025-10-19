# Question
If light traveling at 3 × 10⁸ km/s reaches Earth in 8.3 minutes, the distance of the Sun from Earth is:
A) 150 million km
B) 15 million km
C) 300 million km
D) 200 million km

---
# Answer

## First principles: What connects distance, speed, and time?
Speed tells us “how much distance is covered per unit time.” By definition:
$$
\text{speed} = \frac{\text{distance}}{\text{time}} \quad \Rightarrow \quad \text{distance} = \text{speed} \times \text{time}
$$
This is not a memorized formula; it’s simply the meaning of speed.

Dimensional check:
$$
[\text{distance}] = \frac{[\text{distance}]}{[\text{time}]} \cdot [\text{time}] \Rightarrow \text{km} = \frac{\text{km}}{\text{s}} \cdot \text{s}
$$
Units match, so the relationship is consistent.

---

## Clarify units (crucial!)
Standard physics uses the speed of light as:
- In meters per second: $c \approx 3 \times 10^8\ \text{m/s}$
- In kilometers per second: $c \approx 3 \times 10^5\ \text{km/s}$

Since the answer choices are in kilometers and the travel time is in minutes, we will use $c = 3 \times 10^5\ \text{km/s}$ so units stay consistent.

(Note: If you ever see “$3 \times 10^8$ km/s,” that would be 1000× too large. It’s almost certainly a unit slip; the intended value is $3 \times 10^5$ km/s.)

---

## Step-by-step solution

1) Convert time to seconds (because speed is per second):
$$
t = 8.3\ \text{minutes} \times 60\ \frac{\text{s}}{\text{minute}} = 498\ \text{s}
$$

2) Multiply speed by time:
$$
d = c \times t = \left(3 \times 10^5\ \frac{\text{km}}{\text{s}}\right) \times (498\ \text{s})
$$

3) Compute using scientific notation:
$$
d = 3 \times 498 \times 10^5\ \text{km} = 1494 \times 10^5\ \text{km} = 1.494 \times 10^8\ \text{km}
$$

Rounded to two significant figures (matching 8.3 minutes):
$$
d \approx 1.5 \times 10^8\ \text{km} = 150\ \text{million km}
$$

Answer: A) 150 million km

---

## Intuition and mental models

- Light-minute idea:
  - In 1 minute, light travels $3 \times 10^5\ \text{km/s} \times 60\ \text{s} = 1.8 \times 10^7$ km (18 million km).
  - In 8 minutes: $8 \times 18 = 144$ million km.
  - Extra 0.3 minute = 18 seconds → $18 \times 300{,}000 = 5.4$ million km.
  - Total: $144 + 5.4 = 149.4$ million km ≈ 150 million km.

- Graph view (area under velocity–time graph):
  - Constant speed = horizontal line at 300,000 km/s.
  - Time = 498 s.
  - Distance = area of rectangle = height × width = 300,000 × 498 = 149,400,000 km.

- Real-world connection:
  - The average Sun–Earth distance is called 1 Astronomical Unit (AU) ≈ 149.6 million km.
  - NASA often states the Sun’s “one-way light time” as about 8 min 20 s (≈ 8.3 min) — this is the delay before we see changes on the Sun.

---

## Multiple approaches

- Analytical (definition-based):
  $$
  d = v \times t
  $$
  Convert minutes to seconds, multiply, done.

- Estimation:
  - Round 8.3 min to ≈ 8.3 × 60 ≈ 500 s, and $3 \times 10^5 \times 500 = 1.5 \times 10^8$ km. Very close; then refine with exact 498 s if needed.

- Proportional reasoning:
  - If light travels 18 million km per minute, then 8.3 minutes is $8.3 \times 18$ million km.

- Experimental mindset:
  - Distances in space are measured by timing radio/laser pulses (time-of-flight). Send a signal, measure return time; distance = (speed × time)/2. This is how spacecraft ranging works.

---

## Answer
A) 150 million km

---

## 1) Conceptual follow-up questions

- If the light-time were 16.6 minutes, what would the distance be? (Hint: double 8.3 minutes → distance also doubles.)
- If you mistakenly used $3 \times 10^8$ m/s without converting to km/s, what distance (in meters) would you get, and how would you convert it to km?
- The Earth–Sun distance varies through the year (elliptical orbit). If the distance is 152 million km at aphelion and 147 million km at perihelion, what are the corresponding light-times?
- If light traveled through a medium (like glass), would the time change? Why doesn’t this matter in space?

---

## 2) Applications to real life and modern science

- Space communication: Commands to Mars can take 4–24 minutes one-way depending on distance. Mission control must plan for this delay.
- Space weather alerts: Solar flares and coronal mass ejections are observed about 8 minutes after they happen because of light-time.
- Navigation: The AU (≈ 1.496 × 10^8 km) is a foundational yardstick in astronomy and is tied to light propagation and orbital mechanics.

---

## 3) Common misconceptions and traps

- Forgetting unit conversion: Minutes to seconds is essential because speed is per second.
- Mixing units: Using $3 \times 10^8$ but treating it as km/s instead of m/s introduces a factor-of-1000 error.
- Wrong operation: Some students divide distance by speed when they meant to compute distance; remember “speed = distance/time,” so “distance = speed × time.”
- Rounding too early: Keep extra digits until the final step, then round to match the precision of given data.

---

## 4) Extension challenges

- Given $c = 3 \times 10^8$ m/s, redo the calculation fully in meters, then convert to km. Compare your answer with 150 million km.
- The Earth–Sun distance changes by about ±1.7% around the average. Compute the corresponding change in light-time around 8.3 minutes.
- Recreate Rømer’s historical method: Suppose eclipses of Jupiter’s moon Io appear delayed by 1000 s when Earth is farther from Jupiter by 2 AU. Estimate $c$ from this.
- Laser ranging thought experiment: If a laser pulse sent to a reflector on a spacecraft returns in 12 minutes total, what is the spacecraft’s distance? (Remember: round trip.)

---

## 5) Reflective insight: The essence
Distance–speed–time is one relationship expressed three ways. It’s not a formula to memorize but a definition to understand. Once your units are consistent, the physics becomes “area under the curve” on a velocity–time graph or simply “how much distance per second, multiplied by how many seconds.” Master the units and the logic, and you can confidently tackle any version of these problems—from classroom exercises to interplanetary navigation.