# Commutative idempotent involutive FL-algebras

Abbreviation: **CIdInFL**

## Definition
A ***commutative idempotent involutive FL-algebra*** or ***commutative idempotent involutive residuated lattice*** is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee, \wedge\rangle$ is a [lattice](lattices.md)

$\langle A, \cdot, 1\rangle$ is a [semilattice](semilattices.md) with top

$\sim$ is an ***involution***: ${\sim}{\sim}x=x$ and

$xy\le z\iff x\le {\sim}(y({\sim}z))$

## Definition
A ***commutative involutive FL-algebra*** or ***commutative involutive residuated lattice*** is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee\rangle$ is a [semilattice](semilattices.md)

$\langle A, \cdot\rangle$ is a [semilattice](semilattices.md) and

$x\le z\iff x\cdot{\sim}y\le{\sim}1$, where $x\le y\iff x\vee y=y$.

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

$\begin{array}{lr}
  f(1)= &1\\
  f(2)= &1\\
  f(3)= &1\\
  f(4)= &2\\
  f(5)= &2\\
  f(6)= &4\\
  f(7)= &4\\
  f(8)= &9\\
  f(9)= &10\\
  f(10)= &21\\
  f(11)= &22\\
  f(12)= &49\\
  f(13)= &52\\
  f(14)= &114\\
  f(15)= &121\\
  f(16)= &270\\
\end{array}$


## Subclasses
[Sugihara algebras](sugihara_algebras.md) subvariety

## Superclasses
[Commutative involutive FL-algebras](commutative_involutive_fl-algebras.md) supervariety


## References

[GalatosJipsen2012> N. Galatos and P. Jipsen, ***Residuated frames with applications***, Transactions of the AMS, 365 (2013), 1219-1249 ]


