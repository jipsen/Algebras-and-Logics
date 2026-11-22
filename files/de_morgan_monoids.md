# De Morgan monoids

Abbreviation: **DMMon**

## Definition
A ***De Morgan monoid*** is a structure $\mathbf{A}=\langle A,\vee,\wedge,\cdot,1,',\rangle$ of type $\langle
2,2,2,0,1\rangle$ such that

$\langle A,\vee,\wedge\rangle$ is a [distributive lattice](distributive_lattices.md),

$\langle A,\cdot,1\rangle$ is a [commutative monoid](commutative_monoids.md),

$\cdot$ is involutive residuated: $x\cdot y\le z\iff y\le (z'\cdot x)'$ and

$\cdot$ is square-increasing:  $x\le x\cdot x$.

Remark: It follows that $x''=x$ and that $(x\vee y)'=x'\wedge y'$.

Note that a De Morgan monoid is the same thing as a commutative distributive involutive residuated lattice.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be De Morgan monoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$, $h(x \cdot y)=h(x) \cdot h(y)$, $h(x')=h(x)'$ and $h(1)=1$.


## Examples
Example 1: 

## Basic results


## Properties



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |variety |
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

## Subclasses



## Superclasses



## References





