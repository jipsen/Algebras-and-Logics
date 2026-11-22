# Residuated lattices

Abbreviation: **RL**

## Definition
A ***residuated lattice*** is a structure $\mathbf{L}=\langle L, \vee, \wedge, \cdot, e, \backslash, /\rangle$ of type $\langle
2,2,2,0,2,2\rangle$ such that

$\langle L, \cdot, e\rangle$ is a [monoid](monoids.md)

$\langle L, \vee, \wedge\rangle$ is a [lattice](lattices.md)

$\backslash$ is the left residual of $\cdot$: $y\leq x\backslash z\Longleftrightarrow xy\leq z$

$/$ is the right residual of $\cdot$: $x\leq z/y\Longleftrightarrow xy\leq z$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be residuated lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash
y)=h(x)\backslash h(y)$, $h(x/y)=h(x)/h(y)$, $h(e)=e$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |variety |
|[Equational theory](equational_theory.md)                |decidable [OK1985] implementation |
|[Quasiequational theory](quasiequational_theory.md)           |undecidable |
|[First-order theory](first-order_theory.md)               |undecidable |
|[Locally finite](locally_finite.md)                   |no |
|[Residual size](residual_size.md)                    |unbounded |
|[Congruence distributive](congruence_distributive.md)          |yes |
|[Congruence modular](congruence_modular.md)               |yes |
|[Congruence n-permutable](congruence_n-permutable.md)          |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)               |no |
|[Congruence e-regular](congruence_e-regular.md)             |yes |
|[Congruence uniform](congruence_uniform.md)               |no |
|[Congruence extension property](congruence_extension_property.md)    |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      |no |
|[Amalgamation property](amalgamation_property.md)            | |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 3 |
| 4 | 20 |
| 5 | 149 |
| 6 | 1488 |
| 7 | 18554 |
| 8 | 295292 |

[Small residuated lattices](small_residuated_lattices.md)

## Subclasses
[Commutative residuated lattices](commutative_residuated_lattices.md) 

[Distributive residuated lattices](distributive_residuated_lattices.md) 

[FL-algebras](fl-algebras.md) 

[Integral residuated lattices](integral_residuated_lattices.md) 

## Superclasses
[Multiplicative lattices](multiplicative_lattices.md) 

[Residuated join-semilattices](residuated_join-semilattices.md) 

[Residuated meet-semilattices](residuated_meet-semilattices.md) 


## References


Hiroakira Ono, Yuichi Komori, ***Logics without the contraction rule***,
J. Symbolic Logic, **50**, 1985, 169--201 ZMATH
)]\end{document}
%</pre>
