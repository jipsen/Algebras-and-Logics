# Hoops

## Definition
A ***hoop*** is a structure $\mathbf{A}=\langle A,\cdot,\rightarrow,1\rangle$ of type $\langle 2,2,0\rangle$ such that

$\langle A,\cdot ,1\rangle$ is a [commutative monoid](commutative_monoids.md)

$x\rightarrow ( y\rightarrow z) = (x\cdot y)\rightarrow z$

$x\rightarrow x=1$

$(x\rightarrow y)\cdot x = (y\rightarrow x)\cdot y$


Remark: 
This definition shows that hoops form a variety.

Hoops are partially ordered by the relation $x\leq y \iff
x\rightarrow y=1$.

The operation $x\wedge y = (x\rightarrow y)\cdot x$ is a meet with
respect to this order.


## Definition
A ***hoop*** is a structure $\mathbf{A}=\langle A,\cdot,\rightarrow,1\rangle$ of type $\langle 2,2,0\rangle$ such that

$x\cdot y = y\cdot x$

$x\cdot 1 = x$

$x\rightarrow ( y\rightarrow z) = (x\cdot y)\rightarrow z$

$x\rightarrow x=1$

$(x\rightarrow y)\cdot x = (y\rightarrow x)\cdot y$


## Definition
A ***hoop*** is a structure $\mathbf{A}=\langle A,\cdot,\rightarrow,1\rangle$ of type $\langle 2,2,0\rangle$ such that

$\langle A,\cdot ,1\rangle$ is a [commutative monoid](commutative_monoids.md)

and if $x\le y$ is defined by $x\rightarrow y = 1$ then

$\le$ is a partial order,

$\rightarrow$ is the residual of $\cdot$, i.e., $x\cdot y\le z \iff y\le x\rightarrow z$, and

$(x\rightarrow y)\cdot x = (y\rightarrow x)\cdot y$.


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be hoops. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\cdot y)=h(x)\cdot h(y)$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$, $h(1)=1$

## Examples
Example 1: 

## Basic results

Finite hoops are the same as [generalized BL-algebras](generalized_bl-algebras.md) (= divisible residuated lattices) since the join always exists in a finite meet-semilattice with top, and since all finite GBL-algebras are commutative and integral.

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong..md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &2\\
f(4)= &5\\
f(5)= &10\\
f(6)= &23\\
f(7)= &49\\
\end{array}$

## Subclasses
[Wajsberg hoops](wajsberg_hoops.md) 

[Idempotent hoops](idempotent_hoops.md) 

[Commutative generalized BL-algebras](commutative_generalized_bl-algebras.md) 

## Superclasses
[Pocrims](pocrims.md) 

[Generalized hoops](generalized_hoops.md) 


## References


)]
