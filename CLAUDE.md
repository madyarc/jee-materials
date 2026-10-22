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

**Shared topics are cross-linked, never duplicated.** When physics and chemistry (or maths) cover the same idea, it gets one home page, in the subject whose syllabus treats it most fully. The other subject's index lists it as a "shared with <subject>" row linking there, and its own modules link to it for the foundation instead of re-teaching it. Where the subjects use different conventions (e.g. the sign of work in the first law), the shared page shows both on the same picture and explains why each field chose its own. Current shared foundations:

- Thermodynamics (laws, PV diagrams, engines, sign conventions) → `physics/thermodynamics/`. Chemistry-only topics (enthalpy, Hess's law, entropy and Gibbs energy of reactions, spontaneity) go in `chemistry/physical/` and link back to it.

Create a subject or branch folder only when its first module is written. File names are lowercase-kebab-case.

## Content rules (non-negotiable)

1. **No unverified data.** Every number must be checked against a published source (NIST, CRC Handbook, Wikipedia data pages that cite them, peer-reviewed papers, standard textbooks, NCERT) **before** it goes into a page. Never enter values from memory.
2. **Cite sources** on the page (footer) and in the subject's `DATA-SOURCES.md`. The page footer is for **school students**, who never see the GitHub repo: a short "Based on:" line naming the textbooks they know (NCERT by chapter *name*, H. C. Verma, etc.) plus a "Models used:" line for simplifications. Never put repo files (`DATA-SOURCES.md`), source PDFs/compendiums, example numbers, corrections to source material, or verification notes ("re-derived", "computed by the script") on a page; those go in `DATA-SOURCES.md` only.
3. If sources disagree, use the more authoritative one, and say so on the page if the difference matters.
4. If a value can't be verified, **leave it out** rather than guess.
5. **Label heuristics.** Any rule of thumb, simplified model or hand-waving argument is tagged on the page as such (e.g. "rule of thumb, not a law", "simplified model", "schematic, not to scale").
6. **No extrapolation.** Don't claim more than the data or derivation shows. Mark near-ties as near-ties.
7. **Explain exceptions.** When a trend or approximation breaks, give the concrete reason.

## Design rule: graphics first, never a formula sheet

Handbook scans and coaching sites (Byju's and similar) summarise books into formula lists. This site must not. Its advantage over a book is graphics, so use it.

- **Every idea is built as a picture the student can manipulate**: drag a point, move a slider, step through, predict-then-reveal. The formula appears as a caption on what is visible, after the picture has made it obvious, not as the content itself.
- **Visually clean and minimal.** Inline SVG, flat colours, plenty of space. No flashy animation, decorative effects, stock images or heavy libraries. Motion only when the motion itself is the idea (a wheel rolling, a point moving round the circle).
- **Light on resources.** A page should load instantly on a phone on mobile data.
- **Source material (PDFs, notes) is raw material, not a script.** Pick the ideas that benefit from being seen, rebuild them visually, and leave out tables that would only be transcription. Worked examples become interactive "predict, then check" items.

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

0. **List before building.** Before starting a topic, list every syllabus item for it in `<subject>/SYLLABUS.md`, built from the actual NCERT chapter text (plus JEE extras, marked **[JEE]**), so nothing is missed. After building, tick each item with the module that covers it (`[~]` for partial).
1. Create `<subject>/<branch>/<name>.html`, copying the head and style tokens from an existing module.
2. Verify all data first and record the sources in `<subject>/DATA-SOURCES.md`.
3. Add a row to `<subject>/index.html` (number, title, one-line description, tags), and update the subject's summary line in the root `index.html`.
4. Open it locally (just open `index.html` in a browser) and check light/dark mode and phone width.
5. Commit and push. GitHub Pages updates automatically.

## Adding a subject

1. Create `<subject>/index.html` by copying `chemistry/index.html` (keep the `← All subjects` back link), plus `CLAUDE.md` and `DATA-SOURCES.md`.
2. In the root `index.html`, turn the subject's "Planned" row into a link.
