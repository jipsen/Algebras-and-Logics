# Implicative lattices

Abbreviation: **ImpLat**
## Definition
An ***implicative lattice*** is a structure $\mathbf{A}=\langle A,\vee,\wedge,\to\rangle$ such that 

$\langle A,\vee,\wedge\rangle$ is a [distributive lattice](distributive_lattices.md)
$\to$ is an implication: 


$x\to(y\vee z) = (x\to y)\vee(x\to z)$


$x\to(y\wedge z) = (x\to y)\wedge(x\to z)$


$(x\vee y)\to z = (x\to z)\wedge(y\to z)$


$(x\wedge y)\to z = (x\to z)\vee(y\to z)$
### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be involutive lattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\vee y)=h(x)\wedge h(y)$, $h(x\to y)=h(x)\to h(y)$

Nestor G. Martinez,H. A. Priestley,***On Priestley spaces of lattice-ordered algebraic structures***,
Order,
**15**1998,297--323[MRreview](http://www.ams.org/mathscinet-getitem?mr=2001b:06013)

Nestor G. Martinez,***A simplified duality for implicative lattices and $l$-groups***,
Studia Logica,
**56**1996,185--204[MRreview](http://www.ams.org/mathscinet-getitem?mr=97g:06014)

## Examples
Example 1: 

## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 1 |

## Subclasses
[Goedel algebras](goedel_algebras.md) 

[MV-algebras](mv-algebras.md) 

[Lattice-ordered groups](lattice-ordered_groups.md) 

## Superclasses
[Distributive lattices](distributive_lattices.md) 


## References


)]