# Generalized MV-algebras

Abbreviation: **GMV**

## Definition
A ***generalized MV-algebra*** is a [residuated lattices](residuated_lattices.md) 
$\mathbf{L}=\langle L,\vee, \wedge, \cdot, e, \backslash, /\rangle$ such that

$x\vee y=x/(y\backslash x\wedge e)$, $x\vee y=(x/y\wedge e)\backslash y$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be generalized MV-algebras. A
morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$
that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, 
$h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash
y)=h(x)\backslash h(y)$, $h(x/y)=h(x)/h(y)$, $h(e)=e$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable [http://www.chapman.edu/~jipsen/lgroups/GMVDecisionProc.html implementation] |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence e-regular](congruence_e-regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |no |
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
f(3)= &\\
f(4)= &\\
f(5)= &\\
f(6)= &\\
\end{array}$

## Subclasses

[Commutative generalized MV-algebras](commutative_generalized_mv-algebras.md) 

[Integral generalized MV-algebras](integral_generalized_mv-algebras.md) 

[MV-algebras](mv-algebras.md) 


## Superclasses
[Generalized BL-algebras](generalized_bl-algebras.md) 


## References


)]