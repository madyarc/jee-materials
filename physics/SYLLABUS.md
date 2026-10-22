# Physics syllabus coverage checklist

Built from the NCERT Class 11/12 chapter text, plus items JEE expects beyond it (marked **[JEE]**). Tick an item when a module teaches it visually, and name the module. `[~]` = partly covered. This is a working file for building the site; students never see it.

## Kinetic theory of gases — NCERT Class 11, "Kinetic Theory"

Module: `thermodynamics/kinetic-theory.html` (05), `thermodynamics/degrees-of-freedom.html` (06)

- [~] Molecular nature of matter: Dalton's atomic theory, Avogadro's hypothesis, Avogadro's number — Avogadro covered (05); Dalton's atomic theory (history) not shown
- [x] Gas laws from the molecular picture: Boyle, Charles, ideal-gas equation PV = µRT = Nk<sub>B</sub>T
- [x] Dalton's law of partial pressures
- [x] Real vs ideal gas: PV/T vs P plots, ideal behaviour at low P and high T (qualitative)
- [x] Assumptions of kinetic theory (and which ones fail for real gases)
- [x] Pressure of an ideal gas from molecular collisions: P = ⅓ n m ⟨v²⟩
- [x] Kinetic interpretation of temperature: average KE per molecule = (3/2) k<sub>B</sub>T, independent of the gas
- [x] rms speed: v<sub>rms</sub> = √(3k<sub>B</sub>T/m) = √(3RT/M); dependence on T and molar mass
- [x] Heavier molecules move slower at the same T; diffusion rate (Graham's law) **[JEE]**
- [x] Distribution of molecular speeds (Maxwell) **[JEE; NCERT mentions only that a distribution exists]**
- [x] The three speeds: most probable v<sub>mp</sub> = √(2RT/M), average v<sub>avg</sub> = √(8RT/πM), rms; their order v<sub>mp</sub> < v<sub>avg</sub> < v<sub>rms</sub> and ratio **[JEE]**
- [x] How the distribution changes with T and with molar mass (area stays the same) **[JEE]**
- [x] Degrees of freedom: translational, rotational, vibrational; counting for each molecule type
- [x] Law of equipartition of energy: ½k<sub>B</sub>T per quadratic term; a vibrational mode counts twice (KE + PE)
- [x] Monatomic gas: f = 3, C<sub>v</sub> = 3R/2, C<sub>p</sub> = 5R/2, γ = 5/3
- [x] Diatomic gas, rigid: f = 5, γ = 7/5; with vibration: f = 7, γ = 9/7
- [x] Polyatomic gases: linear vs non-linear, 3 rotational DOF for non-linear, vibrational modes f
- [x] C<sub>p</sub> − C<sub>v</sub> = R; γ = 1 + 2/f
- [x] γ of a gas mixture **[JEE]**
- [x] Specific heat of solids: 3 vibrational modes per atom → C = 3R (Dulong–Petit), and where it fails (low T)
- [x] Specific heat of water (about 9R, qualitative)
- [x] Why classical predictions fail (modes "frozen" at low T; quantum explanation, qualitative)
- [x] Mean free path: l = 1/(√2 n π d²); dependence on n and d
- [x] Brownian motion as evidence of molecular motion (qualitative)

## Heat transfer — NCERT Class 11, "Thermal Properties of Matter" (heat transfer, Newton's law of cooling)

Module: `thermodynamics/heat-transfer.html` (07)

- [x] Three modes: conduction, convection, radiation, and when each dominates
- [x] Conduction: steady state, temperature gradient, H = KA(T<sub>C</sub> − T<sub>D</sub>)/L, thermal conductivity K
- [x] Conductors vs insulators (metals vs air, why fluffy materials insulate)
- [x] Compound bars in series (equivalent K, junction temperature) and parallel
- [x] Thermal resistance R = L/KA and the analogy with electric circuits **[JEE]**
- [x] Non-steady state / growth of ice layer on a pond **[JEE]**
- [x] Convection: natural vs forced; density differences
- [x] Sea breeze and land breeze; trade winds
- [x] Radiation: needs no medium; electromagnetic waves
- [x] Black body; Wien's displacement law λ<sub>m</sub>T = b
- [x] Stefan–Boltzmann law H = AσT⁴; emissivity e; net loss eAσ(T⁴ − T<sub>s</sub>⁴)
- [x] Absorptivity, reflectivity; good absorbers are good emitters; Kirchhoff's law **[JEE]**
- [x] Applications: thermos (Dewar) flask; dark vs light clothing; greenhouse effect (qualitative)
- [x] Newton's law of cooling: dT/dt = −k(T − T<sub>s</sub>), for small temperature differences; exponential cooling curve
- [x] Average-temperature form for problems ((T₁ − T₂)/t = k(T̄ − T<sub>s</sub>)) **[JEE]**
- [x] Newton's law of cooling as the small-difference limit of Stefan's law **[JEE]**

## Rest of "Thermal Properties of Matter" (not yet covered)

- [ ] Temperature and heat; thermometric scales; ideal-gas (absolute) temperature
- [ ] Thermal expansion: linear, area, volume; α, β, γ relations; anomalous expansion of water; thermal stress
- [ ] Specific heat capacity; calorimetry (principle of mixtures)
- [ ] Change of state: latent heat, heating curve, triple point, phase diagrams (water, CO₂), regelation, boiling point vs pressure
