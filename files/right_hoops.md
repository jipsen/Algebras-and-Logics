# Right hoops

## Definition
A ***right hoop*** is a structure $\mathbf{A}=\langle A,\cdot,/,1\rangle$ of type $\langle 2,2,0\rangle$ such that

$\langle A,\cdot ,1\rangle$ is a [monoid](monoids.md)

$x/(y\cdot z) = (x/z)/y$

$x/x=1$

$(x/y)\cdot y = (y/x)\cdot x$


Remark: 
This definition shows that right hoops form a variety.

Right hoops are partially ordered by the relation $x\leq y \iff
y/x=1$.

The operation $x\wedge y = (x/y)\cdot y$ is a meet with respect to this order.


## Definition
A ***right hoop*** is a structure $\mathbf{A}=\langle A,\cdot,/,1\rangle$ of type $\langle 2,2,0\rangle$ such that

$x\cdot y = y\cdot x$

$x\cdot 1 = x$

$x/(y\cdot z) = (x/z)/y$

$x/x=1$

$(x/y)\cdot y = (y/x)\cdot x$


## Definition
A ***right hoop*** is a structure $\mathbf{A}=\langle A,\cdot,/,1\rangle$ of type $\langle 2,2,0\rangle$ such that

$\langle A,\cdot ,1\rangle$ is a [commutative monoid](commutative_monoids.md)

and if $x\le y$ is defined by $y/x = 1$ then

$\le$ is a partial order,

$/$ is the right residual of $\cdot$, i.e., $\x\cdot y\le z \iff x\le z/y$, and

$(x/y)\cdot y = (y/x)\cdot x$.


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be hoops. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\cdot y)=h(x)\cdot h(y)$, $h(x/y)=h(x)/h(y)$, $h(1)=1$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  | |
|[Congruence modular](congruence_modular.md)  | |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 2 |
| 4 | 8 |
| 5 | 24 |
| 6 | 91 |

## Subclasses
[hoops](hoops.md) 

## Superclasses
[Porrims](porrims.md) 

## References


)]