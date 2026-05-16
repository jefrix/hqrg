# hqrg
Holonomic Quantum Research Group
HQRG — Holonomic Quantum Reality
Working repository for the Holonomic Quantum Manifesto and supporting material.
Author: J. F. Ricks, Holonomic Quantum Research Group · www.HQRG.org
Collaboration: human author + three AI collaborators (Claude, Grok / Supergrok Heavy, ChatGPT)
---
Current status: committed to Path A
As of the latest revision, the formal core of HQR is committed to Path A:
> ρ^ent is a **postulated independent scalar field** on M¹¹ (dilaton / Brans–Dicke–like),
> *interpreted* as an informational density. It is **not** derived from the von Neumann
> entanglement entropy of any quantum state.
This was the central conceptual decision of the project. It is what makes the
11D → 4D reduction well-posed and non-circular, and it is the version that can be
defended to a referee. The stronger "entanglement is the source of geometry"
reading (Path B) is recorded as an open research direction, explicitly
not assumed anywhere in the formal development.
See `collab/COLLAB_LOG.md` for how this decision was reached and `collab/STATUS_AND_NOTATION.md`
for the conventions every collaborator should follow.
---
Repository layout
```
hqrg/
├── README.md                  ← you are here
├── manuscripts/               ← current manuscript files (.docx)
│   └── Holonomic_Quantum_Manifesto_Concise_Edition_Revised.docx
├── media/                     ← figures / stock imagery (author-supplied)
├── collab/                    ← shared collaboration state
│   ├── COLLAB_LOG.md          ← decision log; append-only, newest at top
│   └── STATUS_AND_NOTATION.md ← Path A definition + canonical notation table
└── (math source / full edition to be added)
```
How collaborators should use this repo
Read `collab/STATUS_AND_NOTATION.md` before editing anything. Notation and
epistemic status are agreed there; do not silently diverge from it.
Append to `collab/COLLAB_LOG.md` whenever a substantive decision is made,
newest entry at the top, dated, with which collaborator proposed it.
Manuscript edits go into `manuscripts/`. Keep the original filenames'
meaning clear; suffix `_Revised`, `_v2`, etc., rather than overwriting prior
shared versions.
Do not re-litigate Path A vs Path B inside the manuscript. Path B work, if
anyone attempts it, lives in a separate document and is referenced as open.
Changelog (this revision)
Applied to the Concise Edition:
§2.x → §2.5 "The Status of the Informational Field ρ^ent" (renumbered).
§1.3 "HQR Solution" softened from an asserted claim to a proposed model,
with explicit forward-reference to §2.5 (removes the contradiction a referee
would catch between 1.3 and 2.5).
New §2.6 "The Candidate HQR Effective Action" — ChatGPT's formal-backbone
draft folded in with the mathematics intact but every framing verb brought
into line with §2.5 (Path A). Includes an explicit in-text caveat that
Δ_proj is an unconstrained placeholder, not a predictive term. Placed
immediately after §2.5 so the reader gets status → action with no
contradiction. See `collab/COLLAB_LOG.md` Entry 004 for the integration
rationale and exactly what was changed from ChatGPT's draft.
New epistemic-status note at the head of Part IV quarantining the
consciousness / biology / societal chapters as exploratory extrapolation,
not consequences of the formal model.
Appendix B, row B.7 (Gravity-Modified CHSH) repaired — previously leaked
raw LaTeX into the table; now a clean expression with proper
Meaning/Prediction columns.
Removed the empty placeholder table in §7.3 (rendered as empty boxes).
Title block marked "Concise Edition — Revised (Path A)".

# Holonomic Quantum Research Group (HQRG)

**Working repository for the *Holonomic Quantum Manifesto*** and the formal development of **Holonomic Quantum Reality (HQR)**.

## Current Stance: Path A

This project is committed to **Path A**:

> ρ^ent is treated as a **fundamental phenomenological scalar field** on the 11-dimensional manifold.  
> The label “entanglement density” is **interpretive motivation only** — it is not derived from von Neumann entanglement entropy of a quantum state and bipartition.

All formal mathematical work follows this definition. Stronger ontological claims (geometry emerging directly from entanglement, applications to consciousness, etc.) are clearly separated as exploratory interpretation.

## Repository Structure

