# Fields

Abbreviation: **Fld**
## Definition
A ***field*** is a [commutative ring with identity](commutative_rings_with_identity.md) $\mathbf{F}=\langle F,+,-,0,\cdot,1
\rangle$ such that


$\mathbf{F}$ is non-trivial:  $0\ne 1$


every non-zero element has a multiplicative inverse:  $x\ne 0\Longrightarrow \exists y 
(x\cdot y=1)$

Remark: 
The inverse of $x$ is unique, and is usually denoted by $x^{-1}$.


### Morphisms
Let $\mathbf{F}$ and $\mathbf{G}$ be fields. A morphism from $\mathbf{F}$
to $\mathbf{G}$ is a function $h:F\rightarrow G$ that is a homomorphism: 

$h(x+y)=h(x)+h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(1)=1$

Remark: 
It follows that $h(0)=0$ and $h(-x)=-h(x)$.

## Examples
Example 1: $\langle\mathbb{Q},+,-,0,\cdot,1\rangle$, the field of rational numbers with addition, subtraction, zero, multiplication, and one.


## Basic results
$0$ is a zero for $\cdot$: $0\cdot x=x$ and $x\cdot 0=0$.

Fields are exactly the commutative rings with identity that are simple, i.e., have only two ideals.

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |first-order |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |

## Finite members
|$n$       | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 |
|---       |---|---|---|---|---|---|---|---|---|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
|# of algs | 0 | 1 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |  0 |  1 |  0 |  1 |  0 |  0 |  1 |  1 |  0 |  1 | 0  |  0 |  0 |  1 |  0 |  1 |


For every prime $p$ and positive integer $m$ there exists, up to isomorphism, exactly one field of cardinality $p^m$, called the Galois field $GF(p^m)$.

## Subclasses
[Fields of characteristic zero](fields_of_characteristic_zero.md) 

[Algebraically closed fields](algebraically_closed_fields.md) 

## Superclasses
[Integral domains](integral_domains.md) 

