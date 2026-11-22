# Boolean lattices

Abbreviation: **BoolLat**
## Definition
A ***Boolean lattice*** is a 
[bounded distributive lattice](bounded_distributive_lattices.md) 
$\mathbf{L}=\langle L,\vee ,0,\wedge ,1\rangle$ such that

every element has a complement:  $\exists y(x\vee y=1\text{ and }x\wedge y=0)$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be bounded distributive lattices. 
A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\to M$ that is a
bounded lattice homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(0)=0$, $h(1)=1$

## Examples
Example 1: $\langle \mathcal P(S), \cup, \emptyset, \cap, S\rangle$, the collection
of subsets of a set $S$, with union, empty set, intersection, and the whole
set $S$.


## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |first-order |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
|[First-order theory](first-order_theory.md)  |decidable |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes |
|[Congruence regular](congruence_regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |yes |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  | |

## Finite members
Any finite member is a power of the 2-element Boolean lattice.


## Subclasses
[Boolean algebras](boolean_algebras.md)

## Superclasses
[Complemented modular lattices](complemented_modular_lattices.md) 

[Bounded distributive lattices](bounded_distributive_lattices.md) 


## References



