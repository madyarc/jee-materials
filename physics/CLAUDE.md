# Physics — subject rules

The project-wide rules in the root [`CLAUDE.md`](../CLAUDE.md) apply, including the graphics-first design rule. This file adds what is specific to physics.

## Purpose

- Show the physical picture before the equation: forces, velocity vectors, mass distributions and energy flows drawn on the object, with the equation as a caption.
- Simplified models (rigid body, point mass, no air resistance, pure rolling) are labelled as models on the page, with the condition under which they fail.
- Check formulas and constants against NCERT Class 11/12, HC Verma or a standard university text (Halliday–Resnick–Walker). Use g = 9.8 m s⁻² unless a problem states 10.

## Layout

- `mechanics/` — kinematics, laws of motion, work and energy, collisions, centre of mass, torque, moment of inertia, rolling, gravitation, orbits
- `thermodynamics/` — all thermal physics: thermal properties of matter, thermodynamics, kinetic theory. Shared foundation for chemistry too: keep the `#signs` section of `laws-and-pv.html` self-contained, as the chemistry index links straight to it.
- `waves/` — oscillations, travelling waves, standing waves and beats
- Later: `properties-of-matter/` (solids, fluids), then Class 12 branches (`electromagnetism/`, `optics/`, `modern/`)

Physics module numbers are display order only: `physics/index.html` lists modules grouped by branch in NCERT chapter order, numbered 01, 02, … down the page. Renumber freely when inserting a module, and never refer to a physics module by its number on a page (link to the file instead).

## Coverage

`SYLLABUS.md` is the checklist of every syllabus item, built from the NCERT chapter text. Before building a topic, list its items there first; tick each one with the module that teaches it.

## Visual rules

- Velocity vectors, force vectors and axes keep one colour each across all physics pages. Mechanics/waves tokens: `--vel`, `--force`, `--spin`, `--axis`, `--acc`, `--disp`, `--ke`, `--pe` (values in any mechanics page; keep them identical). Thermodynamics tokens: `--heat` (Q), `--work` (W), `--du` (ΔU), `--hot`, `--cold`; reuse them on future thermal pages.
- Quantity colours are for those quantities only. Categorical things (car A vs car B, compression vs rarefaction, a marker for the CM) use `--ink` or a categorical colour (`--b1`…`--b4`, or a page-local token) whose value differs from every quantity colour. Check the value, not just the name: on some pages `--b2`/`--b3` equal `--disp`/`--acc`.
- Notation, the same on every page: initial velocity **u** (v = u + at); optimum banking speed **v<sub>opt</sub>**; circular-orbit speed **v<sub>orb</sub>**; kinetic and potential energy **K** and **U**; one micro sign **µ** everywhere; amplitude **A** for oscillations and **a** for waves (as NCERT), with the slider labelled in words where a clash is possible.
- Axes of rotation are dashed lines; an axis perpendicular to the page is a dot in a circle.
