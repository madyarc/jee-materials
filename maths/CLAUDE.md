# Mathematics — subject rules

The project-wide rules in the root [`CLAUDE.md`](../CLAUDE.md) apply, including the graphics-first design rule. This file adds what is specific to maths.

## Purpose

- Every result gets a picture that makes it believable before it is proved: geometry for identities, graphs for equations and inequalities, block or dot diagrams for sums.
- A picture is not a proof. Where a visual argument only covers some cases (e.g. acute angles), say so and state the general result.
- Material beyond the NCERT syllabus but examinable in JEE is tagged **[beyond NCERT]**.
- Check results against NCERT Class 11/12 and a standard text (S. L. Loney, Hall & Knight). Numbers in examples are computed in the page's script, not typed in.

## Layout

- `trigonometry/` — `unit-circle.html` (01), `identities.html` (02), `equations-inverse.html` (03)
- `algebra/` — `progressions.html` (04), `means-and-sums.html` (05)
- Later branches: `calculus/`, `coordinate-geometry/`, `vectors-3d/`, `probability-statistics/`

Module numbers are per subject, so don't renumber existing modules.

## Visual rules

- Plain HTML maths (sub/sup, Unicode); no MathJax or KaTeX.
- Draggable points work with pointer events (mouse and touch) and show their current value.
