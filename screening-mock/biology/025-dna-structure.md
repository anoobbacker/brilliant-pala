## Question
Statements about DNA structure:

(i) DNA has a double helix structure.

(ii) The bases are Adenine, Thymine, Guanine, and Cytosine.

(iii) Adenine pairs with Guanine.

(iv) Sugar in DNA is deoxyribose.

How many statements are wrong?

## DNA structure — which statements are wrong?

Answer: 1 statement is wrong — only statement (iii).

- (i) True: DNA is a double helix.
- (ii) True: The bases are Adenine (A), Thymine (T), Guanine (G), Cytosine (C).
- (iii) False: Adenine pairs with Thymine, not Guanine.
- (iv) True: The sugar in DNA is deoxyribose.

---

## Deriving this from first principles (no memorized shortcuts)

### 1) Start with a familiar picture: a zip and a ladder
- Imagine a zip: two long strips with teeth that interlock exactly. If the teeth shapes don’t match, the zip won’t close.
- DNA behaves like a “chemical zip.” Its “teeth” are bases that must match precisely to store and copy information reliably.

Now let’s build that “zip” step by step.

### 2) What is DNA made of? Three-piece building blocks
Each unit of DNA (a nucleotide) has:
- A sugar (in DNA, it’s deoxyribose)
- A phosphate group
- A base (A, T, G, or C)

Cause-effect logic:
- Sugars link to phosphates to make a strong, repeating “backbone” (like the sides of a ladder). This makes the outside sturdy and water-friendly.
- Bases stick out like “rungs” and are relatively water-avoiding (hydrophobic), so they prefer to hide inside, pairing with a partner base from the other strand.

Why deoxyribose, not ribose?
- Ribose has an extra -OH at the 2' position; deoxyribose has H there (hence “deoxy”). That missing -OH makes DNA less reactive and more stable for long-term information storage. In RNA, the 2'-OH can attack the backbone, making RNA less stable—fine for temporary messages, not for long-term archives.

### 3) Why a double helix (not just two straight strands)?
- Two strands align in opposite directions (antiparallel) and the bases pair inside, away from water.
- The stacked bases twist, like a spiral staircase, because twisting maximizes stabilizing interactions between flat base “plates” (stacking) while keeping the outside backbone nicely exposed to water.
- Experiments (X-ray diffraction patterns by Rosalind Franklin) showed regular repeating distances consistent with a helix. The pattern implies constant spacing:
  - Distance between stacked base pairs ≈ 0.34 nm
  - One full turn ≈ 10 base pairs ≈ 3.4 nm
  - Helix diameter ≈ 2.0 nm

These numbers aren’t just trivia—they constrain how bases can pair.

### 4) Which bases can pair? Let geometry and bonding decide
Bases come in two sizes:
- Purines: A, G (two rings; larger)
- Pyrimidines: T, C (one ring; smaller)

To keep the helix width constant at ~2.0 nm (so the zip teeth line up perfectly), each rung must be:
- One purine + one pyrimidine
- Because purine + purine would be too wide; pyrimidine + pyrimidine too narrow.

But which specific purine pairs with which pyrimidine? The answer depends on hydrogen-bond matching: donors and acceptors must line up.

- A and T line up to form two hydrogen bonds with proper geometry.
- G and C line up to form three hydrogen bonds with proper geometry.
- A with G (purine–purine) is too wide and their donor/acceptor patterns clash.
- T with C (pyrimidine–pyrimidine) is too narrow and misaligned.

So only A–T and G–C maintain both the right width and the right bonding geometry.

Experimental cross-check (nature’s audit):
```math
[A] \approx [T], \quad [G] \approx [C]
```
These are Chargaff’s rules, measured across many species. If A paired with G, we’d expect [A] ≈ [G], which is not observed.

Therefore, statement (iii) “Adenine pairs with Guanine” is wrong.

### 5) Evaluating each statement with our reasoning
- (i) Double helix: Yes—driven by base stacking, hydration, and X-ray evidence.
- (ii) Four bases A, T, G, C: Yes—those are the DNA bases.
- (iii) A pairs with G: No—A pairs with T; G pairs with C, dictated by size and hydrogen-bond geometry.
- (iv) Sugar is deoxyribose: Yes—explains DNA’s stability for long-term storage.

---

## Quick summary answer
Only one statement is wrong: (iii).

---

## Conceptual follow-up questions
1. If DNA had T–C pairing sometimes, what measured property of DNA (diameter, X-ray pattern, or base ratios) would immediately look “wrong,” and why?
2. Why would a purine–purine pair distort the helix more than a purine–pyrimidine pair?
3. If you heat DNA, which sequence melts first: AT-rich or GC-rich? Explain using hydrogen bonds and stacking.
4. If RNA replaces T with U (uracil), why does base pairing still work with A, and what stability trade-offs appear?

## Application questions
- How does base complementarity enable PCR and DNA sequencing technologies?
- Why do organisms in hot environments often have higher GC content in certain genomic regions?
- How does CRISPR rely on base pairing to find its target?

## Common misconceptions and how to avoid them
- “Any base can pair with any base.” Correction: Geometry and width constraints force purine–pyrimidine pairing; donor/acceptor patterns enforce A–T and G–C only.
- “Hydrogen bonds are the main reason DNA is stable.” Partial truth: hydrogen bonds specify pairing, but overall stability also heavily depends on base stacking and the hydrophilic backbone facing water.
- “DNA and RNA sugars are basically the same.” The missing 2'-OH in DNA greatly reduces backbone self-attack, making DNA far more stable for storage.

## Extension challenges
- Design a hypothetical “DNA-like” molecule with a different set of bases. What constraints must your new pairs satisfy to keep helix width constant and maintain specific pairing?
- Predict how introducing a base analog that pairs weakly with A would affect mutation rates and melting temperatures.
- Use Chargaff’s rules to estimate the fraction of each base given the GC content of a genome.

## Reflective insight — the deep “why”
DNA’s structure is a solution to a problem: how to store, copy, and protect information reliably in a watery, noisy world. The double helix places a strong, water-friendly backbone outside and hides the information-carrying bases inside. Purine–pyrimidine pairing with precise hydrogen-bond geometry keeps the width constant so strands zip up cleanly and can be copied accurately. Deoxyribose makes the archive chemically stable. The logic of form follows the function of faithful information storage—once you see that, the correct pairings and components stop being facts to memorize and start being features you can reason out.