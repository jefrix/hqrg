First Calculable Model: 4D Phenomenological Constraints on Informational Scalar Couplings in URu₂Si₂ (Path A)
Status: revised bound section; conservative Path A treatment  
Purpose: derive what existing URu₂Si₂ thermodynamic data and fifth-force/equivalence-principle limits can and cannot say about a possible HQR-motivated scalar correction to the hidden-order transition temperature.
---
1. Path A Framing
This document operates strictly within Path A.
The field (\phi), interpreted as the effective 4D scalar descending from the 11D informational field (\rho^{\rm ent}), is treated here as a fundamental phenomenological scalar in four-dimensional effective field theory.
It is not assumed to be derived from von Neumann entanglement entropy.
The 11D origin is motivational. The calculation below is deliberately restricted to a 4D effective model so that the assumptions are clear and the result can be falsified or refined independently of a full compactification.
The phrase informational scalar is therefore interpretive shorthand, not yet a derived microscopic identity.
---
2. Minimal 4D Effective Lagrangian
We work with a mostly-plus metric convention ((+,-,-,-)). A minimal 4D phenomenological Lagrangian density is
[
\begin{aligned}
\mathcal{L}{4D}
&=
\frac{1}{16\pi G_4}
\left(
1+\alpha_4\phi
\right)R
-\frac{1}{2}g^{\mu\nu}\partial\mu\phi,\partial_\nu\phi
-V(\phi)
\
&\quad
-\frac{1}{2}m_\psi^2|\psi|^2
-\frac{\lambda}{4}|\psi|^4
-\lambda_{\phi\psi}\phi|\psi|^2
+\mathcal{L}_{\rm matter}.
\end{aligned}
\tag{1}
]
Here:
(\alpha_4) is the effective non-minimal coupling between (\phi) and curvature.
(V(\phi)) is the scalar potential.
(\psi) is a phenomenological hidden-order parameter for URu₂Si₂.
(\lambda_{\phi\psi}) is the direct coupling between the scalar and the hidden-order sector.
(\mathcal{L}_{\rm matter}) contains the ordinary material degrees of freedom.
The coupling
[
-\lambda_{\phi\psi}\phi|\psi|^2
]
is the leading term capable of shifting the hidden-order transition temperature.
---
3. Landau Free Energy and Transition-Temperature Shift
Near the hidden-order transition, define
[
\eta = |\psi|.
]
The effective Landau free energy for the order parameter is
[
F_{\rm eff}(\eta)
\frac{1}{2}a\left(T-T_{\rm HO}^{(0)}\right)\eta^2
+
\frac{u}{4}\eta^4
+
\lambda_{\phi\psi}\langle\phi\rangle\eta^2.
\tag{2}
]
The shifted transition temperature is written as
[
T_{\rm HO}^{\rm eff}
T_{\rm HO}^{(0)}
\frac{\lambda_{\phi\psi}\langle\phi\rangle}{a}.
\tag{3}
]
Thus
[
\boxed{
\delta T_{\rm HO}
-\frac{\lambda_{\phi\psi}\langle\phi\rangle}{a}
}
\tag{4}
]
where
[
\delta T_{\rm HO}
\equiv
T_{\rm HO}^{\rm eff}-T_{\rm HO}^{(0)}.
]
This is the first key result: URu₂Si₂ data constrain the ratio (\lambda_{\phi\psi}\langle\phi\rangle/a), not (\lambda_{\phi\psi}), (\langle\phi\rangle), or (\alpha_4) separately.
---
4. Published URu₂Si₂ Inputs
URu₂Si₂ has a hidden-order transition near
[
T_{\rm HO}\approx 17.5,{\rm K}.
\tag{5}
]
The transition is associated with a large specific-heat anomaly and entropy reconstruction that cannot be explained by the very small ordered magnetic moment alone. This is one reason URu₂Si₂ remains a canonical hidden-order material.
For a Landau estimate, one may use the measured specific-heat jump or entropy release to fit (a) and (u), but this requires a careful choice of normalization for (\eta). Until that normalization is fixed, the safest model-independent statement is the product bound
[
\boxed{
|\lambda_{\phi\psi}\langle\phi\rangle|
\leq
a,|\delta T_{\rm HO}|.
}
\tag{6}
]
If future work adopts a definite normalization for the order parameter and performs a thermodynamic fit, then Eq. (6) can be converted into a numerical bound on (\lambda_{\phi\psi}\langle\phi\rangle).
For now, the direct empirical constraint is better expressed as a bound on (\delta T_{\rm HO}).
---
5. Phenomenological Bound from URu₂Si₂ Data
Existing URu₂Si₂ thermodynamic data constrain any unmodeled scalar-induced transition shift by the observed stability, width, and sample-to-sample variation of the transition.
A conservative phenomenological sensitivity scale is
[
\boxed{
|\delta T_{\rm HO}|_{\rm phen}
\lesssim
10\text{--}50,{\rm mK}.
}
\tag{7}
]
This should be interpreted carefully.
It is not a fifth-force bound. It is a material/experimental sensitivity target: a scalar-induced shift larger than this would likely need to appear in careful high-purity thermodynamic measurements, unless it is degenerate with pressure, strain, sample quality, or some other conventional tuning parameter.
A looser sample-variation bound is
[
|\delta T_{\rm HO}|_{\rm sample}
\lesssim
\mathcal{O}(1),{\rm K}.
\tag{8}
]
This weaker bound is useful only as a conservative sanity check. It is too broad to be a sharp test of HQR.
---
6. Why Fifth-Force Limits Do Not Directly Bound (\lambda_{\phi\psi})
Fifth-force and equivalence-principle experiments constrain the coupling of a light scalar to ordinary matter.
In the present model, however, the transition shift depends on
[
\lambda_{\phi\psi}\langle\phi\rangle.
\tag{9}
]
The coupling (\lambda_{\phi\psi}) is a coupling to the hidden-order sector of URu₂Si₂, not automatically to baryon number, lepton number, mass density, or ordinary Standard Model matter.
Therefore:
[
\boxed{
\text{Fifth-force data do not directly bound }
\lambda_{\phi\psi}\langle\phi\rangle
\text{ unless a matching relation is specified.}
}
\tag{10}
]
This is the central logical point.
To use fifth-force data, HQR must assume one of the following:
(\lambda_{\phi\psi}) tracks the scalar coupling to ordinary matter.
(\phi) couples universally to material energy density.
A compactification or screening model relates (\lambda_{\phi\psi}) to (\alpha_4).
The topological hidden-order sector generates a material-specific coupling that does not reduce to ordinary matter coupling.
Only the first three allow ordinary fifth-force bounds to be applied directly.
---
7. Fifth-Force Bound Under the Universal Unscreened-Scalar Assumption
Assume, for this section only, that (\phi) is an ordinary long-range scalar whose coupling to the hidden-order sector tracks its coupling to ordinary matter.
Then the fractional transition shift should scale like the scalar potential sourced by nearby matter:
[
\frac{\delta T_{\rm HO}}{T_{\rm HO}}
\lesssim
\alpha_\phi
\frac{\Phi_\oplus}{c^2},
\tag{11}
]
where:
(\alpha_\phi) is the effective scalar coupling strength relative to gravity,
(\Phi_\oplus/c^2\approx 7\times10^{-10}) is the gravitational potential at Earth’s surface.
Using the MICROSCOPE-level long-range scalar constraint
[
\alpha_\phi\lesssim10^{-11},
\tag{12}
]
and
[
T_{\rm HO}\approx17.5,{\rm K},
\tag{13}
]
we obtain
[
|\delta T_{\rm HO}|_{\rm fifth-force}
\lesssim
17.5,{\rm K}
\times
10^{-11}
\times
7\times10^{-10}.
\tag{14}
]
Therefore
[
\boxed{
|\delta T_{\rm HO}|_{\rm fifth-force}
\lesssim
1.2\times10^{-19},{\rm K}.
}
\tag{15}
]
Even using a much looser equivalence-principle scale directly, for example
[
\eta\sim2.7\times10^{-15},
\tag{16}
]
gives
[
|\delta T_{\rm HO}|
\lesssim
17.5,{\rm K}
\times
2.7\times10^{-15}
\approx
4.7\times10^{-14},{\rm K}.
\tag{17}
]
This is still far below millikelvin detectability.
---
8. Correct Physical Conclusion
A detectable millikelvin-scale shift in URu₂Si₂ cannot be produced by a standard unscreened long-range scalar obeying current fifth-force and equivalence-principle limits.
Thus,
[
\boxed{
|\delta T_{\rm HO}|_{\rm phen}
\sim
10\text{--}50,{\rm mK}
\quad
\text{is a material sensitivity scale, not a fifth-force bound.}
}
\tag{18}
]
and
[
\boxed{
|\delta T_{\rm HO}|_{\rm fifth-force}
\lesssim
10^{-19},{\rm K}
\quad
\text{under universal unscreened scalar coupling.}
}
\tag{19}
]
This conclusion strengthens the HQR program. It prevents the first calculable model from collapsing into a generic scalar-tensor theory.
An observable HQR-relevant signal in URu₂Si₂ must instead arise through one or more of the following mechanisms:
Screening: the scalar is screened from equivalence-principle tests but not from the correlated-electron environment.
Material-sector specificity: (\lambda_{\phi\psi}) is not tied to baryonic matter coupling.
Topological coupling: the hidden-order sector couples through protected topological or brane-projection terms rather than an ordinary scalar force.
Correlated observables: the signature is not a simple absolute shift in (T_{\rm HO}), but a pattern across pressure, strain, magnetic field, entropy release, anisotropic susceptibility, or neutron-scattering response.
---
9. What Would Count as Evidence Beyond Generic Scalar-Tensor Physics?
A measured shift in (T_{\rm HO}) alone would not uniquely support HQR. It would be consistent with many possible beyond-Standard-Model scalar sectors.
A more distinctive HQR signature would require a correlated pattern such as
[
\delta T_{\rm HO}(P,B,\epsilon)
\tag{20}
]
with a specific pressure (P), magnetic field (B), and strain (\epsilon) dependence predicted by the hidden/topological sector.
Promising observables include:
shift or broadening of (T_{\rm HO}),
specific-heat jump (\Delta C),
entropy release (\Delta S),
anisotropic susceptibility,
strain response,
pressure dependence,
neutron-scattering gap structure,
correlations with proposed HQR signals in Bell tests, Casimir experiments, or gravitational-wave echoes.
For the present model, the strongest falsifiable statement is:
[
\boxed{
\text{If HQR predicts an unscreened universal scalar, it is already excluded as a source of detectable mK-scale URu₂Si₂ shifts.}
}
\tag{21}
]
Therefore, the next model must specify a screened, material-specific, or topological coupling.
---
10. Limitations
The coupling (\lambda_{\phi\psi}) is phenomenological.
The field (\phi) is not yet derived from an 11D compactification.
The order-parameter normalization for (\psi) is not fixed.
The Landau coefficients (a) and (u) require a dedicated fit to published specific-heat data.
Screening mechanisms are not modeled.
The topological hidden-order sector has not yet been reduced to a concrete 4D material coupling.
The bound in Eq. (15) applies only to a universal, unscreened, long-range scalar.
---
11. Next Technical Steps
Fit (a) and (u) using published URu₂Si₂ specific-heat data with a fixed order-parameter normalization.
Replace the single shift (\delta T_{\rm HO}) with a correlated observable vector:
[
\vec{\mathcal{O}}_{\rm HO}
\left(
\delta T_{\rm HO},
\delta \Delta C,
\delta \Delta S,
\delta \chi_{ab},
\delta \chi_c,
\delta \omega_{\rm neutron},
\delta T_{\rm HO}(P,B,\epsilon)
\right).
\tag{22}
]
Develop a screened or material-specific scalar coupling model.
Derive whether the topological hidden-order sector can generate a coupling to URu₂Si₂ that evades ordinary fifth-force bounds.
Identify a cross-domain correlation that would make the signal HQR-specific rather than generic scalar-tensor physics.
---
12. Status
This model now provides a clean separation between
[
\text{Landau shift}
]
[
\text{URu₂Si₂ phenomenological sensitivity}
]
[
\text{fifth-force/equivalence-principle suppression}.
]
The key result is not that HQR predicts a (50,{\rm mK}) fifth-force-compatible signal. It does not.
The key result is:
[
\boxed{
\text{ordinary fifth-force physics is too constrained, so any observable HQR signal must be screened, material-specific, topological, or correlated.}
}
\tag{23}
]
This is the first useful falsifiability constraint for the Path A scalar sector.
---
References
J. S. Kim, D. Hall, P. Kumar, and G. R. Stewart, “Specific Heat of URu₂Si₂ in Fields to 42 T: Clues to the Hidden Order,” arXiv:cond-mat/0301234.
C. R. Wiebe et al., “Gapped itinerant spin excitations account for missing entropy in the hidden order state of URu₂Si₂,” arXiv:0710.0896.
P. Chandra, P. Coleman, and R. Flint, “Hastatic order in the heavy-fermion compound URu₂Si₂,” Nature 493, 621–626 (2013).
H.-H. Kung et al., “Chirality density wave of the hidden order phase in URu₂Si₂,” Science 347, 1339–1342 (2015).
P. Touboul et al., “MICROSCOPE Mission: Final Results of the Test of the Equivalence Principle,” Physical Review Letters 129, 121102 (2022).
J. Bergé et al., “MICROSCOPE mission: first constraints on the violation of the weak equivalence principle by a light scalar dilaton,” arXiv:1712.00483.
