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
