# JEE Materials — project rules

Read this before adding or changing anything. These rules apply to every module in every subject, whoever writes it (you or Claude). Each subject folder also has its own `CLAUDE.md` with subject-specific rules; read that too.

## Purpose

- Make the JEE syllabus **intuitive**, not a PDF of tips and tricks. Each tool should let the student *see* why a trend, law or result happens.
- Audience: a Class 11–12 student preparing for CBSE + JEE.
- Prefer **predict-then-reveal** interactions (quizzes, rank-it, compare mode, sliders) over passive reading.

## Repository layout

```
index.html                 hub: links to each subject
<subject>/                 chemistry/, physics/, maths/
  index.html               numbered list of that subject's modules
  CLAUDE.md                subject-specific rules and planned modules
  DATA-SOURCES.md          sources and verification log for that subject
  <branch>/<module>.html   one self-contained page per module
```

Branches follow the syllabus split:

- `chemistry/` → `physical/`, `inorganic/`, `organic/`
- `physics/` → e.g. `mechanics/`, `thermodynamics/`, `electromagnetism/`, `optics/`, `waves/`, `modern/`
- `maths/` → e.g. `algebra/`, `calculus/`, `coordinate-geometry/`, `trigonometry/`, `vectors-3d/`, `probability-statistics/`

Create a subject or branch folder only when its first module is written. File names are lowercase-kebab-case.

## Content rules (non-negotiable)

1. **No unverified data.** Every number must be checked against a published source (NIST, CRC Handbook, Wikipedia data pages that cite them, peer-reviewed papers, standard textbooks, NCERT) **before** it goes into a page. Never enter values from memory.
2. **Cite sources** on the page (footer) and in the subject's `DATA-SOURCES.md`.
3. If sources disagree, use the more authoritative one, and say so on the page if the difference matters.
4. If a value can't be verified, **leave it out** rather than guess.
5. **Label heuristics.** Any rule of thumb, simplified model or hand-waving argument is tagged on the page as such (e.g. "rule of thumb, not a law", "simplified model", "schematic, not to scale").
6. **No extrapolation.** Don't claim more than the data or derivation shows. Mark near-ties as near-ties.
7. **Explain exceptions.** When a trend or approximation breaks, give the concrete reason.

## Visual rules

- Support light and dark mode with CSS colour tokens on `:root`, and keep pages usable at phone width (~400 px). Wide tables and SVGs scroll inside their own container.
- Fonts: Bricolage Grotesque (headings), IBM Plex Sans (body), IBM Plex Mono (data), from Google Fonts.
- Property heatmaps use the **jet colormap** (dark blue → cyan → yellow → dark red). Categorical colours stay categorical.

## Technical rules

- **One self-contained HTML file per module**, with no build step and no framework. External resources are limited to Google Fonts (plus a pinned CDN library only if it's truly needed).
- Every module starts with `<nav class="back"><a href="../index.html">← <Subject></a></nav>`, linking to its subject index.
- Use relative links only, so the site works on GitHub Pages and locally.
- Keep data in clearly marked arrays or blocks near the top of the script, so values are easy to check and update.
- `localStorage` is only for small conveniences (remembered tab/filter). Wrap it in try/catch, and use a key unique to the module.

## Adding a module

1. Create `<subject>/<branch>/<name>.html`, copying the head and style tokens from an existing module.
2. Verify all data first and record the sources in `<subject>/DATA-SOURCES.md`.
3. Add a row to `<subject>/index.html` (number, title, one-line description, tags), and update the subject's summary line in the root `index.html`.
4. Open it locally (just open `index.html` in a browser) and check light/dark mode and phone width.
5. Commit and push. GitHub Pages updates automatically.

## Adding a subject

1. Create `<subject>/index.html` by copying `chemistry/index.html` (keep the `← All subjects` back link), plus `CLAUDE.md` and `DATA-SOURCES.md`.
2. In the root `index.html`, turn the subject's "Planned" row into a link.
