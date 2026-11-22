# Lukasiewicz algebras of order n

Abbreviation: **LA$_n$**
## Definition
A ***Lukasiewicz algebra of order $n$*** is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\neg,\sigma_0,\ldots,\sigma_{n-1}\rangle$ such that


$\langle A,\vee ,0,\wedge ,1, \neg\rangle$ is a [De Morgan algebras](de_morgan_algebras.md)


1. 
$\sigma_i$ is a lattice homomorphism:  $\sigma_i(x\vee y)=\sigma_i(x)\vee\sigma_i(y)
\text{and} \sigma_i(x\wedge y)=\sigma_i(x)\wedge\sigma_i(y)$

2. 
$\sigma_i(x) \vee \neg(\sigma_i(x)) = 1$, $\sigma_i(x) \wedge \neg(\sigma_i(x)) = 0$

3. 
$\sigma_i(\sigma_j(x)) = \sigma_j(x)$ for $1\le j \le n-1$

4. 
$\sigma_i(\neg x) = \neg(\sigma_{n-i}(x))$

5. 
$\sigma_i(x) \wedge \sigma_j(x) = \sigma_i(x)$ for $i\le j \le n - 1$

6. 
$x\vee \sigma_{n-1}(x) = \sigma_{n-1}(x)$, $x\wedge \sigma_1(x) = \sigma_1(x)$

7. 
$y\wedge (x \vee \neg(\sigma_i(x)) \vee \sigma_{i+1}(y)) = y$ for $i\ne n - 1$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Lukasiewicz algebras of order $n$. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(\neg x)=\neg h(x)$, $h(\sigma_i(x))=\sigma_i(h(x))$ for $i=0,\ldots,n-1$

## Examples
Example 1: 

## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |Variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Congruence distributive](congruence_distributive.md)  |Yes |
|[Congruence modular](congruence_modular.md)  |Yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  |$n$ |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |

## Subclasses
[Boolean algebras](boolean_algebras.md) 

## Superclasses
[De Morgan algebras](de_morgan_algebras.md) 


## References


)]