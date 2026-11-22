# Boolean algebras with operators

Abbreviation: **BAO**

## Definition
A ***Boolean algebra with operators*** is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,f_i\ (i\in I)\rangle$ such that

$\langle A,\vee,0,\wedge,1,\neg\rangle$ is a Boolean algebra

$f_i$ is ***join-preserving*** in each argument:  
$f_i(\ldots,x\vee y,\ldots)=f_i(\ldots,x,\ldots)\vee f_i(\ldots,y,\ldots)$


$f_i$ is ***normal*** in each argument:  $f_i(\ldots,0,\ldots)=0$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Boolean algebras with operators of the same signature. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a Boolean homomorphism and preserves all the operators:

$h(f_i(x_0,\ldots,x_{n-1}))=f_i(h(x_0),\ldots,h(x_{n-1}))$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  |undecidable |
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
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |


## Subclasses
[Modal algebras](modal_algebras.md) 

[Boolean monoids](boolean_monoids.md) 


## Superclasses
[Boolean algebras](boolean_algebras.md) 


## References







