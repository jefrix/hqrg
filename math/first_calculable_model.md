# First Calculable Model: 4D Phenomenological Constraints on Informational Scalar Couplings in URu₂Si₂ (Path A)

**Goal**: Produce a conservative, falsifiable upper bound on any shift in the hidden-order transition temperature of URu₂Si₂ induced by a new phenomenological scalar, while clearly distinguishing what existing data can actually constrain and what would constitute a distinctive signature of the HQR framework.

## 1. Path A Framing

This document operates strictly within **Path A**. The scalar field \(\phi\) (the effective 4D zero mode descending from the 11D field \(\rho^{\rm ent}\)) is treated as a **fundamental phenomenological scalar**. It is **not** derived from von Neumann entanglement entropy. The 11D construction provides motivation and conceptual structure; all explicit calculations below are performed in four-dimensional effective field theory.

## 2. Minimal 4D Effective Model

We work in the mostly-plus signature. The effective 4D Lagrangian density is

\[
\mathcal{L}_{4D} = \frac{1}{16\pi G_4}(1 + \alpha_4 \phi) R 
- \frac12 \partial_\mu\phi \partial^\mu\phi 
- V(\phi) 
- \frac12 m_\psi^2 |\psi|^2 
- \frac{\lambda}{4} |\psi|^4 
- \lambda_{\phi\psi} \phi |\psi|^2 + \mathcal{L}_{\rm matter}.
\]

The term \(\lambda_{\phi\psi} \phi |\psi|^2\) is the leading interaction capable of shifting the hidden-order transition.

## 3. Effective Free Energy and Shift in Transition Temperature

Near the transition we use a mean-field (Landau) approximation. The effective potential for the order parameter magnitude \(\eta = |\psi|\) receives a correction linear in the background value of the informational scalar:

\[
V_{\rm eff}(\eta) = \frac12 a (T - T_{\rm HO}^{(0)}) \eta^2 + \frac{u}{4} \eta^4 + \lambda_{\phi\psi} \langle\phi\rangle \eta^2.
\]

Minimization yields the shifted transition temperature

\[
T_{\rm HO}^{\rm eff} = T_{\rm HO}^{(0)} - \frac{\lambda_{\phi\psi} \langle\phi\rangle}{a},
\]

so the shift is

\[
\delta T_{\rm HO} = -\frac{\lambda_{\phi\psi} \langle\phi\rangle}{a}.
\]

## 4. Corrected Bounds: Phenomenological Sensitivity vs. Fifth-Force Suppression

It is essential to distinguish what is actually being bounded.

### 4.1 Phenomenological Sensitivity from URu₂Si₂ Data

Published thermodynamic data on URu₂Si₂ (specific-heat anomaly, entropy release, and the observed stability of \(T_{\rm HO}\) across samples of varying quality) constrain only the *combination* \(\lambda_{\phi\psi} \langle\phi\rangle / a\). They do not separately determine \(\lambda_{\phi\psi}\) or \(\langle\phi\rangle\).

A conservative estimate based on transition-temperature resolution and sample-to-sample variation gives the following phenomenological sensitivity scale:

\[
|\delta T_{\rm HO}|_{\rm phen} \lesssim 10\text{--}50\,{\rm mK}.
\]

This is an empirical sensitivity limit set by the material and current experimental precision. It is **not** derived from fifth-force experiments.

### 4.2 Fifth-Force / Equivalence-Principle Bound

If \(\phi\) is assumed to behave as an ordinary long-range scalar whose coupling to the hidden-order sector tracks its coupling to ordinary matter, then fifth-force and equivalence-principle constraints apply.

Current limits (torsion-balance experiments and MICROSCOPE) imply that for a light, long-range scalar the effective coupling strength satisfies \(\alpha_\phi \lesssim 10^{-11}\) in the most constrained channels. With the Newtonian potential at Earth’s surface \(\Phi_\oplus / c^2 \approx 7 \times 10^{-10}\), this yields

\[
\frac{\delta T_{\rm HO}}{T_{\rm HO}} \lesssim \alpha_\phi \frac{\Phi_\oplus}{c^2} \lesssim 7 \times 10^{-21}.
\]

Given \(T_{\rm HO} \approx 17.5\) K, the corresponding shift is

\[
|\delta T_{\rm HO}|_{\rm fifth-force} \lesssim 1.2 \times 10^{-19}\,{\rm K}.
\]

Even adopting the looser MICROSCOPE Eötvös-parameter bound directly still gives a shift many orders of magnitude below the millikelvin scale.

### 4.3 Physical Implication

A detectable shift at the level of tens of millikelvin **cannot** be produced by a standard unscreened long-range scalar obeying current fifth-force and equivalence-principle limits.

Therefore, any observable HQR-related effect in URu₂Si₂ at the mK scale must involve at least one of the following:

- The scalar is screened from equivalence-principle tests in ordinary matter but couples differently (or is less screened) inside the correlated-electron system of URu₂Si₂.
- The coupling \(\lambda_{\phi\psi}\) is material-sector specific and is not tied to the usual baryon/mass coupling probed by fifth-force experiments.
- The leading signature is not a simple absolute shift in \(T_{\rm HO}\), but a more distinctive pattern (pressure or magnetic-field dependence, anisotropy, correlated response in other observables, or features arising from the topological hidden-order sector).

In short: ordinary fifth-force physics is already too strongly constrained to produce a detectable mK-scale shift. Any genuine HQR signature must exploit features that go beyond generic scalar-tensor gravity.

## 5. What Would Count as Distinctive Evidence for HQR

An observation of a shift significantly larger than the phenomenological sensitivity scale (~50 mK) would already indicate new physics. However, to be considered supportive of the HQR framework rather than generic beyond-Standard-Model scalar physics, one or more of the following would be required:

- A specific dependence of \(\delta T_{\rm HO}\) on pressure, magnetic field, or strain that follows from the topological terms in \(\mathcal{L}_{\rm hidden}\).
- A measurable correlation between the shift in URu₂Si₂ and other proposed HQR signatures (e.g., modifications to gravitational-wave ringdown/echoes or curvature-dependent Bell-test violations) that is not expected in ordinary scalar-tensor models.
- Evidence that the new scalar couples in a manner consistent with a higher-dimensional or topological origin rather than a generic 4D scalar.

## 6. Limitations

- The coupling \(\lambda_{\phi\psi}\) is introduced phenomenologically.
- No explicit 11D reduction has been performed; the 4D parameters are not yet derived from the higher-dimensional theory.
- Possible screening mechanisms and thermal corrections have been neglected for conservatism.
- The numerical bound is sensitive to the precise value of the Landau coefficient \(a\) and the quartic coupling \(u\).

## 7. Status and Next Steps

This document provides a conservative, data-informed upper limit on \(\delta T_{\rm HO}\) within a purely 4D phenomenological treatment. It demonstrates that the Path A framework can generate concrete, falsifiable statements while clearly identifying the conditions under which an effect would be distinctive of HQR.

**Recommended next technical steps**:
1. Perform a more precise fit to published specific-heat data on URu₂Si₂ to refine the value of \(a\) and tighten the phenomenological bound.
2. Develop a minimal structured (warped or fluxed) compactification to derive relationships between the 4D couplings and 11D parameters (longer-term Route B work).
3. Identify candidate correlated observables that could serve as distinctive HQR signatures alongside a shift in \(T_{\rm HO}\).

**Status**: Provides a usable conservative bound and a clear distinctiveness criterion. Ready for refinement with better thermodynamic fitting.
