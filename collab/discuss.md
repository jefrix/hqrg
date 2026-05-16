# Corrected Bounds on δT_HO in URu₂Si₂: Phenomenological Sensitivity vs. Fifth-Force Constraints

**Date:** 2026-05-16  
**Authors:** (based on collaborative analysis)  
**Purpose:** This note clarifies two distinct upper bounds on a possible shift of the hidden-order transition temperature in URu₂Si₂, corrects a misleading earlier claim (50 mK as a fifth-force bound), and outlines the implications for the HQR framework.

---

## 1. Background

Within Path A of the Holonomic Quantum Reality framework, the effective 4D scalar field φ (descending from the 11D ρ^ent) couples to the hidden-order parameter ψ via λ_{φψ} φ |ψ|². In a Landau mean‑field description, the transition temperature shifts by

\[
\delta T_{\rm HO} = -\frac{\lambda_{\phi\psi}}{a}\,\langle\phi\rangle,
\]

where \(a>0\) is the Landau coefficient (determined by the specific‑heat jump) and \(\langle\phi\rangle\) is the background value of the scalar.

---

## 2. Two Different Kinds of Bounds

Early versions of the “first calculable model” mistakenly treated the 50 mK estimate as a fifth‑force bound. In fact, the 50 mK value came from a mix of experimental sensitivity and guessed couplings, not from a rigorous derivation. A correct treatment distinguishes:

### 2.1 Phenomenological (URu₂Si₂) sensitivity bound

URu₂Si₂ samples with different residual resistivity ratios show \(T_{\rm HO}\) stable to within approximately 0.5–1 K. This empirical stability sets an **upper limit on any unknown shift**:

\[
|\delta T_{\rm HO}|_{\rm phen} \lesssim 1\ {\rm K}.
\]

Using the specific‑heat jump (\(\Delta C/T_{\rm HO}\sim0.3\)–\(0.5\ {\rm J\,mol^{-1}K^{-2}}\)) and mean‑field relations, the Landau coefficient is \(a\sim0.1\)–\(0.3\ {\rm J\,mol^{-1}K^{-2}}\). Hence

\[
|\lambda_{\phi\psi}\langle\phi\rangle| \lesssim a\cdot 1\,{\rm K} \sim 0.1\text{–}0.3\ {\rm J\,mol^{-1}K^{-1}}.
\]

This bound is **material‑specific** and does **not** assume anything about how φ couples to ordinary matter. It simply reflects the observed stability of the transition in real samples.

### 2.2 Fifth‑force / equivalence‑principle bound (universal coupling)

If φ is an **unscreened long‑range scalar** that couples universally to mass (or baryon number) with strength α_φ relative to gravity, then the Earth’s gravitational potential \(\Phi_\oplus/c^2\approx 7\times10^{-10}\) induces a fractional shift

\[
\frac{\delta T_{\rm HO}}{T_{\rm HO}} \lesssim \alpha_\phi \frac{\Phi_\oplus}{c^2}.
\]

The MICROSCOPE satellite experiment constrains \(\alpha_\phi \lesssim 10^{-11}\) for such a scalar (mass \(m_\phi\lesssim10^{-12}\) eV). Therefore

\[
|\delta T_{\rm HO}|_{\rm fifth\text{-}force} \lesssim 17.5\,{\rm K} \times 10^{-11} \times 7\times10^{-10} \approx 1.2\times10^{-19}\ {\rm K}.
\]

Even using the looser Eötvös parameter bound \(|\eta|\lesssim2.7\times10^{-15}\) gives

\[
|\delta T_{\rm HO}|_{\rm fifth\text{-}force} \lesssim 5\times10^{-14}\ {\rm K}.
\]

Both values are **far below the millikelvin scale** that is routinely resolvable in calorimetry.

---

## 3. Key Conclusion for HQR

**An observable shift of order millikelvin or larger cannot be produced by an ordinary unscreened universal fifth‑force scalar without violating existing constraints by at least 14 orders of magnitude.**

Therefore, any claim that HQR predicts a measurable shift in \(T_{\rm HO}\) must rely on **non‑generic** mechanisms, such as:

- **Screening** (chameleon, symmetron) that hides the scalar from fifth‑force tests in dilute space but allows an effect inside a dense correlated material.
- **Material‑specific couplings** where λ_{φψ} is independent of φ’s coupling to ordinary matter – i.e., the hidden‑order sector is uniquely sensitive.
- **Topological or higher‑dimensional effects** (exactly the kind in \(\mathcal{L}_{\rm hidden}\) of the 11D action) that produce a shift without requiring a long‑range scalar background, or that impose discrete, non‑universal couplings.
- **Correlated observables** beyond a simple absolute shift in \(T_{\rm HO}\) (e.g., pressure dependence, strain anisotropy, specific‑heat shape, or relations between different HQR signatures like gravitational wave echoes and hidden‑order anomalies).

Thus, the extreme tightness of fifth‑force bounds **does not falsify HQR** – instead, it forces the framework toward its most distinctive and interesting features.

---

## 4. Recommended Updates to the Manifesto / Model Document

The following changes should be made in the repo:

### 4.1 Remove or rephrase the 50 mK claim

Replace any statement like “fifth‑force limits imply \(|\delta T_{\rm HO}|\lesssim50\,{\rm mK}\)” with:

> **Phenomenological sensitivity:** Current URu₂Si₂ data constrain \(|\delta T_{\rm HO}|_{\rm phen}\lesssim1\,{\rm K}\). A more refined target for future experiments is the millikelvin scale, which is well within reach of modern calorimetry.  
> **Fifth‑force bound (universal coupling):** If φ couples universally, \(|\delta T_{\rm HO}|_{\rm fifth\text{-}force}\lesssim10^{-19}\,{\rm K}\) – far below any measurable level. Hence an observable shift would rule out a universal unscreened scalar and point to the distinctive HQR mechanisms listed above.

### 4.2 Add a new appendix or section

Insert the corrected derivation as a self‑contained appendix (e.g., Appendix D as written in the earlier response). The title should be: **“Corrected Bounds: Phenomenological Sensitivity vs. Fifth‑Force Suppression”**.

### 4.3 Update the experimental test strategy

In Part III, change the URu₂Si₂ test description to emphasize that the search is not for a simple \(T_{\rm HO}\) shift (which is already bounded to ≤ 1 K by sample variation), but for **correlated, non‑generic signatures** such as:
- Anomalous pressure or magnetic‑field dependence of \(T_{\rm HO}\)
- Unusual strain anisotropy
- Specific‑heat shape modifications
- Relations between hidden‑order behavior and other HQR predictions (e.g., gravitational wave echo amplitudes, modified Casimir forces)

This reframes the test as a **search for HQR‑distinctive fingerprints**, not just a scalar coupling.

---

## 5. Suggested File Placement

- **For collaborators:** Place this note in `/collab/` as `corrected_bounds_URu2Si2.md`.
- **For the math/model folder:** Create `/math/bounds_URu2Si2.md` containing the rigorous derivation (Appendix D) and a short summary of the conclusions. This file can be included in the main manifesto via a `\input` or as an appendix.

The final `first_calculable_model.md` (if it stays in `/math/`) should be updated to reflect the above corrected framing.

---

## 6. Next Steps for the Group

1. **Adopt the corrected language** in all documents to avoid overclaiming.
2. **Identify one or two correlated observables** (e.g., pressure derivative dT_HO/dP, or the ratio of specific‑heat jump to entropy) that could be computed from a specific topological/higher‑dimensional sector of HQR.
3. **Compare with existing data** on URu₂Si₂ under pressure, strain, or doping to see if any hint of non‑generic behavior already exists.
4. **Refine the screening argument** – if HQR proposes a chameleon‑like mechanism, estimate the suppression factor inside URu₂Si₂ relative to vacuum.

This note is open for discussion and further refinement.  
— HQR Collaboration
```
