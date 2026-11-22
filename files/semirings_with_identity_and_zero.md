# Semirings with identity and zero

Abbreviation: **SRng**$_{01}$

## Definition
A ***semiring with identity and zero*** is a structure $\mathbf{S}=\langle S,+,0,\cdot,1
\rangle$ of type $\langle 2,0,2,0\rangle$ such that


$\langle S,+,0\rangle$ is a [commutative monoids](commutative_monoids.md)


$\langle S,\cdot,1\rangle$ is a [monoids](monoids.md)


$0$ is a zero for $\cdot$:  $0\cdot x=0$, $x\cdot 0=0$


$\cdot$ distributes over $+$:  $x\cdot(y+z)=x\cdot y+x\cdot z$, $(y+z)\cdot x=y\cdot x+z\cdot x$

### Morphisms
Let $\mathbf{S}$ and $\mathbf{T}$ be semirings with identity and zero. A morphism from $\mathbf{S}$
to $\mathbf{T}$ is a function $h:S\rightarrow T$ that is a homomorphism: 

$h(x+y)=h(x)+h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(0)=0$, $h(1)=1$

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
|[Congruence distributive](congruence_distributive.md)  |no |
|[Congruence modular](congruence_modular.md)  |no |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
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
f(1)= &   1\\
f(2)= &   2\\
f(3)= &   6\\
f(4)= &  40\\
f(5)= & 295\\
f(6)= &3246\\
\end{array}$

## Subclasses
[Idempotent semirings with identity and zero](idempotent_semirings_with_identity_and_zero.md) 

[Rings with identity](rings_with_identity.md) 

## Superclasses
[Semirings with zero](semirings_with_zero.md) 

[Semirings with identity](semirings_with_identity.md) 


## References


)]