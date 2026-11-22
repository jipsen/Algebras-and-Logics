# BCK-algebras

Abbreviation: **BCK**
## Definition
A ***BCK-algebra*** is a structure $\mathbf{A}=\langle A,\cdot ,0\rangle$ of type $\langle 2,0\rangle$ such that

(1):  $((x\cdot y)\cdot (x\cdot z))\cdot (z\cdot y) = 0$

(2):  $x\cdot 0 = x$

(3):  $0\cdot x = 0$

(4):  $x\cdot y=y\cdot x= 0 \Longrightarrow x=y$

Remark: 
$x\le y \iff x\cdot y=0$ is a partial order, with $0$ as least element.

BCK-algebras provide [algebraic semantics](algebraic_semantics.md) for BCK-logic, named after
the combinators B, C, and K by C. A. Meredith, see [Prior1962].

## Definition
A ***BCK-algebra*** is a [BCI-algebra](bci-algebras.md) 
$\mathbf{A}=\langle A,\cdot ,0\rangle$ such that

$x\cdot 0 = x$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be BCK-algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x\cdot y)=h(x)\cdot h(y)$ and $h(0)=0$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |quasivariety [Wronski1983] |
|[Equational theory](equational_theory.md)                | |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               |undecidable |
|[Locally finite](locally_finite.md)                   |no |
|[Residual size](residual_size.md)                    |unbounded |
|[Congruence distributive](congruence_distributive.md)          |no |
|[Congruence modular](congruence_modular.md)               |no |
|[Congruence n-permutable](congruence_n-permutable.md)          |no |
|[Congruence regular](congruence_regular.md)               |no |
|[Congruence uniform](congruence_uniform.md)               |no |
|[Congruence extension property](congruence_extension_property.md)    |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      |no |
|[Amalgamation property](amalgamation_property.md)            |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)     |yes [Wronski1984] |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 3 |
| 4 | 14 |
| 5 | 88 |
| 6 | 775 |

## Subclasses
[Commutative BCK-algebras](commutative_bck-algebras.md) 

## Superclasses
[BCI-algebras](bci-algebras.md) 


## References


A. N. Prior, ***Formal logic***,
Second edition, Clarendon Press, Oxford, 1962, p.316


Andrzej Wronski,***BCK-algebras do not form a variety***,
Math. Japon., **28**, 1983, 211--213


Andrzej Wronski,***Interpolation and amalgamation properties of BCK-algebras***,
Math. Japon., **29**, 1984, 115--121




