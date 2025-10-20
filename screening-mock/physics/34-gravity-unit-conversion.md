# Question
If the acceleration due to gravity is 10 m/s² and the units of length and time are changed in kilometre and hour, respectively, the numerical value of the acceleration is  
1) 360,000  
2) 72,000  
3) 129,600  
4) 36,000


## Converting acceleration units the smart way (not by memorizing formulas)

### Start with a picture in your head
Acceleration is “how quickly your speed changes.” If a car’s speed grows faster each second, it has higher acceleration. The unit m/s² literally means: “how many meters per second your speed increases, for each second.”

Now we’ll express the same physical acceleration in different-sized rulers and clocks: kilometres instead of meters, hours instead of seconds.

---

## Build from first principles

### What are we changing?
- Length unit: from 1 meter to 1 kilometre (1 km = 1000 m)
- Time unit: from 1 second to 1 hour (1 h = 3600 s)
- Acceleration has dimensions of length/time². So when time changes, it affects the value twice (squared).

### Key idea: Same physical thing, different labels
If the physical acceleration is a, its numerical value changes when you change the unit. The relation is:

```math
\text{New number} \times (\text{new unit}) = \text{Old number} \times (\text{old unit})
```

So,
```math
N_{\text{km/h}^2} \times \left(\frac{\text{km}}{\text{h}^2}\right)
= N_{\text{m/s}^2} \times \left(\frac{\text{m}}{\text{s}^2}\right)
```

Therefore,
```math
N_{\text{km/h}^2}
= N_{\text{m/s}^2} \times
\frac{\text{m}/\text{s}^2}{\text{km}/\text{h}^2}
= N_{\text{m/s}^2} \times \left(\frac{\text{m}}{\text{km}}\right)\left(\frac{\text{h}^2}{\text{s}^2}\right)
```

Now plug in the facts:
- m/km = 1/1000 = 0.001 (because 1 km = 1000 m)
- h/s = 3600, so h²/s² = 3600² = 12,960,000

Given g = 10 m/s²,
```math
N_{\text{km/h}^2}
= 10 \times 0.001 \times (3600)^2
= 10 \times 0.001 \times 12{,}960{,}000
= 129{,}600
```

Answer: 129,600 km/h² → Option 3.

---

## Why this makes sense (intuition check)
- We switched to a larger distance unit (km), so the number should get smaller by 1000.
- We switched to a much larger time unit (hr), but time is squared in acceleration. So this increases the number by 3600².
- Net factor = (3600²)/1000 ≈ 12,960. Starting from 10, we expect about 10 × 12,960 = 129,600. The size feels right.

---

## Analytical view (unit-cancellation method)
Write it as a clean chain so units cancel visibly:
```math
10\ \frac{\text{m}}{\text{s}^2}
\times \frac{1\ \text{km}}{1000\ \text{m}}
\times \frac{(3600\ \text{s})^2}{(1\ \text{h})^2}
= 129{,}600\ \frac{\text{km}}{\text{h}^2}
```
All m cancel, all s² cancel, leaving km/h².

---

## Experimental view
If you used a motion sensor to track a falling object and computed g = 10 m/s², and then reported the same data in km and hours, your graphs would look stretched on the axes. The slope (acceleration) in the new units would be much larger in numbers because the hour is a huge time unit—squared.

---

> ### 🧠 Quick Exam Tips
> - Acceleration scales as length/time². If you change time units, square the conversion.
> - 1 hour = 3600 s, so h²/s² = 3600².
> - New numeric value = Old numeric value × (old length unit in new units) × (new time/old time)².
> - Do a quick size check: bigger time unit in the denominator means a much bigger number.

---

## Misconception clinic
- Many students forget to square the time conversion. But acceleration depends on time squared, so you must square the 3600.
- A common mistake is flipping the length factor: using 1000 instead of 0.001 for m/km. Remember: 1 m = 0.001 km.
- Mixing speeds and accelerations: speed scales with time once (T⁻¹), acceleration scales with time squared (T⁻²).

---

## Conceptual follow-ups
- What if we converted to cm/s²? Since 1 m = 100 cm, 10 m/s² = 1000 cm/s².
- What if time unit becomes minutes? Then use (60)² because 1 min = 60 s.

---

## Extension challenges
- Convert 9.8 m/s² to km/h². Predict first: roughly 0.98 of our answer → about 127,008 km/h². Compute exactly to confirm.
- A car’s acceleration is 5 km/h/s (kilometres per hour per second). Convert to m/s². Hint: km → m (×1000), h → s (÷3600).

---

## Interactive practice
1) Convert 3 m/s² to km/h².
- Quick path: 3 × 0.001 × 3600² = 3 × 12,960 ≈ 38,880.

2) Which conversion increases the number more for acceleration: changing seconds to minutes or seconds to hours?
- Hours, because 3600² is much bigger than 60².

3) If a = 20 m/s², what is it in cm/min²?
- Steps: m → cm (×100), s → min (×60) but remember time is squared: ×60² in the denominator becomes ×60² in the numerator when converting. So: 20 × 100 × 60² = 20 × 100 × 3600 = 7,200,000 cm/min².

---

> ### Reflective essence
> Units are lenses. Change the lens size (km vs m, hr vs s), and the number changes—but the underlying reality doesn’t. Master the dimensions, and you master the conversions.