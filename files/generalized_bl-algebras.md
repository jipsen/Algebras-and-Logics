# Generalized BL-algebras

Abbreviation: **GBL**

## Definition
A ***generalized BL-algebra*** is a [residuated lattice](residuated_lattices.md) 
$\mathbf{L}=\langle L, \vee, \wedge, \cdot, e, \backslash, /\rangle$ such that

$x\wedge y=y\cdot(y\backslash x\wedge e)$, $x\wedge y=(x/y\wedge e)\cdot y$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be generalized BL-algebras. A
morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$
that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash
y)=h(x)\backslash h(y)$, $h(x/y)=h(x)/h(y)$, $h(e)=e$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence e-regular](congruence_e-regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |

## Finite members
Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members | subdirectly irreducible |
|--:|--:|--:|
| 1 | 1 | 1 |
| 2 | 1 | 1 |
| 3 | 2 | 2 |
| 4 | 5 | 4 |
| 5 | 10 | 9 |
| 6 | 23 | 19 |
| 7 | 49 | 42 |
| 8 | 111 | 97 |

## Subclasses
[Generalized MV-algebras](generalized_mv-algebras.md) 

[Basic logic algebras](basic_logic_algebras.md) 


## Superclasses
[Distributive residuated lattices](distributive_residuated_lattices.md) 


## References


)]