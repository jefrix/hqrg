# First Calculable Model: Corrections to the Hidden-Order Transition in URu₂Si₂ (Path A)

**Goal**: Extract one concrete, potentially falsifiable correction from the Path A framework by applying it to the hidden-order transition in URu₂Si₂.

## Path A Framing

This document operates strictly within **Path A**: ρ^ent is treated as a **fundamental phenomenological scalar field** on the 11-dimensional manifold. It is **not** derived from the von Neumann entanglement entropy of any quantum state or bipartition. The name “entanglement density” is used for interpretive convenience only.

All calculations are performed within an effective 11D scalar-tensor theory with topological terms. No claim is made that geometry emerges from entanglement or that this constitutes a complete unification of quantum mechanics and gravity.

## Metric Signature and Lagrangian

We work in the **mostly-plus metric signature** \((+,-,-,-)\).

The 11D Lagrangian takes the form

\[
\mathcal{L}_{\rm HQR} = \frac{R^{(11)}}{16\pi G_{11}} 
+ \alpha \rho R^{(11)} 
- \frac{\beta}{2} g^{AB} \partial_A \rho \partial_B \rho 
- \gamma V(\rho) 
+ \mathcal{L}_{\rm hidden},
\]

where the signs are chosen for consistency with a healthy scalar field. The derived informational stress-energy tensor \(T_{AB}^{\rm info}\) is consistent with this Lagrangian (see `01_lagrangian_and_Tinfo.tex`).

## Why URu₂Si₂?

URu₂Si₂ exhibits a well-characterized but microscopically unidentified “hidden order” transition at \(T_{\rm HO} \approx 17.5\) K. High-precision thermodynamic and transport data exist across the transition. Because the order parameter remains debated, there is still room for an additional scalar degree of freedom to influence the transition without immediate contradiction with existing observations.

This makes URu₂Si₂ one of the cleanest near-term targets for testing whether the informational sector produces observable corrections in a real material.

## Compactification Requirement

**Critical point**: Any calculable prediction must use a **structured compactification** (warped product with non-trivial internal curvature or fluxes). 

A flat \(T^7\) reduction with a y-independent zero mode for ρ is degenerate with ordinary non-minimally coupled scalar-tensor gravity (Brans–Dicke type). Any shift \(\delta T_{\rm HO}\) obtained from such a reduction would not be distinctive to HQR. Therefore, step 1 below requires a warped or fluxed internal geometry in which the topological terms and internal curvature can generate effects beyond generic scalar-tensor theory.

## Target Observable

**Primary target**: A shift \(\delta T_{\rm HO}\) in the hidden-order transition temperature, or a modification to the magnitude of the specific-heat jump and entropy release across the transition.

Secondary targets include possible effects in transport or elastic properties below \(T_{\rm HO}\).

## Calculation Roadmap

To produce a concrete result, the following steps are required:

1. **Structured Dimensional Reduction**  
   Choose a specific warped-product or flux compactification ansatz. Perform the reduction of the informational sector (kinetic, non-minimal, and topological terms) to obtain the effective 4D contributions to the stress-energy tensor and to the effective potential felt by matter fields.

2. **Coupling to the Hidden-Order Parameter**  
   Introduce a minimal phenomenological coupling between the reduced informational field and the hidden-order parameter ψ (e.g., terms of the form \(\lambda \rho_{\rm eff} |\psi|^2\)). The topological sector in \(\mathcal{L}_{\rm hidden}\) may generate additional selection rules.

3. **Effective Free Energy and Transition Temperature**  
   Construct the effective Landau free energy including both conventional hidden-order terms and the new contributions from the informational sector. Minimize with respect to the order parameter to obtain
   \[
   T_{\rm HO}^{\rm eff} = T_{\rm HO}^{(0)} + \delta T(\text{couplings}).
   \]

4. **Parameter Constraints from Experiment**  
   Use existing high-precision data on the specific-heat jump, entropy release, and transition width in URu₂Si₂ to place bounds on the new coupling constants.

5. **Numerical Estimate and Comparison**  
   Compute the expected size of \(\delta T_{\rm HO}\) (or modification to the specific-heat anomaly) within the allowed parameter range and compare with current experimental resolution.

## Current Status

- The general mechanism is well-defined within Path A.
- The corrected form of \(T^{\rm info}_{AB}\) (with consistent signs under the mostly-plus signature) is available in `01_lagrangian_and_Tinfo.tex`.
- No numerical value for \(\delta T_{\rm HO}\) or the specific-heat modification has yet been computed.
- The main missing pieces are:
  - An explicit structured (warped/fluxed) reduction.
  - A controlled form for the coupling between ρ^ent and the hidden-order parameter.
  - Quantitative bounds on the new couplings from URu₂Si₂ data.

## Next Steps (Priority)

1. Specify a minimal structured compactification ansatz and carry out the reduction of the informational sector.
2. Introduce and justify a coupling between the reduced informational field and a model hidden-order parameter.
3. Perform a first mean-field estimate of the shift in transition temperature.
4. Use experimental constraints to bound the couplings and estimate the size of the effect.
5. Compare the predicted correction with existing data and conventional explanations.

## Discussion and Limitations

This calculation aims to demonstrate that the Path A framework can produce falsifiable corrections to observables in real materials. Success would show that the model has predictive content beyond generic scalar-tensor gravity. Failure (or very small effects within allowed parameter ranges) would instead constrain the size of the new couplings.

**Important limitations**:
- The coupling between ρ^ent and the hidden-order parameter is currently phenomenological.
- A fully realistic compactification (e.g., involving a specific \(G_2\) or Calabi-Yau manifold with fluxes) remains future work.
- No claim is made that this constitutes evidence that “entanglement sources gravity.”

This document is therefore both a scientific target and a technical stress test of whether the Path A formulation can move from formal consistency to genuine, distinctive predictions.

**Status**: Draft — open for calculation and refinement.
