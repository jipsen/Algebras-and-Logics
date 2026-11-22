# Quantales

Abbreviation: **Quant**

## Definition
A ***quantale*** is a structure $\mathbf{A}=\langle A, \bigvee, \cdot, 0\rangle$ of type $\langle\infty, 2, 0\rangle$ such that

$\langle A, \bigvee, 0\rangle$ is a [complete semilattice](complete_semilattices.md) with $0=\bigvee\emptyset$,

$\langle A, \cdot\rangle$ is a [semigroup](semigroups.md), and

$\cdot$ distributes over $\bigvee$:  $(\bigvee X)\cdot y=\bigvee_{x\in X}(x\cdot y)$ and $y\cdot(\bigvee X)=\bigvee_{x\in X}(y\cdot x)$


Remark: In particular, $\cdot$ distributes over the empty join, so $x\cdot 0=0=0\cdot x$.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be quantales. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(\bigvee X)=\bigvee h[X]$ for all $X\subseteq A$ (hence $h(0)=0$) and
$h(x \cdot y)=h(x) \cdot h(y)$



## Examples
Example 1: 

## Basic results


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |(value, see description) [Ln19xx]  |
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
  f(2)= &2\\
  f(3)= &12\\
  f(4)= &129\\
  f(5)= &1852\\
  f(6)= &33391\\
\end{array}$

Model search done by Mace4 https://www.cs.unm.edu/~mccune/mace4/

## Subclasses



## Superclasses



## References





