# Boolean modules over a relation algebra

Abbreviation: **BRMod**
## Definition
A ***Boolean module over a [relation algebra](relation_algebras.md)*** $\mathbf{R}$ is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,f_r\ (r\in R)\rangle$ such that

$\langle A,\vee,0,\wedge,1,\neg\rangle$ is a [Boolean algebra](boolean_algebras.md)

$f_r$ is ***join-preserving***: $f_r(x\vee y)=f_r(x)\vee f_r(y)$

$f_{r\vee s}(x)=f_r(x)\vee f_s(x)$

$f_r(f_s(x))=f_{r\circ s}(x)$

$f_{1'}$ is the identity map:  $f_{1'}(x)=x$

$f_0(x)=0$

$f_{r^\smile}(\neg (f_r(x)))\le \neg x$

Remark: Assuming that $f_r$ is order-preserving, the last identity is equivalent to the condition that $f_{r^\smile}$ and $f_r$ are conjugate operators. 
It follows that $f_r$ is ***normal***: $f_r(0)=0$.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Boolean modules over a realtion algebra. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a Boolean homomorphism and preserves all $f_r$:

$h(f_r(x))=f_r(h(x))$

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
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
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
[One-element algebras](one-element_algebras.md) 

## Superclasses
[Boolean algebras with operators](boolean_algebras_with_operators.md) 


## References









