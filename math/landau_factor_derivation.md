# Landau Free Energy Normalization and the Factor of 2

**Purpose**: Clarify the origin of the factor of 2 in the shift formula `δT_HO = −2 λ_φψ ⟨φ⟩ / a` and establish a consistent convention for the project.

## Two Common Normalizations

### Convention A (Standard in many condensed-matter texts)
The Landau free energy density is written as:

\[
F = \frac12 a (T - T_c) \eta^2 + \frac{u}{4} \eta^4 + \cdots
\]

The quadratic coefficient is `½ a (T − T_c)`.  
When an additional term `λ φ η²` is added, the total quadratic coefficient becomes:

\[
\frac12 a (T - T_c) + \lambda \langle\phi\rangle
\]

The transition occurs when this coefficient changes sign:

\[
\frac12 a (T - T_c) + \lambda \langle\phi\rangle = 0
\implies
\delta T = -\frac{2\lambda \langle\phi\rangle}{a}
\]

### Convention B (Sometimes used for cleaner algebra)
Some authors absorb the ½ into the definition of `a`:

\[
F = a (T - T_c) \eta^2 + \frac{u}{4} \eta^4 + \cdots
\]

In this convention the shift is simply:

\[
\delta T = -\frac{\lambda \langle\phi\rangle}{a}
\]

## Project Recommendation

We adopt **Convention A** (the version with the explicit ½) for transparency. This makes the factor of 2 explicit and avoids hidden conventions when comparing with literature.

Therefore, throughout HQR documents we use:

\[
\delta T_{\rm HO} = -\frac{2 \lambda_{\phi\psi} \langle\phi\rangle}{a}
\]

and the corresponding product bound:

\[
|\lambda_{\phi\psi} \langle\phi\rangle| \leq \frac{a}{2} |\delta T_{\rm HO}|
\]

This convention is now applied in `first_calculable_model.md`.
