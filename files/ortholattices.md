# Ortholattices

Abbreviation: **OLat**

## Definition
An ***ortholattice*** is a structure $\mathbf{L}=\langle L,\vee,0,\wedge,1,'\rangle$ such that

$\langle L,\vee,0,\wedge,1\rangle$ is a bounded lattice

$'$ is complementation:  $x\vee x'=1$, $x\wedge x'=0$, $x''=x$

$'$ satisfies De Morgan's laws:  $(x\vee y)'=x'\wedge y'$, $(x\wedge y)'=x'\vee y'$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be ortholattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\to M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x')=h(x)'$

## Examples
Example 1: $\langle P(S),\cup ,\emptyset ,\cap ,S\rangle$, the collection
of subsets of a set $S$, with union, empty set, intersection, and the whole
set $S$.



## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  | Yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  | Yes [BrunsHarding1997] |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |

## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members | subdirectly irreducible |
|--:|--:|--:|
| 1 | 1 | 0 |
| 2 | 1 | 1 |
| 3 | 0 | 0 |
| 4 | 1 | 0 |
| 5 | 0 | 0 |
| 6 | 2 | 2 |
| 7 | 0 | 0 |
| 8 | 5 | 3 |
| 9 | 0 | 0 |
| 10 | 15 | 11 |
| 11 | 0 | 0 |
| 12 | 60 | 45 |
| 13 | 0 | 0 |
| 14 | 311 | 240 |
| 15 | 0 | 0 |
| 17 | 0 | 0 |
| 19 | 0 | 0 |
| 21 | 0 | 0 |
| 23 | 0 | 0 |
| 25 | 0 | 0 |

## Subclasses
[Orthomodular lattices](orthomodular_lattices.md) 


## Superclasses
[Complemented lattices](complemented_lattices.md) 


## References


G. Bruns and J. Harding, ***Amalgamation of ortholattices***, Order 14 (1997/98), no. 3, 193–209
[MRreview](http://www.ams.org/mathscinet-getitem?mr=99f:06014)
