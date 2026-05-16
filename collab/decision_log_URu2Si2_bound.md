# Decision Log: URu₂Si₂ Bound Derivation

**Date:** 2026-05-16  
**Topic:** Corrected interpretation of the first calculable Path A model  
**Files affected:** `math/first_calculable_model.md`, `math/corrected_bound_URu2Si2.md`

---

## Decision

Adopt the corrected bound framing:

\[
\text{Landau shift}
\neq
\text{URu₂Si₂ phenomenological sensitivity}
\neq
\text{fifth-force/equivalence-principle bound}.
\]

The previous \(50\,{\rm mK}\) estimate should **not** be described as a fifth-force-derived upper bound.

It should be described as a phenomenological URu₂Si₂ sensitivity scale.

---

## Reason

The Landau model gives

\[
\delta T_{\rm HO}
=
-\frac{\lambda_{\phi\psi}\langle\phi\rangle}{a}.
\]

URu₂Si₂ thermodynamic data directly constrain the product

\[
\frac{\lambda_{\phi\psi}\langle\phi\rangle}{a}.
\]

Fifth-force experiments constrain scalar couplings to ordinary matter. They do not automatically constrain the hidden-sector coupling

\[
\lambda_{\phi\psi}
\]

unless HQR specifies a matching relation between hidden-order coupling and ordinary matter coupling.

---

## Adopted Bounds

### Phenomenological URu₂Si₂ sensitivity

\[
|\delta T_{\rm HO}|_{\rm phen}
\lesssim
10\text{--}50\,{\rm mK}.
\]

This is a material/experimental sensitivity scale.

It is not a fifth-force bound.

### Fifth-force bound under universal unscreened coupling

If the scalar is an ordinary unscreened long-range scalar whose hidden-order coupling tracks ordinary matter coupling, then

\[
\frac{\delta T_{\rm HO}}{T_{\rm HO}}
\lesssim
\alpha_\phi\frac{\Phi_\oplus}{c^2}.
\]

With

\[
\alpha_\phi\lesssim10^{-11},
\qquad
\frac{\Phi_\oplus}{c^2}\approx7\times10^{-10},
\qquad
T_{\rm HO}\approx17.5\,{\rm K},
\]

we obtain

\[
|\delta T_{\rm HO}|_{\rm fifth-force}
\lesssim
1.2\times10^{-19}\,{\rm K}.
\]

This is effectively zero for laboratory thermodynamics.

---

## Consequence for HQR

A measurable mK-scale URu₂Si₂ signal cannot come from a generic unscreened universal fifth-force scalar.

Therefore a meaningful HQR signal must involve one or more of the following:

1. screening,
2. material-sector-specific coupling,
3. topological hidden-order coupling,
4. correlated observables rather than a simple absolute \(T_{\rm HO}\) shift.

This is now the key falsifiability constraint for the first Path A model.

---

## Manuscript Language to Avoid

Avoid:

> Current fifth-force constraints allow \(|\delta T_{\rm HO}|\lesssim50\,{\rm mK}\).

Use instead:

> URu₂Si₂ thermodynamics provide a phenomenological mK-scale sensitivity target, but ordinary fifth-force constraints suppress any universal unscreened scalar contribution to far below detectability.

---

## Next Task

Develop a second model:

```text
math/material_specific_screening_model.md
```

Goal:

derive whether a screened or topological coupling can affect URu₂Si₂ hidden-order observables without violating equivalence-principle and fifth-force bounds.
