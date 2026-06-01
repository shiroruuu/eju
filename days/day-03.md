# Day 3: Basic Trigonometry | ATP & Photosynthesis | Chemical Equations & Stoichiometry

---

# MATHEMATICS — Figures and Measurements (Basic Trigonometry)

## Part 1: Trigonometric Ratios

For a right-angled triangle with angle θ (not the right angle):

```
          /|
         / |
   hyp  /  | opp (opposite to θ)
       /   |
      / θ  |
     /_____|
       adj (adjacent to θ)
```

[FORMULA]
```
sin θ = opposite / hypotenuse
cos θ = adjacent / hypotenuse
tan θ = opposite / adjacent = sin θ / cos θ
```

**Key exact values — MEMORIZE:**

| θ | 0° | 30° | 45° | 60° | 90° |
|---|-----|------|------|------|------|
| sin θ | 0 | 1/2 | √2/2 | √3/2 | 1 |
| cos θ | 1 | √3/2 | √2/2 | 1/2 | 0 |
| tan θ | 0 | 1/√3 | 1 | √3 | undefined |

[TIP] Memory trick for sin: √0/2, √1/2, √2/2, √3/2, √4/2 = 0, 1/2, √2/2, √3/2, 1

---

### 1.2 Relations Between Trigonometric Ratios

[FORMULA — Fundamental identity]
```
sin²θ + cos²θ = 1
tan θ = sin θ / cos θ
1 + tan²θ = 1/cos²θ
```

[EXAMPLE] If sin θ = 3/5 and θ is in 1st quadrant (0° < θ < 90°), find cos θ and tan θ.
```
cos²θ = 1 - sin²θ = 1 - 9/25 = 16/25
cos θ = 4/5   (positive in 1st quadrant)
tan θ = sin θ / cos θ = (3/5)/(4/5) = 3/4
```

[PRACTICE] If tan θ = 2, find sin²θ.

[ANSWER] 1 + tan²θ = 1/cos²θ → cos²θ = 1/5 → sin²θ = 1 - 1/5 = **4/5**

---

## Part 2: Law of Sines and Law of Cosines

These apply to ANY triangle (not just right-angled).

Label: sides a, b, c opposite to angles A, B, C.

### 2.1 Law of Sines

[FORMULA]
```
a/sin A = b/sin B = c/sin C = 2R
```
where R = circumradius (radius of circumscribed circle)

**Use when:** You know an angle and the opposite side, plus one more piece of information.

[EXAMPLE] In △ABC: A = 30°, a = 5, B = 70°. Find b.
C = 180° - 30° - 70° = 80°
b/sin 70° = 5/sin 30° = 5/(0.5) = 10
b = 10 sin 70° ≈ 9.40

---

### 2.2 Law of Cosines

[FORMULA]
```
a² = b² + c² - 2bc·cos A
b² = a² + c² - 2ac·cos B
c² = a² + b² - 2ab·cos C
```

Also written as:
```
cos A = (b² + c² - a²) / (2bc)
```

**Use when:** You know two sides and the included angle (SAS), or all three sides (SSS).

[EXAMPLE] b=5, c=7, A=60°. Find a.
```
a² = 25 + 49 - 2(5)(7)(0.5)
a² = 74 - 35 = 39
a = √39
```

[PRACTICE] Find the largest angle of a triangle with sides 3, 5, 7.

[ANSWER] Largest angle is opposite the longest side (7).
cos C = (9 + 25 - 49)/(2·3·5) = -15/30 = -1/2
C = 120°

---

### 2.3 Area of a Triangle

[FORMULA]
```
Area = (1/2)ab·sin C = (1/2)bc·sin A = (1/2)ac·sin B
```

[EXAMPLE] a=6, b=8, C=30°. Area = (1/2)(6)(8)(1/2) = 12

**Heron's Formula (all three sides known):**
```
s = (a + b + c)/2
Area = √(s(s-a)(s-b)(s-c))
```

---

# BIOLOGY — ATP, Metabolism, and Photosynthesis

## Part 1: Metabolism and Energy

### 1.1 Anabolism and Catabolism

**Metabolism** = all chemical reactions in a living cell.

| Type | Direction | Energy | Example |
|------|-----------|--------|---------|
| **Anabolism** | Small → large | Uses energy | Protein synthesis, photosynthesis |
| **Catabolism** | Large → small | Releases energy | Cellular respiration, digestion |

---

### 1.2 ATP — The Energy Currency

**ATP** (adenosine triphosphate) is how cells store and transfer energy.

```
Adenosine — Phosphate ~ Phosphate ~ Phosphate
                                  ↑
                           High-energy bonds (~)
```

[KEY FACT]
- ATP → ADP + Pᵢ releases energy (~30 kJ/mol)
- ADP + Pᵢ + energy → ATP stores energy
- This cycle is continuous — you synthesize ~40 kg of ATP per day!

**Where is ATP made?**
- Cellular respiration (mitochondria) — main source
- Photosynthesis (chloroplasts) — in plants
- Fermentation (cytoplasm) — anaerobic backup

---

## Part 2: Photosynthesis

### 2.1 Overview

**Overall equation:**
[FORMULA]
```
6CO₂ + 12H₂O → C₆H₁₂O₆ + 6O₂ + 6H₂O
(simplified: 6CO₂ + 6H₂O → C₆H₁₂O₆ + 6O₂)
```

Carbon dioxide + water + light energy → glucose + oxygen

Photosynthesis occurs in **chloroplasts**.

---

### 2.2 Chloroplast Structure

```
Outer membrane
Inner membrane
Stroma (fluid inside)
Granum (stacks of thylakoids)
Thylakoid membrane (contains chlorophyll)
```

| Part | Function |
|------|----------|
| **Thylakoid membrane** | Light reactions (captures light, makes ATP & NADPH) |
| **Stroma** | Calvin cycle (carbon fixation, makes glucose) |

---

### 2.3 Photosynthetic Pigments

**Chlorophyll a** — main pigment, absorbs red and blue-violet light, reflects green.
**Chlorophyll b** — accessory pigment.
**Carotenoids** (yellow/orange) — accessory pigments, broaden the range of light absorbed.

[KEY FACT] Chlorophyll absorbs **red** (~680 nm) and **blue-violet** (~430 nm) light best. It **reflects green** — that's why plants look green.

---

### 2.4 Light Reactions (Thylakoid Membrane)

Also called the "light-dependent reactions."

**What happens:**
1. Light hits chlorophyll → excites electrons
2. Water is split: **H₂O → 2H⁺ + 2e⁻ + ½O₂** (this releases O₂!)
3. Excited electrons pass through electron transport chain
4. ATP is made (by ATP synthase using proton gradient) — **photophosphorylation**
5. NADP⁺ + 2H⁺ + 2e⁻ → **NADPH**

**Products of light reactions:** ATP, NADPH, O₂ (released as waste)

---

### 2.5 Calvin Cycle (Dark Reactions / Light-Independent Reactions)

Occurs in the **stroma**. Uses the ATP and NADPH from light reactions.

Three stages:
1. **Carbon fixation:** CO₂ + RuBP (5C) → 2× 3-PGA (3C) [enzyme: RuBisCO]
2. **Reduction:** 3-PGA + ATP + NADPH → G3P (glyceraldehyde-3-phosphate)
3. **RuBP regeneration:** G3P + ATP → RuBP (cycle continues)

**Net output:** 1 G3P (which is used to make glucose and other organic molecules)

[KEY FACT] For every 3 CO₂ fixed, you get 1 G3P net output. To make 1 glucose, you need 6 CO₂.

---

### 2.6 Bacterial Photosynthesis

Some bacteria (e.g., purple bacteria, green sulfur bacteria) can photosynthesize WITHOUT producing oxygen. They use H₂S instead of H₂O as electron donor:

```
CO₂ + 2H₂S → (CH₂O) + 2S   (no O₂ produced!)
```

**Cyanobacteria** are special — they DO produce O₂ (like plants). They were the first organisms to make oxygen on Earth.

---

# CHEMISTRY — Chemical Equations and Stoichiometry

## Part 1: Chemical Equations

### 1.1 Writing and Balancing Equations

A chemical equation shows reactants → products.

**Rules:**
1. Write correct formulas for all reactants and products
2. Balance atoms on both sides (but NEVER change subscripts!)
3. Balance by adjusting **coefficients**

[EXAMPLE] Balance: H₂ + O₂ → H₂O
- O unbalanced: H₂ + O₂ → 2H₂O
- Now H unbalanced: 2H₂ + O₂ → 2H₂O ✓

[EXAMPLE] Balance: Fe + HCl → FeCl₂ + H₂
Fe: 1=1 ✓; H: 1≠2; Cl: 1≠2
Fe + 2HCl → FeCl₂ + H₂ ✓

**State symbols:**
- (s) = solid, (l) = liquid, (g) = gas, (aq) = dissolved in water

---

## Part 2: Stoichiometry

**Stoichiometry** = quantitative relationships in a chemical reaction.

The **coefficients** in a balanced equation give the mole ratios.

### 2.1 Mole-to-Mole Calculations

[EXAMPLE] How many moles of O₂ are needed to burn 4 mol of C?
```
C + O₂ → CO₂
1 mol C needs 1 mol O₂
4 mol C needs 4 mol O₂
```

[EXAMPLE] 2H₂ + O₂ → 2H₂O
How many moles of H₂O are produced from 5 mol O₂?
```
1 mol O₂ → 2 mol H₂O
5 mol O₂ → 10 mol H₂O
```

### 2.2 Mass-to-Mass Calculations

**Steps:**
1. Convert mass to moles (n = m/M)
2. Use mole ratio from equation
3. Convert moles back to mass (m = n × M)

[EXAMPLE] How many grams of CO₂ are produced by burning 24 g of carbon?
```
C + O₂ → CO₂
Step 1: n(C) = 24/12 = 2 mol
Step 2: 1 mol C → 1 mol CO₂, so 2 mol C → 2 mol CO₂
Step 3: m(CO₂) = 2 × 44 = 88 g
```

[PRACTICE] How many grams of H₂O are produced by burning 4 g of H₂?
(2H₂ + O₂ → 2H₂O; M(H₂)=2, M(H₂O)=18)

[ANSWER] n(H₂) = 4/2 = 2 mol; 2 mol H₂ → 2 mol H₂O; m = 2×18 = **36 g**

---

## Part 3: Acids and Bases (Introduction)

### 3.1 Definitions

**Arrhenius:** Acids produce H⁺ in water; Bases produce OH⁻.

**Brønsted-Lowry (more general):**
- **Acid** = proton (H⁺) donor
- **Base** = proton (H⁺) acceptor

[EXAMPLE] HCl + H₂O → H₃O⁺ + Cl⁻
HCl donates H⁺ → HCl is the acid
H₂O accepts H⁺ → H₂O is the base

### 3.2 Strong and Weak Acids/Bases

**Strong acids** (fully ionize in water):
HCl, HBr, HI, H₂SO₄, HNO₃, HClO₄

**Strong bases** (fully ionize):
NaOH, KOH, Ca(OH)₂, Ba(OH)₂

**Weak acids** (partially ionize):
CH₃COOH (acetic acid), HF, H₂CO₃, H₂SO₃

**Weak bases:**
NH₃ (ammonia), organic amines

[KEY FACT] For **strong** acids: [H⁺] = c × valence
For HCl (0.1 mol/L): [H⁺] = 0.1 mol/L
For H₂SO₄ (0.1 mol/L): [H⁺] = 0.2 mol/L (diprotic)

### 3.3 pH Scale

[FORMULA]
```
pH = -log₁₀[H⁺]
[H⁺] = 10⁻ᵖᴴ

At 25°C: Kw = [H⁺][OH⁻] = 1×10⁻¹⁴
Neutral: [H⁺] = 10⁻⁷ mol/L → pH = 7
Acidic: pH < 7
Basic: pH > 7
```

[EXAMPLE] 0.01 mol/L HCl (strong acid):
[H⁺] = 0.01 = 10⁻² mol/L
pH = -log(10⁻²) = **2**

[EXAMPLE] 0.1 mol/L NaOH:
[OH⁻] = 0.1 = 10⁻¹
[H⁺] = Kw/[OH⁻] = 10⁻¹⁴/10⁻¹ = 10⁻¹³
pH = 13

[PRACTICE] What is the pH of 0.001 mol/L HNO₃?

[ANSWER] [H⁺] = 10⁻³; pH = **3**

---

## Day 3 Summary — Key Points

**Math:**
- sin/cos/tan for right triangles; exact values at 30°, 45°, 60°
- sin²θ + cos²θ = 1; tan θ = sin θ/cos θ
- Law of Sines: a/sin A = 2R
- Law of Cosines: a² = b² + c² - 2bc cos A
- Triangle area = ½ab sin C

**Biology:**
- ATP = energy currency; ATP → ADP + Pᵢ releases ~30 kJ/mol
- Photosynthesis: 6CO₂ + 6H₂O → C₆H₁₂O₆ + 6O₂ (light needed)
- Light reactions (thylakoid): split water, make ATP + NADPH, release O₂
- Calvin cycle (stroma): CO₂ fixation by RuBisCO, makes G3P using ATP + NADPH
- Bacterial photosynthesis: uses H₂S, no O₂ released

**Chemistry:**
- Balance equations by adjusting coefficients (not subscripts)
- Stoichiometry: convert mass → moles → use ratio → back to mass
- Strong acids/bases fully ionize; weak ones partially ionize
- pH = -log[H⁺]; Kw = [H⁺][OH⁻] = 10⁻¹⁴ at 25°C
