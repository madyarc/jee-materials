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
