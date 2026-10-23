# Data sources and verification log

Every numeric value used in the modules, where it came from, and what was corrected during verification (17 Oct 2026).

## Module 01 — Atom-Size Periodic Table (`inorganic/periodic-table.html`)

| Field | Source | Notes |
|---|---|---|
| Covalent radius | Cordero et al., *Dalton Trans.* 2008 (checked via LibreTexts "A3: Covalent Radii" and WebElements) | Mn, Fe, Co use low-spin values (139, 132, 126 pm) |
| IE₁ | Wikipedia "Molar ionization energies of the elements" (NIST data) | |
| Electron affinity → ΔegH = −EA | Wikipedia "Electron affinity (data page)" | Unbound anions shown as "> 0". Po is a calculated value (≈). d-block not shown |
| Electronegativity | Pauling scale, Wikipedia "Electronegativities of the elements (data page)" | Pb value is for Pb(IV) |
| Z_eff | Computed live from Slater's rules | Crude approximation; labelled on page |

Corrected during verification: Ga EA ~41 → 29.1 kJ/mol; Tc IE₁ 702 → 686.9 kJ/mol; In 37.0 and Tl 30.9 kJ/mol confirmed as measured values.

## Module 02 — Electronic Effects Ladder (`organic/effects-ladder.html`)

| Data | Source | Notes |
|---|---|---|
| Hammett σm, σp | Hansch, Leo & Taft, *Chem. Rev.* 1991, 91, 165; Hansch & Leo, *Substituent Constants* (1979); Leffler & Grunwald (1963) | O⁻ removed: unverifiable, sources disagree. NHCOCH₃: tables disagree, the commonly quoted pair (0.21, 0.00) is used |
| Aqueous pKa (25 °C) | CRC Handbook (via LibreTexts E1), Wikipedia compound pages, ATSDR | Chlorobutanoic acids, methoxyphenols and p-cresol were confirmed in a single compiled table (Engineering Toolbox) only |
| Amine pKaH | Wikipedia (methylamines), CRC | Gas-phase proton affinities: NH₃ 854 < CH₃NH₂ 896 < (CH₃)₂NH 923 < (CH₃)₃N 942 kJ/mol |
| Heats of hydrogenation | NIST WebBook, gas phase (Kistiakowsky et al.) | 136, 126, 119, 115, 112, 110 kJ/mol |
| Carbocation hydride ion affinities | Wikipedia "Carbenium ion" (Anslyn & Dougherty values); cross-checked against Kim et al. 2004 and a carbocation review | Gas phase. Order confirmed by all three sources |

Corrected during verification: Cl₂CHCOOH 1.29 → 1.35; Cl₃CCOOH 0.65 → 0.66; ClCH₂COOH 2.86 → 2.87; m-nitrophenol 8.40 → 8.36; p-chlorophenol 9.38 → 9.41; CH₃NH₃⁺ 10.64 → 10.66; hydrogenation values lowered by ~1 kJ/mol to NIST.

## Module 03 — Mechanism Player (`organic/mechanism-player.html`)

No numerical data. Mechanisms, rate laws and directing rules follow the standard textbook treatment (NCERT Class 11/12, Clayden, Klein). The SN1/SN2/E1/E2 table follows the standard Klein-style decision table and is labelled as a heuristic. Energy profiles are schematic.

## Structure of Atom (Oct 2026): `physical/atom-and-light.html`, `physical/bohr-model.html`, `physical/orbitals-configuration.html`

Every formula was checked against the NCERT Class 11 Chemistry rationalised text (2026–27 reprint, Unit 2), with Atkins, *Physical Chemistry*, and NCERT Class 12 Physics ("Atoms", "Dual Nature", "Nuclei") for the physics parts. Every worked number and quiz answer is computed in the page script, and each page was independently reviewed (all quiz answers recomputed). Quizzes use NCERT's printed constants so the answers match the book; the interactive readouts use CODATA values.

| Data | Source |
|---|---|
| e, h, c, N_A, k_B (exact); mₑ, m_p, m_n, u, e/mₑ, r_e, a₀ = 52.9177 pm, R∞, R∞hc = 2.17987×10⁻¹⁸ J, α, m_p/mₑ | NIST CODATA 2022 (physics.nist.gov/cuu); R_H = R∞/(1 + mₑ/m_p) = 109 677.6 cm⁻¹ (matches NCERT 109 677) |
| Work functions: Cs 1.95, K 2.29, Na 2.75, Mg 3.66 eV | CRC Handbook (2008, p. 12-124), via Wikipedia "Work function" |
| Hydrogen lines (air): Hα 656.2711 / 656.2725 / 656.2852 nm (intensities 90 / 30 / 180), Hβ 486.1362, Hγ 434.0462, Hδ 410.174 nm; Lyman α 121.567 nm (vacuum) | NIST Handbook of Basic Atomic Spectroscopic Data, H I table. Bohr/Rydberg values are vacuum wavelengths; the 0.028–0.029 % gap is air's refractive index (stated on the page) |
| Ground-state configurations Z = 1–36; Sc–Zn ions +1 to +3; Nb, Mo, Pd, Ag, W, Au | NIST Atomic Spectra Database. Note: V⁺ 3d⁴, Co⁺ 3d⁸, Ni⁺ 3d⁹ break the simple "4s leaves first" rule; the rule holds for all 2+ and 3+ ions of Sc–Zn |
| H ionisation energy 13.598434599702 eV | NIST ASD |
| Hydrogen radial functions (associated-Laguerre form) | Atkins, *Physical Chemistry*; normalisation and node positions checked numerically |
| Wien constant b = 2.897771955×10⁻³ m K; Stefan–Boltzmann σ = 5.670374419×10⁻⁸ W m⁻² K⁻⁴ | CODATA |
| Nuclear radius R₀ = 1.2 fm; α-particle energy 7.7 MeV | NCERT Class 12 Physics, "Nuclei" and "Atoms" |
| Classical collapse time t = a₀³/(4r_e²c) ≈ 1.6×10⁻¹¹ s | Olsen & McDonald, "Classical Lifetime of a Bohr Atom" (2005) |
| Spin-only µ = √(n(n+2)) BM | NCERT Class 12 Chemistry, "The d- and f-Block Elements" |
| Cricket ball 155.9–163 g, circumference 22.4–22.9 cm | MCC Laws of Cricket, Law 4 |

Simulated or schematic, labelled on the pages: Millikan drop masses (±3 % scatter); the gold-foil picture exaggerates large deflections (~1 % back-scattered) with the nucleus drawn ~10 000× too big; Zeeman/Stark patterns; visible-band colours (approximate); orbital slices use hydrogen ψ for all atoms (a model for many-electron atoms).

Errors and inconsistencies in NCERT (not repeated on the pages):
- §2.2.5: a classical electron would spiral in after 10⁻⁸ s; the standard estimate is ≈ 1.6×10⁻¹¹ s.
- Table 2.2 work functions (Li 2.42, Na 2.3, Cu 4.8, Ag 4.3 eV) disagree with CRC (Li 2.9, Na 2.75, Cu 4.53–5.10, Ag 4.26–4.74). §2.3.2 gives potassium's threshold as 5.0×10¹⁴ Hz, but its own 2.25 eV gives 5.44×10¹⁴ Hz, and its claim that yellow light ejects electrons from potassium contradicts both. Problem 2.8's sodium value (2.40 eV) matches neither.
- §2.6.2 calls all angular nodes planes; d_z²'s two angular nodes are cones.
- §2.6.4–2.6.5 refer to a non-existent "Section 2.6.7" (it is §2.6.6). Exercise 2.27 lists no species. Exercise 2.45 calls cosmic rays radiation (they are mostly particles).
- Problem 2.14 ("mass of a photon") is conceptually dubious; left out.
