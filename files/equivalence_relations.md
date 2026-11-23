# Equivalence relations

Abbreviation: **EqRel**

## Definition
An ***equivalence relation*** is a structure $\mathbf{X}=\langle X,\equiv\rangle$ such that $\equiv$ is a ***binary relation on $X$*** 
(i.e. $\equiv\ \subseteq X\times X$) that
is

reflexive:  $x\equiv x$

symmetric:  $x\equiv y\Longrightarrow y\equiv x$

transitive: $x\equiv y\text{ and }y\equiv z\Longrightarrow x\equiv z$

Remark: This is a template.
If you know something about this class, click on the ``Edit text of this page'' link at the bottom and fill out this page.

It is not unusual to give several (equivalent) definitions. Ideally, one of the definitions would give an irredundant axiomatization that does not refer to other classes.

### Morphisms
Let $\mathbf{X}$ and $\mathbf{Y}$ be equivalence relations. A morphism from $\mathbf{X}$ to $\mathbf{Y}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$x\equiv^{\mathbf X} y\Longrightarrow h(x)\equiv^{\mathbf Y}h(y)$

## Definition
An ***equivalence relation*** is a [qoset](qosets.md) that is ***symmetric***: $x\equiv y\Longrightarrow y\equiv x$

## Examples
Example 1: 

## Basic results
Equivalence relations are in 1-1 correspondence with [partitions](partitions.md).


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |quasivariety  |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   |yes |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          |no |
|[Congruence modular](congruence_modular.md)               |no |
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
| 2 | 2 |
| 3 | 3 |
| 4 | 5 |
| 5 | 7 |
| 6 | 11 |
| 7 | 15 |
| 8 | 22 |
| 9 | 30 |
| 10 | 42 |

An equivalence relation on $n$ elements is determined up to isomorphism by the sizes of its blocks, so the table gives the number of integer partitions of $n$, [OEIS A000041](https://oeis.org/A000041).

The number of (labelled) equivalence relations on a fixed $n$-element set is the Bell number $B_n=\sum_{k} S(n,k)$, a sum of Stirling numbers of the second kind, [OEIS A000110](https://oeis.org/A000110).

## Subclasses

## Superclasses
  [Preordered sets](preordered_sets.md) supervariety


## References


)]