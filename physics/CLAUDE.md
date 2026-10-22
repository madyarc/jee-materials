# Physics — subject rules

The project-wide rules in the root [`CLAUDE.md`](../CLAUDE.md) apply, including the graphics-first design rule. This file adds what is specific to physics.

## Purpose

- Show the physical picture before the equation: forces, velocity vectors, mass distributions and energy flows drawn on the object, with the equation as a caption.
- Simplified models (rigid body, point mass, no air resistance, pure rolling) are labelled as models on the page, with the condition under which they fail.
- Check formulas and constants against NCERT Class 11/12, HC Verma or a standard university text (Halliday–Resnick–Walker). Use g = 9.8 m s⁻² unless a problem states 10.

## Layout

- `mechanics/` — `moment-of-inertia.html` (Module 01), `rolling-motion.html` (Module 02)
- `thermodynamics/` — `laws-and-pv.html` (Module 03), `heat-engines.html` (Module 04), `kinetic-theory.html` (05), `degrees-of-freedom.html` (06), `heat-transfer.html` (07), `temperature-expansion.html` (08), `calorimetry-phase.html` (09). The folder holds all thermal physics (thermodynamics, kinetic theory, thermal properties of matter). Shared foundation for chemistry too: keep the `#signs` section self-contained, as the chemistry index links straight to it.
- Later branches: `electromagnetism/`, `optics/`, `waves/`, `modern/`

Module numbers are per subject, so don't renumber existing modules.

## Coverage

`SYLLABUS.md` is the checklist of every syllabus item, built from the NCERT chapter text. Before building a topic, list its items there first; tick each one with the module that teaches it.

## Visual rules

- Velocity vectors, force vectors and axes keep one colour each across all physics pages. Thermodynamics tokens: `--heat` (Q), `--work` (W), `--du` (ΔU), `--hot`, `--cold`; reuse them on future thermal pages.
- Axes of rotation are dashed lines; an axis perpendicular to the page is a dot in a circle.
