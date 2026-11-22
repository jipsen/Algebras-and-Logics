# Basic logic algebras

Abbreviation: **BLA**

## Definition
A ***basic logic algebra*** or ***BL-algebra*** is a structure $\mathbf{A}=\langle A,\vee ,0,\wedge ,1,\cdot ,\to \rangle$ such that

$\langle A,\vee ,0,\wedge ,1\rangle$ is a 
[bounded lattice](bounded_lattices.md)

$\langle A,\cdot ,1\rangle$ is a [commutative monoid](commutative_monoids.md)

$\to$ gives the residual of $\cdot$:  $x\cdot y\leq z\Longleftrightarrow y\leq x\to z$

prelinearity:  $(x\to y) \vee ( y\to x) =1$

BL:  $x\cdot(x\to y)=x\wedge y$

Remark: 
The BL identity implies that the lattice is distributive.

## Definition
A ***basic logic algebra*** is a [FLe-algebra](fle-algebras.md) $\mathbf{A}=\langle
A,\vee ,0,\wedge ,1,\cdot ,\to \rangle$ such that

linearity:  $(x\to y) \vee ( y\to x) =1$

BL:  $x\cdot (x\to y)=x\wedge y$

Remark: 
The BL identity implies that the identity element $1$ is the top of the lattice.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be basic logic algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(1)=1$, $h(x\wedge
y)=h(x)\wedge h(y)$, $h(0)=0$, $h(x\cdot
y)=h(x)\cdot h(y)$, $h(x\to y)=h(x)\to h(y)$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence e-regular](congruence_e-regular.md)  |yes, $e=1$ |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
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
f(8)= &111\\
\end{array}$

The number of subdirectly irreducible BL-algebras of size $n$ is $2^{n-2}$.


## Subclasses
[MV-algebras](mv-algebras.md) 

[Heyting algebras](heyting_algebras.md) 


## Superclasses
[Generalized basic logic algebras](generalized_basic_logic_algebras.md) 

[FLew-algebras](flew-algebras.md) 


## References

