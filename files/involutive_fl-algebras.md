# Involutive FL-algebras

Abbreviation: **InFL**

## Definition
An ***involutive FL-algebra*** or ***involutive residuated lattice*** is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim, -\rangle$ of type $\langle 2, 2, 2, 0, 1, 1\rangle$ such that

$\langle A, \vee, \wedge\rangle$ is a [lattice](lattices.md)

$\langle A, \cdot, 1\rangle$ is a [monoid](monoids.md)

$(\sim,-)$ are an ***involutive pair***: ${\sim}-x=x=-{\sim}x$ and

$xy\le z\iff x\le -(y({\sim}z))\iff y\le {\sim}((-z)x)$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be involutive residuated lattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$, $h(x \cdot y)=h(x) \cdot h(y)$, $h({\sim}x)={\sim}h(x)$ and $h(1)=1$. 

## Definition
An ***involutive FL-algebra*** is an [FL-algebra](fl-algebras.md) $\mathbf{A}=\langle A,\vee,\wedge,\cdot,1,\backslash,/,0\rangle$ such that

involution holds: $(0/x)\backslash 0=x=0/(x\backslash 0)$

## Examples
Example 1: 

## Basic results


## Properties



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |Value  |
|[Equational theory](equational_theory.md)                |Decidable [GalatosJipsen2012] |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   |No |
|[Residual size](residual_size.md)                    |$\infty$ |
|[Congruence distributive](congruence_distributive.md)          |Yes |
|[Congruence modular](congruence_modular.md)               |Yes |
|[Congruence n-permutable](congruence_n-permutable.md)        | |
|[Congruence regular](congruence_regular.md)               | |
|[Congruence uniform](congruence_uniform.md)               | |
|[Congruence extension property](congruence_extension_property.md)    | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      |No |
|[Amalgamation property](amalgamation_property.md)            | |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |

## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 2 |
| 4 | 9 |
| 5 | 21 |
| 6 | 101 |
| 7 | 284 |
| 8 | 1464 |

## Subclasses
[Cyclic involutive FL-algebras](cyclic_involutive_fl-algebras.md) subvariety

[Integral involutive FL-algebras](integral_involutive_fl-algebras.md) subvariety


## Superclasses
[FL-algebras](fl-algebras.md) supervariety


## References


N. Galatos and P. Jipsen, ***Residuated frames with applications***, Transactions of the AMS, to appear 



