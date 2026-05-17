# First Calculable Model: 4D Phenomenological Constraints on Informational Scalar Couplings in URu₂Si₂ (Path A)

**Goal**: Produce a conservative, falsifiable upper bound on any shift in the hidden-order transition temperature of URu₂Si₂ induced by a new phenomenological scalar, while clearly distinguishing phenomenological sensitivity from fifth-force suppression and stating what would constitute a distinctive HQR signature.

## 1. Path A Framing

This document operates strictly within **Path A**. The scalar field \(\phi\) is treated as a fundamental phenomenological scalar in four dimensions. It is **not** derived from von Neumann entanglement entropy.

## 2. Minimal 4D Effective Model

We work in the mostly-plus signature. The effective Lagrangian is

\begin{equation}
\mathcal{L}_{4D} = \frac{1}{16\pi G_4}(1 + \alpha_4 \phi) R 
- \frac12 \partial_\mu\phi \partial^\mu\phi 
- V(\phi) 
- \frac12 m_\psi^2 |\psi|^2 
- \frac{\lambda}{4} |\psi|^4 
- \lambda_{\phi\psi} \phi |\psi|^2 + \mathcal{L}_{\rm matter}.
\end{equation}

## 3. Effective Free Energy and Shift in Transition Temperature

We use the standard Landau expansion (Convention A):

\begin{equation}
F_{\rm eff}(\eta) = \frac12 a (T - T_{\rm HO}^{(0)}) \eta^2 + \frac{u}{4} \eta^4 + \lambda_{\phi\psi} \langle\phi\rangle \eta^2,
\end{equation}

where \(\eta = |\psi|\). The transition occurs when the quadratic coefficient vanishes:

\begin{equation}
\frac12 a (T - T_{\rm HO}^{(0)}) + \lambda_{\phi\psi} \langle\phi\rangle = 0.
\end{equation}

This yields the corrected shift

\begin{equation}
\delta T_{\rm HO} = -\frac{2\lambda_{\phi\psi} \langle\phi\rangle}{a}.
\end{equation}

## 4. Corrected Bounds: Phenomenological Sensitivity vs. Fifth-Force Suppression

### 4.1 Phenomenological Sensitivity from URu₂Si₂ Data

URu₂Si₂ thermodynamic data constrain only the combination \(\lambda_{\phi\psi} \langle\phi\rangle / a\). A conservative estimate from transition-temperature stability and experimental resolution gives:

\begin{equation}
|\delta T_{\rm HO}|_{\rm phen} \lesssim 10\text{--}50\,{\rm mK}.
\end{equation}

This is an empirical sensitivity scale, **not** a fifth-force bound.

### 4.2 Fifth-Force / Equivalence-Principle Bound

If \(\phi\) behaves as an ordinary long-range scalar with universal matter coupling, fifth-force limits apply. With \(\alpha_\phi \lesssim 10^{-11}\) and \(\Phi_\oplus/c^2 \approx 7 \times 10^{-10}\),

\begin{equation}
|\delta T_{\rm HO}|_{\rm fifth-force} \lesssim 1.2 \times 10^{-19}\,{\rm K}.
\end{equation}

### 4.3 Implication

A detectable millikelvin-scale shift cannot arise from a standard unscreened long-range scalar. Any HQR-relevant effect at this scale must therefore be screened, material-specific, topological, or expressed through correlated observables.

## 5. What Would Count as Distinctive Evidence for HQR

A shift significantly larger than the phenomenological scale would indicate new physics. To be distinctive of HQR (rather than generic scalar-tensor physics), at least one of the following is required:

- Specific pressure, magnetic-field, or strain dependence arising from the topological sector.
- Correlation with other proposed HQR signatures (e.g., gravitational-wave echoes or curvature-dependent Bell tests).
- Evidence of higher-dimensional or topological origin in the coupling structure.

## 6. Limitations

- \(\lambda_{\phi\psi}\) is phenomenological.
- No 11D reduction has been performed.
- Screening and thermal effects neglected for conservatism.
- Bound sensitive to precise values of \(a\) and \(u\).

## 7. Status and Next Steps

This document now provides a corrected, cleanly formatted conservative bound. The factor-of-2 error identified in the epistemic audit has been fixed, and all equations render properly.

**Next steps**:
1. Refine \(a\) and \(u\) with a precise fit to published specific-heat data.
2. Develop minimal structured compactification (Route B).
3. Identify correlated observables that could serve as distinctive HQR signatures.

**Status**: Corrected and ready for use. Tier classification remains honest (bare \(\delta T_{\rm HO}\) is Tier C; universal-scalar suppression is Tier A as a negative result).
