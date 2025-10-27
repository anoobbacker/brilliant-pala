# Question
A sound wave with wavelength λ travels from a medium where its speed is V into another medium where its speed is 4V. What is its new wavelength?

Choices:  
A) λ  B) 2λ  C) 3λ  D) 4λ

# Answer
## Visual reasoning (no formulas)
- Imagine wave crests like runners leaving a gate at a steady rhythm set by the starter. That rhythm doesn’t suddenly change at a boundary.
- In the new medium, runners can move 4 times faster.
- Same rhythm of starts, but each runner now covers 4 times more distance before the next runner starts.
- So the spacing between runners (the wavelength) stretches to 4 times what it was.

Answer: D) 4λ

### Fast reasoning checks
- If the wave moves faster while the beat of arrivals stays the same, gaps must get bigger: here, 4 times bigger.
- If the new medium had been slower, you’d expect shorter gaps. Faster → longer, slower → shorter.

## Build from first principles

### 1) What do wavelength and frequency mean?
- Wavelength (λ): the distance between two neighboring crests (or compressions) in a wave.
- Frequency (f): how many crests pass a fixed point each second. Unit: 1/s (Hz).
- Period (T): time between two crests passing; it’s the inverse of frequency, T = 1/f.

### 2) How do speed, wavelength, and frequency connect?
Imagine watching one crest move. In one period T, one crest travels forward exactly one wavelength λ. So distance/time = speed:
```math
v = \frac{\text{distance in one period}}{\text{time for one period}} = \frac{\lambda}{T}
```
Since f = 1/T, this becomes:
```math
v = f\,\lambda
```
Dimensional check:
- [v] = L/T
- [f] = 1/T
- [λ] = L
- So [fλ] = (1/T)(L) = L/T, consistent.

### 3) What happens at a boundary between two media?
At the interface, the air (or medium 1) and the new medium (medium 2) touch at the same physical surface. That surface can only wiggle at one time rate; otherwise, it would tear itself apart. Therefore, the oscillation rate (frequency f) must be the same on both sides. In short:
- Frequency is set by the source and stays the same across the boundary.
- The medium determines the wave speed v.
- Therefore, when v changes but f stays the same, λ must adjust so that v = fλ still holds.

This is like cars entering a wider road: if cars per second (frequency) stays the same but their allowed speed increases, the spacing between cars (wavelength) increases.

---

## Apply to the given numbers

- In medium 1: speed v₁ = V, wavelength λ₁ = λ, frequency f (unknown, but same on both sides).
- In medium 2: speed v₂ = 4V, wavelength λ₂ = ?, same frequency f.

Use v = fλ in both media:
```math
v_1 = f \lambda_1 \quad \Rightarrow \quad f = \frac{v_1}{\lambda_1} = \frac{V}{\lambda}
```
```math
v_2 = f \lambda_2 \quad \Rightarrow \quad \lambda_2 = \frac{v_2}{f} = \frac{4V}{V/\lambda} = 4\lambda
```
Or directly by ratio with f constant:
```math
\frac{\lambda_2}{\lambda_1} = \frac{v_2}{v_1} = \frac{4V}{V} = 4
```
So λ₂ = 4λ.

Answer: D) 4λ

---

## Intuitive and experimental viewpoints

- Intuitive picture: Count crests per second (frequency). That count can’t suddenly change at the seam between materials, because the seam is driven by the same up-down (or in-out) motion. If the crests move faster on the other side, to keep the same number per second, they must be spaced farther apart—hence longer wavelength.

- Experimental way: Put a speaker at a boundary between two materials (e.g., air and a tube filled with a different gas). Measure the frequency with a microphone and oscilloscope on both sides—it’s the same. Measure speed in the second medium (via time-of-flight or known properties). Then calculate λ₂ = v₂/f. You’ll find it grows in proportion to speed.

- Real-world link: In helium (where sound travels faster than in air), a sound of the same frequency has a longer wavelength than in air. The pitch you hear can change mainly due to the vocal tract resonances shifting, but the emitted frequency from your vocal cords remains the same; the medium changes speed and thus wavelength.

---

## Multiple approaches summarized

- Analytical: Use v = fλ and continuity of frequency at the boundary.
- Dimensional: Ensure only v or λ can change to keep v = fλ with constant f; quadrupling v must quadruple λ.
- Visual: Crests moving faster must be spaced farther apart if the “crests per second” count is fixed.

---

## Final selection
D) 4λ

---

## Conceptual follow-up questions

1) If the second medium had speed 0.5V, what would the new wavelength be?  
2) Does the frequency of the wave ever change when passing into a new medium? If not, what situations can change the frequency detected by an observer?  
3) If instead of crossing a boundary, the source itself speeds up or slows down its oscillation, which quantities change in a given medium?  
4) How is this different for light passing from air into glass? Which quantity stays the same for light at a boundary?

---

## Application questions

1) Sonar in water vs. air: Water has much higher sound speed than air. For the same ping frequency, how do sonar wavelengths compare in water and air? Why does this matter for resolution and range?  
2) Medical ultrasound: Higher frequency increases image resolution but shortens wavelength. How does selecting frequency balance penetration depth and image sharpness in tissue?  
3) Architectural acoustics: Knowing that wavelength grows with speed, how might temperature gradients (which change air’s sound speed) affect how sound bends and is heard outdoors?

---

## Common misconceptions and reasoning traps

- “Frequency changes when entering a new medium.”  
  Reality: Frequency is set by the source and remains continuous at the boundary; wavelength adjusts.

- “Bigger speed means louder sound.”  
  Loudness relates to amplitude and energy delivery, not directly to speed.

- “v = fλ is a memorized formula only.”  
  It comes from the simple distance-per-period idea: one period advances one wavelength.

- Confusing Doppler effect with refraction.  
  Doppler changes the observed frequency when source or observer moves. Refraction across media keeps frequency the same but changes speed and wavelength.

---

## Extension challenges

1) Angle refraction for sound: Derive a Snell-like law for sound crossing an interface at an angle and show that sinθ₁/sinθ₂ = v₁/v₂.  
2) Temperature gradient in air: Sound speed increases with temperature. Predict how a vertical temperature gradient bends sound rays (mirage-like bending) and how that affects audibility over distance.  
3) Layered media: If sound passes through multiple layers each with different speed, track how wavelength changes layer by layer while frequency stays constant.

---

## Reflective insight

The essence: A wave is a rhythm (frequency) marching through space at a pace (speed). The medium sets the pace; the source sets the rhythm. To keep the rhythm the same while the pace changes, the spacing between steps (wavelength) must adjust. That’s all v = fλ really says—and it’s why the wavelength quadruples when the speed quadruples across a boundary.