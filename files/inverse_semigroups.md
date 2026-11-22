# Inverse semigroups

Abbreviation: **InvSgrp**
## Definition
An ***inverse semigroup*** is a structure $\mathbf{S}=\langle
S,\cdot,^{-1}\rangle$ such that


$\cdot$ is associative:  $(xy)z=x(yz)$


$^{-1}$ is an inverse:  $xx^{-1}x=x$ and $(x^{-1})^{-1}=x$


idempotents commute:  $xx^{-1}yy^{-1}=yy^{-1}xx^{-1}$
### Morphisms
Let $\mathbf{S}$ and $\mathbf{T}$ be inverse semigroups. A morphism from 
$\mathbf{S}$ to $\mathbf{T}$ is a function $h:S\rightarrow T$ that is a
homomorphism: 

$h(xy)=h(x)h(y)$, $h(x^{-1})=h(x)^{-1}$

## Examples
Example 1: $\langle I_X,\circ,^{-1}\rangle$, the ***symmetric inverse semigroup*** of all one-to-one partial functions on a set $X$, with
composition and function inverse. Every inverse semigroup can be embedded in a symmetric inverse semigroup.


## Basic results

$x*x=x \implies \exists y\ x=y*y^{-1}$

$\forall x\exists y\ xx^{-1}=y^{-1}y$

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |Variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |No |
|[Residual size](residual_size.md)  | |
|[Congruence distributive](congruence_distributive.md)  |No |
|[Congruence modular](congruence_modular.md)  |No |
|[Congruence n-permutable](congruence_n-permutable.md)  |No |
|[Congruence regular](congruence_regular.md)  |No |
|[Congruence uniform](congruence_uniform.md)  |No |
|[Congruence extension property](congruence_extension_property.md)  |No |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |No |
|[Amalgamation property](amalgamation_property.md)  |Yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |Yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |Yes |
## Finite members

Number of members with $n$ elements, counted up to isomorphism and anti-isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 2 |
| 3 | 5 |
| 4 | 16 |
| 5 | 52 |
| 6 | 208 |
| 7 | 911 |
| 8 | 4637 |
| 9 | 26422 |
| 10 | 169163 |
| 11 | 1198651 |
| 12 | 9324047 |
| 13 | 78860687 |
| 14 | 719606005 |
| 15 | 7035514642 |

[OEIS A001428](https://oeis.org/A001428)

## Subclasses
[Groups](groups.md) 

[Commutative inverse semigroups](commutative_inverse_semigroups.md) 

## Superclasses
[Semigroups](semigroups.md) 


## References


)]