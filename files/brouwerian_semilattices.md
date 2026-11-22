# Brouwerian semilattices

Abbreviation: **BrSlat**

## Definition
A ***Brouwerian semilattice*** is a structure $\mathbf{A}=\langle A, \wedge, 1, \rightarrow\rangle$ such that

$\langle A, \wedge, 1\rangle$ is a [semilattice with identity](semilattice_with_identitys.md)

$\rightarrow$ gives the residual of $\wedge$:  $x\wedge y\leq z\Longleftrightarrow y\leq x\rightarrow z$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Brouwerian semilattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\wedge y)=h(x)\wedge h(y)$, $h(1)=1$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$

## Definition
A ***Brouwerian semilattice*** is a [hoop](hoops.md) $\mathbf{A}=\langle A, \cdot, 1, \rightarrow\rangle$ such that

$\cdot$ is idempotent:  $x\cdot x=x$

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
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence e-regular](congruence_e-regular.md)  |yes, $e=1$ |
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
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &3\\
f(6)= &5\\
f(7)= &8\\
f(8)= &15\\
f(9)= &26\\
f(10)= &47\\
f(11)= &82\\
f(12)= &151\\
f(13)= &269\\
f(14)= &494\\
f(15)= &891\\
f(16)= &1639\\
f(17)= &2978\\
f(18)= &5483\\
f(19)= &10006\\
f(20)= &18428\\
\end{array}$

Values known up to size 49 [ErneHeitzigReinhold2002]


## Subclasses
[Brouwerian algebras](brouwerian_algebras.md) 


## Superclasses
[Semilattices with identity](semilattices_with_identity.md) 

[Hoops](hoops.md) 


## References


M. Ern\'e, J. Heitzig, J. Reinhold,
***On the number of distributive lattices***, 
Electronic J. Combinatorics 9 (2002), no. 1, Research Paper 24, 23 pp.
)]