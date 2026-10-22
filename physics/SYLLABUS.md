# Physics syllabus coverage checklist

Built from the NCERT Class 11/12 chapter text, plus items JEE expects beyond it (marked **[JEE]**). Tick an item when a module teaches it visually, and name the module. `[~]` = partly covered. This is a working file for building the site; students never see it.

## Motion in a straight line — NCERT Class 11, "Motion in a Straight Line"

Module: `mechanics/motion-in-a-line.html`

Note: the supplied NCERT text (2026-27 reprint) lists "2.5 Relative velocity" in its contents box but has no body for it; it also starts §2.2 using "average velocity" without defining position, path length or displacement (those sections were dropped in the rationalised book). Exercise 2.14 still needs relative velocity. All of these are covered on the page (marked [JEE] where NCERT no longer has the text).

### 2.1 Introduction
- [x] Kinematics: describing motion without its causes — lede
- [x] Rectilinear motion; the point-object approximation (size ≪ distance moved) — lede + Models line; Ex 2.1 idea in lede
- [x] Choice of origin and positive direction is free; signs follow it (Points to ponder 1) — §4 "positive direction up/down" chips
### Position, path length, displacement, average velocity, average speed **[JEE; dropped from the rationalised NCERT text, used by its exercises]**
- [x] Position x on an axis, positive/negative sides — §1 track with origin
- [x] Displacement vs path length (distance); |displacement| ≤ path length, equality only without turning back (Ex 2.9a) — §1 readouts + signed area
- [x] Average velocity Δx/Δt vs average speed = path length / time; avg speed ≥ |avg velocity| (Ex 2.9b, 2.10) — §1 readouts, §2 quiz
### 2.2 Instantaneous velocity and speed
- [x] v = lim Δx/Δt = dx/dt; slope of the tangent to the x–t graph — §1 tangent on x–t, §2 secant → tangent
- [x] Numerical limit (Table 2.1, x = 0.08 t³, Δt = 2 → 0.01 s, limit 3.84 m s⁻¹) — §2 chips
- [x] Example 2.1 (x = a + bt²) — §2 quiz
- [x] Speed = |velocity|; instantaneous speed equals |instantaneous velocity| (Ex 2.11) — §2 caption
### 2.3 Acceleration
- [x] Average acceleration Δv/Δt; instantaneous a = dv/dt = slope of v–t — §1 (v–t slope ↔ a–t), §2 caption
- [x] x–t curves up for a > 0, down for a < 0, straight for a = 0 (Fig 2.2) — §1 presets, §1 sketch quiz
- [x] v–t graphs for the four constant-a cases (Fig 2.3 a–d), including turning back at t₁ — §1 presets
- [x] Area under v–t = displacement (Fig 2.4); area dimension = length — §1 shading, §3
- [x] Kinks in idealised graphs; real v, a change continuously — §1 caption
- [x] Area under a–t = change in velocity **[JEE]** — §1 a–t shading
- [x] Speeding up when v and a have the same sign, slowing down when opposite; sign of a alone says nothing (Points to ponder 2, 3; Ex 2.7d) — §1 readout, §3 quiz
- [x] v = 0 does not mean a = 0 (Points to ponder 4, Ex 2.7a) — §4
- [x] Constant speed in 1D … (Ex 2.7c) — §1 lab (turn-around case); constant speed in 1D with no reversal means a = 0
### 2.4 Kinematic equations for constant acceleration
- [x] v = v₀ + at as the v–t line — §3
- [x] x = v₀t + ½at² as rectangle + triangle under v–t — §3
- [x] x = ½(v₀ + v)t, average velocity = mean of end velocities (constant a only) — §3 mean-height line
- [x] v² = v₀² + 2ax by eliminating t — §3 caption
- [x] Non-zero x₀ form; quantities are algebraic (signs) (Points to ponder 5) — §3 / §4
- [x] Calculus derivation (Example 2.2), a = v dv/dx works for non-uniform a — §3 caption **[JEE]**
- [x] Equations only for constant a; definitions always exact (Points to ponder 6) — §3 caption
- [x] Displacement in the nth second s = u + a(n − ½) **[JEE]** — §3 1-s strips
- [x] Example 2.3 (ball up from 25 m building, g = 10) — §4 preset + quiz
- [x] Example 2.4 free fall: a = −g, v = −gt, y = −½gt², v² = −2gy; a–t, v–t, y–t graphs (Fig 2.7) — §4
- [x] Example 2.5 Galileo's odd-number rule 1:3:5:7 — §3 "from rest" strips
- [x] Example 2.6 stopping distance ∝ v₀²; NCERT car data (10, 20, 34, 50 m at 11, 15, 20, 25 m/s) — §5 chart
- [x] Example 2.7 reaction time from a dropped ruler (d = 21 cm → 0.21 s) — §5 ruler game
- [x] Exercise 2.6 (ball up at 29.4 m/s, choice of downward positive) — §4 chips + quiz
- [x] Symmetry of a vertical throw (time up = time down, same speed at the same height) **[JEE]** — §4 caption
- [x] Total stopping distance = reaction distance + braking distance **[JEE]** — §5
### 2.5 Relative velocity (in TOC; body missing from the supplied text)
- [x] v_BA = v_B − v_A; x–t lines of two objects; separation line slope; parallel lines = constant gap — §6
- [x] Meeting/overtaking (Ex 2.2e) and head-on approach — §6 presets
- [x] Exercise 2.14 (bullet from police van) — §6 quiz
- [x] Relative velocity in 2D, river/rain problems **[JEE]** — linked to `vectors-relative-motion.html` (kin2)
### Exercises / graph reading
- [x] Graphs that cannot be real motion (Ex 2.12): two positions at once, negative speed, decreasing path length — §1 quiz
- [x] Sketch-matching x–t ↔ v–t ↔ a–t **[JEE]** — §1 quiz
- [~] Exercise 2.8 (bouncing ball speed–time graph) — not built; §4 stops at the ground
- [~] Exercise 2.16 (SHM x–t signs) — left to `../waves/oscillations.html`

## Motion in a plane — NCERT Class 11, "Motion in a Plane"

Modules: `mechanics/vectors-relative-motion.html` (VRM), `mechanics/projectile-circular.html` (PC: §1 launcher, §2 incline, §3 two projectiles, §4 circular motion)

Note: the 2026-27 rationalised NCERT text has no separate "relative velocity in two dimensions" section; it keeps only the rain–umbrella example (Ex. 3.1) and Points to Ponder 5 (v₁₂ = v₁ − v₂). River–boat is therefore marked [JEE].

- [x] Scalars vs vectors: magnitude only vs magnitude + direction + obeys triangle law; examples (distance, mass, temperature, time / displacement, velocity, acceleration, force) — VRM §1 (sorting quiz)
- [x] Vector notation, magnitude |v| — VRM §2 readouts
- [x] Position and displacement vectors; displacement independent of path; |displacement| ≤ path length — VRM §1 (three paths, same arrow)
- [x] Equality of vectors; free vectors (moving a vector parallel to itself leaves it unchanged) — VRM §2 (triangle mode slides B to A's head; caption)
- [x] Multiplication of a vector by a real number (positive, negative, zero → null vector); dimension of λA — VRM §2 (λA mode)
- [x] Addition: triangle (head-to-tail) method — VRM §2
- [x] Addition: parallelogram method, equivalent to triangle — VRM §2
- [x] Commutative law A + B = B + A — VRM §2 (both triangles on one parallelogram)
- [x] Associative law (A + B) + C = A + (B + C) — VRM §2 caption + quiz [~ shown as caption only, not a third draggable arrow]
- [x] Null vector: A + (−A) = 0, properties A + 0 = A, λ0 = 0, 0A = 0; physical meaning (round trip) — VRM §1 (closed path) + §2 (λ = 0)
- [x] Subtraction A − B = A + (−B) — VRM §2
- [x] Resolution of a vector along two given non-parallel vectors a, b: A = λa + µb — VRM §3 (slanted-axis mode)
- [x] Unit vectors î, ĵ, k̂; n̂ = A/|A| — VRM §3
- [x] Rectangular components Ax = A cos θ, Ay = A sin θ; components can be +, −, 0 — VRM §3 (rotating angle, quadrant signs)
- [x] Magnitude and direction from components A = √(Ax² + Ay²), tan θ = Ay/Ax — VRM §3
- [~] Three-dimensional components (cos α, cos β, cos γ; A = √(Ax² + Ay² + Az²)) — VRM §3 caption only (2-D picture)
- [x] Analytical addition by components Rx = Ax + Bx, Ry = Ay + By — VRM §2 (components toggle)
- [x] Law of cosines R² = A² + B² + 2AB cos θ and direction tan α = B sin θ/(A + B cos θ); law of sines (Ex. 3.2) — VRM §2 readouts/caption
- [x] Resultant range |A − B| ≤ |A + B| ≤ A + B (vector inequalities, Ex. 3.6) **[JEE]** — VRM §2 + quiz
- [x] Position vector r = x î + y ĵ; displacement Δr = Δx î + Δy ĵ — VRM §4
- [x] Average velocity Δr/Δt along Δr; instantaneous velocity dr/dt tangent to path (limit Δt → 0) — VRM §4 (Δt slider)
- [x] Velocity components vx = dx/dt, vy = dy/dt; magnitude and angle (Ex. 3.4: r = 3t î + 2t² ĵ) — VRM §4
- [x] Average and instantaneous acceleration Δv/Δt, components; angle between v and a can be 0°–180° in 2-D — VRM §4 (Δv toggle)
- [x] Motion with constant acceleration in a plane: v = u + at, r = r₀ + ut + ½at²; x and y motions independent — PC §1 (shadows on the axes) + VRM §4 caption
- [x] Projectile: ax = 0, ay = −g; vx constant, vy = u sin θ − gt — PC §1 (component arrows at equal time steps)
- [x] Assumption: air resistance negligible — PC (labelled "no air resistance")
- [x] Trajectory equation y = x tan θ − gx²/(2u² cos² θ): a parabola — PC §1 caption + parabola check
- [x] Time to maximum height tₘ = u sin θ/g; time of flight T = 2tₘ — PC §1
- [x] Maximum height hₘ = (u sin θ)²/2g — PC §1
- [x] Range R = u² sin 2θ/g; maximum at 45°, Rₘ = u²/g — PC §2 (range-vs-angle plot)
- [x] Complementary angles (45° ± α) give equal ranges (Ex. 3.6, Galileo) — PC §2 (ghost path)
- [x] Projectile launched horizontally from a height (Ex. 3.7 cliff) — PC §1 preset
- [x] Projectile launched from a height at an angle; best angle below 45° **[JEE]** — PC §1 (height slider + range plot)
- [x] Velocity (speed and direction) at any instant; at the top v = u cos θ, horizontal — PC §1 (time scrubber)
- [x] Trajectory shape depends on initial conditions, not only on acceleration (Points to Ponder 7) — PC §1 (θ = 90° gives a straight line) + quiz
- [x] Uniform circular motion: speed constant, velocity tangent, direction changes — PC §4
- [x] Centripetal acceleration via Δv construction (similar triangles Δv/v = Δr/R), directed to the centre — PC §4 (Δθ slider)
- [x] aᶜ = v²/R = ω²R = 4π²ν²R; not a constant vector — PC §4
- [x] Angular displacement, angular speed ω = Δθ/Δt, v = ωR — PC §4
- [x] Period T, frequency ν = 1/T, ω = 2πν, v = 2πRν — PC §4
- [x] Kinematic equations for constant acceleration do not apply to circular motion (direction of a changes) — PC §4 caption
- [x] Non-uniform circular motion: tangential + centripetal components; resultant not toward centre (Points to Ponder 6) **[JEE]** — PC §4 (tangential slider)
- [x] Relative velocity v_AB = v_A − v_B in a plane (Points to Ponder 5) — VRM §5
- [x] Rain–umbrella: tilt angle tan θ = v_horizontal,rel / v_rain (Ex. 3.1), wind case and walking case — VRM §5 (ground frame vs walker frame side by side)
- [x] River–boat: shortest time (head straight across), drift = u·d/v **[JEE]** — VRM §6
- [x] River–boat: shortest path (zero drift needs v > u, sin α = u/v); minimum drift when v < u (sin α = v/u) **[JEE]** — VRM §6
- [x] River–boat in the water frame vs ground frame **[JEE]** — VRM §6 side by side
- [x] Projectile on an inclined plane: tilted axes, g sin α / g cos α, T = 2u sin β/(g cos α), R = u²[sin(2β + α) − sin α]/(g cos²α), max at β = 45° − α/2 (bisects slope–vertical angle), R_max = u²/[g(1 + sin α)] **[JEE]** — PC §2
- [x] Relative motion of two projectiles: straight line at constant v_B − v_A in A's frame; collide-or-miss prediction (monkey-and-hunter preset) **[JEE]** — PC §3

## Laws of motion — NCERT Class 11, "Laws of Motion"

Modules: `mechanics/laws-of-motion.html` (LM), `mechanics/friction-circular-dynamics.html` (FC)

### 4.1–4.3 Aristotle's fallacy and the law of inertia
- [x] Force needed to start or stop motion; contact and non-contact (gravity, magnetic) agencies — LM §1 lede, LM §3 (Earth's pull on the book acts at a distance)
- [x] Aristotle's law ("a force is needed to keep a body moving") and why it is wrong: friction opposes motion — LM §1 (friction slider: with friction the ball stops; at zero friction it never stops)
- [x] Galileo's single inclines (down speeds up, up slows down, horizontal = in between) — LM §1 caption + right slope at 0°
- [x] Galileo's double inclined plane: ball returns to the same height; lower slope → longer path; horizontal → moves forever — LM §1 (right-slope angle slider, animation)
- [x] Inertia: rest and uniform motion are equivalent states; "resistance to change" — LM §1
### 4.4 First law
- [x] Statement; zero net force ⇔ zero acceleration — LM §1
- [x] Inferring forces from the state of motion: book on table (R = W because it is at rest, not the reverse); car at constant velocity — LM §1 quiz, LM §3
- [x] Car accelerates only through an external force (friction from the road), not internal forces — LM §3 quiz, FC §1
- [x] Inertia examples: thrown back when a bus starts, forward when it stops — LM §1 quiz
- [x] Astronaut leaving an accelerating spaceship has zero acceleration (Example 4.1) — LM §1 quiz
### 4.5 Second law, momentum, impulse
- [x] Momentum p = mv as a vector; heavier/faster bodies need more force to stop — LM §2
- [x] Same force for the same time gives the same momentum to different masses — LM §2 (two carts)
- [x] Catching a ball: drawing hands back lengthens the time, lowering the force — LM §2 (catch slider, F–t pulse)
- [x] Force needed to change only the direction of momentum (stone whirled on a string) — FC §4
- [x] F = dp/dt = ma; definition of the newton; k = 1 — LM §2 caption
- [x] Second law is a vector law: Fx = max etc.; force changes only the velocity component along it (projectile) — LM §2 quiz
- [x] Applies to systems: F = total external force, a = acceleration of the CM; internal forces excluded — LM §3 (book + table system), LM §6 (two blocks as one system)
- [x] Second law is local: no memory of past acceleration (stone dropped from an accelerating train) — LM §2 quiz
- [x] Impulse = F Δt = Δp; impulsive force; area under the F–t graph — LM §2
- [x] Ball bounced back by a bat: impulse 2mv (Example 4.4) — LM §2 quiz
- [x] Ball hitting a wall at an angle: force on the wall is normal to the wall (Example 4.5) — LM §4 quiz
### 4.6 Third law
- [x] Forces occur in pairs; F_AB = −F_BA; also at a distance (stone pulls the Earth) — LM §3
- [x] No cause and effect: the pair is simultaneous — LM §3 caption
- [x] Pair forces act on different bodies and never cancel each other — LM §3 (pick a force, see its partner on the other body)
- [x] Internal forces of a system cancel in pairs — LM §3 (book + table chip)
- [x] Weight and normal force on a book are NOT a third-law pair (Example 4.12 discussion) — LM §3
### 4.7 Conservation of momentum
- [x] Gun recoil: p_gun = −p_bullet — LM §4
- [x] Isolated system: total momentum conserved; collisions, elastic or not — LM §4 (link to `collisions.html` for collisions)
- [x] Nucleus splitting into two: fragments fly apart in opposite directions (Ex 4.17) — LM §4 preset
### 4.8 Equilibrium of a particle
- [x] Two forces: equal and opposite; three forces: vector sum zero, closed triangle; n forces: closed polygon — LM §5
- [x] Component form ΣFx = ΣFy = 0 — LM §5 caption
- [x] Rope and weight pulled sideways at a point (Example 4.6); answer independent of rope length — LM §5
- [x] Footnote: a rigid body also needs zero torque — LM §5 caption, link to `torque-angular-momentum.html`
### 4.9 Common forces
- [x] Gravity vs contact forces; contact force = normal + friction components — FC §1
- [~] Buoyancy, viscous drag, air resistance as contact forces — named only (LM §6 caption); buoyancy belongs to fluids
- [x] Spring force F = −kx; tension in a light string is the same throughout — LM §6 (pulley systems, caption)
- [x] Contact forces are electrical in origin (qualitative) — FC §1 caption
### 4.9.1 Friction
- [x] Static friction self-adjusting, f_s ≤ µ_s N; opposes impending motion — FC §1 (push slider + graph)
- [x] Limiting friction independent of contact area — FC §1 caption
- [x] Kinetic friction f_k = µ_k N < µ_s N, nearly independent of speed; a = (F − f_k)/m — FC §1
- [x] Laws of friction are empirical — FC §1 tag
- [x] Friction opposes relative motion, not motion: box in an accelerating train, a_max = µ_s g (Example 4.7) — FC §1 quiz
- [x] Angle of repose: tan θ_max = µ_s, independent of mass (Example 4.8) — FC §2
- [x] Block on a rough incline: friction up or down the slope, range of push for equilibrium **[JEE]** — FC §2
- [x] Block on a rough table pulled by a hanging block (Example 4.9) — LM §6 (pulley system with µ_k slider)
- [x] Rolling friction: why it exists (deformation), much smaller than sliding friction — FC §3, link to `rolling-motion.html`
- [x] Friction as useful and harmful; lubricants, ball bearings, air cushion; walking and driving need friction — FC §3
### 4.10 Circular motion
- [x] Centripetal force f_c = mv²/R is not a new kind of force: tension, gravity, friction, normal force supply it — FC §4
- [x] String cut → stone flies off along the tangent (Ex 4.22) — FC §4 (cut the string)
- [x] Car on a level road: friction supplies it; v_max = √(µ_s R g), independent of mass — FC §5
- [x] Cyclist turning on a level road (Example 4.10) — FC §5 quiz
- [x] Banked road: N cos θ = mg + f sin θ, N sin θ + f cos θ = mv²/R — FC §6
- [x] Optimum speed v₀ = √(R g tan θ): no friction needed — FC §6
- [x] Maximum speed on a banked road with friction, v_max = √(Rg (µ_s + tan θ)/(1 − µ_s tan θ)) — FC §6
- [x] Below v₀ friction acts up the slope; car can be parked only if tan θ ≤ µ_s — FC §6
- [x] Minimum speed on a banked road, v_min = √(Rg (tan θ − µ_s)/(1 + µ_s tan θ)) **[JEE]** — FC §6
- [x] Feeling of being pushed outward on a merry-go-round vs the real inward force (Points to ponder 11) — FC §4 caption
- [x] Vertical circle — not in this NCERT chapter (no vertical-circle section in the 2026–27 text); covered with energy conservation in `mechanics/work-energy.html` §7
### 4.11 Solving problems: free-body diagrams
- [x] Choose a system, draw all forces on it by the environment (not the forces it exerts) — LM §6
- [x] Block on a table with an applied force — LM §6
- [x] Block pushed on a smooth incline — LM §6
- [x] Two blocks in contact; two blocks joined by a string (Ex 4.15) **[JEE]** — LM §6
- [x] Atwood machine (Ex 4.16): a = (m₂ − m₁)g/(m₁ + m₂), T = 2m₁m₂g/(m₁ + m₂) — LM §6
- [x] Lift: apparent weight N = m(g + a); free fall reads zero (Ex 4.13) — LM §6
- [x] Block + cylinder sinking into a soft floor; action on the floor (Example 4.12) — LM §3 quiz

## Work, energy and power — NCERT Class 11, "Work, Energy and Power"

Module: `mechanics/work-energy.html`, `mechanics/collisions.html`

- [~] Scalar (dot) product: A·B = AB cos θ; projection of one vector on the other; component form AxBx + AyBy + AzBz; commutative, distributive; A·B = 0 for perpendicular vectors — work-energy.html §1 (projection drawn; component form in caption; quiz Q1). Commutative/distributive laws stated only implicitly
- [x] Work–energy theorem from v² − u² = 2a·d: K_f − K_i = W_net — work-energy.html §2
- [x] Work by a constant force: W = Fd cos θ = F·d; positive, zero and negative work — work-energy.html §1
- [x] The three zero-work cases: no displacement, no force, force ⟂ displacement — work-energy.html §1
- [x] Unit (joule) and dimensions [ML²T⁻²]; alternative units (eV, kWh) — work-energy.html §1 caption, §7 caption (kWh, eV)
- [x] Work done on A by B is not minus the work on B by A (Newton's third law pairs; cyclist and road) — work-energy.html quiz Q2
- [x] Kinetic energy K = ½mv²; scalar; speed vs KE fraction (bullet example) — work-energy.html §2, quiz Q3
- [x] Work by a variable force = area under F–x graph (sum of strips → integral); area below the axis is negative — work-energy.html §2 (strip stepper, negative area)
- [x] Work–energy theorem for a variable force; it is the integral (scalar) form of Newton's 2nd law and loses time and direction information — work-energy.html §2 caption
- [x] Use of WE theorem when a force is unknown (raindrop with air resistance) — work-energy.html quiz Q4
- [x] Potential energy as stored energy; gravitational PE mgh (h ≪ R_E) — work-energy.html §3
- [x] F = −dV/dx — work-energy.html §4 (slope = force, F(x) plot)
- [x] Conservative force: three definitions (from a potential; path-independent work; zero work round a closed path) — work-energy.html §3
- [x] Non-conservative forces (friction): path-dependent work, no PE — work-energy.html §3, §6
- [x] Conservation of mechanical energy K + V = constant (falling ball from a cliff) — work-energy.html §6 (energy bars)
- [x] Pendulum / vertical circle with energy conservation (NCERT Ex 5.7: v₀ = √(5gL), v_B = √(3gL), v_C = √(gL)) — work-energy.html §7 (string / rod / bead, T–θ graph, slack point and projectile path, questions 7.1–7.2), §6 pendulum, quiz Q6
- [x] Zero of potential energy is arbitrary; only changes matter — work-energy.html §3 caption
- [x] Spring: Hooke's law F = −kx, spring constant (stiff/soft) — work-energy.html §5
- [x] Work by spring force −½kx² as the triangle area; from x_i to x_f; zero round a cycle → conservative — work-energy.html §5
- [x] Spring PE ½kx²; K and V parabolas complementary; v_max = √(k/m)·x_m — work-energy.html §5, §6 spring, §4 spring landscape
- [x] Spring with friction (car into spring): W_nc = ΔE = E_f − E_i — work-energy.html §6 friction, quiz Q5
- [x] Power: average W/t and instantaneous dW/dt = F·v; watt, horsepower (1 hp = 746 W); kWh as a unit of energy — work-energy.html §7, quiz Q7
- [x] Collisions: momentum conserved (third law, impulses equal and opposite); KE need not be — collisions.html §1
- [x] Elastic, inelastic, completely inelastic collisions; deformation as a "compressed spring" — collisions.html §1 (bumper = compressed spring)
- [x] Completely inelastic 1D: v_f = m₁v₁ᵢ/(m₁ + m₂); KE lost ½·m₁m₂/(m₁+m₂)·v₁ᵢ² — collisions.html §1 preset, quiz Q4
- [x] Elastic 1D with target at rest: v₁f = (m₁ − m₂)v₁ᵢ/(m₁+m₂), v₂f = 2m₁v₁ᵢ/(m₁+m₂) — collisions.html §2
- [x] Special cases: equal masses exchange velocities; m₂ ≫ m₁ → light body bounces back — collisions.html §1 presets, §2
- [x] Slowing down of neutrons: fraction of KE transferred 4m₁m₂/(m₁+m₂)² (deuterium 8/9, carbon 28.4%) — collisions.html §2 presets, quiz Q5
- [x] Collisions in 2D: momentum components; 4 unknowns vs 3 equations (one angle must be given) — collisions.html §3 caption
- [x] Equal masses, elastic, one at rest → move off at 90° (billiards, θ₂ = 37° → θ₁ = 53°) — collisions.html §3, quiz Q8
- [x] During the collision KE is not conserved even for elastic; momentum conserved at every instant; bodies momentarily at rest relative to each other — collisions.html §1 bars, quiz Q7
- [ ] Scattering (action at a distance) mentioned, qualitative — not covered (one-line qualitative mention in NCERT; left out)
- [x] Coefficient of restitution e = (separation speed)/(approach speed); e = 1 elastic, 0 perfectly inelastic **[JEE]** — collisions.html §1
- [x] General 1D formulas with both bodies moving, any e **[JEE]** — collisions.html §1
- [x] Centre-of-mass frame view of a collision: velocities reverse (scaled by e) **[JEE]** — collisions.html §1 (lower track)
- [x] KE loss in general: ½·μ(1 − e²)·u_rel² with μ = m₁m₂/(m₁+m₂) **[JEE]** — collisions.html §1
- [x] Ball bouncing on the floor: height after n bounces e²ⁿh **[JEE]** — collisions.html quiz Q3
- [x] Ballistic pendulum **[JEE]** — collisions.html quiz Q2
- [x] Potential-energy curves: turning points, allowed/forbidden regions, stable/unstable/neutral equilibrium **[JEE; NCERT exercises 5.3, 5.4]** — work-energy.html §4
- [x] Constant-power motion: v ∝ t^½, x ∝ t^(3/2) **[JEE; NCERT exercise 5.10]** — work-energy.html quiz Q8
- [x] Work by a spring between two stretched positions ½k(x₂² − x₁²) **[JEE]** — work-energy.html §5 (start x₁ slider)
- [x] Vertical circle critical speeds: √(5gL) string, 2√(gL) rod/bead; slack angle cos θ = (2gL − u²)/(3gL) for √(2gL) < u < √(5gL); T_bottom − T_top = 6mg **[JEE]** — work-energy.html §7

## System of particles and rotational motion — NCERT Class 11, "System of Particles and Rotational Motion"

Modules: `mechanics/centre-of-mass.html` (CM), `mechanics/torque-angular-momentum.html` (TAM); existing `mechanics/moment-of-inertia.html` (01), `mechanics/rolling-motion.html` (02)

### 6.1 Introduction
- [x] Rigid body as an idealisation (no real body is truly rigid) — TAM §1 caption
- [x] Pure translation: every particle has the same velocity at an instant — CM §3 ("Baton, no spin" chip vs "Tumbling baton")
- [x] Rotation about a fixed axis: each particle moves in a circle in a plane ⊥ axis, centre on the axis; points on the axis stay still — TAM §1
- [x] Rotation with one point fixed / moving axis (spinning top, precession; oscillating fan), qualitative — TAM §1 caption
- [x] General motion of an unconstrained body = translation of the CM + rotation about it (Fig. 6.6) — CM §3 tumbling baton
- [x] Rolling = translation + rotation — linked to rolling-motion.html (02)

### 6.2 Centre of mass
- [x] Two particles: X = (m₁x₁ + m₂x₂)/(m₁ + m₂), mass-weighted mean; equal masses → midpoint — CM §1
- [x] CM lies closer to the heavier mass; divides the line in the inverse ratio of masses **[JEE]** — CM §1
- [x] n particles on a line; in a plane; in space; vector form R = Σmᵢrᵢ/M — CM §1 (up to 4 draggable masses, 2D)
- [x] Three equal masses → centroid of the triangle; unequal masses → not the centroid (Example 6.1) — CM §1 preset
- [x] Choosing the CM as origin: Σmᵢrᵢ = 0 — CM §1 ("origin at CM" toggle)
- [x] CM does not depend on the choice of origin **[JEE]** — CM §1 (drag the origin)
- [x] Continuous bodies: R = (1/M)∫r dm — CM §2 caption
- [x] Symmetry: CM of uniform rod, ring, disc, sphere, cylinder, cube at the geometric centre (reflection symmetry) — CM §2
- [x] Triangular lamina: CM on each median, at the centroid (Example 6.2) — CM §2 (draggable vertices, strips)
- [x] Composite bodies: L-shaped lamina (Example 6.3), parts replaced by point masses at their CMs; parts of different masses — CM §2
- [x] Cavity / removed part as negative mass: disc with a hole (Exercise 6.15) **[JEE]** — CM §2
- [x] CM need not lie inside the body (ring, semicircular ring) (Exercise 6.1) — CM §2
- [x] Semicircular ring 2R/π, semicircular disc 4R/3π, solid hemisphere 3R/8, hemispherical shell R/2, solid cone h/4 **[JEE]** — CM §2
- [x] Molecule CM: HCl (Exercise 6.2) — CM §1 preset + quiz

### 6.3 Motion of the centre of mass
- [x] MV = Σmᵢvᵢ, MA = Σmᵢaᵢ — CM §3 caption
- [x] MA = F_ext: internal forces cancel in pairs (Newton's third law) — CM §3, §4
- [x] CM moves as if all mass were there and all external forces acted there — CM §3
- [x] Exploding projectile: CM continues the parabola (Fig. 6.12); and why it stops doing so once a fragment hits the ground **[JEE]** — CM §3

### 6.4 Linear momentum of a system
- [x] P = Σpᵢ = MV; dP/dt = F_ext — CM §3 (momentum arrows add to M·v_cm)
- [x] Conservation of total momentum when F_ext = 0; V_cm constant — CM §4
- [x] Internal forces cannot move the CM: person walking on a boat / child on a trolley (Exercise 6.3) **[JEE]** — CM §4
- [x] Radioactive decay (Ra → Rn + α) in lab frame and CM frame — CM §5
- [x] Binary stars: CM in uniform motion; circles about the CM in the CM frame — CM §5
- [x] K = K′ + ½MV² (Points to ponder 2) — CM §3 (energy bars)

### 6.5 Vector product
- [x] Definition: |a × b| = ab sin θ, ⊥ to the plane of a and b — TAM §2
- [x] Direction: right-hand screw / right-hand rule; take the smaller angle — TAM §2 (⊙/⊗, curl arrow)
- [x] Not commutative: a × b = −b × a — TAM §2 (swap button)
- [x] a × a = 0; parallel vectors give zero — TAM §2
- [x] Unaffected by reflection (a × b → (−a) × (−b)) — TAM §2 caption
- [x] Distributive over addition — TAM §2 caption
- [x] î × ĵ = k̂ etc.; cyclic order positive, anti-cyclic negative — TAM §2 (cycle diagram)
- [x] Component / determinant form; Example 6.4 — TAM §2 caption + quiz
- [x] Area of parallelogram = |a × b|; triangle = ½|a × b| (Exercise 6.4) — TAM §2
- [x] Scalar triple product = volume of parallelepiped (Exercise 6.5) **[JEE]** — TAM §2 caption

### 6.6 Angular velocity
- [x] Angular displacement, ω = dθ/dt, same ω for every particle of the rigid body — TAM §1
- [x] v = ωr⊥ for each particle; points on the axis at rest — TAM §1
- [x] ω as a vector along the axis (right-hand rule); v = ω × r — TAM §1
- [x] Angular acceleration α = dω/dt — TAM §7

### 6.7 Torque and angular momentum
- [x] Torque τ = r × F; τ = rF sin θ = r⊥F = rF⊥; zero if F passes through the origin — TAM §3 (door)
- [x] Units N m; same dimensions as work, but a vector and a different quantity — TAM §3 caption
- [x] Reversing F reverses τ (TAM §3 caption); reversing both vectors leaves the product unchanged (TAM §2 caption)
- [x] Angular momentum of a particle l = r × p; l = r⊥p = rp⊥ — TAM §4
- [x] dl/dt = τ for a particle (v × mv = 0 step) — TAM §4
- [x] Particle in a straight line at constant velocity: l constant (Example 6.6) — TAM §4
- [x] System: L = Σlᵢ; dL/dt = τ_ext; internal torques cancel (central forces) — TAM §4 caption, §5
- [x] Conservation of angular momentum when τ_ext = 0 — TAM §5
- [x] Two particles on parallel lines: L same about every point (Exercise 6.7) **[JEE]** — TAM §4
- [x] Bicycle-rim gyroscope / precession, qualitative — TAM §5 caption (qualitative only)

### 6.8 Equilibrium of a rigid body
- [x] Translational equilibrium ΣF = 0 AND rotational equilibrium Στ = 0; 6 scalar conditions, 3 for coplanar forces — TAM §6
- [x] Partial equilibrium: net torque zero but net force not, and vice versa — TAM §6 (rod with two forces)
- [x] Couple: equal, opposite, different lines of action; rotation without translation; moment independent of origin (Example 6.7) — TAM §6
- [x] Torque about any point is the same if ΣF = 0 — TAM §6
- [x] Principle of moments, lever, load arm/effort arm, mechanical advantage — TAM §6 (seesaw)
- [x] Bar on two knife-edges (Example 6.8) — TAM §6 preset
- [x] Ladder against a frictionless wall (Example 6.9) — TAM quiz
- [x] Metre stick balanced with coins (Exercise 6.16) — TAM §6 preset
- [x] Centre of gravity: point of zero gravitational torque; = CM in uniform g; differs if g varies — CM §6
- [x] Finding CG by suspension (Fig. 6.25) — CM §6

### 6.9 Moment of inertia
- [x] I = Σmᵢrᵢ², depends on mass distribution and axis — covered by moment-of-inertia.html §1
- [x] Radius of gyration — covered by moment-of-inertia.html §1
- [x] Table of standard I values — covered by moment-of-inertia.html §1, §4
- [x] Parallel- and perpendicular-axis theorems **[JEE]** — covered by moment-of-inertia.html §2, §3
- [x] Rotational KE ½Iω² (derivation from Σ½mv²) — TAM §8 (dictionary, flywheel)
- [x] Flywheel — TAM §8 (Example 6.12)

### 6.10 Kinematics of rotation about a fixed axis
- [x] ω = ω₀ + αt, θ = ω₀t + ½αt², ω² = ω₀² + 2αθ as analogues of the linear equations — TAM §7 (ω–t graph, area = θ)
- [x] Example 6.11: 1200 → 3120 rpm in 16 s — TAM §7 preset
- [x] rpm ↔ rad/s conversion — TAM §7

### 6.11 Dynamics of rotation about a fixed axis
- [x] Only torque components along the axis matter for fixed-axis rotation — TAM §8 caption
- [x] Work by a torque dW = τ dθ; power P = τω — TAM §8
- [x] τ = Iα (from work–energy) — TAM §8
- [x] Translation ↔ rotation dictionary (Table 6.2) — TAM §8 (paired live panels)
- [x] Flywheel with a cord (Example 6.12) — TAM §8
- [x] Rope on a cylinder, block hanging from a pulley with I **[JEE]** — TAM quiz

### 6.12 Angular momentum for fixed-axis rotation
- [x] L_z = Iω; L along the axis only for symmetric bodies (L and ω not always parallel) — TAM §5 caption
- [x] d(Iω)/dt = τ — TAM §5
- [x] Conservation: swivel chair, skater, diver; Iω = const; KE rises when I falls (Exercise 6.12) — TAM §5

### Rolling (6.1 / rolling sections)
- [x] Rolling = translation + rotation, v = ωR, KE of rolling, incline — covered by rolling-motion.html

## Gravitation — NCERT Class 11, "Gravitation"

Modules: `mechanics/gravitation.html` (G), `mechanics/orbits-satellites.html` (O)

Note: the 2026-27 NCERT text (rationalised) has sections 7.1–7.10: introduction, Kepler's laws, universal law, G, g of the Earth, g above and below the surface, gravitational PE, escape speed, Earth satellites, energy of an orbiting satellite. Geostationary/polar satellites and weightlessness are no longer separate NCERT sections (weightlessness survives in "Points to ponder"); they are kept below as [JEE].

### 7.1–7.2 Kepler's laws
- [x] History: geocentric (Ptolemy) vs heliocentric (Copernicus), Tycho Brahe's data, Kepler — G §1 lede (one line, no pictures needed)
- [x] Ellipse: foci, sum of distances from the foci constant (string-and-pins construction), semi-major axis, perihelion/aphelion; circle as special case — G §1 (string lines r₁ + r₂ = 2a live)
- [x] Law of orbits: Sun at one focus — G §1
- [x] Law of areas: equal areas in equal times; planet faster near perihelion — G §1 (equal-time wedges shaded, speed arrow)
- [x] Law of areas from conservation of angular momentum (central force): dA/dt = L/2m — G §1 caption
- [x] v_p r_p = v_a r_a, i.e. v_p/v_a = (1 + e)/(1 − e) **[JEE]** — G §1 readout + quiz
- [x] Law of periods T² ∝ a³, with real planet data — G §2 (log–log plot, NASA data, T²/a³ table)
- [x] Kepler's third law derived for a circular orbit (GMm/r² = mv²/r) — G §2 caption; O §3
- [x] Planet orbits nearly circular except Mercury and Mars (NCERT note); eccentricities of real planets — G §1 presets

### 7.3 Universal law of gravitation
- [x] F = Gm₁m₂/r², inverse square, along the line joining the masses; equal and opposite (Newton III) — G §3 (drag)
- [x] Vector form F₁₂ = −Gm₁m₂ r̂₁₂/r² — G §3 caption
- [x] Superposition of gravitational forces (Example 7.2, masses at a triangle) — G §3 (triangle toggle) + quiz
- [x] Newton's Moon test: a_moon = g(R_E/R_m)² (NCERT box) — G §3 quiz item
- [x] Shell theorem: uniform shell acts as a point mass outside, zero force inside — G §4 (numerical sum over the shell, F vs distance plot, cone argument)
- [x] Force between extended bodies not necessarily along the line of centres; central for spheres (Points to ponder 8) — G §4 caption
- [x] No gravitational shielding (Points to ponder 9, Ex 7.1a) — G §4 caption

### 7.4 The gravitational constant
- [x] Cavendish torsion balance: torque GMmL/d² = τθ — G §4b (schematic)
- [x] Value G = 6.674 × 10⁻¹¹ N m² kg⁻² (CODATA); weakness of gravity — G §4b

### 7.5 g of the Earth
- [x] g = GM_E/R_E² from the shell theorem — G §5
- [x] "Cavendish weighed the Earth": M_E = gR²/G (Example 7.6) — G §5 + quiz
- [x] Variation of g with latitude (rotation) g' = g − ω²R cos²λ, and oblateness **[JEE]** — G §5 (latitude slider)

### 7.6 g above and below the surface
- [x] g(h) = GM/(R + h)², falls as 1/r² — G §6 (one graph, drag)
- [x] Small heights: g(h) ≈ g(1 − 2h/R) — G §6 (dashed tangent)
- [x] Depth: g(d) = g(1 − d/R) for uniform density; zero at centre — G §6
- [x] g maximum at the surface (uniform model); real Earth is denser inside (exception) — G §6 caption
- [x] Comparisons: depth d vs height h for equal g (d = 2h small) **[JEE]** — G §6 quiz
- [x] Gravitational field intensity E = F/m (as g) inside/outside a sphere and a shell **[JEE]** — G §4 (shell plot) and §6 (solid sphere)

### 7.7 Gravitational potential energy
- [x] Work done by gravity between r₁ and r₂; U(r) = −GMm/r with U(∞) = 0; only differences matter — G §7
- [x] mgh as the near-surface approximation of ΔU, error factor 1/(1 + h/R) — G §7 (slider, both shown)
- [x] Gravitational potential V = U/m — G §7
- [x] Potential energy of a system of particles (sum over pairs; Example 7.3, square −5.41Gm²/l) — G §7 quiz
- [x] Potential inside a uniform solid sphere −GM(3R² − r²)/2R³ **[JEE]** — G §7 (curve inside)
- [x] Neutral point between two masses (Example 7.4) — G quiz

### 7.8 Escape speed
- [x] Energy condition ½mv² − GMm/r ≥ 0; v_e = √(2GM/R) = √(2gR) ≈ 11.2 km/s — O §2
- [x] Escape speed from a height h: √(2GM/(R + h)) — O §2 caption
- [x] Moon's escape speed (about 2.4 km/s) and thin atmosphere — O §2 (Earth/Moon/Mars chips, labelled simplified)
- [x] Escape speed independent of launch direction and of mass **[JEE]** — O §2 caption
- [x] Maximum height for v < v_e: r_max = R/(1 − v²/v_e²) (Ex 7.17); speed at infinity √(v² − v_e²) (Ex 7.18) — O §2 (energy well)

### 7.9 Earth satellites
- [x] Newton's cannon: falls back / circular / elliptical / escape **[JEE framing]** — O §1
- [x] Orbital speed v_orb = √(GM/(R + h)), near surface √(gR) ≈ 7.9 km/s; v_e = √2 v_orb — O §1, §3
- [x] Period T = 2π(R + h)^{3/2}/√(GM); near-surface T₀ = 2π√(R/g) ≈ 85 min — O §3
- [x] Kepler's third law for satellites; holds for ellipses with a — O §3 caption; G §2
- [x] Moon’s period from T² = kr³ (Examples 7.6, 7.7) — O §3 marker + O quiz Q9 (Kepler vs measured 27.32 d, Moon’s own mass)
- [x] Geostationary satellite: period one sidereal day, equatorial, h ≈ 36 000 km **[JEE]** — O §4
- [x] Polar satellites: low orbit, Earth turns beneath, ground track shift **[JEE]** — O §4

### 7.10 Energy of an orbiting satellite
- [x] K = GMm/2r, U = −GMm/r, E = −GMm/2r; K = −E = −½U — O §5 (bars)
- [x] Negative total energy = bound; E ≥ 0 escapes — O §5, §1
- [x] Elliptical orbit E = −GMm/2a — O §5 caption
- [x] Binding energy / energy to move to a higher orbit or escape (Ex 7.19, Example 7.8) **[JEE]** — O §5 + quiz
- [x] Higher orbit: more total energy, but slower (K falls) **[JEE]** — O §5 caption

### Points to ponder / exercises
- [x] Conserved: angular momentum and mechanical energy (not linear momentum of the planet) — G §1 caption
- [x] Weightlessness in orbit: free fall, not absence of gravity — O §6
- [~] Tidal effect of Moon vs Sun (Ex 7.1c) — not covered (needs its own picture; not core JEE)
- [~] Two-body motion about the centre of mass, reduced mass **[JEE advanced]** — not covered

## Kinetic theory of gases — NCERT Class 11, "Kinetic Theory"

Module: `thermodynamics/kinetic-theory.html` (05), `thermodynamics/degrees-of-freedom.html` (06)

- [~] Molecular nature of matter: Dalton's atomic theory, Avogadro's hypothesis, Avogadro's number — Avogadro covered (05); Dalton's atomic theory (history) not shown
- [x] Gas laws from the molecular picture: Boyle, Charles, ideal-gas equation PV = µRT = Nk<sub>B</sub>T
- [x] Dalton's law of partial pressures
- [x] Real vs ideal gas: PV/T vs P plots, ideal behaviour at low P and high T (qualitative)
- [x] Assumptions of kinetic theory (and which ones fail for real gases)
- [x] Pressure of an ideal gas from molecular collisions: P = ⅓ n m ⟨v²⟩
- [x] Kinetic interpretation of temperature: average KE per molecule = (3/2) k<sub>B</sub>T, independent of the gas
- [x] rms speed: v<sub>rms</sub> = √(3k<sub>B</sub>T/m) = √(3RT/M); dependence on T and molar mass
- [x] Heavier molecules move slower at the same T; diffusion rate (Graham's law) **[JEE]**
- [x] Distribution of molecular speeds (Maxwell) **[JEE; NCERT mentions only that a distribution exists]**
- [x] The three speeds: most probable v<sub>mp</sub> = √(2RT/M), average v<sub>avg</sub> = √(8RT/πM), rms; their order v<sub>mp</sub> < v<sub>avg</sub> < v<sub>rms</sub> and ratio **[JEE]**
- [x] How the distribution changes with T and with molar mass (area stays the same) **[JEE]**
- [x] Degrees of freedom: translational, rotational, vibrational; counting for each molecule type
- [x] Law of equipartition of energy: ½k<sub>B</sub>T per quadratic term; a vibrational mode counts twice (KE + PE)
- [x] Monatomic gas: f = 3, C<sub>v</sub> = 3R/2, C<sub>p</sub> = 5R/2, γ = 5/3
- [x] Diatomic gas, rigid: f = 5, γ = 7/5; with vibration: f = 7, γ = 9/7
- [x] Polyatomic gases: linear vs non-linear, 3 rotational DOF for non-linear, vibrational modes f
- [x] C<sub>p</sub> − C<sub>v</sub> = R; γ = 1 + 2/f
- [x] γ of a gas mixture **[JEE]**
- [x] Specific heat of solids: 3 vibrational modes per atom → C = 3R (Dulong–Petit), and where it fails (low T)
- [x] Specific heat of water (about 9R, qualitative)
- [x] Why classical predictions fail (modes "frozen" at low T; quantum explanation, qualitative)
- [x] Mean free path: l = 1/(√2 n π d²); dependence on n and d
- [x] Brownian motion as evidence of molecular motion (qualitative)

## Heat transfer — NCERT Class 11, "Thermal Properties of Matter" (heat transfer, Newton's law of cooling)

Module: `thermodynamics/heat-transfer.html` (07)

- [x] Three modes: conduction, convection, radiation, and when each dominates
- [x] Conduction: steady state, temperature gradient, H = KA(T<sub>C</sub> − T<sub>D</sub>)/L, thermal conductivity K
- [x] Conductors vs insulators (metals vs air, why fluffy materials insulate)
- [x] Compound bars in series (equivalent K, junction temperature) and parallel
- [x] Thermal resistance R = L/KA and the analogy with electric circuits **[JEE]**
- [x] Non-steady state / growth of ice layer on a pond **[JEE]**
- [x] Convection: natural vs forced; density differences
- [x] Sea breeze and land breeze; trade winds
- [x] Radiation: needs no medium; electromagnetic waves
- [x] Black body; Wien's displacement law λ<sub>m</sub>T = b
- [x] Stefan–Boltzmann law H = AσT⁴; emissivity e; net loss eAσ(T⁴ − T<sub>s</sub>⁴)
- [x] Absorptivity, reflectivity; good absorbers are good emitters; Kirchhoff's law **[JEE]**
- [x] Applications: thermos (Dewar) flask; dark vs light clothing; greenhouse effect (qualitative)
- [x] Newton's law of cooling: dT/dt = −k(T − T<sub>s</sub>), for small temperature differences; exponential cooling curve
- [x] Average-temperature form for problems ((T₁ − T₂)/t = k(T̄ − T<sub>s</sub>)) **[JEE]**
- [x] Newton's law of cooling as the small-difference limit of Stefan's law **[JEE]**

## Temperature and thermal expansion — NCERT Class 11, "Thermal Properties of Matter" (temperature, thermometry, expansion)

Module: `thermodynamics/temperature-expansion.html` (08)

- [x] Temperature vs heat (heat = energy in transit because of a temperature difference)
- [x] Thermometers use a property that changes with temperature; two fixed points (ice point, steam point)
- [x] Celsius and Fahrenheit scales, conversion t<sub>F</sub> = (9/5)t<sub>C</sub> + 32 (straight-line graph); any linear scale conversion **[JEE]**
- [x] Constant-volume gas thermometer: P ∝ T at low density, extrapolation of all gases to the same absolute zero (−273.15 °C)
- [x] Kelvin scale T = t<sub>C</sub> + 273.15; triple point of water 273.16 K as the fixed point
- [x] Ideal-gas equation PV = µRT as the link between gas thermometry and absolute temperature
- [x] Thermal expansion: linear (α<sub>l</sub>), area (α<sub>a</sub>), volume (α<sub>v</sub>); ΔL = α<sub>l</sub>LΔT
- [x] Relations α<sub>a</sub> = 2α<sub>l</sub>, α<sub>v</sub> = 3α<sub>l</sub> (from the square / cube picture)
- [x] Typical values: metals vs glass vs invar; liquids expand more than solids; gases most (α<sub>v</sub> = 1/T for an ideal gas)
- [x] α<sub>v</sub> depends on temperature (copper curve, qualitative)
- [x] Molecular reason for expansion (asymmetric interatomic potential, qualitative) **[JEE]**
- [x] Anomalous expansion of water: densest at 4 °C; why lakes freeze from the top and life survives
- [x] Thermal stress: rod clamped between walls, stress = YαΔT; railway tracks, rings on wheels
- [x] A hole expands like the material around it **[JEE]**
- [x] Bimetallic strip (bending, thermostats) **[JEE]**
- [x] Apparent vs real expansion of a liquid in an expanding container **[JEE]**
- [x] Pendulum clock losing/gaining time with temperature; error of a metal scale **[JEE]**

## Heat, calorimetry and change of state — NCERT Class 11, "Thermal Properties of Matter" (specific heat, calorimetry, change of state)

Module: `thermodynamics/calorimetry-phase.html` (09)

- [x] Heat capacity S = ΔQ/ΔT; specific heat capacity s = ΔQ/(mΔT); molar specific heat C
- [x] Molar specific heats at constant pressure and constant volume for gases (Table 10.4; link to modules 03, 06)
- [x] Water's high specific heat and its consequences (coolant, climate; link to sea breeze in 07)
- [x] Calorimetry: principle of heat exchange (heat lost = heat gained in an isolated system); the calorimeter
- [x] Finding a specific heat by the method of mixtures (NCERT example)
- [x] Water equivalent of a calorimeter **[JEE]**
- [x] Change of state: melting, freezing, vaporisation, condensation, sublimation; states coexist at constant temperature
- [x] Heating curve of water (temperature vs heat): sloped parts and plateaus; slopes differ because specific heats differ
- [x] Latent heat Q = mL; L<sub>f</sub> and L<sub>v</sub> of water; latent heat depends on pressure; Table 10.5
- [x] Why steam burns are worse than boiling-water burns
- [x] Mixing ice and water: final state when not all the ice melts **[JEE]**
- [x] Melting point and boiling point depend on pressure; normal melting/boiling points
- [x] Boiling point vs pressure: cooking on hills, pressure cooker; boiling under reduced pressure (NCERT activity)
- [x] Regelation and skating (melting point lowered by pressure)
- [x] Sublimation: dry ice, iodine
- [x] Phase (P–T) diagrams of water and CO₂: fusion, vaporisation and sublimation curves; triple point; why water's fusion curve slopes backwards

## Oscillations and SHM — NCERT Class 11, "Oscillations" (Ch 13, rationalised)

Module: `waves/oscillations.html`

- [x] Periodic motion; examples — §1 (whirled ball, bouncing ball, V-trough, block on spring; heartbeat quiz). NCERT's insect-on-ramp and child-on-step pictures not redrawn (same idea as the bouncing ball)
- [x] Equilibrium position and restoring force; oscillatory motion; every oscillatory motion is periodic, not every periodic motion is oscillatory (circular motion) — §1 classifier + nested boxes
- [x] Oscillation vs vibration (only a matter of frequency); real oscillations die out (damping, qualitative mention) — §1 caption
- [x] Period T, frequency ν = 1/T, unit hertz; ν need not be an integer — §1 caption, §2 readouts, §1 Q1 (1.25 Hz)
- [x] Displacement in the general sense (angle of a pendulum, voltage, pressure) — §1 caption; pendulum angle §7
- [x] Periodic functions: A cos ωt, period 2π/ω; A sin ωt + B cos ωt = D sin(ωt + φ) — §2, §9 Q1
- [x] Fourier: any periodic function is a sum of sines and cosines (qualitative) — §9 Q3 explanation
- [x] Periodic vs non-periodic functions (sin ωt + cos 2ωt + sin 4ωt; e<sup>−ωt</sup>) — §9 Q3, Q4 (log ωt not used)
- [x] SHM defined: x(t) = A cos(ωt + φ); amplitude, phase, phase constant, angular frequency — §2 sliders + caption
- [x] ω = 2π/T = 2πν; curves with different A, different φ, different ω — §2 live trace responds to each slider
- [x] SHM vs periodic-but-not-SHM functions (sin ωt − cos ωt; sin²ωt) — §9 Q1, Q2
- [x] SHM as the projection of uniform circular motion: reference particle, reference circle — §2 (key picture)
- [x] Projection on the y-diameter is SHM with phase difference π/2 — §2 toggle
- [x] Force in linear SHM differs from the centripetal force of the circular motion — §2 caption
- [x] Velocity v = −ωA sin(ωt + φ) from the reference circle; v<sub>max</sub> = ωA — §2 velocity arrows (projection), §3
- [x] Acceleration a = −ω²x; a<sub>max</sub> = ω²A; always toward the mean position — §2 accel arrows, §3 graphs + track
- [x] x, v, a graphs: same period, v differs in phase by π/2, a by π — §3 stacked graphs with T/4 marker
- [x] Speed at displacement x: v = ω√(A² − x²) **[JEE]** — §3 readout + Q3
- [x] Force law F = −kx, k = mω², ω = √(k/m); restoring force; two equivalent definitions — §4 drag + F–x graph
- [x] Linear vs non-linear oscillators — §4 caption, §4 Q2
- [x] Two springs on either side of a block: T = 2π√(m/2k) — §4 Q1
- [x] Springs in series and parallel; cutting a spring **[JEE]** — §8 comparisons, §5 Q2
- [x] Energy: K, U = ½kx², E = ½kA² constant; K and U have period T/2 — §6
- [x] K and U vs x and vs t — §6 (both graphs)
- [x] Average K = average U = E/2 over a cycle **[JEE]** — §6 caption (stated, not derived)
- [x] Spring–mass oscillator: T = 2π√(m/k), independent of amplitude, phase, energy — §4 readout, §5 twin release + x–t graph
- [x] Vertical spring–mass: same period as horizontal **[JEE]** — §8 comparison
- [x] Simple pendulum: forces, restoring torque −mgL sin θ — §7 drawing (mg, mg sin θ) + caption
- [x] Small-angle approximation sin θ ≈ θ (Table 13.1) and where it breaks — §7 ghost vs real, sin θ vs θ chart, period-ratio chart
- [x] T = 2π√(I/mgd) for a physical pendulum **[JEE]**, T = 2π√(L/g) — §7 caption
- [x] Seconds pendulum — §7 Q1
- [x] Period independent of bob mass; T on the Moon — §8 comparisons, §7 g chips
- [x] Large-amplitude period longer than 2π√(L/g) **[JEE]** — §7 (exact, computed), Q3
- [x] Pendulum in an accelerating frame (effective g) **[JEE]** — lift (§8, §7 Q2); horizontally accelerating car, g_eff = √(g² + a²), tilted equilibrium (§7 Q4 with picture; NCERT Ex 13.16)
- [x] Two initial conditions fix the motion — §2 Q2
- [x] Sum of two SHMs periodic only for commensurate frequencies — §9 Q5
- [~] 2-D SHM with phase difference π/2 gives uniform circular motion — shown the other way round (§2: x and y shadows of circular motion differ by π/2); not stated as a 2-D force law
- [~] Floating cork, liquid in a U-tube **[JEE]** — U-tube in §9 Q6; floating cork not covered
- [x] Damped oscillations: exponential amplitude envelope A e^(−bt/2m), ω′ = √(k/m − b²/4m²), energy ∝ e^(−bt/m) **[JEE Advanced]** — §10 damping slider + envelope
- [x] Light / critical / heavy damping (qualitative), b_c = 2√(km); shock absorbers **[JEE Advanced]** — §10 presets, §10 Q4
- [x] Forced oscillations: oscillates at ω_d; steady-state amplitude A(ω_d) = (F₀/m)/√((ω₀² − ω_d²)² + (bω_d/m)²) **[JEE Advanced]** — §10 sweep of ω_d, driven block with force arrow
- [x] Resonance: peak near ω₀, sharper and taller as damping falls; damping limits the amplitude; examples (swing, Millennium Footbridge, radio tuning) **[JEE Advanced]** — §10 curve + faint reference curves, Q3
(Damped/forced/resonance are not in rationalised NCERT or in the current JEE Main syllabus; included for JEE Advanced.)

## Waves — NCERT Class 11, "Waves"

Modules: `waves/travelling-waves.html` (TW), `waves/standing-waves-beats.html` (SB)

### 14.1 Introduction
- [x] A wave is a moving disturbance: energy and pattern travel, matter does not flow (cork on water, wind vs sound) — TW §1 (one highlighted particle stays put)
- [x] Mechanical waves need a medium; EM waves travel in vacuum (c); matter waves (mention only) — TW §1 caption
- [x] Medium as coupled oscillators (springs, train bogies, compressions spreading in air, atoms in a lattice) — TW §1 (row of particles, springs drawn between them)

### 14.2 Transverse and longitudinal waves
- [x] Transverse: particles oscillate perpendicular to propagation (pulse/sine wave on a string) — TW §1 toggle
- [x] Longitudinal: particles oscillate along propagation; compressions and rarefactions (sound in a piston pipe) — TW §1 toggle, C/R labels
- [x] Transverse waves need shear rigidity (solids only); longitudinal in all media; air carries only longitudinal — TW §1 caption + quiz
- [x] Water waves: capillary vs gravity waves, particles move up/down and back/forth (combination) — TW §1 caption (qualitative)
- [~] Examples to classify (NCERT Ex. 14.1) — TW §1 quiz uses the ultrasonic-quartz and floating-cork cases; slinky kink and motorboat not used
- [x] Travelling (progressive) wave vs bulk flow of the medium — TW §1

### 14.3 Displacement relation in a progressive wave
- [x] y(x,t) = a sin(kx − ωt + φ); equivalence with A sin + B cos — TW §2 (sin/cos form in caption)
- [x] Two views: snapshot (y vs x at fixed t) and history of one particle (y vs t at fixed x) — TW §2 linked graphs
- [x] Wave in −x direction: a sin(kx + ωt + φ) — TW §2 direction toggle
- [x] Amplitude a, phase (kx − ωt + φ), initial phase φ — TW §2 sliders and labels
- [x] Wavelength λ, angular wave number k = 2π/λ — TW §2 labelled on the snapshot
- [x] Period T, angular frequency ω = 2π/T, frequency ν = 1/T — TW §2 labelled on the history graph
- [x] Longitudinal displacement s(x,t) with the same form — TW §1/§2 caption
- [x] Phase difference between two points Δφ = kΔx = 2πΔx/λ **[JEE]** — TW §2 (P's phase lag readout) + quiz (Ex. 14.10)

### 14.4 Speed of a travelling wave
- [x] Crest (fixed phase) moves: dx/dt = ω/k; v = λ/T = λν — TW §2 (crest marker, distance λ in one period)
- [x] Speed set by the medium; source sets ν, then λ = v/ν — TW §3 caption + quiz
- [x] Any f(x ∓ vt) is a travelling wave; sin + cos combination is one wave (Ex. 14.5, 14.13) — TW §2 caption + quiz
- [x] Transverse wave on a string v = √(T/µ) (dimensional argument, C = 1) — TW §3 sliders
- [x] Longitudinal wave in a fluid v = √(B/ρ); bulk modulus B — TW §4
- [x] Longitudinal wave in a solid bar v = √(Y/ρ) — TW §4 caption
- [x] Why sound is faster in solids/liquids (B grows much more than ρ) — TW §4 caption
- [x] Newton's formula v = √(P/ρ) (isothermal), 280 m s⁻¹ for air at STP — TW §4
- [x] Laplace correction v = √(γP/ρ) (adiabatic), γ = 7/5 for air, 331 m s⁻¹ — TW §4 toggle
- [x] Effect of temperature (v ∝ √T), pressure (no effect at fixed T), humidity on speed of sound **[JEE]** (NCERT Ex. 14.4) — TW §4 temperature slider + caption
- [x] Particle velocity from the wave shape: v_p = −v ∂y/∂x **[JEE]** — TW §2 drag + quiz
- [x] Max particle speed aω vs wave speed ω/k **[JEE]** — TW §2 readout + quiz
- [ ] Energy, power and intensity of a wave on a string (P = ½µω²a²v) **[JEE]** — not covered: not in rationalised NCERT text or JEE Main unit wording; left for a later page

### 14.5 Principle of superposition
- [x] Pulses pass through each other unchanged; displacement is the algebraic sum — SB §1 (pulses animation, same/opposite sign)
- [x] Interference of two equal waves with phase difference φ: amplitude 2a cos(φ/2); constructive / destructive — SB §1 (phase slider)

### 14.6 Reflection of waves
- [x] Reflection at a rigid (fixed) end: phase change π, pulse inverted — SB §2
- [x] Reflection at a free (open) end: no phase change, pulse upright; end moves 2a — SB §2
- [~] Partial reflection/transmission at an interface; refraction (Snell) mentioned — SB §2 caption (qualitative, not animated)

### 14.6.1 Standing waves and normal modes
- [x] Two opposite travelling waves → y = 2a sin kx cos ωt; kx and ωt separate — SB §3
- [x] Nodes at x = nλ/2, antinodes at (n + ½)λ/2; spacing λ/2 — SB §3
- [x] All points between two nodes in phase; neighbouring loops opposite — SB §3 caption + quiz
- [x] String fixed at both ends: λ = 2L/n, ν = nv/2L; fundamental, harmonics — SB §4 mode stepper
- [x] Real string = superposition of modes; where it is plucked selects modes (sitar, violin) — SB §4 caption
- [x] Same note, different instruments: harmonic content (Ex. 14.19c) — SB §4 caption
- [x] Laws of a vibrating string (ν ∝ 1/L, √T, 1/√µ) / sonometer **[JEE]** — SB §4 sliders + quiz
- [x] Pipe closed at one end: node at closed end, antinode at open end; ν = (2n+1)v/4L, only odd harmonics — SB §5
- [x] Pipe open at both ends: all harmonics, ν = nv/2L — SB §5
- [x] Displacement node = pressure antinode — SB §5 (pressure toggle)
- [x] End correction (e ≈ 0.6r) **[JEE]** — SB §5 caption, labelled rule of thumb
- [x] Resonance tube (NCERT Ex 14.15-type, resonances λ/2 apart) **[JEE]** — SB §5 quiz
- [x] Resonance with an external source (worked example: 30 cm pipe and 1.1 kHz) — SB §5 quiz
- [x] Circular membrane (tabla) normal modes, qualitative — SB §4 caption

### 14.7 Beats
- [x] Two close frequencies add: s = 2a cos(ω_b t) cos(ω_a t); average-frequency tone with a slowly varying envelope — SB §6 sliders
- [x] Beat frequency ν₁ ~ ν₂ (envelope has frequency |ν₁ − ν₂|) — SB §6
- [x] Tuning with beats (sitar Example 14.6: which way the frequency moved) — SB §6 quiz
- [ ] Musical pillars box — not shown (cultural note, nothing to visualise)
- [ ] Longitudinal vibration of a rod clamped at its middle (Ex. 14.16) — not shown; exercise only

### Doppler effect
- [x] Doppler effect in sound **[JEE Adv]**: moving source (wavefronts bunched ahead, spread behind, drawn live), moving observer, ν′ = ν(v ± v_o)/(v ∓ v_s) with the sign rule "approaching → higher" — SB §7 + 3 quiz items. Not in the rationalised NCERT chapter or the current JEE Main unit wording (dropped in the 2024 revision per coaching-site lists); still listed in the JEE Advanced syllabus.
