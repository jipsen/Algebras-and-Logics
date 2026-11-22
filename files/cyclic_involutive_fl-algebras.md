# Cyclic involutive FL-algebras

Abbreviation: **CyInFL**

## Definition
A ***cyclic involutive FL-algebra*** or ***cyclic involutive residuated lattice*** is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee, \wedge\rangle$ is a [lattice](lattices.md)

$\langle A, \cdot, 1\rangle$ is a [monoid](monoids.md)

$\sim$ is an ***involution***: ${\sim}{\sim}x=x$ and

$xy\le z\iff x\le {\sim}(y({\sim}z))\iff y\le {\sim}(({\sim}z)x)$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be involutive residuated lattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$, $h(x \cdot y)=h(x) \cdot h(y)$, $h({\sim}x)={\sim}h(x)$ and $h(1)=1$. 

## Definition
An ***involutive FL-algebra*** is an [FL-algebra](fl-algebras.md) $\mathbf{A}=\langle A,\vee,\wedge,\cdot,1,\backslash,/,0\rangle$ such that

cyclic involution holds: $(0/x)\backslash 0=x=0/(x\backslash 0)$ and $0/x=x\backslash 0$

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
  f(3)= &2\\
  f(4)= &9\\
  f(5)= &21\\
\end{array}$     
$\begin{array}{lr}
  f(6)= &101\\
  f(7)= &279\\
  f(8)= &1433\\
  f(9)= &\\
  f(10)= &\\
\end{array}$


## Subclasses
[Cyclic integral involutive FL-algebras](cyclic_integral_involutive_fl-algebras.md) subvariety

## Superclasses
[involutive FL-algebras](involutive_fl-algebras.md) supervariety


## References


N. Galatos and P. Jipsen, ***Residuated frames with applications***, Transactions of the AMS, 365 (2013), 1219-1249 



