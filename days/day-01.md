# Day 1: Numbers & Algebra | Cell Structure | Atoms & Periodic Table

---

# MATHEMATICS — Numbers, Expressions, Sets, and Propositions

## Part 1: Calculation of Expressions

### 1.1 Polynomials — Addition, Subtraction, Multiplication

A **polynomial** is an expression with variables and coefficients, like `3x² + 2x - 5`.

**Addition/Subtraction:** Collect **like terms** (same variable, same exponent).

[EXAMPLE]
```
(3x² + 2x - 1) + (x² - 5x + 4)
= (3+1)x² + (2-5)x + (-1+4)
= 4x² - 3x + 3
```

**Multiplication:** Use distributive law. Every term in the first bracket multiplies every term in the second.

**Key expansion formulas — MEMORIZE these:**

[FORMULA]
```
(a + b)² = a² + 2ab + b²
(a - b)² = a² - 2ab + b²
(a + b)(a - b) = a² - b²
(a + b)(a² - ab + b²) = a³ + b³
(a - b)(a² + ab + b²) = a³ - b³
(a + b + c)² = a² + b² + c² + 2ab + 2bc + 2ca
```

[EXAMPLE]
```
(2x + 3)(x - 4)
= 2x·x + 2x·(-4) + 3·x + 3·(-4)
= 2x² - 8x + 3x - 12
= 2x² - 5x - 12
```

[PRACTICE] Expand: (3x - 2)²

[ANSWER] 9x² - 12x + 4  (use (a-b)² = a² - 2ab + b², a=3x, b=2)

---

### 1.2 Factorization

Factorization is the **reverse** of expansion. You turn a sum into a product.

**Common factorization patterns:**

[FORMULA]
```
a² + 2ab + b² = (a + b)²
a² - 2ab + b² = (a - b)²
a² - b² = (a + b)(a - b)
x² + (a+b)x + ab = (x + a)(x + b)
acx² + (ad+bc)x + bd = (ax + b)(cx + d)
a³ + b³ = (a + b)(a² - ab + b²)
a³ - b³ = (a - b)(a² + ab + b²)
```

[EXAMPLE] Factorize: x² + 5x + 6
Find two numbers that multiply to 6 and add to 5 → 2 and 3.
Answer: (x + 2)(x + 3)

[EXAMPLE] Factorize: 6x² + 7x - 3
Use the cross-multiplication method (試行錯誤):
Try (2x + 3)(3x - 1) = 6x² - 2x + 9x - 3 = 6x² + 7x - 3 ✓

[PRACTICE] Factorize: x² - 9

[ANSWER] (x + 3)(x - 3)  — difference of squares

---

## Part 2: Real Numbers

### 2.1 Types of Real Numbers

```
Real Numbers
├── Rational Numbers (can be written as p/q)
│   ├── Integers (...-2, -1, 0, 1, 2...)
│   │   ├── Negative integers
│   │   ├── Zero
│   │   └── Natural numbers (positive integers)
│   └── Fractions (1/2, 3/4, ...)
└── Irrational Numbers (cannot be p/q)
    Examples: √2, √3, π, e
```

[KEY FACT] √2 = 1.41421356... — it never terminates or repeats.

### 2.2 Calculation with Square Roots

[FORMULA]
```
√(a·b) = √a · √b      (a ≥ 0, b ≥ 0)
√(a/b) = √a / √b      (a ≥ 0, b > 0)
(√a)² = a
√(a²) = |a|
```

**Rationalizing the denominator** — never leave √ in the denominator in your final answer.

[EXAMPLE]
```
1/√2 = 1/√2 × √2/√2 = √2/2
```

[EXAMPLE] Simplify: (√3 + 1)(√3 - 2)
```
= (√3)² - 2√3 + √3 - 2
= 3 - √3 - 2
= 1 - √3
```

[PRACTICE] Simplify: (2 + √5)(2 - √5)

[ANSWER] 4 - 5 = -1   (use (a+b)(a-b) = a² - b², a=2, b=√5)

---

## Part 3: Linear Inequalities and Absolute Values

### 3.1 Absolute Value

**|x| = distance from 0 on the number line.**

```
|x| = x   if x ≥ 0
|x| = -x  if x < 0

So |x| = 3 means x = 3 or x = -3
And |x| < 3 means -3 < x < 3
And |x| > 3 means x < -3 or x > 3
```

[FORMULA]
```
|x| = a  (a > 0) → x = a or x = -a
|x| < a  (a > 0) → -a < x < a
|x| > a  (a > 0) → x < -a or x > a
```

[EXAMPLE] Solve: |2x - 1| < 5
```
-5 < 2x - 1 < 5
-4 < 2x < 6
-2 < x < 3
```

[PRACTICE] Solve: |x + 3| ≥ 2

[ANSWER] x ≥ -1 or x ≤ -5

---

## Part 4: Sets and Propositions

### 4.1 Sets

A **set** is a collection of distinct objects (called **elements**).

**Notation:**
- A = {1, 2, 3} — listing elements
- A = {x | x is an even number} — describing elements
- x ∈ A means "x is in A"
- x ∉ A means "x is not in A"
- ∅ = empty set (no elements)

**Special sets:**
- **Subset:** A ⊆ B means every element of A is in B
- **Union:** A ∪ B = all elements in A OR B (or both)
- **Intersection:** A ∩ B = elements in BOTH A and B
- **Complement:** Aᶜ = everything NOT in A (relative to universal set U)

[FORMULA — De Morgan's Laws]
```
(A ∪ B)ᶜ = Aᶜ ∩ Bᶜ
(A ∩ B)ᶜ = Aᶜ ∪ Bᶜ
```

[EXAMPLE] U = {1,2,3,4,5}, A = {1,2,3}, B = {2,3,4}
- A ∪ B = {1,2,3,4}
- A ∩ B = {2,3}
- Aᶜ = {4,5}

**Number of elements in a set:**
[FORMULA]
```
n(A ∪ B) = n(A) + n(B) - n(A ∩ B)
```
This prevents double-counting elements in both sets.

[EXAMPLE] 30 students: 18 like Math, 15 like Bio, 8 like both. How many like at least one?
n(M ∪ B) = 18 + 15 - 8 = 25 students

---

### 4.2 Propositions and Conditions

A **proposition** is a statement that is either TRUE or FALSE.

**"p → q" means "if p, then q"**
- p is the **hypothesis** (condition)
- q is the **conclusion**

**Contrapositive:** "not q → not p" — This is ALWAYS logically equivalent to "p → q"

[KEY FACT] To prove "p → q", you can instead prove "not q → not p". They are the same!

**Converse:** "q → p" — NOT the same as the original!
**Inverse:** "not p → not q" — NOT the same as the original!

| Statement | Form | Equivalent to |
|-----------|------|---------------|
| Original | p → q | contrapositive |
| Converse | q → p | inverse |
| Inverse | ¬p → ¬q | converse |
| Contrapositive | ¬q → ¬p | original |

**Necessary and Sufficient Conditions:**
- p is a **sufficient** condition for q if: p → q (p guarantees q)
- p is a **necessary** condition for q if: q → p (q requires p)
- p is **necessary and sufficient** (p ↔ q) when both directions hold

[EXAMPLE]
"x = 2" is sufficient for "x² = 4" (if x=2, then x²=4 ✓)
"x = 2" is NOT necessary (x could be -2 and x²=4 still holds)

---

# BIOLOGY — Cell Structure and Biomolecules

## Part 1: Substances That Compose Cells

All living things are made of **cells**. Every cell is made from a small set of key chemical building blocks.

### 1.1 Major Biomolecules

| Molecule | Elements | Examples | Function |
|----------|----------|---------|---------|
| Carbohydrates | C, H, O | Glucose (C₆H₁₂O₆), starch | Energy, structure |
| Proteins | C, H, O, N, S | Enzymes, hemoglobin | Catalysis, structure, transport |
| Lipids | C, H, O | Fats, phospholipids | Energy storage, membrane |
| Nucleic Acids | C, H, O, N, P | DNA, RNA | Genetic info |
| Water | H, O | — | Solvent, reactions |

[KEY FACT] The most abundant compound in cells is **water** (~70%). The most abundant organic compound is **protein**.

### 1.2 Water and Its Importance

- Water is a **polar molecule** (partial + on H, partial - on O)
- Forms **hydrogen bonds** between molecules → high boiling point, high surface tension
- Excellent **solvent** (dissolves ionic and polar substances)
- Participates directly in chemical reactions (hydrolysis, condensation)

---

## Part 2: Cell Structure

### 2.1 Prokaryotic vs. Eukaryotic Cells

| Feature | Prokaryotic | Eukaryotic |
|---------|-------------|------------|
| Nucleus | No (DNA is free) | Yes (membrane-bound) |
| Size | 1–10 μm (small) | 10–100 μm (larger) |
| Organelles | None (ribosomes only) | Many types |
| Examples | Bacteria, archaea | Animals, plants, fungi, protists |

[KEY FACT] Prokaryotes evolved FIRST on Earth (~3.8 billion years ago). Eukaryotes came later (~2 billion years ago).

---

### 2.2 Eukaryotic Cell Organelles

Learn these organelles, their structure, and their function:

| Organelle | Structure | Function |
|-----------|-----------|----------|
| **Nucleus** | Double membrane (nuclear envelope), contains DNA | Controls cell activity; stores genetic info |
| **Mitochondria** | Double membrane; inner membrane folded into **cristae** | **Aerobic respiration** → produces ATP |
| **Chloroplast** | Double membrane + thylakoids + stroma; contains chlorophyll | **Photosynthesis** → converts light to sugar |
| **Ribosome** | rRNA + protein; no membrane | **Protein synthesis** (translation) |
| **Endoplasmic Reticulum (ER)** | Membrane network; rough ER has ribosomes | Protein synthesis/transport (rough); lipid synthesis (smooth) |
| **Golgi apparatus** | Stack of flat membrane sacs | Processing, packaging, and secretion of proteins |
| **Lysosome** | Membrane-bound sac with digestive enzymes | Intracellular digestion, waste breakdown |
| **Vacuole** | Large in plant cells | Storage; water pressure (turgor) in plants |
| **Cell wall** | Rigid outer layer (cellulose in plants) | Support and protection |
| **Centriole** | 9 pairs of microtubules | Cell division (forms spindle fibers) — absent in plants |

[TIP] Mitochondria and chloroplasts both have their own DNA and ribosomes — evidence of **endosymbiosis** (they were once free-living bacteria swallowed by larger cells).

---

### 2.3 Biomembranes (Cell Membranes)

**Structure:** The **fluid mosaic model**
- Two layers of **phospholipids** (bilayer)
- Each phospholipid has a **hydrophilic head** (water-loving, faces outside) and a **hydrophobic tail** (water-fearing, faces inside)
- **Proteins** float in the bilayer (transport, receptors, enzymes)
- **Cholesterol** stabilizes the membrane

```
Outside (water)
─────────────────────────────────────
○○○○○○○○○○○○○○○○○○○○○○○  ← hydrophilic heads
||||||||||||||||||||||||  ← hydrophobic tails
||||||||||||||||||||||||  ← hydrophobic tails
○○○○○○○○○○○○○○○○○○○○○○○  ← hydrophilic heads
─────────────────────────────────────
Inside (cytoplasm)
```

**Selective permeability:** The membrane controls what enters and exits.
- **Small nonpolar molecules** (O₂, CO₂) pass freely
- **Ions and large molecules** need protein channels or active transport

---

### 2.4 Cytoskeleton

A network of protein fibers inside the cell that:
- Gives the cell shape
- Helps cells move
- Moves organelles and chromosomes around

Three types:
1. **Microtubules** (tubulin) — thickest; form spindle during cell division
2. **Intermediate filaments** — medium thickness; structural support
3. **Microfilaments (actin)** — thinnest; muscle contraction, cell movement

---

# CHEMISTRY — Atoms, Periodic Table & Chemical Bonds

## Part 1: Structure of the Atom

### 1.1 Subatomic Particles

Every atom has a **nucleus** (center) surrounded by **electrons**.

| Particle | Symbol | Location | Charge | Relative Mass |
|----------|--------|----------|--------|---------------|
| Proton | p | Nucleus | +1 | 1 |
| Neutron | n | Nucleus | 0 | 1 |
| Electron | e | Around nucleus | -1 | 1/1836 ≈ 0 |

[KEY FACT]
- **Atomic number (Z)** = number of protons = number of electrons (in neutral atom)
- **Mass number (A)** = protons + neutrons
- **Neutrons** = A - Z

[FORMULA]
```
Atomic number Z = number of protons
Mass number A = protons + neutrons
Neutrons = A - Z
```

[EXAMPLE] Carbon-12 (¹²C):
- Atomic number Z = 6 → 6 protons, 6 electrons
- Mass number A = 12 → neutrons = 12 - 6 = 6

### 1.2 Isotopes

**Isotopes** = atoms of the same element with **different numbers of neutrons** (same Z, different A).

[EXAMPLE]
- ¹H (protium): 1 proton, 0 neutrons
- ²H (deuterium): 1 proton, 1 neutron
- ³H (tritium): 1 proton, 2 neutrons

All three are hydrogen (Z=1), just different masses.

**Atomic weight** = average mass of all isotopes, weighted by natural abundance.

[EXAMPLE] Chlorine: ³⁵Cl (75.77%) and ³⁷Cl (24.23%)
Atomic weight = 35 × 0.7577 + 37 × 0.2423 = 26.52 + 8.97 = **35.45**

---

## Part 2: Electron Configuration

### 2.1 Electron Shells

Electrons occupy **shells** (energy levels) around the nucleus:
- Shell 1 (K shell): holds max 2 electrons
- Shell 2 (L shell): holds max 8 electrons
- Shell 3 (M shell): holds max 18 electrons

Fill from innermost shell outward.

[EXAMPLE] Electron configurations for first 20 elements:

| Element | Z | Config | Valence e⁻ |
|---------|---|--------|------------|
| H | 1 | 1 | 1 |
| He | 2 | 2 | 2 (full) |
| Li | 3 | 2,1 | 1 |
| Be | 4 | 2,2 | 2 |
| B | 5 | 2,3 | 3 |
| C | 6 | 2,4 | 4 |
| N | 7 | 2,5 | 5 |
| O | 8 | 2,6 | 6 |
| F | 9 | 2,7 | 7 |
| Ne | 10 | 2,8 | 8 (full) |
| Na | 11 | 2,8,1 | 1 |
| Mg | 12 | 2,8,2 | 2 |
| Al | 13 | 2,8,3 | 3 |
| Si | 14 | 2,8,4 | 4 |
| P | 15 | 2,8,5 | 5 |
| S | 16 | 2,8,6 | 6 |
| Cl | 17 | 2,8,7 | 7 |
| Ar | 18 | 2,8,8 | 8 (full) |
| K | 19 | 2,8,8,1 | 1 |
| Ca | 20 | 2,8,8,2 | 2 |

[KEY FACT] **Valence electrons** = electrons in the outermost shell. These determine chemical behavior.
Noble gases (He, Ne, Ar) have full outer shells → very unreactive.

---

## Part 3: The Periodic Table

The periodic table arranges elements by **atomic number** and groups elements with similar properties.

- **Period (row):** Elements in the same period have the same number of electron shells.
- **Group (column):** Elements in the same group have the same number of valence electrons → similar chemistry.

### Key Groups to Know:

| Group | Name | Valence e⁻ | Typical Ion | Examples |
|-------|------|------------|------------|---------|
| 1 | Alkali metals | 1 | +1 | Li, Na, K |
| 2 | Alkaline earth metals | 2 | +2 | Mg, Ca, Ba |
| 17 | Halogens | 7 | -1 | F, Cl, Br, I |
| 18 | Noble gases | 8 | none | He, Ne, Ar |

**Periodic trends (going across a period, left to right):**
- Atomic radius **decreases** (more protons pull electrons in)
- Ionization energy **increases** (harder to remove electrons)
- Electronegativity **increases**

**Periodic trends (going down a group):**
- Atomic radius **increases** (more shells)
- Ionization energy **decreases** (outer electron farther from nucleus)

---

## Part 4: Flame Reactions and Element Detection

Some metals produce characteristic colors when heated in a flame:

| Element | Flame Color |
|---------|------------|
| Li (lithium) | Crimson red |
| Na (sodium) | Yellow |
| K (potassium) | Violet/purple |
| Ca (calcium) | Orange-red |
| Ba (barium) | Yellow-green |
| Cu (copper) | Blue-green |

[TIP] Na produces such a strong yellow that it can mask other colors. Use blue cobalt glass to filter out yellow when checking for K.

---

## Day 1 Summary — Key Points

**Math:**
- Expand using (a±b)², (a+b)(a-b), (a±b)³ formulas
- Factorize by reversing these formulas
- |x| < a means -a < x < a; |x| > a means x < -a or x > a
- A ∪ B, A ∩ B, Aᶜ, De Morgan's laws
- Contrapositive of p→q is ¬q→¬p (equivalent); converse is q→p (not equivalent)

**Biology:**
- Prokaryotes: no nucleus, bacteria; Eukaryotes: nucleus, organelles
- Mitochondria → ATP; Chloroplast → photosynthesis; Ribosome → proteins
- Cell membrane = phospholipid bilayer (hydrophilic heads out, hydrophobic tails in)
- Cytoskeleton: microtubules, intermediate filaments, microfilaments

**Chemistry:**
- Atomic number = protons = electrons; Mass number = protons + neutrons
- Isotopes = same element, different neutrons
- Electron shells: K=2, L=8, M=18
- Periodic trends: radius ↓ across period; ionization energy ↑ across period
- Flame colors: Na=yellow, K=violet, Li=red, Ca=orange-red
