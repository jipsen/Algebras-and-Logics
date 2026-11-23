# Pseudocomplemented distributive lattices

Abbreviation: **pcDLat**

## Definition
A ***pseudocomplemented distributive lattice*** is a structure $\mathbf{L}=\langle L,\vee,0,\wedge,^*\rangle$ such that


$\langle L,\vee,0,\wedge\rangle$ is a [distributive lattice](distributive_lattices.md) with bottom element $0$


$x^*$ is the ***pseudo complement*** of $x$:  $y\leq x^* \iff x\wedge y=0$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be pseudocomplemented distributive lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(0)=0$, $h(x^*)=h(x)^*$

## Definition
A ***pseudocomplemented distributive lattice*** is a structure $\mathbf{L}=\langle L,\vee,0,\wedge,^*\rangle$ such that


$\langle L,\vee,0,\wedge\rangle$ is a [distributive lattice](distributive_lattices.md)


$0$ is the bottom element:  $0\leq x$


$x\wedge(x\wedge y)^*=x\wedge y^*$


$x\wedge 0^*=x$


$0^{**}=0$


## Examples
Example 1: 

## Basic results
Pseudocomplemented distributive lattices are term equivalent to [distributive p-algebras](distributive_p-algebras.md).


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
|[Locally finite](locally_finite.md)  | |
|[Residual size](residual_size.md)  | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 1 |

## Subclasses
[Distributive double p-algebras](distributive_double_p-algebras.md) 

## Superclasses
[Distributive lattices](distributive_lattices.md) 


## References


)]