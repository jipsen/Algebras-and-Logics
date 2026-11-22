# Commutative BCK-algebras

Abbreviation: **ComBCK**
## Definition
A ***commutative BCK-algebra*** is a structure $\mathbf{A}=\langle A,\cdot ,0\rangle$ of type $\langle 2,0\rangle$ such that


(1):  $((x\cdot y)\cdot (x\cdot z))\cdot (z\cdot y) = 0$


(2):  $x\cdot 0 = x$


(3):  $0\cdot x = 0$


(4):  $x\cdot y=y\cdot x= 0 \Longrightarrow x=y$


(5):  $x\cdot (x\cdot y) = y\cdot (y\cdot x)$

Remark: 
Note that the commutativity does not refer to the operation $\cdot$, but rather to the
term operation $x\wedge y=x\cdot (x\cdot y)$, which turns out to be a meet with respect
to the following partial order:

$x\le y \iff x\cdot y=0$, with $0$ as least element.

## Definition
A ***commutative BCK-algebra*** is a [BCK-algebra](bck-algebras.md) 
$\mathbf{A}=\langle A,\cdot ,0\rangle$ such that

$x\cdot (x\cdot y) = y\cdot (y\cdot x)$

## Definition
A ***commutative BCK-algebra*** is a structure $\mathbf{A}=\langle A,\cdot ,0\rangle$ of type $\langle 2,0\rangle$ such that

(1):  $(x\cdot y)\cdot z = (x\cdot z)\cdot y$

(2):  $x\cdot (x\cdot y) = y\cdot (y\cdot x)$

(3):  $x\cdot x = 0$

(4):  $x\cdot 0 = x$

This definition shows that commutative BCK algebras form a variety.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be commutative BCK-algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\cdot y)=h(x)\cdot h(y) \text{ and } h(0)=0$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |variety |
|[Equational theory](equational_theory.md)                | |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   |no |
|[Residual size](residual_size.md)                    |unbounded |
|[Congruence distributive](congruence_distributive.md)          |yes |
|[Congruence modular](congruence_modular.md)               |yes |
|[Congruence n-permutable](congruence_n-permutable.md)          |yes, $n=3$ |
|[Congruence regular](congruence_regular.md)               | |
|[Congruence uniform](congruence_uniform.md)               | |
|[Congruence extension property](congruence_extension_property.md)    | |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      |no |
|[Amalgamation property](amalgamation_property.md)            | |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &2\\
f(4)= &5\\
f(5)= &11\\
f(6)= &28\\
f(7)= &72\\
f(8)= &192\\
\end{array}$

## Subclasses
[Tarski algebras](tarski_algebras.md)

[MV-algebras](mv-algebras.md)

## Superclasses
[BCK-algebras](bck-algebras.md) 


## References








