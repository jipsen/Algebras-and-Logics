# Kleene logic algebras

Abbreviation: **KLA**
## Definition
A ***Kleene logic algebra*** is a [De Morgan algebra](de_morgan_algebras.md) $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\neg\rangle$ that satisfies


$x\wedge \neg x\le y\vee \neg y$.


Remark: Also called Kleene algebras, but this name more commonly refers to the algebraic models of regular languages.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Kleene logic algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(\neg x)=\neg h(x)$
## Examples
Example 1: Let $\{0<a<1\}$ be the 3-element lattice with $0'=1,a'=a,b'=b$.
## Basic results

The algebra in Example 1 generates the variety of Kleene logic algebras

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |Variety |
|[Equational theory](equational_theory.md)  |Decidable |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Congruence distributive](congruence_distributive.md)  |Yes |
|[Congruence modular](congruence_modular.md)  |Yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  |Yes |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
|[Locally finite](locally_finite.md)  |Yes |
|[Residual size](residual_size.md)  | 3 |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &1\\
f(6)= &3\\
f(7)= &2\\
f(8)= &6\\
f(9)= &4\\
f(10)= &10\\
\end{array}$

## Subclasses
[Boolean algebras](boolean_algebras.md) 

## Superclasses
[De Morgan algebras](de_morgan_algebras.md) 


## References


)]