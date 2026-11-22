# Partially ordered monoids

Abbreviation: **PoMon**

## Definition
A ***partially ordered monoid*** is a structure $\mathbf{A}=\langle A,\cdot,1,\le\rangle$ such that

$\langle A,\cdot,1\rangle$ is a [monoid](monoids.md)

$\langle G,\le\rangle$ is a [partially ordered set](partially_ordered_sets.md)

$\cdot$ is ***orderpreserving***:  $x\le y\Longrightarrow wxz\le wyz$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be partially ordered monoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is an orderpreserving homomorphism: 
$h(x \cdot y)=h(x) \cdot h(y)$, $h(1)=1$,
$x\le y\Longrightarrow h(x)\le h(y)$

## Examples
Example 1: 

## Basic results

Every monoid with the discrete partial order is a po-monoid. 

## Properties




|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |quasivariety  |
|[Equational theory](equational_theory.md)                | |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   | |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          | |
|[Congruence modular](congruence_modular.md)               | |
|[Congruence n-permutable](congruence_n-permutable.md)        | |
|[Congruence regular](congruence_regular.md)               | |
|[Congruence uniform](congruence_uniform.md)               | |
|[Congruence extension property](congruence_extension_property.md)    | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      | |
|[Amalgamation property](amalgamation_property.md)            | |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |

## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 4 |
| 3 | 37 |
| 4 | 549 |

## Subclasses
[Commutative partially ordered monoids](commutative_partially_ordered_monoids.md)

[Lattice-ordered monoids](lattice-ordered_monoids.md) expanded type


## Superclasses
[Partially ordered semigroups](partially_ordered_semigroups.md) reduced type


## References





