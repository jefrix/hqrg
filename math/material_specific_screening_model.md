# Material-Specific Screening and Topological Coupling in URu₂Si₂

**Status:** second-pass Path A derivation after Claude audit  
**Lane chosen by:** ChatGPT  
**Purpose:** test whether the Path A scalar can produce a correlated URu₂Si₂ hidden-order response without behaving like an excluded universal fifth-force scalar.

---

## 1. Motivation

The first calculable model established a useful negative result:

\[
|\delta T_{\rm HO}|_{\rm fifth-force}
\ll 1\,{\rm mK}
\]

for any ordinary unscreened long-range scalar whose coupling to the hidden-order sector tracks its coupling to ordinary matter.

Therefore, a detectable HQR-relevant signal in URu₂Si₂ cannot be a generic universal fifth-force effect. It must instead be one of the following:

1. screened,
2. material-sector-specific,
3. topological,
4. or visible only as a correlated observable pattern rather than as an absolute shift of \(T_{\rm HO}\).

This file develops the minimal version of that lane.

---

## 2. Path A Constraint

We remain strictly within **Path A**.

The field

\[
\phi
\]

is treated as a postulated 4D phenomenological scalar descending from the 11D scalar \(\rho^{\rm ent}\). It is interpreted as informational in the HQR framework, but it is not derived from von Neumann entanglement entropy.

This model is therefore a 4D effective-field-theory testbed, not a proof of the full 11D theory.

---

## 3. Minimal Landau Sector and Factor-of-2 Convention

Let

\[
\eta = |\psi|
\]

be the hidden-order amplitude. Near the hidden-order transition,

\[
F_{\rm HO}
=
\frac{1}{2}a\left(T-T_{\rm HO}^{(0)}\right)\eta^2
+
\frac{u}{4}\eta^4.
\]

To remove the factor-of-2 ambiguity flagged in the audit trail, we define the scalar-order coupling with the same quadratic normalization:

\[
F_{\phi\psi}
=
\frac{1}{2}\lambda_{\phi\psi}^{\rm eff}\,\phi_{\rm loc}\,\eta^2.
\]

Then the effective quadratic coefficient is

\[
a\left(T-T_{\rm HO}^{(0)}\right)
+
\lambda_{\phi\psi}^{\rm eff}\phi_{\rm loc}.
\]

The transition shift is therefore

\[
\boxed{
\delta T_{\rm HO}
=
-\frac{\lambda_{\phi\psi}^{\rm eff}\phi_{\rm loc}}{a}
}
\tag{1}
\]

where \(\phi_{\rm loc}\) is the scalar background inside the correlated-electron medium and \(\lambda_{\phi\psi}^{\rm eff}\) is a material effective coupling.

If another convention is used, for example \(F_{\phi\psi}=\lambda_{\phi\psi}^{\rm eff}\phi\eta^2\), then Eq. (1) becomes \(-2\lambda_{\phi\psi}^{\rm eff}\phi/a\). All files in this lane use the normalized \(1/2\) convention above.

The ordinary universal scalar case corresponds to

\[
\lambda_{\phi\psi}^{\rm eff}\phi_{\rm loc}
\rightarrow
\lambda_{\rm matter}\phi_{\rm Earth},
\]

which is already fifth-force suppressed. The HQR-relevant case must differ from this.

---

## 4. Material-Specific Effective Coupling

We define

\[
\lambda_{\phi\psi}^{\rm eff}
=
\lambda_0\,\mathcal{S}_{\rm mat}(T,P,B,\epsilon,\chi,\Delta_{\rm HO}),
\tag{2}
\]

where:

- \(T\) is temperature,
- \(P\) is pressure,
- \(B\) is magnetic field,
- \(\epsilon\) is strain,
- \(\chi\) is susceptibility,
- \(\Delta_{\rm HO}\) is a hidden-order gap or collective-mode scale,
- \(\mathcal{S}_{\rm mat}\) is a material response/screening function.

The transition shift becomes

\[
\delta T_{\rm HO}(P,B,\epsilon)
=
-\frac{\lambda_0\,\mathcal{S}_{\rm mat}(P,B,\epsilon)\,\phi_{\rm loc}}{a}.
\tag{3}
\]

This is important: the prediction is no longer a single number. It is a correlated pattern.

---

## 5. Local Scalar Equation in the Material

To avoid treating \(\mathcal{S}_{\rm mat}\) as a free fudge factor, define \(\phi\) through a local static response equation:

\[
\left(
-\nabla^2 + m_{\rm eff}^2({\rm env})
\right)\phi
=
J_{\rm HO}.
\tag{4}
\]

Here the effective mass may depend on the environment:

\[
m_{\rm eff}^2({\rm env})
=
m_0^2
+\xi_\rho \rho_{\rm matter}
+\xi_\eta \eta^2
+\xi_\epsilon \epsilon_{ij}\epsilon^{ij}
+\xi_\chi \chi_{ij}\chi^{ij}.
\tag{5}
\]

The hidden-order source is taken to be

\[
J_{\rm HO}
=
q_\eta \eta^2
+q_v e_v
+q_\epsilon \epsilon_{ij}^{\rm dev}\epsilon_{\rm dev}^{ij}
+q_B \chi_{ij}B_iB_j
+q_{\rm top}\mathcal{Q}_{\rm top}.
\tag{6}
\]

where

\[
e_v={\rm Tr}(\epsilon)
\]

is the volume strain and \(\epsilon_{ij}^{\rm dev}\) is the deviatoric strain tensor.

This equation encodes the proposed evasion of fifth-force limits:

\[
J_{\rm HO}\neq \rho_{\rm matter}.
\]

Fifth-force experiments constrain scalar response to ordinary matter sources. This model instead tests a scalar response to hidden-order and correlated-electron sources.

---

## 6. Homogeneous Approximation

In a clean uniform sample, neglect gradients:

\[
\nabla^2\phi\approx0.
\]

Then

\[
\phi_{\rm loc}
\approx
\frac{J_{\rm HO}}{m_{\rm eff}^2}.
\tag{7}
\]

Substituting into Eq. (1),

\[
\boxed{
\delta T_{\rm HO}
\approx
-\frac{\lambda_{\phi\psi}^{\rm eff}}{a}
\frac{J_{\rm HO}}{m_{\rm eff}^2}
}
\tag{8}
\]

or explicitly,

\[
\delta T_{\rm HO}
\approx
-\frac{\lambda_{\phi\psi}^{\rm eff}}{a}
\frac{
q_\eta \eta^2
+q_v e_v
+q_\epsilon \epsilon_{ij}^{\rm dev}\epsilon_{\rm dev}^{ij}
+q_B \chi_{ij}B_iB_j
+q_{\rm top}\mathcal{Q}_{\rm top}
}{
m_0^2
+\xi_\rho \rho_{\rm matter}
+\xi_\eta \eta^2
+\xi_\epsilon \epsilon_{ij}\epsilon^{ij}
+\xi_\chi \chi_{ij}\chi^{ij}
}.
\tag{9}
\]

This is the first useful material-specific HQR ansatz.

It is still phenomenological, but it is no longer just an arbitrary scalar shift. It predicts dependence on the same quantities that tune hidden order experimentally: pressure, strain, field, susceptibility, and hidden-order amplitude.

---

## 7. Linearized Observable Predictions

For small perturbations around a reference condition,

\[
P=P_0,
\quad
B=0,
\quad
\epsilon=0,
\quad
T\approx T_{\rm HO},
\]

expand Eq. (3):

\[
\delta T_{\rm HO}(P,B,\epsilon)
\approx
\delta T_0
+A_P(P-P_0)
+A_B B^2
+A_\epsilon \epsilon
+A_{\epsilon^2}\epsilon^2
+\cdots.
\tag{10}
\]

Time-reversal symmetry usually favors even powers of magnetic field unless the hidden-order candidate itself permits a symmetry-breaking linear term.

The coefficients are not arbitrary if the model is to be useful. They should be related to the response of \(J_{\rm HO}\) and \(m_{\rm eff}\):

\[
A_X
=
-\frac{1}{a}
\frac{\partial}{\partial X}
\left(
\lambda_{\phi\psi}^{\rm eff}\frac{J_{\rm HO}}{m_{\rm eff}^2}
\right)_{X=X_0}.
\tag{11}
\]

This gives a direct fitting target for published pressure, field, strain, and susceptibility data.

---

## 8. Coupling-Independent Falsifier Ratios

Claude's audit correctly noted that Eq. (11) is still globally rescalable unless the model produces at least one dimensionless ratio independent of \(\lambda_0\), the \(q\)'s, the \(\xi\)'s, and \(m_0\). This section supplies two minimal failable ratios. They are not universal predictions of all HQR; they are **channel tests**. If the corresponding source channel is adopted, the ratio must hold.

### 8.1 Hydrostatic pressure versus volume strain

Assume the leading material source is volume strain,

\[
J_{\rm HO}^{(v)}=q_v e_v,
\qquad
 e_v={\rm Tr}(\epsilon),
\tag{12}
\]

and assume \(m_{\rm eff}\) and \(\lambda_{\phi\psi}^{\rm eff}\) vary slowly over the small perturbation. Define

\[
C\equiv \frac{\lambda_{\phi\psi}^{\rm eff}}{a m_{\rm eff}^2}.
\]

Then

\[
\delta T_{\rm HO}^{(v)}=-Cq_v e_v.
\tag{13}
\]

For a hydrostatic perturbation,

\[
e_v=-\frac{P}{K},
\tag{14}
\]

where \(K\) is the bulk modulus. Therefore

\[
A_{e_v}=-Cq_v,
\qquad
A_P=\frac{Cq_v}{K}.
\tag{15}
\]

The coupling-independent ratio is

\[
\boxed{
\mathcal{R}_{P/e}
\equiv
-\frac{K A_P}{A_{e_v}}
=1.
}
\tag{16}
\]

This ratio is failable. If pressure and independently applied volume strain do not obey Eq. (16), the pure volume-strain source channel is rejected.

For tetragonal URu₂Si₂ the practical version should use the measured elastic compliance tensor rather than an isotropic \(K\). The simple Eq. (16) is the isotropic limit; the tensor version replaces \(K^{-1}\) by the appropriate compliance combination.

### 8.2 Magnetic anisotropy ratio

Assume the leading magnetic source is susceptibility-mediated and time-reversal even:

\[
J_{\rm HO}^{(B)}=q_B\chi_{ij}B_iB_j.
\tag{17}
\]

For field along the \(c\)-axis,

\[
\delta T_{\rm HO}^{(c)}=-Cq_B\chi_c B_c^2,
\]

so

\[
A_{B,c}=-Cq_B\chi_c.
\tag{18}
\]

For field in the basal plane,

\[
A_{B,ab}=-Cq_B\chi_{ab}.
\tag{19}
\]

The coupling-independent anisotropy ratio is

\[
\boxed{
\mathcal{R}_B
\equiv
\frac{A_{B,c}}{A_{B,ab}}\frac{\chi_{ab}}{\chi_c}
=1.
}
\tag{20}
\]

This ratio is also failable. If the field-orientation dependence of \(T_{\rm HO}\) does not track the susceptibility anisotropy in this way, the pure susceptibility-source channel is rejected.

### 8.3 What these ratios accomplish

Equations (16) and (20) close the specific D3 gap flagged in the audit. They do not prove HQR, but they convert the screening lane from a globally fittable framework into a set of channel-specific tests.

A successful model must now choose a channel and accept its falsifier. The model is no longer allowed to fit arbitrary pressure, strain, and field data by freely adjusting unrelated coefficients.

---

## 9. Falsifiability Conditions

The model is falsifiable only if it satisfies all of the following.

### Condition 1: Universal scalar suppression

The universal component must remain below fifth-force bounds:

\[
|\delta T_{\rm HO}|_{\rm universal}
\ll 1\,{\rm mK}.
\tag{21}
\]

### Condition 2: Material response must be correlated

If a mK-scale effect exists, it must appear as a correlated response vector, not merely as a one-off offset:

\[
\vec{\mathcal{O}}_{\rm HO}
=
\left(
\delta T_{\rm HO},
\delta\Delta C,
\delta\Delta S,
\delta\chi_{ab},
\delta\chi_c,
\delta\omega_{\rm neutron},
\delta T_{\rm HO}(P,B,\epsilon)
\right).
\tag{22}
\]

### Condition 3: Source terms must respect material symmetry

Candidate source terms in \(J_{\rm HO}\) must transform as allowed scalar invariants under the relevant crystal symmetry and hidden-order symmetry.

### Condition 4: No arbitrary absorption into \(\mathcal{S}_{\rm mat}\)

The function \(\mathcal{S}_{\rm mat}\) cannot be used as an arbitrary fit function. It must be constructed from measured or symmetry-defined quantities.

### Condition 5: The model must fail somewhere

The model must choose at least one source channel and accept the corresponding failable ratio, such as Eq. (16) or Eq. (20). Failure of the selected ratio rejects that channel as an HQR testbed mechanism.

---

## 10. What This Model Predicts Qualitatively

If this lane is correct, then any HQR-like scalar signature in URu₂Si₂ should not show up primarily as a universal environmental shift. It should instead track hidden-order control parameters.

Promising correlations:

1. \(\delta T_{\rm HO}\) should vary with pressure in a way tied to the HO-to-AF boundary.
2. \(\delta T_{\rm HO}\) should vary with strain if the source couples to symmetry-breaking lattice channels.
3. Specific-heat anomaly changes should correlate with susceptibility or neutron-gap changes.
4. If \(\mathcal{Q}_{\rm top}\) is chiral, Raman or polarization-resolved probes may be more relevant than ordinary thermodynamics.
5. Magnetic-field dependence should be even in \(B\) unless the proposed hidden-order state breaks the relevant symmetry.

---

## 11. Immediate Research Tasks

1. Use `math/topological_source_terms.md` to choose whether \(\mathcal{Q}_{\rm top}\) is scalar, pseudoscalar, texture-based, or Berry-curvature-based.
2. Build `math/observable_vector_URu2Si2.md` listing the data streams that can constrain Eq. (22).
3. Identify the cleanest pressure/field/strain data to test Eq. (16) and Eq. (20).
4. Decide whether the first fitted channel should be:
   - volume-strain source \(q_v e_v\),
   - susceptibility source \(q_B\chi_{ij}B_iB_j\),
   - deviatoric strain source \(q_\epsilon\epsilon_{ij}^{\rm dev}\epsilon_{\rm dev}^{ij}\),
   - or topological source \(q_{\rm top}\mathcal{Q}_{\rm top}\).

---

## 12. Provisional Conclusion

The next viable HQR lane is not an ordinary long-range scalar correction to \(T_{\rm HO}\). That lane is already suppressed by fifth-force bounds.

The viable lane is a material-specific effective scalar response:

\[
\boxed{
\delta T_{\rm HO}
\approx
-\frac{\lambda_{\phi\psi}^{\rm eff}}{a}
\frac{J_{\rm HO}}{m_{\rm eff}^2}
}
\]

where \(J_{\rm HO}\) is a hidden-order source rather than ordinary mass density.

The Tier-A gate is now explicit: choose a channel and test its coupling-independent ratio.

For the volume-strain channel:

\[
\mathcal{R}_{P/e}=1.
\]

For the susceptibility channel:

\[
\mathcal{R}_B=1.
\]

If neither class of ratio can survive published URu₂Si₂ data, this lane should be rejected or pushed into a more specific topological source model.

---

## References to Use in the Next Pass

- J. S. Kim, D. Hall, P. Kumar, and G. R. Stewart, “Specific Heat of URu₂Si₂ in Fields to 42 T: Clues to the Hidden Order,” arXiv:cond-mat/0301234.
- H. Amitsuka et al., “Pressure-temperature phase diagram of the heavy-electron superconductor URu₂Si₂,” arXiv:cond-mat/0610139.
- E. Hassinger et al., “Suppression of hidden order in URu₂Si₂ under pressure and restoration in magnetic field,” arXiv:0909.4188.
- H.-H. Kung et al., “Chirality density wave of the hidden order phase in URu₂Si₂,” arXiv:1410.6398.
- P. Touboul et al., “MICROSCOPE Mission: Final Results of the Test of the Equivalence Principle,” Physical Review Letters 129, 121102 (2022).
- J. Bergé et al., “MICROSCOPE mission: first constraints on the violation of the weak equivalence principle by a light scalar dilaton,” arXiv:1712.00483.
