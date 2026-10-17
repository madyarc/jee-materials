# JEE Materials

Interactive pages for building intuition across the JEE syllabus (CBSE + JEE). Plain static HTML, with no build step.

## Subjects

### Chemistry — [`chemistry/`](chemistry/index.html)

| # | Module | Branch | What it does |
|---|---|---|---|
| 01 | [Atom-Size Periodic Table](chemistry/inorganic/periodic-table.html) | Inorganic | Atoms drawn to scale; overlays for IE, ΔegH, EN, Z_eff; exception spotlight; compare two elements; trend strips |
| 02 | [Electronic Effects Ladder](chemistry/organic/effects-ladder.html) | Organic | I / R / hyperconjugation / steric effects with Hammett σ, pKa and stability data; rank-it quizzes |
| 03 | [Mechanism Player](chemistry/organic/mechanism-player.html) | Organic | Step-by-step curved-arrow mechanisms, energy profiles, SN1/SN2/E1/E2 decision table |

### Physics — planned

### Mathematics — planned

## Layout

```
index.html                 hub: links to each subject
chemistry/
  index.html               chemistry module list
  CLAUDE.md                chemistry-specific rules
  DATA-SOURCES.md          sources and verification log
  inorganic/  organic/  physical/
physics/  maths/           (added when their first module is written)
```

## Run locally

Open `index.html` in a browser.

## Publish on GitHub Pages

On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main`, folder `/ (root)` → Save**. After a minute the site is live at `https://<your-username>.github.io/jee-materials/`.

`.nojekyll` tells GitHub Pages to serve the files as they are.

## Adding to it

Read [`CLAUDE.md`](CLAUDE.md) first: it holds the content, data-verification and design rules every module follows, plus the steps for adding a module or a subject. Each subject has its own `CLAUDE.md` and `DATA-SOURCES.md`.
