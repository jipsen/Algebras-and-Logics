# Partially ordered groups

Abbreviation: **PoGrp**

## Definition
A ***partially ordered group*** is a structure $\mathbf{G}=\langle G,\cdot,^{-1},1,\le\rangle$ such that

$\langle G,\cdot,^{-1},1\rangle$ is a [group](groups.md)

$\langle G,\le\rangle$ is a [partially ordered set](partially_ordered_sets.md)

$\cdot$ is ***orderpreserving***:  $x\le y\Longrightarrow wxz\le wyz$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be partially ordered groups. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is an orderpreserving homomorphism: 
$h(x \cdot y)=h(x) \cdot h(y)$,
$x\le y\Longrightarrow h(x)\le h(y)$

## Examples
Example 1: The integers, the rationals and the reals with the usual order.

## Basic results

Any [group](groups.md) is a partially ordered group with equality as partial order.

Any finite partially ordered group has only the equality relation as partial order.


## Properties



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |quasivariety  |
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

$\begin{array}{lr}
  f(1)= &1\\
  f(2)= &1\\
  f(3)= &1\\
  f(4)= &2\\
  f(5)= &1\\
\end{array}$     
$\begin{array}{lr}
  f(6)= &2\\
  f(7)= &1\\
  f(8)= &5\\
  f(9)= &2\\
  f(10)= &2\\
\end{array}$


## Subclasses
[Abelian partially ordered groups](abelian_partially_ordered_groups.md)

[Lattice-ordered groups](lattice-ordered_groups.md) expanded type


## Superclasses
[Partially ordered monoids](partially_ordered_monoids.md) reduced type


## References





