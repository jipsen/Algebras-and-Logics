# Cancellative monoids

Abbreviation: **CanMon**
## Definition
A ***cancellative monoid*** is a [monoid](monoids.md) $\mathbf{M}=\langle M, \cdot, e\rangle$ such that

$\cdot$ is left cancellative:  $z\cdot x=z\cdot y\Longrightarrow x=y$

$\cdot$ is right cancellative:  $x\cdot z=y\cdot z\Longrightarrow x=y$

### Morphisms
Let $\mathbf{M}$ and $\mathbf{N}$ be cancellative monoids. A morphism from $\mathbf{M}$
to $\mathbf{N}$ is a function $h:M\rightarrow N$ that is a homomorphism: 

$h(x\cdot y)=h(x)\cdot h(y)$, $h(e)=e$

## Examples
Example 1: $\langle\mathbb{N},+,0\rangle$, the natural numbers, with addition and
zero. 


## Basic results
All free monoids are cancellative.

All finite (left or right) cancellative monoids are reducts of [groups](groups.md).


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |quasivariety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |no |
|[Congruence modular](congruence_modular.md)  | |
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
| 4 | 2 |
| 5 | 1 |
| 6 | 2 |
| 7 | 1 |

## Subclasses
[Groups](groups.md) 

[Cancellative residuated lattices](cancellative_residuated_lattices.md) 

## Superclasses
[Cancellative semigroups](cancellative_semigroups.md) 

[Monoids](monoids.md) 


## References



