# Chemistry — subject rules

The project-wide rules in the root [`CLAUDE.md`](../CLAUDE.md) apply. This file adds what is specific to chemistry.

## Purpose

- Core idea for inorganic trends: start from **atom size**, then add Z_eff and subshell effects. Show where size works and exactly where it fails.
- Core idea for organic: every "order" comes from the electronic effects (I, R, hyperconjugation, steric, solvation). Show their size with measured numbers.
- Cover the "effect order" questions for both organic (I/R/hyperconjugation orders, acidity, basicity, carbocation/alkene stability) and inorganic (electronegativity, ionization enthalpy, electron gain enthalpy).
- Exceptions get a concrete reason: subshell stability, e⁻–e⁻ repulsion in compact shells, poor d/f shielding, relativistic effects, solvation, sterics. Mark small differences (≤ 0.1 pKa, a few kJ/mol) as near-ties.
- Preferred sources: CRC/NIST first.

## Layout

- `physical/` — physical chemistry (none yet)
- `inorganic/` — `periodic-table.html` (Module 01)
- `organic/` — `effects-ladder.html` (Module 02), `mechanism-player.html` (Module 03)

Module numbers are per subject and are referenced across pages ("Module 2's σ map"), so don't renumber existing modules.

## Visual rules

- In the periodic table, circle area ∝ (covalent radius)². Use one radius type throughout (Cordero 2008 covalent radii).
- Curved arrows in mechanisms are red and always go **from** an electron pair (lone pair or bond) **to** where it ends up.

## Planned modules / ideas

- More mechanisms (aldol, Cannizzaro, esterification, SN at acyl carbon, halogenation of benzene, Friedel–Crafts).
- Inorganic: ionic radii and isoelectronic series, lattice/hydration enthalpy trends, oxidation-state stability (inert pair effect).
- Acidity/basicity explorer combining Modules 1 and 2 (e.g. HX acidity, oxoacids).
- Physical: equilibrium, kinetics, electrochemistry.
- Thermodynamics: the laws, PV work and the sign conventions live in `physics/thermodynamics/` (shared, see the root `CLAUDE.md`), and the chemistry index links there. Chemistry-only pages to add in `physical/`: enthalpy and Hess's law, bond enthalpies, entropy and Gibbs energy, spontaneity. These use the IUPAC convention (ΔU = q + w) and link back to the shared page's sign-convention section (`#signs`).
