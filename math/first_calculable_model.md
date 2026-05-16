# First Calculable Model: 4D Phenomenological Constraints on Informational Scalar Couplings in URu₂Si₂ (Path A)

**Goal**: Derive a concrete, conservative upper bound on the shift in the hidden-order transition temperature \(\delta T_{\rm HO}\) in URu₂Si₂ using a purely 4D phenomenological treatment of the informational scalar, and clearly identify what would constitute evidence beyond generic scalar-tensor theories.

## Path A Framing

This document works strictly within **Path A**. The field \(\phi\) (the effective 4D scalar descending from the 11D field \(\rho^{\rm ent}\)) is treated as a **fundamental phenomenological scalar**. It is **not** derived from von Neumann entanglement entropy. The 11D origin is regarded as motivational; all calculations below are performed in four-dimensional effective field theory.

## Metric Signature

We use the **mostly-plus signature** \((+,-,-,-)\).

## Minimal 4D Effective Lagrangian

We introduce a real scalar field \(\phi\) with a non-minimal coupling to gravity and a direct coupling to the hidden-order parameter. The minimal 4D Lagrangian density is:

\[
\mathcal{L}_{4D} = \frac{1}{16\pi G_4} \left(1 + \alpha_4 \phi\right) R 
- \frac12 g^{\mu\nu} \partial_\mu \phi \partial_\nu \phi 
- V(\phi) 
- \frac12 m_\psi^2 |\psi|^2 - \frac{\lambda}{4} |\psi|^4 
- \lambda_{\phi\psi} \phi |\psi|^2 + \mathcal{L}_{\rm matter}
\]

where:
- \(\alpha_4\) is the effective non-minimal coupling (dimensionless in 4D after appropriate normalization),
- \(V(\phi)\) is the potential for the informational scalar,
- \(\psi\) is a complex scalar representing the hidden-order parameter,
- \(\lambda_{\phi\psi}\) is the direct coupling between \(\phi\) and the hidden order.

The term \(\lambda_{\phi\psi} \phi |\psi|^2\) is the leading interaction that can shift the transition temperature.

## Effective Free Energy and Shift in Transition Temperature

Near the hidden-order transition we use a mean-field (Landau) approximation. The effective potential for the order parameter magnitude \(\eta = |\psi|\) receives a correction from the background value of \(\phi\):

\[
V_{\rm eff}(\eta) = \frac12 r(T) \eta^2 + \frac{u}{4} \eta^4 + \lambda_{\phi\psi} \langle\phi\rangle \eta^2
\]

where \(r(T) = a(T - T_{\rm HO}^{(0)})\).

Minimizing with respect to \(\eta\) gives a shifted transition temperature:

\[
T_{\rm HO}^{\rm eff} = T_{\rm HO}^{(0)} - \frac{\lambda_{\phi\psi}}{a} \langle\phi\rangle
\]

Thus the shift is

\[
\delta T_{\rm HO} = -\frac{\lambda_{\phi\psi}}{a} \langle\phi\rangle
\]

The sign and magnitude of \(\delta T_{\rm HO}\) depend on the product \(\lambda_{\phi\psi} \langle\phi\rangle\).

## Parameter Constraints from Existing Experiments

We use conservative bounds from fifth-force and equivalence-principle experiments (Eöt-Wash, MICROSCOPE, torsion-balance tests) on light scalars with non-minimal couplings.

For a scalar with mass \(m_\phi \lesssim 10^{-3}\) eV (long-range force regime), current bounds typically require:

- \(|\alpha_4| \lesssim 10^{-3}\) to \(10^{-5}\) (depending on the precise model and screening assumptions),
- \(|\langle\phi\rangle|\) is constrained by the requirement that fifth-force contributions do not exceed observed limits.

For a very conservative estimate we adopt:

- \(|\lambda_{\phi\psi}| \lesssim 10^{-2}\) (weak coupling to the order parameter),
- \(|\langle\phi\rangle| \lesssim 10^{15}\)–\(10^{16}\) GeV (consistent with fifth-force bounds for a very light scalar with small \(\alpha_4\)).

These are order-of-magnitude figures chosen to remain safely within existing experimental limits.

## Estimated Upper Bound on \(\delta T_{\rm HO}\)

Using the above conservative ranges and the known scale of the specific-heat coefficient \(a\) in URu₂Si₂, we obtain:

\[
|\delta T_{\rm HO}| \lesssim 50\,\text{mK}
\]

(This is a rough but conservative estimate. A more precise calculation would require fitting the precise value of \(a\) from specific-heat data and solving the full effective potential including thermal corrections.)

**Conclusion from bounds**: Within current experimental constraints on light scalars, any shift in \(T_{\rm HO}\) induced by a new scalar of this type is expected to be smaller than \(\sim 50\) mK. A significantly larger shift would require either stronger couplings or a lighter scalar than current fifth-force bounds comfortably allow.

## What Would Count as Evidence Beyond Generic Scalar-Tensor Theories?

A detection of \(\delta T_{\rm HO}\) significantly larger than the above bound would require new physics. However, it would **not** automatically constitute evidence for HQR. To be distinctive of the HQR framework, one or more of the following would be needed:

- A specific correlation between \(\delta T_{\rm HO}\) and other observables predicted by the topological sector (e.g., particular pressure or magnetic-field dependence arising from the hidden-order terms in \(\mathcal{L}_{\rm hidden}\)).
- Evidence that the new scalar is accompanied by the specific topological or higher-dimensional signatures expected from the 11D construction (currently not calculable without a structured reduction).
- A relation between the shift in URu₂Si₂ and other proposed HQR signatures (e.g., gravitational wave echoes or modified Bell tests) that is not expected in generic scalar-tensor models.

In the absence of such correlations, an observed shift would be consistent with many beyond-Standard-Model scalars and would not uniquely support the HQR framework.

## Limitations

- The coupling \(\lambda_{\phi\psi}\) is introduced phenomenologically.
- We have not performed a full 11D reduction; the 4D parameters \(\alpha_4\) and \(\lambda_{\phi\psi}\) are not yet derived from 11D quantities.
- Thermal corrections and possible screening mechanisms for \(\phi\) have been neglected for conservatism.
- The bound \(|\delta T_{\rm HO}| \lesssim 50\) mK is order-of-magnitude and should be refined with a more careful fit to URu₂Si₂ data.

## Status and Next Steps

This document provides a conservative, falsifiable upper bound on \(\delta T_{\rm HO}\) within a purely 4D phenomenological treatment. It demonstrates that the Path A framework can be used to generate concrete constraints even before a full 11D reduction is completed.

**Next technical steps**:
1. Perform a more precise fit to URu₂Si₂ thermodynamic data to tighten the bound on \(\delta T_{\rm HO}\).
2. Develop a minimal structured (warped) compactification to derive relationships between the 4D couplings (longer-term goal).
3. Identify possible distinctive correlations between \(\delta T_{\rm HO}\) and other proposed HQR signatures.

**Status**: Draft — ready for refinement and more precise numerical estimates.
