# Data sources and verification log — Physics

Physics modules use standard results rather than measured data. Each result was re-derived from first principles (I = Σ m r⊥², Newton's laws for translation and rotation) and checked against the textbooks below (17 Oct 2026).

## Module 01 — Moment of Inertia (`mechanics/moment-of-inertia.html`)
## Module 02 — Rolling Motion (`mechanics/rolling-motion.html`)

| Content | Source |
|---|---|
| Standard moments of inertia, parallel- and perpendicular-axis theorems | NCERT Physics Class XI Part I, "System of Particles and Rotational Motion"; H. C. Verma, *Concepts of Physics* Vol. 1, Ch. 10; Halliday, Resnick & Walker, *Fundamentals of Physics*, Ch. 10 |
| Rolling kinematics, rolling down an incline (a = g sin θ / (1 + k²/R²)), friction needed to roll, slipping → rolling, push height h = k²/R | NCERT (as above); H. C. Verma Vol. 1, Ch. 10; Halliday, Resnick & Walker, Ch. 11 |
| Worked-example selection | *Moment of Inertia & Rolling Motion* compendium (study PDF, not kept in the repo). All examples were re-derived and no errors of substance were found |

Conventions: interactive sections use g = 9.8 m s⁻². Quiz items use g = 10 m s⁻² where the original problem did, so one slipping preset gives ≈ 2.55 s where the compendium (g = 10) gives 2.5 s.

To check: chapter numbers are cited from memory of the editions. NCERT's chapter number changed in the 2023 rationalised edition.

## Module 03 — Thermodynamics: the PV Diagram (`thermodynamics/laws-and-pv.html`)
## Module 04 — Heat Engines and the Second Law (`thermodynamics/heat-engines.html`)

| Content | Source |
|---|---|
| Zeroth law; ΔQ = ΔU + ΔW with ΔW the work done *by* the system; Cp − Cv = R; PV^γ = const; adiabatic W = µR(T₁ − T₂)/(γ − 1); isothermal W = µRT ln(V₂/V₁); ΔU = 0 over a cycle; Kelvin–Planck and Clausius statements (quoted); reversible/irreversible; Carnot η = 1 − T₂/T₁ | NCERT Physics Class XI Part II (rationalised 2023 edition), Ch. 11 "Thermodynamics", checked against the text (keph204.pdf) |
| γ = 5/3 (monatomic), Cv = 5R/2 and γ = 7/5 (rigid diatomic, vibration ignored) | NCERT Physics Class XI, Ch. 12 "Kinetic Theory" (keph205.pdf). Kinetic-theory ideal values, labelled as such on the page |
| Chemistry convention ΔU = q + w, w = −p<sub>ex</sub>ΔV | NCERT Chemistry Class XI Part I, "Thermodynamics"; IUPAC Green Book, 3rd ed. |
| History of the two conventions (Clausius: ΔU = Q − W; IUPAC/Planck: ΔU = Q + W) | Wikipedia, "First law of thermodynamics" |
| R = 8.314 J mol⁻¹ K⁻¹ | CODATA 2018 / NIST (8.314462618) |
| Further reading | H. C. Verma, *Concepts of Physics* Vol. 2, "Laws of Thermodynamics" and "Specific Heat Capacities of Gases"; Halliday, Resnick & Walker, *Fundamentals of Physics*, ch. on entropy and the second law |

Model choices: n = 0.1 mol, so kPa × L = J; the Carnot cycle uses a monatomic gas. No real-engine efficiency figures are given (none verified), so real engines are described only as below the Carnot limit.

To check: the HC Verma and Halliday chapter numbers, and the NCERT Chemistry chapter (not opened during verification; the convention itself is standard).

## Module 05 — Kinetic Theory (`thermodynamics/kinetic-theory.html`)

| Content | Source |
|---|---|
| P = ⅓nm⟨v²⟩, mean KE = (3/2)k<sub>B</sub>T, Dalton's law, mean free path l = 1/(√2 nπd²) (Eq. 12.40), UF₆ masses 349 and 352 (Ex. 12.6), Exercise 12.9 data, molecular size ≈ 2 Å, 22.4 L per mole at 273 K and 1 atm, real gases ideal at low P and high T (Fig. 12.1) | NCERT Physics Class 11, "Kinetic Theory" (keph205.pdf) |
| Maxwell distribution f(v); v<sub>mp</sub> = √(2RT/M), ⟨v⟩ = √(8RT/πM), v<sub>rms</sub> = √(3RT/M) | Wikipedia "Maxwell–Boltzmann distribution"; H. C. Verma Vol. 2, "Kinetic Theory of Gases" |
| k<sub>B</sub>, N<sub>A</sub> (exact, SI 2019); R = 8.314462618 (CODATA) | NIST |
| Molar masses (H₂ 2.016, He 4.003, N₂ 28.014, O₂ 31.998, CO₂ 44.009, Ar 39.95, Xe 131.29 g/mol) | IUPAC standard atomic weights |
| Fraction of molecules faster than v<sub>mp</sub> = 0.5724 | Numerical integration of the Maxwell distribution |

Error in NCERT, not carried over: Eq. 12.41 gives l = 2.9 × 10⁻⁷ m for d = 2 Å and n = 2.7 × 10²⁵ m⁻³. That value is 1/(nπd²) without the √2; with the √2 of Eq. 12.40 it is ≈ 2.1 × 10⁻⁷ m. The page uses Eq. 12.40 and does not quote 2.9 × 10⁻⁷.

The box simulation is a 2D model in relative pressure units; the real-gas PV/(µRT) curves are schematic shapes (no van der Waals data). Both are labelled on the page.

## Module 06 — Degrees of Freedom and Equipartition (`thermodynamics/degrees-of-freedom.html`)

| Content | Source |
|---|---|
| Equipartition; monatomic, diatomic and polyatomic Cv = (3 + f)R; solids 3R; "carbon is an exception"; bond-axis rotation not counted | NCERT Physics Class 11, "Kinetic Theory" §12.5–12.6 |
| γ of a mixture; γ = 1 + 2/f | H. C. Verma Vol. 2, "Specific Heat Capacities of Gases" |
| Measured Cp at 298.15 K: Cu 24.47, Al 24.21, Pb 26.85, liquid water 75.37 J mol⁻¹ K⁻¹ | NIST-JANAF Thermochemical Tables (Chase 1998, via the NIST Chemistry WebBook Shomate coefficients) |
| Vibrational mode counts 3N − 5 (linear) / 3N − 6 (non-linear): CO₂ 4, H₂O 3, CH₄ 9 | Standard result |

The current NCERT reprint has no water ≈ 9R passage and no "frozen modes" subsection (its footnote points to one that isn't there); both are kept qualitative and labelled as models. No value is given for carbon/diamond because published values disagree. Molecule geometry, the energy ladders, the Cv staircase and the Einstein curve are schematic and labelled.

## Module 07 — Heat Transfer (`thermodynamics/heat-transfer.html`)

| Content | Source |
|---|---|
| Thermal conductivities (all 19 values), ice K = 1.6 W m⁻¹ K⁻¹ | NCERT Physics Class 11, "Thermal Properties of Matter", Table 10.6 |
| Latent heat of fusion 3.33 × 10⁵ J kg⁻¹; c of water 4186 J kg⁻¹ K⁻¹ | NCERT Tables 10.5, 10.3 |
| Ice density 917 kg m⁻³ | CRC Handbook (0.9167 g cm⁻³ at 0 °C) |
| Skin emissivity ≈ 0.97, tungsten ≈ 0.4, solar peak 4753 Å | NCERT §10.9.4 |
| σ = 5.670374419 × 10⁻⁸ W m⁻² K⁻⁴; b = 2.897771955 × 10⁻³ m K; h, c, k<sub>B</sub> exact | CODATA / NIST |
| Draper point ≈ 800 K | Wikipedia "Draper point" (798 K) |
| Worked items | NCERT Examples 10.6, 10.8; Exercises 10.19, 10.20 |
| Ice growth t = ρL(x₂² − x₁²)/(2Kθ); Newton's law as the small-ΔT limit of Stefan's law (k = 4eσAT<sub>s</sub>³/ms) | H. C. Verma Vol. 2, "Heat Transfer" (re-derived) |

The glow-colour swatch is approximate (Planck's law sampled at three wavelengths), and the ice-growth and rod warm-up pictures are simplified models; all are labelled on the page.

## Module 08 — Temperature and Thermal Expansion (`thermodynamics/temperature-expansion.html`)

| Content | Source |
|---|---|
| α<sub>l</sub>: Al 2.5, brass 1.8, iron 1.2, Cu 1.7, Ag 1.9, Au 1.4, pyrex 0.32 (×10⁻⁵ K⁻¹) | NCERT Class 11, "Thermal Properties of Matter", Table 10.1 |
| α<sub>V</sub>: invar 2×10⁻⁶, pyrex 1×10⁻⁵, glass 2.5×10⁻⁵, iron 3.55×10⁻⁵, brass 6×10⁻⁵, Al 7×10⁻⁵, hard rubber 2.4×10⁻⁴, mercury 18.2×10⁻⁵, water 20.7×10⁻⁵ (near 20 °C), ethanol 110×10⁻⁵; α<sub>V</sub> = 1/T for an ideal gas (Eq. 10.6) | NCERT Table 10.2. Invar and ethanol differ from Wikipedia's table (3.6×10⁻⁶; 75×10⁻⁵); NCERT kept |
| Steel rail (α 1.2×10⁻⁵, Y 2×10¹¹ N m⁻², 5 m, 40 cm²); Example 10.2; Exercises 10.1, 10.2, 10.6, 10.8, 10.9, 10.11 | NCERT §10.5 |
| Water density 0–12 °C (maximum at 3.98 °C) | Tanaka et al., *Metrologia* 38 (2001) 301 formula; cross-checked with Wikipedia "Water (data page)" (CRC) |
| Triple point of water 273.16 K, 611.657 Pa | Guildner, Johnson & Jones 1976 (via Wikipedia "Water (data page)") |

Errors in NCERT, not carried over:
- The phase-diagram box gives the triple-point pressure of water as 6.11 × 10⁻³ Pa. Correct: 611.657 Pa (≈ 6.04 × 10⁻³ atm; 6.11 is the value in mbar).
- Table 10.1 gives lead's α<sub>l</sub> as 0.29 × 10⁻⁵ K⁻¹; the real value is 2.9 × 10⁻⁵. Lead is left off the page.
- "Points to ponder" calls 273.16 K exact by definition; that ended with the 2019 SI redefinition. The page says it "is assigned".

Schematic, labelled on the page: gas-sample pressures, lake layer temperatures, bond-energy curve, copper α<sub>V</sub> curve, bimetal bend.

## Module 09 — Heat, Calorimetry and Change of State (`thermodynamics/calorimetry-phase.html`)

| Content | Source |
|---|---|
| Specific heats (incl. ice 2060 J kg⁻¹ K⁻¹), gas C<sub>p</sub> and C<sub>v</sub>, latent heats (water L<sub>f</sub> 3.33×10⁵, L<sub>v</sub> 22.6×10⁵ J kg⁻¹) | NCERT Tables 10.3, 10.4, 10.5 |
| Worked items | NCERT Examples 10.3–10.5; Exercises 10.12–10.14 |
| Boiling point and L<sub>v</sub> vs pressure (0.2–2.5 atm; 99.97 °C and 2256.4 kJ kg⁻¹ at 1 atm; 120.63 °C at 2 atm); water triple point 0.01 °C, 611.657 Pa; critical point 373.95 °C, 22.064 MPa; steam c<sub>p</sub> ≈ 2040 J kg⁻¹ K⁻¹ (100–120 °C average) | NIST Chemistry WebBook (IAPWS-95) |
| CO₂ triple point −56.56 °C, 5.11 atm; critical point 30.98 °C, 72.81 atm | NIST Chemistry WebBook |
| Dry ice sublimes at −78.5 °C at 1 atm; ice melting point falls 0.0073 °C per atm; iodine melts at 113.7 °C (triple point 12.1 kPa); Everest 8848.86 m; pressure cooker ≈ 2 atm absolute; skating explanation | Wikipedia "Dry ice", "Properties of water", "Iodine", "Mount Everest", "Pressure cooking", "Ice skating" |
| Pressure vs altitude P = P₀(1 − 2.25577×10⁻⁵ h)^5.25588 | US Standard Atmosphere 1976 |

Errors / outdated values in NCERT, not carried over: the triple-point pressure (as above); gold in Table 10.5 (boiling point 2660 °C, L<sub>v</sub> 15.8×10⁵ — modern values 2970 °C, ≈ 17.4×10⁵ J kg⁻¹; gold left off); lead's melting and boiling points differ slightly from modern values (not shown). NCERT explains skating by pressure melting alone; the page labels that a simplified picture.

The phase diagrams are schematic with correct key points; the flask-activity pressures (1.3 and 0.4 atm) and the steam-burn model (skin at 37 °C) are illustrative and labelled.
