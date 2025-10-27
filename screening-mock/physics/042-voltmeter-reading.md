# Question
In the circuit shown, A and V are ideal ammeter and voltmeter respectively. Reading of the voltmeter in V will be:

The diagram shows a simple electrical circuit consisting of a 2V battery, two resistors of 1Ω each, an ideal ammeter labeled A, and a ideal voltmeter labeled V. The resistors are connected in series with the battery, forming a single path for current flow. The ammeter is placed in series to measure the total current flowing through the circuit. The voltmeter is connected in parallel across the ammeter to measure the potential difference across it.

```
   +--[ 2 V cell ]------------------+----+
   |                                 |   |
   |                                 |   |
   |                                (A) (V)
   |                                 |   |
   |                                 |   |
   +--[ 1 Ω ]----[ 1 Ω ]-------------+---+
```

---
# Answer
## Fast visual reasoning
- Picture the ammeter as a perfect, fat, shiny wire segment: it offers no “narrowing,” so charges glide through without any push being used up there.
- The two 1 Ω resistors are the only “rough” parts where the battery’s push is used.
- The voltmeter is just a peek-through window: it sips no current and simply compares the “electric pressure” on both sides of the ammeter.
- Since the ammeter is just a plain wire, the “height” (electric pressure) at its top and bottom is the same. No step, no drop.

Answer: 0 V

## Creative twists
- Seeing current flow and assuming there must be a drop across every element. Wires (ideal ammeter) don’t “eat” any push.
- Thinking the voltmeter in parallel will change the circuit. An ideal voltmeter is like a pressure gauge with an infinitely thin tube—reads, doesn’t disturb.
- Confusing “across the ammeter” with “across the battery.” Only the resistors take the battery’s push; the ammeter doesn’t.
- Replace the ammeter with a closed switch or a plain wire: a voltmeter across it still reads zero. Open the switch: now it would read the full battery.
- Water analogy: gauge across a wide, smooth pipe section shows no pressure drop; only valves or narrow sections (resistors) cause drops.
- Engineering echo: measuring across a thick busbar shows near-zero difference; the drops are across loads, not across ideal connections.

## Start with a picture in your head
Imagine water flowing through a narrow pipe. Two identical narrow sections in series mean the water faces the same “difficulty” twice. The total difficulty (resistance) adds up, and the pressure drop (voltage) is shared between the sections depending on how “narrow” they are.

Now imagine water flowing in a pipe:
- A very wide, perfectly open valve offers no resistance — the pressure drop across it is zero.
- A pressure gauge connected across that valve would read 0 pressure difference, even though water is flowing elsewhere in the loop.

Now swap “water flow” for electric current and “pressure” for voltage. That’s our circuit.

In circuits:
- The “wide open valve” is an ideal ammeter (zero resistance).
- The “pressure gauge” is an ideal voltmeter (measures potential difference without drawing current).

Your circuit puts the voltmeter directly across the ammeter. What should a perfect pressure gauge read across a perfect open valve? Zero.

---

## What “ideal” really means (simple first, then technical)

- Ideal ammeter: like a perfect piece of wire. It has zero resistance, so it doesn’t “use up” any voltage.
  - Technical: its resistance R_A = 0 Ω, so V_A = I × R_A = 0 V.
- Ideal voltmeter: like a pressure probe that doesn’t let any water through.
  - Technical: infinite resistance (no current through it), so it doesn’t disturb the circuit.

---

## Rebuild from fundamentals

### 1) Total resistance and current in the loop
Only the two 1 Ω resistors provide resistance. The ammeter is 0 Ω, the voltmeter draws no current.

```math
R_{\text{total}} = 1\ \Omega + 1\ \Omega = 2\ \Omega
```

Battery = 2 V, so by Ohm’s law:

```math
I = \frac{V}{R} = \frac{2\ \text{V}}{2\ \Omega} = 1\ \text{A}
```

So 1 A flows around the loop.

### 2) Voltage across the ammeter
Voltage drop across any element is V = I × R. For the ammeter:

```math
V_{\text{ammeter}} = I \times 0\ \Omega = 1\ \text{A} \times 0 = 0\ \text{V}
```

### 3) What does the voltmeter read?
The voltmeter is connected across the ammeter, so it measures the same potential difference:

```math
V_{\text{voltmeter}} = V_{\text{ammeter}} = 0\ \text{V}
```

Answer: 0 V.

---

## Multiple lenses

- Intuitive view: Measuring across a perfect wire gives zero voltage — both ends are effectively the same point electrically.
- Analytical view: V = I R. With R = 0, V = 0 regardless of I.
- Experimental view: In the lab, the ammeter would show about 1 A. The voltmeter across it would show 0 V. All the 2 V is dropped across the two 1 Ω resistors (1 V on each, equally).

---

> ### 🧠 Quick Exam Tips
> - Ideal ammeter has zero resistance → zero voltage across it.
> - Ideal voltmeter has infinite resistance → draws no current and doesn’t affect the circuit.
> - Voltmeter reads the potential difference only between its two terminals — not “the battery voltage” unless connected across the battery.

---

## Conceptual follow-ups

- What if the ammeter weren’t ideal? If R_A were small but non-zero, the voltmeter would read V = I × R_A (a small value).
- If the battery were 4 V instead of 2 V, the current would be 2 A, but the voltmeter still reads 0 V across the ideal ammeter.
- If the voltmeter were placed across one 1 Ω resistor, it would read 1 V (half the battery, because the two resistors are equal).

---

## Misconception clinic

- Many students think “the voltmeter shows the battery’s voltage.” But actually, it shows the voltage between its two leads only. Here, both leads sit across a zero-resistance element → 0 V.
- A common mistake is assuming the voltmeter “steals current” and changes the reading. An ideal voltmeter doesn’t draw current; it leaves the circuit behavior unchanged.
- Some think “current must cause some voltage drop everywhere.” Not true — across an ideal conductor (zero resistance), the drop is zero even with current flowing.

---

## Extension challenges

- Real-world: In precision circuits, even tiny wire or meter resistances matter. How would a small ammeter resistance alter current and power dissipation in the resistors?
- Cross-discipline: In fluid flow, a high-flow, low-loss segment has near-zero pressure drop — the same pattern as zero voltage across an ideal conductor.

---

## Interactive practice

1) If the ammeter had 0.5 Ω resistance (not ideal), what would the voltmeter read?
- Total R = 1 + 1 + 0.5 = 2.5 Ω, I = 2/2.5 = 0.8 A, so V across ammeter = 0.8 × 0.5 = 0.4 V.

2) If the voltmeter is moved across both 1 Ω resistors together, what does it read?
- 2 V (the entire battery, since the ammeter is ideal).

3) The two 1 Ω resistors are replaced by one 2 Ω resistor. What changes?
- Nothing essential: I = 2/2 = 1 A; V across ideal ammeter still 0 V.

---

> “Reflective essence”
> Nature loves differences: flow needs a push (voltage/pressure). Where there is no opposition (zero resistance), there is no “push drop.” That’s why an ideal wire has zero voltage across it — no matter how much current flows.