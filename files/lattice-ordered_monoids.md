# Lattice-ordered monoids

Abbreviation: **LMon**

## Definition
A ***lattice-ordered monoid*** (or ***$\ell$-monoid***) is a structure $\mathbf{A}=\langle A\vee,\wedge,\cdot,1\rangle$ of type $\langle 2,2,2,0\rangle$ such that

$\langle A,\vee,\wedge\rangle$ is a [lattice](lattices.md)

$\langle A,\cdot,1\rangle$ is a [monoid](monoids.md)

$\cdot$ distributes over $\vee$:  $x(y\vee z)=xy\vee xz$, $(x\vee y)z=xz\vee yz$

Remark: This is a template.
If you know something about this class, click on the ``Edit text of this page'' link at the bottom and fill out this page.

It is not unusual to give several (equivalent) definitions. Ideally, one of the definitions would give an irredundant axiomatization that does not refer to other classes.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be lattice ordered monoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$,
$h(x \wedge y)=h(x) \wedge h(y)$,
$h(x \cdot y)=h(x) \cdot h(y)$,
$h(1)=1$.

## Examples
Example 1: 

## Basic results


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |variety  |
|[Equational theory](equational_theory.md)                | |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   | |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          |yes |
|[Congruence modular](congruence_modular.md)               |yes |
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
| 3 | 8 |

## Subclasses
  [Residuated lattices](residuated_lattices.md) expanded type


## Superclasses
  [Lattice ordered semigroups](lattice_ordered_semigroups.md) reduced type


## References





