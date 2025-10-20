# Question
The frequency of a sound wave is 'n' and its velocity is 'v'. If the frequency is increased to 4n, the velocity of the wave will be:  
1) v/4  
2) 2v  
3) 4v  
4) v

## Intuition First: What actually controls how fast sound moves?

Imagine a row of people passing a hand-squeeze down the line.
- How fast the “message” travels depends on how quickly each person responds and how closely they stand (the medium), not on how often the first person starts squeezing.
- In sound, the “people” are air molecules. The speed of sound depends on the air’s properties (temperature, density, elasticity), not on the pitch (frequency) you produce.

So in a fixed medium (same air conditions), changing the frequency does not change the speed of sound.

---

## Build the relation from first principles

Ask: How far does a wave “front” move in 1 second?

- Frequency n (or f) = how many wave cycles pass per second.
- Wavelength λ = distance between two crests (or compressions for sound).

In 1 second:
- The wave advances by “number of cycles” × “distance per cycle” = n × λ.

So the speed v (distance per second) must be:
```math
v = n \, \lambda
```

This is not a formula to memorize; it’s just “how many steps per second” times “length of each step.”

---

## Apply it to the question

Initial: frequency = n, speed = v. So wavelength initially is:
```math
\lambda_1 = \frac{v}{n}
```

Frequency becomes 4n. In the same medium, the speed of sound stays set by the medium. So:
```math
v = (4n)\,\lambda_2 \quad \Rightarrow \quad \lambda_2 = \frac{v}{4n} = \frac{\lambda_1}{4}
```

Conclusion: the wavelength shrinks to one-quarter, but the speed v stays the same.

Answer: 4) v

---

## Experimental view

- Strike a low-pitch and a high-pitch tuning fork at the same place in air. Measure time to reach a microphone a fixed distance away. Times are (essentially) the same.
- What changed? You’d see more wave crests per second (higher frequency), but they’re more tightly packed (shorter wavelength), keeping speed constant.

---

## Intuitive “what if” checks

- Double frequency? Wavelength halves. Speed unchanged.
- Change the medium (e.g., warm the air)? Speed changes because the medium changed, even if the source frequency stayed the same.

---

> ### 🧠 Quick Exam Tips
> - In a given medium: v is fixed; v = nλ.
> - Increase n → λ decreases proportionally so that v stays constant.
> - Crossing into a new medium: frequency stays the same; speed and wavelength adjust.

---

## Misconception Clinic

- Many students think “v = nλ, so if n increases, v must increase.” Actually, v is not controlled by n; it’s controlled by the medium. The product nλ must equal the medium-set speed, so λ adapts when n changes.
- Another common slip: thinking wavelength stays fixed when frequency changes. In one medium, wavelength flexes to keep v constant.

---

## Extension

- Sound in air (audible range) is essentially non-dispersive: speed doesn’t depend on frequency.
- Some waves (like many water waves or light in certain materials) can be dispersive: speed can depend on frequency. That’s why a prism splits colors.

---

## Practice questions

1) In the same air, a sound’s frequency is doubled. What happens to its wavelength and speed?
- Answer: Wavelength halves; speed stays the same.

2) A string’s wave speed is fixed by tension and mass per length. If you triple the frequency of the standing wave pattern, what happens to wavelength?
- Answer: It becomes one-third.

3) If air temperature increases, what happens to the speed of sound and the frequency emitted by a fixed source?
- Answer: Speed increases; source frequency stays the same; wavelength increases.

---

> “The deeper pattern: Systems often have a ‘medium-set’ speed limit. The source can change how often it ‘steps’ (frequency), but the medium decides how fast the message travels. The system balances by resizing the step length (wavelength).”