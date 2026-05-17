# HQR — Status & Notation (read before editing anything)

This file is the **single source of truth** for (a) the epistemic status of the
framework, (b) the metric convention, and (c) notation. It must not itself be
duplicated or concatenated — if you find two copies stitched together, that is a
merge accident; reconcile to one. If the manuscript and this file ever disagree,
that is a bug — flag it in `COLLAB_LOG.md` and reconcile.

---

## 1. Epistemic status — PATH A is binding

**The formal core of HQR is Path A.** Stated precisely:

> rho^ent is a **postulated independent real scalar field** on M^11, with its
> own kinetic term, potential U(rho), and non-minimal coupling alpha*rho*R^(11).
> It behaves like a dilaton / Brans-Dicke scalar. The label "entanglement
> density" / "informational density" is **interpretation and motivation**, not a
> derivation. rho^ent is **not** defined as, and is not computed from, the von
> Neumann entanglement entropy -Tr(rho_A log rho_A) of any state or bipartition.

**Path B** — the stronger reading in which the 4D field equations *emerge from
an entanglement-entropy functional* (Jacobson / entropic-gravity style) — is an
**open research direction**. It is **not assumed anywhere** in the formal
development and must not be presented as established.

### What every collaborator must NOT do
- Do not write "entanglement is the source of curvature" / "information ->
  geometry" as a derived or established result. It is allowed **only** as
  explicitly-flagged motivation ("motivates the interpretation", "in the
  motivational sense").
- Do not silently strengthen rho^ent from "postulated scalar we interpret as
  informational" to "the entanglement content of the quantum state."
- Do not introduce free tensors/functions (e.g. Delta_proj) on the RHS of field
  equations without an explicit in-text caveat that they are unconstrained
  placeholders, not predictive terms.
- Do not re-open Path A vs Path B inside the manuscript. Path B work goes in a
  separate document and is referenced as open.

### What collaborators SHOULD do
- When restating the central claim, use the de-escalated form: *"a postulated
  informational scalar contributes to curvature in the manner of a
  non-minimally coupled scalar."*
- Treat self-flagged open problems as a credibility asset; name them before a
  referee does (rho-dynamics/stabilization, Delta_proj form, realistic
  compactification, the Path B obstacles).

---

## 2. Metric convention — RATIFIED (binding for all formal work)

**The project standard is the mostly-plus signature: (-,+,+,...,+) in D = 11
(and (-,+,+,+) in 4D).**

This was provisionally chosen in COLLAB_LOG Entry 006 and is **ratified here**
as of Entry 008. It was selected because it requires the fewest sign changes
across existing correct work: `math/01_lagrangian_and_Tinfo.tex` already uses
it consistently, and the actual Lagrangian signs in
`math/first_calculable_model.md` already imply it (only that file's *label*
was wrong, now corrected).

**Consequences that every collaborator must respect:**

- With mostly-plus, a healthy (non-ghost) scalar enters the Lagrangian with a
  **negative** kinetic term **and** a **negative** potential:
  L_scalar = -(beta/2) g^AB grad_A rho grad_B rho - V(rho),  with beta > 0.
- Kinetic and potential therefore carry the **same leading sign** (both -) in
  L. They are **not** independently choosable.
- In the derived stress tensor, the gradient-squared piece and the potential
  piece carry **opposite** relative signs:
  T_AB contains beta(grad_A rho grad_B rho - 1/2 g_AB |grad rho|^2) - g_AB gamma V(rho).
- The sign of the potential term in T^info is what fixes whether the
  informational sector behaves as **dark energy** (accelerating) or as
  **ordinary matter** (decelerating) after reduction, and it sets the **sign**
  of delta T_HO in the URu2Si2 model. A mislabeled or inconsistent signature
  silently flips physical predictions.

**If anyone wants to switch to mostly-minus (+,-,-,...,-):** that is a
legitimate preference (common in particle-physics-flavored work), but it is a
*group decision* requiring a new COLLAB_LOG entry, and whoever proposes it must
flip the signs **consistently** in `01_lagrangian_and_Tinfo.tex`,
`first_calculable_model.md`, and any derived file in the same commit. Do not
introduce a second convention piecemeal.

---

## 3. Canonical notation

Use these forms consistently. The manuscript previously drifted between symbol
sets (e.g. Q_munu vs T_munu^info); converge on the left column.

| Use this | Meaning | Do NOT use |
|---|---|---|
| rho, rho^ent | the postulated informational scalar (Path A) | "the entanglement entropy field" |
| S_HQR = S_local + S_hidden/top | total action split | — |
| alpha | non-minimal coupling rho<->R^(11) | — |
| beta | kinetic coefficient for rho | — |
| U(rho) | informational potential (hidden-order vacua) | — |
| R^(11), G_AB^(11) | 11D Ricci scalar / Einstein tensor | — |
| kappa_11 | 11D gravitational coupling | — |
| F_4 = dC_3 | M-theory four-form / three-form | — |
| K^7 | internal compact 7-manifold | "the Calabi-Yau" (unless one is fixed) |
| pi : M^11 -> M^4 | projection map | — |
| T_munu^info | projected informational stress tensor | T_munu^QI, Q_munu |
| T_munu^hidden | hidden/topological stress contribution | — |
| Delta_proj_munu | projection-residue tensor (UNCONSTRAINED placeholder) | treating it as predictive |
| Lambda_eff = Lambda_0 + Lambda_rho + Lambda_hidden | effective cosmological term | — |
| delta_grav(T^info) | CHSH/Tsirelson correction term | raw LaTeX in tables |
| phi | effective 4D scalar descending from rho^ent | conflating with 11D rho |
| lambda_phipsi | scalar <-> hidden-order-parameter coupling (4D) | — |
| psi, eta=\|psi\| | URu2Si2 hidden-order parameter / amplitude | — |

- **11D indices**: capital Latin (A, B, ...). **4D indices**: lowercase Greek (mu, nu, ...).
- **f**: effective gravitational coupling function, f = 1/(16 pi G_11) + alpha rho.

**Master chain (canonical statement):**
S_HQR -> pi:M^11->M^4 -> T_munu^info -> S_hidden -> Delta_observable

**Manuscript placement convention (agreed):**
- 2.5 — status of rho^ent (Path A declaration). *Must precede any action.*
- 2.6 — candidate effective action, term interpretation, stress tensor,
  projection, master-chain mapping (Path-A-framed).
- Part III — testable signatures.
- Part IV — explicitly fenced as exploratory extrapolation (status note at head).
- Appendix A — full derivation, sign conventions, explicit reduction integral.

---

## 4. Scope

- **In scope (formal core):** Lagrangian, stress-tensor derivation, dimensional
  reductions, effective 4D theory, and phenomenological consequences under
  Path A and the ratified signature.
- **Out of scope (interpretive):** direct claims that geometry emerges from
  entanglement entropy, applications to consciousness, or strong ontological
  statements. These are labeled as exploratory and quarantined.

---

## 5. Open problems (shared list — keep current)

1. **Dynamics/stabilization of rho.** Equation of motion + topological terms
   must determine which rho profile is selected; until then rho_0(x) is free
   and predictions are not fixed.
2. **Delta_proj is unconstrained.** Needs its form fixed on an explicit
   compactification so it cannot absorb arbitrary discrepancies.
3. **Realistic compactification.** T^7 is a consistency check only (degenerate
   with an ordinary modulus). Distinctive HQR physics needs a structured K^7
   (G2 or CY3 x S^1 with flux) — heavier, not yet done.
4. **Path B (open).** Entropic/Jacobson-style derivation. Known obstacles:
   non-locality of entanglement entropy; a first law that closes variationally;
   the role of the hidden-order terms in supplying the missing constraints.
5. **One real number.** No prediction yet yields a definite magnitude. The
   URu2Si2 work shows a universal unscreened scalar is suppressed to ~1e-19 K;
   a distinctive signal requires a screened / material-specific / topological /
   correlated mechanism (next model: `math/material_specific_screening_model.md`).

---

## 6. How to contribute

1. Read this file and the latest `COLLAB_LOG.md` before editing anything.
2. Propose changes via clear descriptions or full file content.
3. Every substantive modeling decision (especially status of rho^ent or the
   metric convention) requires a dated, attributed `COLLAB_LOG.md` entry.
4. Keep this file singular. Do not append a second "status" document — edit
   this one.

This document is the single source of truth for the current formal stance of
the project.
