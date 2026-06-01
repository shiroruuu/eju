# Day 2: Quadratic Functions | Proteins & Enzymes | Chemical Bonds & Moles

---

# MATHEMATICS — Quadratic Functions

## Part 1: Quadratic Functions and Their Graphs

A **quadratic function** has the form: **y = ax² + bx + c** (a ≠ 0)

The graph is a **parabola**:
- Opens **upward** if a > 0
- Opens **downward** if a < 0
- The **vertex** is the highest or lowest point

### 1.1 Standard (Vertex) Form

[FORMULA]
```
y = a(x - p)² + q
```
- Vertex is at **(p, q)**
- Axis of symmetry: x = p

**Converting ax² + bx + c to vertex form: "complete the square"**

[EXAMPLE] Convert y = 2x² - 8x + 3 to vertex form.
```
y = 2(x² - 4x) + 3
y = 2(x² - 4x + 4 - 4) + 3       ← add and subtract (b/2)² = 4 inside
y = 2(x - 2)² - 8 + 3
y = 2(x - 2)² - 5
```
Vertex: (2, -5), opens upward (a=2>0)

[FORMULA — Vertex from standard form]
```
For y = ax² + bx + c:
Vertex x-coordinate: x = -b/(2a)
Vertex y-coordinate: y = c - b²/(4a)
```

[PRACTICE] Find the vertex of y = x² - 6x + 11.

[ANSWER] x = -(-6)/(2·1) = 3, y = 11 - 36/4 = 11 - 9 = 2. Vertex: (3, 2)
Or complete the square: y = (x-3)² + 2 ✓

---

### 1.2 Maximum and Minimum Values

- If a > 0: minimum value at vertex (parabola opens up)
- If a < 0: maximum value at vertex (parabola opens down)

[EXAMPLE] y = -3(x + 1)² + 7
- a = -3 < 0 → has a **maximum**
- Maximum value = **7** at x = -1

**Maximum/minimum on a restricted domain [α, β]:**

This is tricky! You must check:
1. Where the vertex is relative to [α, β]
2. The values at both endpoints

[EXAMPLE] Find the maximum and minimum of y = (x-1)² - 3 on [0, 4].

Vertex at x=1, y=-3 (minimum of the parabola, a=1>0).
- At x=0: y = 1 - 3 = -2
- At x=1: y = -3 (vertex, minimum)
- At x=4: y = 9 - 3 = 6

So on [0,4]: **Maximum = 6** at x=4, **Minimum = -3** at x=1.

---

### 1.3 Determining a Quadratic Function

Given the right information, you can find a, b, c.

**Method 1:** If you know the vertex (p, q) and one other point:
Use y = a(x-p)² + q, substitute the point to find a.

**Method 2:** If you know 3 points (x₁,y₁), (x₂,y₂), (x₃,y₃):
Write 3 equations using y = ax² + bx + c, solve the system.

[EXAMPLE] Find y = a(x-p)² + q with vertex (2, -1) passing through (4, 7).
```
7 = a(4-2)² + (-1)
7 = 4a - 1
a = 2
Answer: y = 2(x-2)² - 1
```

---

## Part 2: Quadratic Equations

### 2.1 Solving Quadratic Equations

**Method 1: Factorization**
```
x² - 5x + 6 = 0
(x-2)(x-3) = 0
x = 2 or x = 3
```

**Method 2: Quadratic Formula**

[FORMULA]
```
For ax² + bx + c = 0:
x = (-b ± √(b² - 4ac)) / 2a
```

**Discriminant:** D = b² - 4ac
- D > 0 → two distinct real roots
- D = 0 → one repeated real root (double root)
- D < 0 → no real roots (two complex roots)

[EXAMPLE] Solve 2x² - 3x - 1 = 0.
```
x = (3 ± √(9 + 8)) / 4 = (3 ± √17) / 4
```

[PRACTICE] Does x² - 4x + 5 = 0 have real solutions?

[ANSWER] D = 16 - 20 = -4 < 0. No real solutions.

---

### 2.2 Vieta's Formulas (Relations Between Roots and Coefficients)

If α and β are the two roots of ax² + bx + c = 0:

[FORMULA]
```
α + β = -b/a    (sum of roots)
α · β = c/a     (product of roots)
```

[EXAMPLE] For 3x² - 7x + 2 = 0, find α + β and αβ without solving.
α + β = 7/3,   αβ = 2/3

[PRACTICE] Two roots are 2 and -5. Write the equation (with a=1).

[ANSWER] Sum = -3, Product = -10 → x² + 3x - 10 = 0

---

### 2.3 Graph and Quadratic Inequalities

To solve ax² + bx + c > 0 (or < 0):
1. Find the roots (solve ax² + bx + c = 0)
2. Determine where the parabola is above/below x-axis

**Case: a > 0, two roots α < β:**
```
ax² + bx + c > 0  when  x < α or x > β
ax² + bx + c < 0  when  α < x < β
```

[EXAMPLE] Solve x² - x - 6 > 0.
Roots: (x-3)(x+2) = 0 → x = 3, x = -2
Since a=1>0: answer is **x < -2 or x > 3**

[EXAMPLE] Solve x² - x - 6 < 0.
Answer: **-2 < x < 3**

[TIP] When D < 0 and a > 0: ax² + bx + c > 0 for ALL x (always positive)
When D < 0 and a < 0: ax² + bx + c < 0 for ALL x (always negative)

---

# BIOLOGY — Proteins and Enzymes

## Part 1: Structure of Proteins

### 1.1 Amino Acids — The Building Blocks

Proteins are made from **amino acids** linked together.

Every amino acid has:
- An **amino group** (-NH₂)
- A **carboxyl group** (-COOH)
- A **side chain** (R group) — this is what makes each amino acid unique
- All attached to the same central carbon

```
         H
         |
H₂N — C — COOH
         |
         R (side chain)
```

There are **20 types** of amino acids used in proteins (determined by their R group).

### 1.2 Peptide Bond Formation

When two amino acids join, the **-COOH of one** reacts with the **-NH₂ of another**, releasing water (H₂O). This forms a **peptide bond** (-CO-NH-).

[KEY FACT] 
- 2 amino acids joined = **dipeptide**
- Many amino acids joined = **polypeptide** or **protein**
- Number of peptide bonds = number of amino acids - 1

### 1.3 Levels of Protein Structure

| Level | What it is | Forces involved |
|-------|-----------|-----------------|
| **Primary** | Sequence of amino acids | Peptide bonds |
| **Secondary** | Local folding: α-helix or β-sheet | Hydrogen bonds |
| **Tertiary** | Full 3D shape of one polypeptide | H-bonds, disulfide bonds, hydrophobic interactions |
| **Quaternary** | Multiple polypeptide chains together | Same as tertiary |

[EXAMPLE] Hemoglobin (carries oxygen in blood) has **quaternary structure** — 4 polypeptide chains.

### 1.4 Protein Denaturation

**Denaturation** = the protein loses its 3D shape (unfolding) due to:
- High temperature (boiling an egg)
- Extreme pH (strong acid or base)
- Chemical agents (detergents, urea)

When denatured, the protein loses its function. The PRIMARY structure (sequence) is NOT broken — only the higher structures collapse.

[TIP] Denaturation is usually **irreversible** (cooked egg white cannot go back to raw). Exceptions exist (some proteins can **renature**).

---

## Part 2: Enzymes

### 2.1 What Are Enzymes?

Enzymes are **biological catalysts** — they speed up chemical reactions without being consumed.

- Almost all enzymes are **proteins**
- Each enzyme is **specific** — it only works on one substrate (or a few similar ones)
- The region where the substrate binds is the **active site**

**Lock and Key Model:** The active site is a specific shape that fits the substrate exactly.

**Induced Fit Model:** The active site changes shape slightly to fit the substrate (more accurate).

### 2.2 Enzyme Kinetics

**Factors affecting enzyme activity:**

**1) Temperature:**
- Rate increases as temperature rises (more collisions)
- Above **optimum temperature**: enzyme denatures → activity drops sharply
- Human enzymes: optimum ≈ 37°C

**2) pH:**
- Each enzyme has an optimum pH
- Pepsin (stomach enzyme): optimum pH ≈ 2
- Amylase (saliva): optimum pH ≈ 7
- Trypsin (small intestine): optimum pH ≈ 8

**3) Substrate concentration:**
- As [substrate] ↑, rate ↑ until the enzyme is saturated (all active sites occupied)
- At saturation: maximum rate (Vmax) — adding more substrate has no effect

```
Rate
↑          ___________  ← Vmax (plateau)
|        /
|       /
|      /
|     /
|    /
+──────────────────→ [Substrate]
```

**4) Enzyme concentration:**
- More enzyme → faster reaction (as long as there's enough substrate)

### 2.3 Inhibitors

**Competitive inhibitor:** Molecule similar to substrate that blocks the active site.
- Effect is reversible — adding more substrate competes it out.

**Non-competitive inhibitor:** Binds to a different site (allosteric site), changes the shape of the active site.
- Adding more substrate does NOT overcome this inhibition.

### 2.4 Coenzymes and Cofactors

Some enzymes need helpers:
- **Cofactors**: inorganic ions (Mg²⁺, Zn²⁺, Fe²⁺)
- **Coenzymes**: organic molecules (e.g., NAD⁺, FAD — involved in cellular respiration)

**Apoenzyme** = enzyme protein alone (inactive)
**Holoenzyme** = apoenzyme + cofactor (active)

---

## Part 3: Membrane Transport Proteins

Proteins in the cell membrane help move substances across it:

| Type | Energy needed? | Example |
|------|---------------|---------|
| Ion channels | No (passive) | Na⁺, K⁺ channels |
| Carrier proteins (facilitated diffusion) | No (passive) | Glucose transporter |
| Pumps (active transport) | YES (ATP) | Na⁺/K⁺ ATPase |

**Na⁺/K⁺ pump:** Uses 1 ATP to pump **3 Na⁺ out** and **2 K⁺ in** — essential for nerve cell function.

---

# CHEMISTRY — Chemical Bonds and Moles

## Part 1: Chemical Bonds

### 1.1 Ionic Bonds

Form between a **metal** and a **non-metal**.
- Metal loses electrons → positive ion (cation)
- Non-metal gains electrons → negative ion (anion)
- Opposite charges attract

[EXAMPLE] NaCl (table salt):
Na (2,8,1) → Na⁺ (2,8) + e⁻
Cl (2,8,7) + e⁻ → Cl⁻ (2,8,8)

**Ionic crystals** are arranged in a regular lattice.
- High melting points (strong electrostatic forces)
- Conduct electricity when **dissolved** or **melted** (ions are free to move)
- Brittle (layers shift → like charges repel → crystal shatters)

**Ionization energy:** Energy needed to remove one electron from a gaseous atom.
**Electron affinity:** Energy released when a gaseous atom gains one electron.

---

### 1.2 Metallic Bonds

Metal atoms give up their valence electrons to form a "sea of free electrons."

```
Metal cations (+) surrounded by a sea of electrons
+ + + + + + +
  electrons flowing freely between cations
+ + + + + + +
```

**Properties of metals:**
- **Electrical conductivity**: free electrons carry charge
- **Thermal conductivity**: free electrons transfer heat
- **Malleability and ductility**: layers can slide without breaking bond
- **Metallic luster**: electrons reflect light

---

### 1.3 Covalent Bonds

Form between **non-metals**. Atoms **share** electron pairs.

**Types of covalent bonds:**
- **Single bond** (one shared pair): C-H, H-H
- **Double bond** (two shared pairs): C=C, O=O
- **Triple bond** (three shared pairs): N≡N, C≡C

**Coordinate (dative) bond**: Both electrons in the shared pair come from ONE atom.
[EXAMPLE] NH₃ + H⁺ → NH₄⁺ (the N donates both electrons to the bond)

**Electronegativity** = how strongly an atom attracts shared electrons.
- F is most electronegative. Goes: F > O > N > Cl > Br > S > C > H

**Polar bonds:** When two atoms with different electronegativities share electrons, the bond is polar (unequal sharing).

[EXAMPLE]
- H₂: nonpolar (same atoms)
- HCl: polar (Cl pulls electrons toward itself → δ⁻ on Cl, δ⁺ on H)

**Molecular polarity** depends on BOTH bond polarity AND molecular shape:
- CO₂ (linear): bond dipoles cancel → **nonpolar molecule**
- H₂O (bent): bond dipoles don't cancel → **polar molecule**

---

### 1.4 Intermolecular Forces

These are forces BETWEEN molecules (not within a molecule).

| Force | Strength | Between... | Example |
|-------|----------|------------|---------|
| **Van der Waals (London dispersion)** | Weak | All molecules | Noble gases, hydrocarbons |
| **Dipole-dipole** | Medium | Polar molecules | HCl, SO₂ |
| **Hydrogen bond** | Strong (for intermolecular) | H bonded to N, O, or F | H₂O, HF, NH₃ |

[KEY FACT] Hydrogen bonds explain why water has an unusually high boiling point (100°C) compared to similar molecules like H₂S (-60°C).

**Crystal types summary:**

| Crystal Type | Particles | Forces | Properties | Examples |
|-------------|-----------|--------|------------|---------|
| Ionic | Ions | Ionic bonds | Hard, brittle, high mp, conducts when dissolved | NaCl, CaCO₃ |
| Metallic | Metal cations + e⁻ | Metallic bonds | Conducts, malleable, lustrous | Fe, Cu, Al |
| Covalent | Atoms | Covalent bonds | Very hard, very high mp, does not conduct | Diamond (C), SiO₂ |
| Molecular | Molecules | Van der Waals, H-bonds | Soft, low mp, does not conduct | Ice (H₂O), dry ice (CO₂), sugar |

---

## Part 2: The Mole — Quantitative Chemistry

### 2.1 Atomic Mass and Molar Mass

**Atomic mass unit (u):** 1/12 the mass of a ¹²C atom.
**Atomic weight:** relative mass of one atom (no units, but numerically = g/mol).

**Molar mass:** mass of one mole of substance (in g/mol).
- Same number as the atomic/molecular weight.

### 2.2 Avogadro's Number

[FORMULA]
```
1 mol = 6.022 × 10²³ particles (Avogadro's number, Nₐ)
```

So 1 mol of any substance contains 6.022 × 10²³ particles of that substance.

### 2.3 Key Mole Formulas

[FORMULA]
```
n (mol) = m (g) / M (g/mol)         ← amount from mass
m (g) = n (mol) × M (g/mol)         ← mass from amount
N = n × Nₐ                          ← number of particles
```

At STP (0°C, 1 atm):
```
V (L) = n × 22.4 L/mol              ← volume of gas at STP
```

[EXAMPLE] How many moles of H₂O in 36 g?
M(H₂O) = 2(1) + 16 = 18 g/mol
n = 36/18 = **2 mol**
Number of molecules = 2 × 6.022 × 10²³ = 1.204 × 10²⁴

[EXAMPLE] What is the mass of 3 mol of CO₂?
M(CO₂) = 12 + 2(16) = 44 g/mol
m = 3 × 44 = **132 g**

[PRACTICE] How many moles of NaCl in 117 g? (Na=23, Cl=35.5)

[ANSWER] M(NaCl) = 23 + 35.5 = 58.5 g/mol; n = 117/58.5 = **2 mol**

### 2.4 Molar Concentration

[FORMULA]
```
c (mol/L) = n (mol) / V (L)
n = c × V
```

[EXAMPLE] 500 mL solution containing 4 g NaOH (M=40 g/mol).
n(NaOH) = 4/40 = 0.1 mol
c = 0.1 / 0.5 = **0.2 mol/L**

[TIP] Watch units! V must be in **liters**, not mL.

---

## Day 2 Summary — Key Points

**Math:**
- Vertex form: y = a(x-p)² + q, vertex at (p,q)
- Complete the square to convert from standard form
- Quadratic formula: x = (-b ± √(b²-4ac)) / 2a
- Discriminant D > 0 (two roots), = 0 (one root), < 0 (no real roots)
- Vieta: α+β = -b/a, αβ = c/a
- Inequality: if a>0, roots α<β → parabola negative between roots

**Biology:**
- Amino acids → peptide bonds → proteins (primary→quaternary structure)
- Denaturation = loss of 3D structure (NOT primary structure)
- Enzymes: specific, have active site, affected by T and pH
- Competitive inhibitor blocks active site; non-competitive changes its shape
- Na⁺/K⁺ pump uses ATP: pumps 3 Na⁺ out, 2 K⁺ in

**Chemistry:**
- Ionic: metal loses e⁻, non-metal gains e⁻; high mp, conducts when dissolved
- Metallic: sea of free electrons; conducts, malleable
- Covalent: share electrons; can be polar (different electronegativities)
- Hydrogen bonds: H bonded to N, O, or F; strong intermolecular force
- 1 mol = 6.022×10²³ particles; n = m/M; at STP: V = n × 22.4 L
