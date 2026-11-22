# Partial monoids

Abbreviation: **PMon**

## Definition
A ***partial monoid*** is a structure $\mathbf{A}=\langle A,\cdot,e\rangle$, where $\langle A,\cdot\rangle$ is a [partial semigroup](partial_semigroups.md) and

$e$ is an identity for $\cdot$: $x\cdot e=x=e\cdot x$ for all $x\in A$.


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be partial monoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(e)=e$ and
if $x\cdot y\ne *$ then $h(x \cdot y)=h(x) \cdot h(y)$.

## Examples
Example 1: Any partial semigroup with a new element $e$ and $\cdot$ extended with $x\cdot e=x=e\cdot x$.

## Basic results


## Properties



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |first-order  |
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
| 2 | 3 |
| 3 | 15 |
| 4 | 112 |

http://mathv.chapman.edu/~jipsen/uajs/PMon.html

## Subclasses
[Partial commutative monoids](partial_commutative_monoids.md)

[Monoids](monoids.md)


## Superclasses
[Partial semigroups](partial_semigroups.md)


## References


