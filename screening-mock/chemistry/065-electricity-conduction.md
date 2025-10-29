# Question
How many of the following conduct electricity through them?
i) Iron
ii) Diamond
iii) Graphite
iv) Mercury
v) Bromine
vi) Iodine
vii) Gallium

---
# Answer

## Quick visual reasoning
Think: Can tiny charges move freely inside?

- Iron (metal): Like a hall with loose marbles on the floor; push one and many roll. Charges can drift. Conducts.
- Diamond (rigid carbon network): Everyone’s hands locked to four neighbors in 3D; no one can slip through. Doesn’t conduct.
- Graphite (layered carbon): Stack of slippery pages; some charges can slide along each page. Conducts along layers.
- Mercury (liquid metal): Same loose marbles, but the hall is a liquid pool; still plenty of free movement. Conducts.
- Bromine (liquid non‑metal molecules): A crowd of tightly paired dancers; pairs move as whole neutral units, no free charges. Doesn’t conduct.
- Iodine (molecular solid): Shiny crystals of paired dancers stuck in place; no loose charges. Doesn’t conduct.
- Gallium (metal): Even if it softens, it’s still a sea of loose charges. Conducts.

Count of conductors: 4.
4 conduct: i) Iron, iii) Graphite, iv) Mercury, vii) Gallium.


## Create twists
- Trap: “Shiny means conductor.” Iodine is shiny but its charges are not free. Shiny ≠ conductive.
- Trap: “Liquid means conductor.” Bromine flows, but neutral molecules carry no charge flow. Liquid ≠ conductive.
- Trap: “Hard means conductor.” Diamond is ultra‑hard yet locks all charges. Hardness ≠ conductive.
- Twist: “Non‑metals don’t conduct.” Graphite is a non‑metal but its layered structure lets charges slide.

Use the idea elsewhere:
- Pencil line as a wire: A dark graphite streak on paper can light a small bulb; a diamond ring can’t.
- Salt vs sugar in water: Salt splits into free-moving charged bits; sugar stays as whole neutral molecules. Only salt solution conducts.
- Mercury tilt switch: A blob of liquid metal rolls to touch two contacts and closes a circuit—proof that a liquid metal conducts.

## Big Idea: What does it mean to “conduct electricity through” a substance?

- Everyday observation: When you connect a metal wire to a battery and a bulb, the bulb lights because electric charge can move through the metal. If you replace the wire with a dry wooden stick, it doesn’t light—charge can’t move through the wood.
- So “conduct electricity through them” means: if you push on charges with a battery (a voltage), do charges actually flow through the material’s bulk?

Two ingredients are needed:
1) Mobile charges inside the material (like free electrons or ions).
2) A pathway that lets those charges drift through the structure without getting stuck.

Let’s formalize “flow of charge” from first principles.

### What is electric current?
Current is just “how much charge passes per second.”

```math
I = \frac{\Delta Q}{\Delta t}
```

If there are mobile charge carriers (say electrons), with number density $n$ (number per cubic meter), each with charge $q$, moving with a slow average drift speed $v_d$ through a wire of cross-sectional area $A$, then in time $\Delta t$ the charges contained in the “slice” of length $v_d \Delta t$ cross the area $A$.

- Volume of that slice: $A\, v_d \Delta t$
- Number of carriers in that slice: $n \, A \, v_d \Delta t$
- Total charge in that slice: $q\, n \, A \, v_d \Delta t$

Divide by time to get current:
```math
I \;=\; \frac{q\, n \, A \, v_d \Delta t}{\Delta t} \;=\; q\, n \, A \, v_d
```

Key insight: If there are no mobile charges ($n \approx 0$), the current is essentially zero: the substance is an insulator. If there are many mobile electrons (typical of metals), current is large: the substance conducts.

So our test becomes: In each substance, are there mobile charges inside the structure that can move when a voltage is applied?

## How bonding controls mobility

- Metals: Atoms share their outer electrons in a “sea” of delocalized electrons. These electrons are already mobile, so $n$ is large. Good conductors.
- Ionic solids (like NaCl): Ions are present but locked in place when solid. They conduct only when molten or dissolved (ions become mobile).
- Covalent network solids (like diamond): Electrons are tightly held in bonds; no free carriers. Insulators.
- Molecular solids and liquids (like iodine or bromine): Neutral molecules with electrons bound in specific bonds; no mobile charges. Insulators.
- Layered covalent like graphite: Within each sheet, some electrons are delocalized over the sheet, so they can move. Conducts well along the layers.

## Evaluate each substance

i) Iron — A metal. Many delocalized electrons are free to move. Conducts.

ii) Diamond — A covalent network: each carbon makes 4 strong bonds in a rigid 3D structure. All valence electrons are locked into bonds; essentially no free carriers. Does not conduct.

iii) Graphite — Also carbon, but arranged in sheets. Each carbon uses only 3 of its 4 valence electrons for bonds; the 4th is delocalized over the sheet. Those delocalized electrons can drift when pushed by a voltage. Conducts (especially along the layers).

iv) Mercury — A metal (unusual because it’s liquid at room temperature). Even as a liquid metal, it still has delocalized electrons. Conducts.

v) Bromine — A molecular liquid (Br2 molecules). Neutral molecules with electrons confined in bonds. No free electrons or ions in the pure element. Does not conduct.

vi) Iodine — A molecular solid (I2 molecules). Same reasoning as bromine. Electrons are localized in molecules; no mobile charges. Does not conduct.

vii) Gallium — A metal (melts just above room temperature). Like other metals, it has delocalized electrons. Conducts in both solid and liquid metal states.

## Final count and answer

- Conductors: Iron, Graphite, Mercury, Gallium → 4
- Non-conductors (in their usual pure forms): Diamond, Bromine, Iodine

Answer: 4

## Quick experimental mindset

- If you had a safe setup, you could test with a battery and bulb: graphite pencil lead completes the circuit (bulb glows faintly), a steel nail works well, gallium metal would work, mercury conducts but is hazardous (never try), bromine and iodine won’t light the bulb, diamond won’t either.

## Subtle points and real-world connections

- Graphite conducts mainly along the planes; across layers it’s worse. Engineers use graphite for electrodes because it tolerates high temperatures and conducts.
- Diamond is an excellent insulator, but if “doped” with a tiny amount of boron, it becomes a p-type semiconductor and can conduct. This shows conduction depends on whether mobile carriers exist—not just on the element itself.
- Mercury was used in old tilt switches because its liquid metal nature completes circuits when tilted.
- Gallium’s low melting point allows safe “liquid metal” circuits in some applications; its alloys (like Galinstan) are used as thermal interface materials.

---

## 1) Conceptual follow-up questions

- If iodine is melted, will it conduct? Why or why not?
- Salt (NaCl) doesn’t conduct when solid, but its molten form does. What changed in terms of mobile charges?
- Graphite and diamond are both carbon. What structural difference creates mobile electrons in one but not the other?
- If diamond is doped with boron (one fewer valence electron), what kind of charge carriers are introduced, and how does that enable current?

## 2) Application questions

- Why are power lines made from metals like aluminum or copper rather than graphite, even though graphite conducts?
- Why are graphite electrodes used in high-temperature electrolysis rather than metal electrodes?
- How could a thin film of liquid gallium be used in a flexible electronic connection?
- Mercury is a great conductor. Why is it no longer used in household switches and thermometers?

## 3) Common misconceptions and reasoning traps

- “Any liquid conducts electricity.” False. Liquids conduct only if they have mobile ions or electrons. Bromine is a liquid but doesn’t conduct.
- “All shiny substances conduct.” Not always. Many shiny insulators exist (e.g., some crystals). Shine relates to light reflection, not mobile charges.
- “If two substances are made of the same element, they must conduct similarly.” False. Diamond vs. graphite shows structure controls conduction.
- “Conductivity equals magnetism.” No—iron is magnetic and conducts, but copper conducts and is not strongly magnetic. They’re different properties.

## 4) Extension challenges

- Design a decision tree to predict conductivity of a substance from its bonding type and state (solid/liquid/gas).
- Measure the resistance of a pencil line on paper using a battery and a small bulb or multimeter; compare with a strip of aluminum foil. Explain differences using the idea of carrier density and geometry.
- Research how doping changes carrier density $n$ in semiconductors and sketch how that would change the current $I = q n A v_d$ for the same voltage.
- Explore anisotropy: Why does graphite conduct better along the sheet than across it? How could engineers exploit this?

## 5) Reflective insight: the essence

Electric conduction is not about being a metal or a liquid by name—it’s about whether charges inside the material are free to move when pushed. The microscopic structure (bonding and electron arrangement) decides if there are mobile carriers. If $n$ (mobile carriers per volume) is large, current can flow; if $n \approx 0$, it cannot. Understand the carriers and the pathways, and you can confidently predict conductivity for familiar and unfamiliar materials alike.