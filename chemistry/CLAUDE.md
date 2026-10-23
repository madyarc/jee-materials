# Chemistry — subject rules

The project-wide rules in the root [`CLAUDE.md`](../CLAUDE.md) apply. This file adds what is specific to chemistry.

## Purpose

- Core idea for inorganic trends: start from **atom size**, then add Z_eff and subshell effects. Show where size works and exactly where it fails.
- Core idea for organic: every "order" comes from the electronic effects (I, R, hyperconjugation, steric, solvation). Show their size with measured numbers.
- Cover the "effect order" questions for both organic (I/R/hyperconjugation orders, acidity, basicity, carbocation/alkene stability) and inorganic (electronegativity, ionization enthalpy, electron gain enthalpy).
- Exceptions get a concrete reason: subshell stability, e⁻–e⁻ repulsion in compact shells, poor d/f shielding, relativistic effects, solvation, sterics. Mark small differences (≤ 0.1 pKa, a few kJ/mol) as near-ties.
- Preferred sources: CRC/NIST first.

## Layout

- `physical/` — atomic structure: `atom-and-light.html`, `bohr-model.html`, `orbitals-configuration.html`. These are the shared home of the Bohr model, spectra, photoelectric effect and de Broglie (see the root `CLAUDE.md`).
- `inorganic/` — `periodic-table.html`
- `organic/` — `effects-ladder.html`, `mechanism-player.html`

`chemistry/index.html` lists modules grouped by branch (physical, inorganic, organic) in NCERT chapter order, numbered down the page. Numbers are display order only: renumber freely when inserting, and never refer to a module by its number on a page (link to it by name).

`SYLLABUS.md` is the coverage checklist, built from the NCERT chapter text before building a chapter (see the root `CLAUDE.md`).

## Visual rules

- Atomic-structure colour tokens: `--e` (electron), `--nuc` (nucleus/proton), `--neu` (neutron), `--photon`, `--ph1`/`--ph2` (orbital phase), `--s` `--p` `--d` `--f` (subshells). Reuse them on later chapters. Spectral lines are drawn in their approximate real colour in the visible band (labelled approximate), --muted outside it.
- In the periodic table, circle area ∝ (covalent radius)². Use one radius type throughout (Cordero 2008 covalent radii).
- Curved arrows in mechanisms are red and always go **from** an electron pair (lone pair or bond) **to** where it ends up.

## Planned modules / ideas

- More mechanisms (aldol, Cannizzaro, esterification, SN at acyl carbon, halogenation of benzene, Friedel–Crafts).
- Inorganic: ionic radii and isoelectronic series, lattice/hydration enthalpy trends, oxidation-state stability (inert pair effect).
- Acidity/basicity explorer combining the periodic table and the effects ladder (e.g. HX acidity, oxoacids).
- Physical: equilibrium, kinetics, electrochemistry.
- Thermodynamics: the laws, PV work and the sign conventions live in `physics/thermodynamics/` (shared, see the root `CLAUDE.md`), and the chemistry index links there. Chemistry-only pages to add in `physical/`: enthalpy and Hess's law, bond enthalpies, entropy and Gibbs energy, spontaneity. These use the IUPAC convention (ΔU = q + w) and link back to the shared page's sign-convention section (`#signs`).
