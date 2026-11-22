# Neardistributive lattices

Abbreviation: **NdLat**
## Definition
A ***neardistributive lattice*** is a [Lattices](lattices.md) $\mathbf{L}=\langle L,\vee
,\wedge \rangle$ such that


SD$_{\wedge}^2$:  $x\wedge(y\vee z)=x\wedge[y\vee (x\wedge [z\vee(x\wedge y)])]$


SD$_{\vee}^2$:  $x\vee(y\wedge z)=x\vee[y\wedge (x\vee [z\wedge(x\vee y)])]$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be neardistributive lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function 
$h:L\rightarrow M$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$

## Examples
Example 1: $D[d]=\langle D\cup\{d'\},\vee ,\wedge\rangle$, where $D$ is any distributive lattice and $d$ is an element in it that
is split into two elements $d,d'$ using Alan Day's doubling construction.


## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  |no |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 1 |

## Subclasses
[Almost distributive lattices](almost_distributive_lattices.md) 

## Superclasses
[Semidistributive lattices](semidistributive_lattices.md) 


## References


)]