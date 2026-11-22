# Residuated partially ordered semigroups

Abbreviation: **RpoSgrp**

## Definition
A ***residuated partially ordered semigroups*** is a structure $\mathbf{A}=\langle A,\le,\cdot,\backslash,/\rangle$ of signature $\langle-2,2,2,2\rangle$ such that

$\langle A,\le\rangle$ is a [poset](partially_ordered_sets.md)

$\backslash$ is the left residual of $\cdot$:  $xy\le z\Longleftrightarrow y\le x\backslash z$

$/$ is the right residual of $\cdot$:  $xy\le z\Longleftrightarrow x\le z/y$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be residuated partially ordered semigroups. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is an order-preserving homomorphism: $x\le y\Longrightarrow h(x)\le h(y)$, 
$h(x\cdot y)=h(x)\cdot h(y)$, 
$h(x\backslash y)=h(x)\backslash h(y)$, 
$h(x/y)=h(x)/h(y)$.

## Examples
Example 1: 

## Basic results


## Properties

|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |po-variety [Pigozzi2004]  |
|[Equational theory](equational_theory.md)                | |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   |no|
|[Residual size](residual_size.md)                    |$\infty$|
|[Congruence distributive](congruence_distributive.md)          |no|
|[Congruence modular](congruence_modular.md)               | |
|[Congruence n-permutable](congruence_n-permutable.md)        |no|
|[Congruence regular](congruence_regular.md)               |no|
|[Congruence uniform](congruence_uniform.md)               |no|
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

## Subclasses
  [Residuated partially ordered monoids](residuated_partially_ordered_monoids.md) subvariety

## Superclasses
  [Partially ordered semigroups](partially_ordered_semigroups.md) supervariety


## References



