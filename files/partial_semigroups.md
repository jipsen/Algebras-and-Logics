# Partial semigroups

Abbreviation: **PSgrp**

## Definition
A ***partial semigroup*** is a structure $\mathbf{A}=\langle A,\cdot\rangle$, where 

$\cdot$ is a ***partial binary operation***, i.e., $\cdot: A\times A\to A+\\{*\\}$ and

$\cdot$ is ***associative***: $(x\cdot y)\cdot z\ne *$ or $x\cdot (y\cdot z)\ne *$ imply $(x\cdot y)\cdot z=x\cdot (y\cdot z)$.


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be partial groupoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
if $x\cdot y\ne *$ then $h(x \cdot y)=h(x) \cdot h(y)$

## Examples
Example 1: The morphisms is a small category under composition.

## Basic results
Partial semigroups can be identified with [semigroups with zero](semigroups_with_zero.md) since for any partial semigroup $A$ we can define a semigroup $A_0=A\cup\{0\}$ (assuming $0\notin A$)
and extend the operation on $A$ to $A_0$ by $0x=0=x0$ for all $x\in A$. Conversely, given a semigroup with zero, say $B$, define a partial semigroup 
$A=B\setminus\{0\}$ and for $x,y\in A$ let $xy=*$ if $xy=0$ in $B$. These two maps are inverses of each other. 

However, the category of partial semigroups is not the same as the category of semigroups with zero since the morphisms differ.

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

http://mathv.chapman.edu/~jipsen/uajs/PSgrp.html 

$\begin{array}{lr}
  f(1)= &2\\
  f(2)= &12\\
  f(3)= &90\\
  f(4)= &960\\
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
[Semigroups](semigroups.md)

[Partial monoids](partial_monoids.md)


## Superclasses
[Partial groupoids](partial_groupoids.md)


## References


