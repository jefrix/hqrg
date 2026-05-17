# Topological Source Terms for the URu₂Si₂ Material-Specific Screening Lane

**Status:** first-pass candidate list  
**Purpose:** define possible \(\mathcal{Q}_{\rm top}\) terms for the material-specific screening model without turning the topological sector into a free parameter.

---

## 1. Why This File Exists

The material-specific screening model uses

\[
J_{\rm HO}
=
q_\eta \eta^2
+q_v e_v
+q_\epsilon \epsilon_{ij}^{\rm dev}\epsilon_{\rm dev}^{ij}
+q_B\chi_{ij}B_iB_j
+q_{\rm top}\mathcal{Q}_{\rm top}.
\]

The audit correctly flagged that \(\mathcal{Q}_{\rm top}\) is the only plausible D2 path toward an HQR-specific structural origin. If it remains undefined, the model stays Tier B.

This file ranks possible topological or quasi-topological source terms by how defensible they are.

---

## 2. Rules for Acceptable \(\mathcal{Q}_{\rm top}\)

A candidate source term is admissible only if it satisfies all four rules.

### Rule 1: Symmetry allowed

It must transform as a scalar under the unbroken symmetries of the term it appears in.

If it is a pseudoscalar or time-reversal-odd quantity, it must couple only through a matching pseudoscalar or time-reversal-odd structure.

### Rule 2: Not a fit parameter in disguise

It must be measurable, symmetry-defined, or tied to a specific order-parameter texture.

### Rule 3: Distinguishable from ordinary scalar-tensor coupling

It must not reduce to ordinary mass density or a generic scalar source.

### Rule 4: Failable

It must imply at least one observable relation that can be wrong.

---

## 3. Candidate A: Chiral Hidden-Order Pseudoscalar

If the hidden order is represented by two components

\[
\psi_x,
\qquad
\psi_y,
\]

then a natural chiral pseudoscalar is

\[
\mathcal{Q}_{\chi}
=
{\rm Im}(\psi_x^*\psi_y).
\tag{1}
\]

This term is appropriate only if the hidden-order state breaks the relevant mirror or time-reversal/chiral symmetry in the required way.

A scalar \(\phi\) cannot couple linearly to \(\mathcal{Q}_{\chi}\) unless the product is symmetry-even. Therefore the safe scalar source is

\[
\mathcal{Q}_{\rm top}^{(\chi^2)}
=
\mathcal{Q}_{\chi}^2.
\tag{2}
\]

A pseudoscalar partner \(\tilde{\phi}\) could couple linearly:

\[
J_{\rm top}=\tilde{q}_{\chi}\tilde{\phi}\,\mathcal{Q}_{\chi},
\]

but that introduces a new field and should not be assumed in the minimal Path A scalar model.

### Observable implication

If \(\mathcal{Q}_{\chi}^2\) is the source, the leading thermodynamic shift should be insensitive to the sign of chirality but sensitive to probes of chiral domain formation.

A possible failable relation is:

\[
\delta T_{\rm HO}\propto \mathcal{Q}_{\chi}^2.
\]

So reversing chirality should not reverse the sign of \(\delta T_{\rm HO}\), but changing chiral-domain fraction should change its magnitude.

**Tier:** B candidate until a measured chiral order parameter is specified.

---

## 4. Candidate B: Texture / Winding Density

If the hidden-order parameter has a spatial texture, define a normalized two-component vector

\[
\hat{n}
=
(n_1,n_2,n_3)
\]

or an appropriate multipolar analogue. A skyrmion-like topological density is

\[
\mathcal{Q}_{\rm sk}
=
\hat{n}\cdot
\left(
\partial_x\hat{n}\times\partial_y\hat{n}
\right).
\tag{3}
\]

For a scalar source, use either

\[
\mathcal{Q}_{\rm top}^{({\rm sk})}
=
\mathcal{Q}_{\rm sk}^2
\]

or a domain-wall density derived from gradients:

\[
\mathcal{Q}_{\rm grad}
=
(\partial_i\eta)(\partial^i\eta).
\tag{4}
\]

### Observable implication

This source predicts that the HQR-like signal is enhanced by domain walls, strain-induced textures, defects, or phase coexistence.

A failable relation is:

\[
\delta T_{\rm HO}^{\rm texture}
\propto
\langle \mathcal{Q}_{\rm grad}\rangle
\]

so cleaner homogeneous samples should show a smaller effect than textured or strained samples, after controlling for ordinary disorder.

**Tier:** B/C depending on whether a real texture observable is identified.

---

## 5. Candidate C: Berry-Curvature / Anomalous Response Source

A more electronic topological source can be written schematically as a Berry-curvature invariant:

\[
\mathcal{Q}_{\Omega}
=
\int_{\rm FS}
{\rm Tr}\left(\Omega\wedge\Omega\right),
\tag{5}
\]

where \(\Omega\) is a Berry curvature associated with reconstructed heavy-fermion bands or the hidden-order quasiparticle manifold.

This is appealing because it is closer to an electronic topological response than to ordinary strain or density.

### Observable implication

If this source is active, the HQR-like shift should correlate with band reconstruction observables, not merely with pressure or disorder.

Possible correlated probes:

- quantum oscillation reconstruction,
- anomalous Hall-like responses if symmetry permits,
- optical/Raman signatures,
- changes in gap topology across the hidden-order transition.

**Tier:** B candidate if a concrete band/topological invariant is computed; C if left schematic.

---

## 6. Candidate D: Chern-Simons-Like Effective Source

A formal 4D topological density could be written as

\[
\mathcal{Q}_{\rm CS}
\sim
\epsilon^{\mu\nu\rho\sigma}
A_\mu F_{\nu\rho}F_{\sigma\lambda}u^\lambda,
\tag{6}
\]

or, in condensed-matter language, as an axion-like magnetoelectric response

\[
\mathcal{Q}_{\theta}
\sim
\theta_{\rm HO}\,\mathbf{E}\cdot\mathbf{B}.
\tag{7}
\]

This is only admissible if the hidden-order state supports such an axion-like or magnetoelectric response. It should not be inserted by analogy alone.

### Observable implication

A Chern-Simons-like source predicts electromagnetic response correlations, not just thermodynamic shifts.

**Tier:** C until tied to a concrete URu₂Si₂ hidden-order model.

---

## 7. Current Recommendation

For the next pass, do **not** begin with the most exotic topological term.

Use this order of attack:

1. **Volume strain channel**: most directly failable through pressure/strain ratio.
2. **Susceptibility channel**: directly failable through magnetic anisotropy ratio.
3. **Chiral source \(\mathcal{Q}_{\chi}^2\)**: plausible if the chirality-density-wave interpretation is adopted.
4. **Berry-curvature source**: promising but requires more band-structure work.
5. **Chern-Simons/axion source**: defer until a real magnetoelectric/axion response is identified.

---

## 8. Minimum Tier-A Gate for a Topological Source

A topological source reaches Tier A only if it produces a coupling-independent failable relation.

Examples:

### Chirality-domain test

\[
\delta T_{\rm HO}\propto f_{\chi}\,\mathcal{Q}_{\chi}^2
\]

where \(f_\chi\) is a measured chiral-domain fraction.

Then

\[
\frac{\delta T_{\rm HO}^{(1)}}{\delta T_{\rm HO}^{(2)}}
=
\frac{f_\chi^{(1)}}{f_\chi^{(2)}}
\]

if all other conditions are controlled.

### Texture-density test

\[
\frac{\delta T_{\rm HO}^{\rm strained}}{\delta T_{\rm HO}^{\rm relaxed}}
=
\frac{
\langle\mathcal{Q}_{\rm grad}\rangle_{\rm strained}
}{
\langle\mathcal{Q}_{\rm grad}\rangle_{\rm relaxed}
}.
\]

These are hard tests. That is the point.

---

## 9. Conclusion

The topological source lane is promising but dangerous. It can make HQR distinctive, but only if \(\mathcal{Q}_{\rm top}\) is not used as a symbolic placeholder for unknown physics.

The safest immediate path is to test the scalar/material channels first using coupling-independent ratios, then introduce topological terms only when they imply measurable domain, chirality, texture, or Berry-curvature relations.
