# Residuated partially ordered monoids

Abbreviation: **RpoMon**

## Definition
A ***residuated partially ordered monoid*** (or ***rpo-monoid***) is a structure $\mathbf{A}=\langle A,\le,\cdot,1,\backslash,/\rangle$ such that

$\langle A,\le\rangle$ is a [partially ordered set](partially_ordered_sets.md),

$\langle A,\cdot,1\rangle$ is a [monoid](monoids.md) and

$\backslash$ is the left residual of $\cdot$:  $x\cdot y\le z\iff y\le x\backslash z$

$/$ is the right residual of $\cdot$:  $x\cdot y\le z\iff x\le z/y$.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be residuated po-monoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is an order-preserving homomorphism: 
$x\le y\implies h(x)\le h(y)$, $h(x \cdot y)=h(x) \cdot h(y)$, $h(x \backslash y)=h(x) \backslash h(y)$, $h(x / y)=h(x) / h(y)$.

## Examples

## Basic results


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |order variety [Ln19xx]  |
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
  f(2)= &\\
  f(3)= &\\
  f(4)= &\\
  f(5)= &\\
\end{array}$     
$\begin{array}{lr}
  f(6)= &\\
  f(7)= &\\
  f(8)= &\\
  f(9)= &\\
  f(10)= &\\
\end{array}$


## Subclasses

[Commutative residuated partially ordered monoids](commutative_residuated_partially_ordered_monoids.md)

[Involutive residuated partially ordered monoids](involutive_residuated_partially_ordered_monoids.md)

[Residuated lattices](residuated_lattices.md)


## Superclasses

[Partially ordered monoids](partially_ordered_monoids.md)

[Residuated partially ordered semigroups](residuated_partially_ordered_semigroups.md)


## References





