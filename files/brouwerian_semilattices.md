# Brouwerian semilattices

Abbreviation: **BrSlat**

## Definition
A ***Brouwerian semilattice*** is a structure $\mathbf{A}=\langle A, \wedge, 1, \rightarrow\rangle$ such that

$\langle A, \wedge, 1\rangle$ is a [semilattice with identity](semilattices_with_identity.md)

$\rightarrow$ gives the residual of $\wedge$:  $x\wedge y\leq z\Longleftrightarrow y\leq x\rightarrow z$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Brouwerian semilattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\wedge y)=h(x)\wedge h(y)$, $h(1)=1$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$

## Definition
A ***Brouwerian semilattice*** is a [hoop](hoops.md) $\mathbf{A}=\langle A, \cdot, 1, \rightarrow\rangle$ such that

$\cdot$ is idempotent:  $x\cdot x=x$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence e-regular](congruence_e-regular.md)  |yes, $e=1$ |
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

Values known up to size 49 [ErneHeitzigReinhold2002]

## Subclasses
[Brouwerian algebras](brouwerian_algebras.md) 


## Superclasses
[Semilattices with identity](semilattices_with_identity.md) 

[Hoops](hoops.md) 


## References


M. Ern\'e, J. Heitzig, J. Reinhold,
***On the number of distributive lattices***, 
Electronic J. Combinatorics 9 (2002), no. 1, Research Paper 24, 23 pp.
)]