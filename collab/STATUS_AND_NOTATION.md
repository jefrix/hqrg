# HQR — Status & Notation (read before editing anything)

This file is the single source of truth for (a) the epistemic status of the
framework and (b) notation conventions. If the manuscript and this file ever
disagree, that is a bug — flag it in `COLLAB_LOG.md` and reconcile.

---

## 1. Epistemic status — PATH A is binding

**The formal core of HQR is Path A.** Stated precisely:

> ρ^ent is a **postulated independent real scalar field** on M¹¹, with its own
> kinetic term, potential U(ρ), and non-minimal coupling αρR^(11). It behaves
> like a dilaton / Brans–Dicke scalar. The label "entanglement density" /
> "informational density" is **interpretation and motivation**, not a
> derivation. ρ^ent is **not** defined as, and is not computed from, the von
> Neumann entanglement entropy −Tr(ρ_A log ρ_A) of any state or bipartition.

**Path B** — the stronger reading in which the 4D field equations *emerge from
an entanglement-entropy functional* (Jacobson / entropic-gravity style) — is an
**open research direction**. It is **not assumed anywhere** in the formal
development and must not be presented as established.

### What every collaborator must NOT do
- Do not write "entanglement is the source of curvature" / "information →
  geometry" as a derived or established result. It is allowed **only** as
  explicitly-flagged motivation ("motivates the interpretation", "in the
  motivational sense").
- Do not silently strengthen ρ^ent from "postulated scalar we interpret as
  informational" to "the entanglement content of the quantum state."
- Do not introduce free tensors/functions (e.g. Δ_proj) on the RHS of field
  equations without an explicit in-text caveat that they are unconstrained
  placeholders, not predictive terms.
- Do not re-open Path A vs Path B inside the manuscript. Path B work goes in a
  separate document and is referenced as open.

### What collaborators SHOULD do
- When restating the central claim, use the de-escalated form: *"a postulated
  informational scalar contributes to curvature in the manner of a
  non-minimally coupled scalar."*
- Treat self-flagged open problems as a credibility asset; name them before a
  referee does (ρ-dynamics/stabilization, Δ_proj form, realistic
  compactification, the Path B obstacles).

---

## 2. Canonical notation

Use these forms consistently. The manuscript previously drifted between symbol
sets (e.g. Q_μν vs T_μν^info); converge on the left column.

| Use this | Meaning | Do NOT use |
|---|---|---|
| ρ, ρ^ent | the postulated informational scalar (Path A) | "the entanglement entropy field" |
| S_HQR = S_local + S_hidden/top | total action split | — |
| α | non-minimal coupling ρ↔R^(11) | — |
| β | kinetic coefficient for ρ | — |
| U(ρ) | informational potential (hidden-order vacua) | — |
| R^(11), G_AB^(11) | 11D Ricci scalar / Einstein tensor | — |
| κ_11 | 11D gravitational coupling | — |
| F_4 = dC_3 | M-theory four-form / three-form | — |
| K⁷ | internal compact 7-manifold | "the Calabi-Yau" (unless one is fixed) |
| π : M¹¹ → M⁴ | projection map | — |
| T_μν^info | projected informational stress tensor | T_μν^QI, Q_μν |
| T_μν^hidden | hidden/topological stress contribution | — |
| Δ_proj_μν | projection-residue tensor (UNCONSTRAINED placeholder) | treating it as predictive |
| Λ_eff = Λ_0 + Λ_ρ + Λ_hidden | effective cosmological term | — |
| δ_grav(T^info) | CHSH/Tsirelson correction term | raw LaTeX in tables |

**Master chain (canonical statement):**
S_HQR → π:M¹¹→M⁴ → T_μν^info → S_hidden → Δ_observable

**Manuscript placement convention (agreed):**
- §2.5 — status of ρ^ent (Path A declaration). *Must precede any action.*
- §2.6 — candidate effective action, term interpretation, stress tensor,
  projection, master-chain mapping (Path-A-framed).
- Part III — testable signatures.
- Part IV — explicitly fenced as exploratory extrapolation (status note at head).
- Appendix A — full derivation, sign conventions, explicit reduction integral.

---

## 3. Open problems (shared list — keep current)

1. **Dynamics/stabilization of ρ.** Equation of motion + topological terms must
   determine which ρ profile is selected; until then ρ_0(x) is free and
   predictions are not fixed.
2. **Δ_proj is unconstrained.** Needs its form fixed on an explicit
   compactification so it cannot absorb arbitrary discrepancies.
3. **Realistic compactification.** T⁷ is a consistency check only (degenerate
   with an ordinary modulus). Distinctive HQR physics needs a structured K⁷
   (G₂ or CY₃×S¹ with flux) — heavier, not yet done.
4. **Path B (open).** Entropic/Jacobson-style derivation. Known obstacles:
   non-locality of entanglement entropy; a first law that closes variationally;
   the role of the hidden-order terms in supplying the missing constraints.
5. **One real number.** No prediction yet yields a definite magnitude. Highest
   value next step remains: push one observable (URu₂Si₂ hidden-order signature
   is the best candidate) through a defined model to an actual number.
   
# STATUS AND NOTATION — Holonomic Quantum Research Group

**Current Commitment: Path A**

## Path A Definition (Authoritative)

ρ^ent is a **fundamental phenomenological scalar field** defined on the 11-dimensional manifold.  
It is **not** derived from the von Neumann entanglement entropy of a quantum state and a bipartition. The name “entanglement density” is interpretive motivation only.

All formal work in this repository operates under this definition unless explicitly stated otherwise.

## Current Canonical Lagrangian (Path A)

See `math/01_lagrangian_and_Tinfo.tex` for the full expression.

Key features:
- 11D Einstein-Hilbert term + non-minimal coupling α ρ R
- Standard kinetic and potential terms for ρ
- Topological hidden-order sector (Chern-Simons + curvature invariants)
- ρ is varied independently in the action

## Notation Conventions

- **11D indices**: Capital Latin letters (A, B, …) or Greek letters with context.
- **4D indices**: Lowercase Greek letters (μ, ν, …).
- **ρ**: Shorthand for ρ^ent (the fundamental scalar).
- **T^info**: The effective quantum informational stress-energy tensor derived from the action.
- **f**: Effective gravitational coupling function f = 1/(16πG₁₁) + α ρ.

## Decision Log Reference

All substantive modeling decisions (especially regarding the status of ρ^ent) must be recorded in `COLLAB_LOG.md` with date and proposer.

## Scope

- **In scope (formal core)**: Lagrangian, stress tensor derivation, dimensional reductions, effective 4D theory, and phenomenological consequences under Path A.
- **Out of scope (interpretive)**: Direct claims that geometry emerges from entanglement entropy, applications to consciousness, or strong ontological statements. These are labeled as exploratory.

## How to Contribute

1. Read this file and the latest `COLLAB_LOG.md`.
2. Propose changes via clear descriptions or full file content.
3. Major modeling shifts require an entry in the decision log.

This document is the single source of truth for the current formal stance of the project.
