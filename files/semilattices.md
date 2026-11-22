# Semilattices

Abbreviation: **Slat**
## Definition
A ***semilattice*** is a structure $\mathbf{S}=\langle S,\cdot
\rangle$, where $\cdot$ is an infix binary operation, called the 
***semilattice operation***, such that


$\cdot$ is associative:  $(xy)z=x(yz)$


$\cdot$ is commutative:  $xy=yx$


$\cdot$ is idempotent:  $xx=x$


Remark: 
This definition shows that semilattices form a variety.

### Morphisms
Let $\mathbf{S}$ and $\mathbf{T}$ be semilattices. A morphism from $\mathbf{S}$ to $\mathbf{T}$ is a function $h:S\to T$ that is a homomorphism: 

$h(xy)=h(x)h(y)$

## Definition
A ***join-semilattice*** is a structure $\mathbf{S}=\langle S,\leq,\vee\rangle$, where $\vee$ is an infix binary operation, called the ***join***, such that

$\leq$ is a partial order,

$x\leq y\implies x\vee z\leq y\vee z$ and $z\vee x\leq z\vee y$,

$x\le x\vee y$ and $y\leq x\vee y$,

$x\vee x\leq x$.

This definition shows that semilattices form a partially-ordered variety.
## Definition
A ***join-semilattice*** is a structure $\mathbf{S}=\langle S,\vee
\rangle$, where $\vee$ is an infix binary operation, called the ***join***, such that


$\leq$ is a partial order, where $x\leq y\Longleftrightarrow x\vee y=y$


$x\vee y$ is the least upper bound of $\{x,y\}$.
## Definition
A ***meet-semilattice*** is a structure $\mathbf{S}=\langle S,\wedge
\rangle$, where $\wedge$ is an infix binary operation, called the ***meet***, such that


$\leq$ is a partial order, where $x\leq y\Longleftrightarrow x\wedge y=x$


$x\wedge y$ is the greatest lower bound of $\{x,y\}$.

## Examples
Example 1: $\langle \mathcal{P}_\omega(X)-\{\emptyset\},\cup\rangle$, the set of finite nonempty subsets of a set $X$, with union, is the free join-semilattice with singleton subsets of $X$ as generators.


## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable in polynomial time |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  |2 |
|[Congruence distributive](congruence_distributive.md)  |no |
|[Congruence modular](congruence_modular.md)  |no |
|[Congruence meet-semidistributive](congruence_meet-semidistributive.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |yes |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |
\end{table}## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &2\\
f(4)= &5\\
f(5)= &15\\
f(6)= &53\\
f(7)= &222\\
f(8)= &1078\\
f(9)= &5994\\
f(10)= &37622\\
f(11)= &262776\\
f(12)= &2018305\\
f(13)= &16873364\\
f(14)= &152233518\\
f(15)= &1471613387\\
f(16)= &15150569446\\
f(17)= &165269824761\\
\end{array}$

These results follow from the paper below and the observation that semilattices with $n$ elements 
are in 1-1 correspondence to lattices with $n+1$ elements.

Jobst Heitzig,J\"urgen Reinhold,***Counting finite lattices***,
Algebra Universalis,
**48**2002,43--53

## Subclasses
[Semilattices with zero](semilattices_with_zero.md) 

[Semilattices with identity](semilattices_with_identity.md) 

## Superclasses
[Bands](bands.md)

[Commutative semigroups](commutative_semigroups.md) 

[Partial semilattices](partial_semilattices.md) 


## References



