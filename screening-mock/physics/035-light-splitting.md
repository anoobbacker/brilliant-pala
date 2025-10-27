# Question
Splitting of light into its colours is called:—  
1) Dispersion  
2) Scattering  
3) Refraction  
4) Reflection

---
# Answer
## Quick visual reasoning
- Imagine a white torch beam entering a glass prism. Inside, the colors don’t stay stacked together; they fan out into a neat rainbow strip. That neat spreading into separate colors is the key action.
- Which word matches “a single beam separating into its colors”?
  - Reflection: like a mirror—beam bounces, stays white.
  - Refraction: beam bends when entering/leaving glass, but can still stay white.
  - Scattering: tiny particles toss light in many random directions (sky looks blue), not an ordered rainbow.
  - Dispersion: colors split apart because each color takes a slightly different path—exactly the prism rainbow.

Answer: 1) Dispersion

## Creative twists
- Mixing up refraction and dispersion: If it just bends as one piece, it’s refraction. If it spreads into colors, it’s dispersion.
- Thinking rainbows are “reflection”: raindrops do reflect light inside, but the color separation that creates the rainbow arc is due to dispersion.
- Confusing scattering with rainbows: scattering gives hazy, direction-mixed light (blue sky), not a clean spectrum band.
- Spectroscopes use prisms to “unwrap” white light into a color barcode to identify materials—pure dispersion at work.
- Camera lenses fight unwanted dispersion (color fringes) by pairing glasses so separated colors recombine sharply.
- Nature’s rainbow: sunlight enters a raindrop, colors separate (dispersion), then reflect and exit—ordered color spread you can see.

## Start with a real-world picture

Why does a glass prism or a raindrop turn white sunlight into a rainbow, while a mirror just gives you a plain reflection of the whole beam?

Because the prism doesn’t just bend light — it bends each color by a slightly different amount and separates them. That splitting into colors has a special name.

Answer: 1) Dispersion

## Build it from first principles

### Step 1: What is “white light”?
- White light is a mix of many colors (red, orange, yellow, green, blue, indigo, violet).
- In physics language: it contains many wavelengths. Red has a longer wavelength; violet has a shorter one.

### Step 2: What does glass do to light?
- Light travels slower in glass than in air. How much slower is described by the refractive index n.
- Key idea: For real materials, n depends slightly on wavelength. This is the “color sensitivity” of the material.

We can capture both points with:
```math
v(\lambda) = \frac{c}{n(\lambda)}
```
- v(λ) is the speed of that color in the medium.
- c is the speed of light in vacuum.
- n(λ) changes with color (λ). In ordinary glass, violet has a larger n than red. So violet slows more.

### Step 3: How do we get bending and splitting?
When light enters glass at an angle, it refracts (bends). The bending obeys Snell’s law:
```math
n_1 \sin i = n_2(\lambda) \sin r(\lambda)
```
- n1 = refractive index of air (≈1), i = angle of incidence
- n2(λ) = refractive index of glass which depends on λ (color)
- r(λ) = refracted angle that now depends on color

Because n2 is different for red vs violet, r is also different. That means the colors fan out instead of staying together. This phenomenon — splitting of white light into its component colors due to wavelength-dependent refraction — is called dispersion.

Intuition chain:
- Different colors → different speeds in glass → different bending angles → fan out → spectrum

---

## Why the other options are not correct

- Reflection: bouncing off a surface. A mirror reflects the whole beam; it doesn’t separate colors.
- Refraction: bending when light enters a different medium. Needed for dispersion, but refraction alone doesn’t imply splitting unless n depends on wavelength.
- Scattering: light gets redirected by small particles (example: sky looks blue). That’s not orderly splitting into a spectrum.

So the precise term for “splitting into colors” is dispersion.

---

## Visual aid (described)
Imagine a triangular glass prism. A white beam enters from the left. Inside the prism, the beam spreads into a fan: the top ray (red) bends a little; the bottom ray (violet) bends more. Exiting the prism, the rays separate further, making a rainbow-like stripe on a screen.

---

> ### 🧠 Quick Exam Tips
> - Splitting of white light into its colors: Dispersion.
> - Refraction bends; dispersion splits (because bending is slightly different for each color).
> - In glass: Violet bends most, red bends least.
> - Sky blue? That’s scattering, not dispersion.

---

## Conceptual follow-ups

- What if we used a monochromatic (single-color) green laser on a prism? No splitting — there’s only one wavelength.
- What if the material had the same n for all wavelengths? Refraction would happen, but no dispersion; all colors would bend by the same amount and stay together.
- Why do rainbows happen? Sunlight enters raindrops and undergoes refraction + dispersion + internal reflection. The dispersion part creates color separation.

---

## Experimental view

- Shine white light through a prism onto a white screen: you’ll see a spectrum strip.
- Try different materials: crown glass vs flint glass. Flint glass has stronger dispersion (bigger color spread).

---

## Misconception clinic

- Many students think “refraction” = “splitting.” But refraction just means bending. Splitting only occurs when the bending depends on wavelength — that’s dispersion.
- A common mistake is assuming red bends more because it looks “stronger.” Actually, in most common glasses (normal dispersion), violet (shorter wavelength) bends more than red.
- Some confuse dispersion with scattering because both produce colors. Scattering (e.g., blue sky) is random redirection by tiny particles; dispersion is orderly splitting by wavelength-dependent refraction.

---

## Extension connections

- Lenses suffer from chromatic aberration (colors focus at different points) due to dispersion. Camera lenses use combinations of glasses to reduce this.
- CDs/DVDs make rainbows too, but that’s from diffraction and interference (a different mechanism, not dispersion).

---

## Practice questions

1) A mirror makes a white beam bounce without color separation. Which phenomenon?
A. Reflection  B. Refraction  C. Dispersion  D. Scattering
Answer: A

2) A green laser passes through a prism. What do you see?
A. A rainbow spectrum
B. A single green beam, bent
C. No bending at all
D. A blue beam and a red beam
Answer: B

3) The blue color of the sky is mainly due to:
A. Reflection  B. Refraction  C. Dispersion  D. Scattering
Answer: D

4) In ordinary glass, which color is deviated the most by a prism?
A. Red  B. Yellow  C. Green  D. Violet
Answer: D

---

> “Reflective essence”
> Nature often separates mixtures by how strongly each component responds to a medium. In optics, different wavelengths “feel” the material differently, so light self-sorts by color. Understanding the cause (wavelength-dependent response) is more powerful than memorizing the label (dispersion).