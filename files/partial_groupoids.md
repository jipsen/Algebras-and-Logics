# Partial groupoids

Abbreviation: **Pargoid**

## Definition
A ***partial groupoid*** is a structure $\mathbf{A}=\langle A,\cdot\rangle$, where 

$\cdot$ is a ***partial binary operation***, i.e., $\cdot: A\times A\to A+\{*\}$.

Remark: The domain of definition of $\cdot$ is Dom$(\cdot)=\{\langle x,y\rangle\in A^2 \mid x\cdot y\ne *\}$ 

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be partial groupoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
if $x\cdot y\ne *$ then $h(x \cdot y)=h(x) \cdot h(y)$

## Examples
Example 1: The empty partial binary operation on any set $A$ gives a partial groupoid.

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
| 1 | 2 |
| 2 | 45 |
| 3 | 43968 |
| 4 | 6358196250 |
| 5 | 236919104155855296 |

See [OEIS A090601](https://oeis.org/A090601)

## Subclasses
[Groupoids](groupoids.md)

[Partial semigroups](partial_semigroups.md)


## Superclasses
[Ternary relations](ternary_relations.md)


## References


E. S. Ljapin and A. E. Evseev, ***The theory of partial algebraic operations***, Kluwer, 1997 



