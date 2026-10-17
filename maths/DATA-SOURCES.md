# Sources and verification log — Mathematics

Maths modules use standard results, not measured data. Every result and worked answer was re-derived before use, and every decimal on a page is computed by its script rather than typed in (17 Oct 2026).

## Modules 01–03 — Trigonometry (`trigonometry/`)

| Content | Source |
|---|---|
| Definitions, signs, allied angles, compound and double angles, sum-to-product, general solutions | NCERT Mathematics Class 11, "Trigonometric Functions" |
| Principal-value branches of inverse functions | NCERT Mathematics Class 12, "Inverse Trigonometric Functions" |
| Stacked-triangle proof of sin(A + B) (acute angles), general-solution templates | S. L. Loney, *Plane Trigonometry* |
| 18° and 36° values | Derived on the page from the golden triangle; they match the standard values |
| Worked-example ideas | *Trigonometry JEE Compendium* (study PDF, not kept in the repo) |

Errors found in the compendium and not carried over:
- App. A.3 gives a cos A + b cos B + c cos C = 4Δ/R. The correct value is **2Δ/R**: the sum is 4R sin A sin B sin C, and Δ = 2R² sin A sin B sin C.
- §2.7 swaps the sign exponents in its rule for reading off sin(A+B+C) and cos(A+B+C).
- Example 4.17 remark: cos 36° and −cos 72° are both roots of 4t² − 2t − 1 = 0. The roots of 4t² + 2t − 1 = 0 are cos 72° and −cos 36°.
- §2.14 says the general templates fail for sin θ = ±1 and cos θ = ±1. They don't fail; they list each solution twice.
- T8: tan x = a/b gives both the maximum and the minimum of a sin x + b cos x, not just the maximum.

## Modules 04–05 — Sequences and series (`algebra/`)

| Content | Source |
|---|---|
| AP, GP, S∞, AM, GM, AM ≥ GM, Σk, Σk², Σk³ | NCERT Mathematics Class 11, "Sequences and Series" |
| HM, AP × GP series, method of differences, recurrences | S. L. Loney / Hall & Knight, *Higher Algebra* |
| Semicircle construction of the three means, odd numbers as L-shapes, Σk² from three triangles, Σk³ as a square | R. B. Nelsen, *Proofs Without Words* (MAA, 1993) |
| Worked-example ideas | *Sequences & Series JEE Compendium* (study PDF, not kept in the repo) |

Errors found in the compendium and not carried over:
- Example 4.6: the factor is ((1.1)¹⁰ − 1)/0.1 ≈ 15.937, not 6.137. The final amounts given, ₹8,765.58 and ₹7,968.71, are correct.
- T1 / §3.1: three terms give two differences and two ratios, not one of each.
- Internal section references for the method of differences and recurrences are off by one.
