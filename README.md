# JEE Materials

Interactive pages for building intuition across the JEE syllabus (CBSE + JEE). Plain static HTML, with no build step.

## Subjects

### Chemistry — [`chemistry/`](chemistry/index.html)

| # | Module | Branch | What it does |
|---|---|---|---|
| 01 | [Atom-Size Periodic Table](chemistry/inorganic/periodic-table.html) | Inorganic | Atoms drawn to scale; overlays for IE, ΔegH, EN, Z_eff; exception spotlight; compare two elements; trend strips |
| 02 | [Electronic Effects Ladder](chemistry/organic/effects-ladder.html) | Organic | I / R / hyperconjugation / steric effects with Hammett σ, pKa and stability data; rank-it quizzes |
| 03 | [Mechanism Player](chemistry/organic/mechanism-player.html) | Organic | Step-by-step curved-arrow mechanisms, energy profiles, SN1/SN2/E1/E2 decision table |
| ↗ | [Thermodynamics sign conventions](physics/thermodynamics/laws-and-pv.html#signs) | Shared with physics | Why chemistry uses ΔU = q + w and physics ΔQ = ΔU + ΔW, on one picture |

### Physics — [`physics/`](physics/index.html)

| # | Module | Branch | What it does |
|---|---|---|---|
| 01 | [Moment of Inertia](physics/mechanics/moment-of-inertia.html) | Mechanics | Mass distribution vs distance from the axis; drag the axis for I = I_cm + Md²; perpendicular-axis theorem; one value → whole family |
| 02 | [Rolling Motion](physics/mechanics/rolling-motion.html) | Mechanics | Velocity arrows on a rolling/slipping wheel; incline race by β = k²/R²; friction needed to roll; slipping → rolling |
| 03 | [Thermodynamics: the PV Diagram](physics/thermodynamics/laws-and-pv.html) | Thermodynamics | Zeroth law; work as area; Q = ΔU + W bars; cycles; path dependence; Cp vs Cv; physics vs chemistry sign conventions |
| 04 | [Heat Engines and the Second Law](physics/thermodynamics/heat-engines.html) | Thermodynamics | Energy-flow bands; Kelvin–Planck and Clausius as impossible machines; Carnot cycle; refrigerators and heat pumps |
| 05 | [Kinetic Theory](physics/thermodynamics/kinetic-theory.html) | Thermodynamics | Molecule box → pressure and gas laws; KE ∝ T; Maxwell curve with v_mp, v_avg, v_rms; Graham; mean free path; real gases |
| 06 | [Degrees of Freedom and Equipartition](physics/thermodynamics/degrees-of-freedom.html) | Thermodynamics | Molecule viewer toggling each DOF; ½kT buckets → Cv, Cp, γ; mixtures; solids 3R; frozen modes |
| 07 | [Heat Transfer](physics/thermodynamics/heat-transfer.html) | Thermodynamics | Conduction (series/parallel, thermal resistance, ice growth); convection; black-body radiation; Newton's law of cooling |

### Mathematics — [`maths/`](maths/index.html)

| # | Module | Branch | What it does |
|---|---|---|---|
| 01 | [The Unit Circle](maths/trigonometry/unit-circle.html) | Trigonometry | All six functions as line segments, unrolled into graphs; allied angles as reflections |
| 02 | [Identities as Pictures](maths/trigonometry/identities.html) | Trigonometry | sin(A+B) from stacked triangles; a sin x + b cos x as adding arrows; sum-to-product as waves |
| 03 | [Equations and Inverses](maths/trigonometry/equations-inverse.html) | Trigonometry | General solutions as crossings; inverse functions as reflected branches |
| 04 | [Progressions: Add or Multiply](maths/algebra/progressions.html) | Algebra | AP as a staircase, GP as shrinking hops; AP vs GP; AP × GP |
| 05 | [Means and Sums You Can See](maths/algebra/means-and-sums.html) | Algebra | AM ≥ GM ≥ HM in a semicircle; Σk, Σk², Σk³ as blocks; telescoping; recurrences |

## Layout

```
index.html                 hub: links to each subject
chemistry/
  index.html               chemistry module list
  CLAUDE.md                chemistry-specific rules
  DATA-SOURCES.md          sources and verification log
  inorganic/  organic/  physical/
physics/                   same structure: mechanics/ …
maths/                     same structure: trigonometry/  algebra/ …
```

## Run locally

Open `index.html` in a browser.

## Publish on GitHub Pages

On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main`, folder `/ (root)` → Save**. After a minute the site is live at `https://<your-username>.github.io/jee-materials/`.

`.nojekyll` tells GitHub Pages to serve the files as they are.

## Adding to it

Read [`CLAUDE.md`](CLAUDE.md) first: it holds the content, data-verification and design rules every module follows, plus the steps for adding a module or a subject. Each subject has its own `CLAUDE.md` and `DATA-SOURCES.md`.
