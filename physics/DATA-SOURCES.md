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
