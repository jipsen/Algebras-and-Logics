# Distributive lattices

Abbreviation: **DLat**
## Definition
A ***distributive lattice*** is a lattice $\mathbf{L}=\langle L,\vee
,\wedge\rangle$ such that

$\wedge$ distributes over $\vee$:  $x\wedge (y\vee z) = (x\wedge y) \vee (x\wedge z)$

## Definition
A ***distributive lattice*** is a lattice $\mathbf{L}=\langle L,\vee
,\wedge\rangle$ such that

$\vee$ distributes over $\wedge$:  $x\vee (y\wedge z) = (x\vee y) \wedge (x\vee z)$

## Definition
A ***distributive lattice*** is a lattice $\mathbf{L}=\langle L,\vee
,\wedge \rangle$ such that

$(x\wedge y) \vee (x\wedge z) \vee (y\wedge z) = (x\vee y) \wedge (x\vee z) \wedge (y\vee z)$

## Definition
A ***distributive lattice*** is a lattice $\mathbf{L}=\langle L,\vee
,\wedge \rangle$ such that $\mathbf{L}$ has no sublattice isomorphic
to the diamond $\mathbf{M}_{3}$ or the pentagon $\mathbf{N}_{5}$

## Definition
A ***distributive lattice*** is a structure $\mathbf{L}=\langle L,\vee ,\wedge
\rangle$ of type $\langle 2,2\rangle$ such that

$x\wedge(x\vee y)=x$ and

$x\wedge(y\vee z)=(z\wedge x)\vee(y\wedge x)$.[Sholander1951] 


### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be distributive lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\to M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$

## Examples
Example 1: $\langle P(S),\cup ,\cap ,\subseteq \rangle$, the collection of
subsets of a sets $S$, ordered by inclusion.


## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
Equationally def. pr. cong. & yes, $\begin{array}{c}\langle c,d\rangle\in \text{Cg}(a,b)\iff \\
(a\wedge b)\wedge c=(a\wedge b)\wedge d\\ (a\vee b)\vee c=(a\vee b)\vee d\end{array}$\\\hline
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |no |
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  |2 |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 1 |
| 4 | 2 |
| 5 | 3 |
| 6 | 5 |
| 7 | 8 |
| 8 | 15 |
| 9 | 26 |
| 10 | 47 |
| 11 | 82 |
| 12 | 151 |
| 13 | 269 |
| 14 | 494 |
| 15 | 891 |
| 16 | 1639 |
| 17 | 2978 |
| 18 | 5483 |
| 19 | 10006 |
| 20 | 18428 |

Values known up to size 49 [ErneHeitigReinhold2002]

## Subclasses
[One-element algebras](one-element_algebras.md) 

[Bounded distributive lattices](bounded_distributive_lattices.md) 

[Complete distributive lattices](complete_distributive_lattices.md) 

## Superclasses
[Modular lattices](modular_lattices.md) 

[Semidistributive lattices](semidistributive_lattices.md) 


## References


M. Ern\'e, J. Heitzig, J. Reinhold,
***On the number of distributive lattices***,
Electronic J. Combinatorics 9 (2002), no. 1, Research Paper 24, 23 pp.



M. Sholander, 
***Postulates for distributive lattices***. 
Canadian J. Math. 3, (1951). 28–30.
)]