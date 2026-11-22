# Generalized effect algebras

Abbreviation: **GEAlg**

## Definition
A ***generalized effect algebra*** is a [separation algebra](separation_algebras.md) that is

***positive***: $x\cdot y=e$ implies $x=e=y$.

## Definition
A ***generalized effect algebra*** is of the form $\langle A,+,0\rangle$ where $+:A^2\to A\cup\{*\}$ is a partial operation such that

$+$ is ***commutative***: $x+y\ne *$ implies $x+y=y+x$

$+$ is ***associative***: $x+y\ne *$ implies $(x+y)+z=x+(y+z)$

$0$ is an ***identity***: $x+0=x$

$+$ is ***cancellative***: $x+y=x+z$ implies $y=z$ and

$+$ is ***positive***: $x+y=0$ implies $x=0$.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be generalized effect algebra. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(e)=e$ and
if $x+ y\ne *$ then $h(x + y)=h(x) + h(y)$.

## Examples
Example 1: 

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
| 2 | 1 |
| 3 | 2 |
| 4 | 5 |
| 5 | 12 |
| 6 | 35 |
| 7 | 119 |
| 8 | 496 |
| 9 | 2699 |
| 10 | 21888 |
| 11 | 292496 |

## Subclasses
[Effect algebras](effect_algebras.md)

[Generalized orthoalgebras](generalized_orthoalgebras.md)

## Superclasses
[separation algebras](separation_algebras.md)

[Generalized pseudo-effect algebras](generalized_pseudo-effect_algebras.md)

## References


