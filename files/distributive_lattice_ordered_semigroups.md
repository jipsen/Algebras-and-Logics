# Distributive lattice-ordered semigroups

Abbreviation: **DLOS**

## Definition
A ***distributive lattice ordered semigroup*** is a structure $\mathbf{A}=\langle A,\vee,\wedge,\cdot\rangle$ of type $\langle 2,2,2\rangle$ such that

$\langle A,\vee,\wedge\rangle$ is a [distributive lattice](distributive_lattices.md)

$\langle A,\cdot\rangle$ is a [semigroup](semigroups.md)

$\cdot$ distributes over $\vee$:  $x\cdot(y\vee z)=(x\cdot y)\vee (x\cdot z)$ and $(x\vee y)\cdot z=(x\cdot z)\vee (y\cdot z)$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be distributive lattice-ordered semigroups. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x\vee y)=h(x) \vee h(y)$,
$h(x\wedge y)=h(x) \wedge h(y)$,
$h(x\cdot y)=h(x) \cdot h(y)$

## Examples
Example 1: Any collection $\mathbf A$ of binary relations on a set $X$ such that $\mathbf A$ is closed under union, intersection and composition.

H. Andreka[Andreka1991] proves that these examples generate the variety DLOS.

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

$\begin{array}{lr}
  f(1)= &1\\
  f(2)= &6\\
  f(3)= &44\\
  f(4)= &479\\
  f(5)= &\\
\end{array}$

## Subclasses
[Distributive lattice-ordered monoids](distributive_lattice-ordered_monoids.md)

[Commutative distributive lattice-ordered semigroups](commutative_distributive_lattice-ordered_semigroups.md)

## Superclasses
[Lattice-ordered semigroups](lattice-ordered_semigroups.md)

## References

[Andreka1991>Hajnal Andreka, ***Representations of distributive lattice-ordered semigroups with binary relations***, Algebra Universalis **28** (1991), 12--25]


