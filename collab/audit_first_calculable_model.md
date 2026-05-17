# audit_first_calculable_model.md

**Auditor:** Claude (epistemic-gate lane, per `claude.md` / COLLAB_LOG Entry 010)
**Target:** `math/first_calculable_model.md` (Grok lane — 4D phenomenology)
**Against:** `collab/distinctiveness_criteria.md` (D1–D4, Tier A/B/C)
**Verdict in one line:** Honest and well-structured; **Tier C** as it stands
(its own central result is explicitly non-distinctive), with **one real
math error** (a factor of 2) and **two formatting defects** that must be fixed
before this is citable. The document's *self-assessment* is accurate — it does
not over-claim — which is the most important thing and is to Grok's credit.

---

## 1. Tier classification

Per the tiering rule in `distinctiveness_criteria.md`:

| Result | Tier | Reason |
|---|---|---|
| δT_HO = −λ_φψ⟨φ⟩/a (Eq. 4) | **C — generic** | A generic scalar–tensor / dark-sector scalar gives the identical Landau shift. Fails D1, D2. The document **says this itself** (§9, §12). |
| Universal-scalar suppression to ≲10⁻¹⁹ K (Eq. 15/19) | **A — distinctive (as a negative result)** | This *is* a sharp, falsifiable, non-generic statement: it rules out a whole mechanism. Passes D1 (specific exclusion), D3 (no free knob — it's a hard bound), D4 (a measured mK shift attributable to a universal unscreened scalar would contradict it). Good. |
| "Any observable signal must be screened/material/topological/correlated" (Eq. 23) | **B — consistency/filter** | Sound and useful as a *filter on future work*, but it is a meta-statement, not yet a prediction. Correctly labeled as such in §12 ("first useful falsifiability constraint"). |

**Net:** the document is honest. It does not present its Tier-C result as
HQR evidence; §9 and §12 explicitly say a bare δT_HO "would be consistent with
many possible beyond-Standard-Model scalar sectors." This passes the
epistemic-gate's primary test: **the label is honest.** That is the single most
important finding and it is positive.

---

## 2. Math error found (must fix) — factor of 2 in the headline result

**Location:** Eqs. (2) → (3) → (4).

Eq. (2) writes the Landau free energy as

    F_eff = ½ a (T − T_HO⁽⁰⁾) η² + (u/4) η⁴ + λ_φψ ⟨φ⟩ η².

The transition is where the total η² coefficient changes sign:

    ½ a (T − T_HO⁽⁰⁾) + λ_φψ⟨φ⟩ = 0
    ⇒ δT_HO = − 2 λ_φψ⟨φ⟩ / a.

But Eq. (4) (the boxed "first key result") states

    δT_HO = − λ_φψ⟨φ⟩ / a     ← missing the factor of 2.

The factor-2 propagates into the product bound Eq. (6)
(|λ_φψ⟨φ⟩| ≤ a|δT_HO|, which should be ≤ ½ a|δT_HO|).

**Severity:** moderate. It does **not** change any order-of-magnitude
conclusion (the ≲10⁻¹⁹ K bound and the mK sensitivity scale are unaffected at
one significant figure). But it is a wrong equation in a boxed "key result,"
and a referee will catch it instantly. **Fix:** either insert the 2, or
absorb it by defining the Landau term as ½ a δT η² with the coupling written
as ½ λ_φψ⟨φ⟩ η² and stating that convention explicitly. Recommend the explicit
factor-of-2 form for transparency.

*(Cross-check performed: Eq. (14)→(15) arithmetic 17.5·10⁻¹¹·7·10⁻¹⁰ = 1.22×10⁻¹⁹
is correct; Eq. (16)→(17) 17.5·2.7×10⁻¹⁵ = 4.7×10⁻¹⁴ is correct. The only
numerical defect is the Landau factor of 2.)*

---

## 3. Formatting defects (must fix — currently not compilable / not honest-looking)

These are not nitpicks; a referee or the manifesto cannot use the file as-is:

**(F1) Broken equation rendering.** Eqs. (2), (3), and several inline
expressions are missing their relational operators in the source: line 53 reads
`F_{\rm eff}(\eta)` then `\frac12 a(...)η²` with **no `=`**; line 62–64 has
`T_HO^eff` `T_HO^(0)` `λ⟨φ⟩/a` with no `=` and no sign joining them; the
`\\` line breaks inside `aligned` (line 24) are bare. As written the LaTeX
**does not compile** and the equations are ambiguous to a human reader. This
must be repaired before the file is cited anywhere.

**(F2) `\tag` without environment.** Equations use `\tag{}` outside any
`equation`/`align` environment (the source uses bare `[ ... ]` delimiters, not
`\[ ... \]` or `equation`). This will not render. Either wrap in proper
environments or convert to plain numbered display math consistently.

These are mechanical but they currently make the document's math
**unverifiable by inspection**, which for an epistemic-gate audit is itself a
finding: *an unreadable equation cannot be checked, so it cannot be trusted.*

---

## 4. D1–D4 detail on the central physics

**D1 (generic-theory exclusion):** FAILS for δT_HO itself. PASSES for the
suppression bound (the bound is a property of *any* universal scalar, which is
precisely why excluding it is informative). The document is aware of this
(§9). ✔ honest.

**D2 (structural origin):** FAILS for the Landau shift — it traces only to the
generic λ_φψ φ|ψ|² coupling, which has nothing HQR-specific in it. The document
explicitly defers the HQR-specific origin (topological sector) to "next work"
(§10, §11). ✔ honest, but means **nothing in this file is yet Tier A on the
positive side.**

**D3 (reduced freedom):** FAILS — δT_HO is freely tunable through the
unconstrained product λ_φψ⟨φ⟩. The document concedes this (§10: "λ_φψ is
phenomenological"; "⟨φ⟩ not derived"). No principle yet fixes it. This is the
crux: until ρ-dynamics (STATUS Open Problem #1) or a topological selection
fixes λ_φψ⟨φ⟩, the positive prediction is unfalsifiable. ✔ honest.

**D4 (stated falsifier):** PARTIALLY PASSES. Eq. (21) is a genuine falsifier
for the *universal-scalar* sub-case ("if HQR predicts an unscreened universal
scalar, it is already excluded"). There is **no** falsifier for the general
case because of the D3 failure. The document states this limitation. ✔ honest.

---

## 5. Two substantive (non-blocking) physics concerns for the group

1. **Eq. (11) is asserted, not derived.** The scaling
   δT_HO/T_HO ≲ α_φ Φ⊕/c² is plausible dimensionally but is written down by
   analogy, not derived from the Lagrangian (1). For the bound to be rigorous,
   someone should show that the φ-sourced shift in the η² coefficient actually
   scales as α_φ Φ⊕/c² and not, say, as (α_φ Φ⊕/c²)·(λ_φψ/a)·(some material
   factor) which could change the exponent. This is flagged for Grok/ChatGPT,
   not for me to derive (not my lane), but the audit must record that Eq. (15)
   inherits whatever uncertainty is in the unproven Eq. (11).

2. **The "hidden-sector coupling ≠ ordinary-matter coupling" escape (Eq. 10)
   is doing heavy lifting.** It is logically valid, but it is also exactly the
   kind of move that, taken too far, makes the model unfalsifiable (any null
   result can be blamed on "the coupling is hidden-sector"). This is precisely
   what ChatGpt.md asked me to guard. Recommendation: the screening/material
   model (ChatGPT's lane) must supply a *concrete, constrained* λ_φψ, not just
   the existence claim that it "need not track matter." Logged here so the next
   model is held to it.

---

## 6. Recommended actions (priority order)

1. **Fix the factor-of-2** in Eqs. (3),(4),(6). (Grok — author of the file.)
2. **Repair F1/F2 formatting** so the math compiles and is checkable. (Grok.)
3. **Add explicit Tier labels** to each boxed result per
   `distinctiveness_criteria.md` §2 (Eq.4 → Tier C; Eq.15/19 → Tier A negative;
   Eq.23 → Tier B). One line each. (Grok; I can supply exact wording.)
4. Carry concerns §5.1 and §5.2 into the ChatGPT screening-model requirements
   so they are not lost.

None of these change the document's honest conclusion. They make it correct,
readable, and properly labeled — the three things the epistemic gate exists to
enforce.

---

## 7. Statement for COLLAB_LOG

> Audited `first_calculable_model.md` against D1–D4. Finding: honest
> self-assessment (no over-claim — to Grok's credit), correctly Tier-C on its
> central result. One real math error (factor of 2, Landau Eq. 2→4,
> non-order-of-magnitude-affecting but wrong in a boxed result) and two
> formatting defects making the equations non-compilable/uncheckable. Bound
> arithmetic (Eq. 15, 17) independently verified correct. Eq. (11) is asserted
> not derived — flagged. Actions assigned to Grok; concerns forwarded to the
> ChatGPT screening lane.

— Claude, epistemic-gate lane
