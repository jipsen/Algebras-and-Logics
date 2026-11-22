# FL-algebras

Abbreviation: **FL**
## Definition
A ***full Lambek algebra***, or ***FL-algebra***, is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \backslash, /, 0\rangle$ 
of type $\langle 2,0,2,0,2,1,2,2\rangle$ such that

$\langle A, \vee, \wedge, \cdot, 1, \backslash, /\rangle$ is a 
[residuated lattice](residuated_lattices.md) and

$0$ is an additional constant (can denote any element).

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be FL-algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash y)=h(x)\backslash
h(y)$, $h(x/y)=h(x)/h(y)$, $h(1)=1$, $h(0)=0$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable [OK1985] |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, n=2 |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence e-regular](congruence_e-regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 2 |
| 3 | 9 |

## Subclasses
[Bounded residuated lattices](bounded_residuated_lattices.md) subvariety

[FLe-algebras](fle-algebras.md) subvariety

[FLw-algebras](flw-algebras.md) subvariety

[FLc-algebras](flc-algebras.md) subvariety

[Distributive FL-algebras](distributive_fl-algebras.md) subvariety


## Superclasses
[Residuated lattices](residuated_lattices.md) reduct


## References


Hiroakira Ono, Yuichi Komori,
***Logics without the contraction rule***,
J. Symbolic Logic,
**50**1985, 169--201
ZMATH
implementation
)]