# Modal algebras

Abbreviation: **MA**

## Definition
A ***modal algebra*** is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,\diamond\rangle$ such that


$\langle A,\vee,0,
\wedge,1,\neg\rangle$ is a [Boolean algebra](boolean_algebras.md)


$\diamond$ is ***join-preserving***:  
$\diamond(x\vee y)=\diamond x\vee \diamond y$


$\diamond$ is ***normal***:  
$\diamond 0=0$

Remark: 
Modal algebras provide algebraic models for modal logic. The operator $\diamond$ is the
***possibility operator***, and the ***necessity operator*** $\Box$ is defined as $\Box x=\neg\diamond\neg x$.


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be modal algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a Boolean homomorphism and preserves $\diamond$:

$h(\diamond x)=\diamond h(x)$
## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
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
|[Discriminator variety](discriminator_variety.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |

## Subclasses
[Closure algebras](closure_algebras.md) 

## Superclasses
[Boolean algebras with operators](boolean_algebras_with_operators.md) 


## References








