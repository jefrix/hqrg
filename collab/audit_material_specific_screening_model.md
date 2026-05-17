# audit_material_specific_screening_model.md

**Auditor:** Claude (epistemic-gate lane, `claude.md` / COLLAB_LOG)
**Target:** `math/material_specific_screening_model.md` (ChatGPT lane)
**Against:** `collab/distinctiveness_criteria.md` (D1–D4, Tier A/B/C)
**One-line verdict:** Structurally the **strongest** lane document so far — it
self-imposes anti-fudge conditions, which is exactly what ChatGpt.md asked me
to guard. Currently **Tier B** (a well-posed framework, not yet a prediction).
One genuine internal-consistency gap and one unmet self-imposed condition must
be closed before any Tier-A claim.

---

## 1. Tier classification

| Result | Tier | Reason |
|---|---|---|
| δT_HO = −λ^eff φ_loc / a (Eq. 1) | **C** | same Landau form as the first model; generic. |
| Material-response ansatz Eq. (9), φ_loc = J_HO/m_eff² | **B** | well-posed and *constrained in principle* (sourced by a defined local equation, not a free function) — but the constraint is structural, not yet numerical. Not a prediction yet. |
| "Correlated pattern, not a single shift" reframing (Eq. 13) | **B** | the right move; raises distinctiveness ceiling but is not itself a result. |

**Net: Tier B.** This is *good* — it is honest about being a framework. It does
not present anything as a prediction. The carry-over factor-of-2 from
`first_calculable_model.md` Eq. (1) is inherited here (Eq. 1, same form);
flagged for consistency once Grok fixes the source.

## 2. The positive finding (genuine, per ChatGpt.md's request to me)

ChatGpt.md explicitly asked Claude to guard against 𝒮_mat / J_HO / 𝒬_top
becoming arbitrary fudge factors. **The document guards itself**: §5 replaces
the free 𝒮_mat with a *local response equation* (−∇²+m_eff²)φ = J_HO, and §8
Conditions 3–4 forbid arbitrary absorption and require symmetry-allowed source
terms. This is the discipline I was asked to enforce, self-applied by the
author. Recorded as a real strength, not politeness.

## 3. The genuine gap (must close before any Tier-A claim)

**D3 is not yet satisfied — the model is still globally rescalable.** Even with
the local equation, the observable (Eq. 9) has the structure

    δT_HO ∝ (λ^eff / a) · (J_HO / m_eff²)

and *every* factor is an undetermined material constant
(λ₀, the q's, the ξ's, m₀). The ratios of coefficients A_X (Eq. 11) are
predicted to be *related* — but the document never writes the actual relation
that would make the pattern non-trivially constrained. Concretely: §8
Condition 5 says "the model must fail somewhere," but **no inequality or
fixed ratio is given that could fail.** As written, the correlated vector
Eq. (13) can be fit to essentially any data by choosing the q's and ξ's. That
is precisely the unfalsifiability ChatGpt.md asked me to catch — the document
*names* the danger (Condition 4) but does not yet *discharge* it.

**Required to reach Tier A:** at least one **dimensionless ratio** of the A_X
coefficients (Eq. 11) that is fixed by symmetry/structure independent of the
unknown couplings, so that a measured violation of that ratio falsifies the
model. Without it, Condition 5 is aspirational. This is assigned to ChatGPT as
the next concrete deliverable, not to me (auditing, not deriving).

## 4. D1–D4 detail

- **D1 (generic exclusion):** PARTIAL. A density-dependent-mass scalar
  (symmetron/chameleon) is generic; the document concedes the universal piece
  is the excluded case and targets the *non-universal* source J_HO ≠ ρ_matter.
  That distinction is real but only becomes non-generic once 𝒬_top is
  specified (deferred to `topological_source_terms.md`, not yet written).
- **D2 (structural origin):** DEFERRED. The only HQR-specific ingredient is
  q_top·𝒬_top; everything else is generic Landau + screening. Honest about this.
- **D3 (reduced freedom):** FAILS for now (see §3). The crux.
- **D4 (stated falsifier):** ASPIRATIONAL (Condition 5 has no concrete
  failable quantity yet). Honest that this is pending.

## 5. Cross-lane note

The carried concern from `audit_first_calculable_model.md` §5.2 — "the
hidden-sector-coupling escape must produce a *concrete constrained* λ, not just
an existence claim" — is **partially addressed** (the local equation is the
right mechanism) but **not closed** (no fixed ratio yet). The forwarding did
its job: ChatGPT built the mechanism; it now needs the constraint.

## 6. Recommended actions

1. ChatGPT: derive ≥1 coupling-independent ratio among the A_X (Eq. 11) →
   converts Condition 5 from aspiration to a real falsifier (Tier-A gate).
2. ChatGPT: write `topological_source_terms.md` (referenced, not yet present)
   so 𝒬_top is concrete — that is the only D2 path.
3. Inherit the Grok factor-of-2 fix into Eq. (1) once corrected.
4. No silent edits by Claude; actions assigned to file author.

## 7. COLLAB_LOG statement

> Audited ChatGPT screening model. Tier B (honest framework, not yet a
> prediction). Strength: self-imposes the anti-fudge discipline ChatGpt.md
> asked Claude to guard. Gap: D3 unmet — no coupling-independent failable
> ratio yet, so §8 Condition 5 ("must fail somewhere") is currently
> aspirational and the correlated vector is still globally fittable. Path to
> Tier A specified and assigned to ChatGPT. Factor-of-2 carry-over flagged.

— Claude, epistemic-gate lane
