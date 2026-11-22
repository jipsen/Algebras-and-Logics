# Commutative involutive FL-algebras

Abbreviation: **CInFL**

## Definition
A ***commutative involutive FL-algebra*** or ***commutative involutive residuated lattice*** is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee, \wedge\rangle$ is a [lattice](lattices.md)

$\langle A, \cdot, 1\rangle$ is a [commutative monoid](commutative_monoids.md)

$\sim$ is an ***involution***: ${\sim}{\sim}x=x$ and

$xy\le z\iff x\le {\sim}(y({\sim}z))$

## Definition
A ***commutative involutive FL-algebra*** or ***commutative involutive residuated lattice*** is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee\rangle$ is a [semilattice](semilattices.md)

$\langle A, \cdot\rangle$ is a [commutative semigroup](commutative_semigroups.md) and

$x\le z\iff x\cdot{\sim}y\le{\sim}1$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be involutive residuated lattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$, $h(x \cdot y)=h(x) \cdot h(y)$, $h({\sim}x)={\sim}h(x)$ and $h(1)=1$. 

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
| 6 | 100 |
| 7 | 276 |
| 8 | 1392 |

## Subclasses
[Commutative idempotent involutive FL-algebras](commutative_idempotent_involutive_fl-algebras.md) subvariety

## Superclasses
[Cyclic involutive FL-algebras](cyclic_involutive_fl-algebras.md) supervariety


## References


N. Galatos and P. Jipsen, ***Residuated frames with applications***, 
Transactions of the AMS, 365 (2013), 1219-1249


