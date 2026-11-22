# BCK-meet-semilattices

Abbreviation: **BCKJMlat**

## Definition
A ***BCK-meet-semilattice*** is a structure $\mathbf{A}=\langle A,\wedge,\rightarrow,1\rangle$ of type $\langle 2,2,0\rangle$ such that

(1):  $(x\rightarrow y)\rightarrow
((y\rightarrow z)\rightarrow (x\rightarrow z)) = 1$

(2):  $1\rightarrow x = x$

(3):  $x\rightarrow 1 = 1$

(4):  $(x\wedge y)\rightarrow y = 1$

(5):  $x\wedge((x\rightarrow y)\rightarrow y) = x$

$\wedge$ is idempotent:  $x\wedge x = x$

$\wedge$ is commutative:  $x\wedge y = y\wedge x$

$\wedge$ is associative:  $(x\wedge y)\wedge z = x\wedge (y\wedge z)$

Remark: 
$x\le y \iff x\rightarrow y=1$ is a partial order, with $1$ as greatest element, and $\wedge$ is a meet in this partial order. [Idziak1984]

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be BCK-meet-semilattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\wedge y)=h(x)\wedge h(y)$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$ and $h(1)=1$.

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
|[Locally finite](locally_finite.md)  | |
|[Residual size](residual_size.md)  | |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &\\
f(3)= &\\
f(4)= &\\
f(5)= &\\
f(6)= &\\
\end{array}$


## Subclasses
[BCK-lattices](bck-lattices.md) 

## Superclasses
[BCK-algebras](bck-algebras.md) 


## References


Pawel M. Idziak, ***Lattice operation in BCK-algebras***,
Math. Japon., **29**, 1984, 839--846
)]