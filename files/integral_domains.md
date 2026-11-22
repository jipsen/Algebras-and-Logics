# Integral Domain

Abbreviation: **IntDom**
## Definition
An ***integral domain*** is a [commutative rings with identity](commutative_rings_with_identity.md) $\mathbf{R}=\langle R,+,-,0,\cdot,1\rangle$ that 


has no zero divisors:  
$\forall x,y\ (x\cdot y=0\Longrightarrow x=0\ \text{or}\ y=0)$

### Morphisms
Let $\mathbf{R}$ and $\mathbf{S}$ be integral domains. A morphism from $\mathbf{R}$
to $\mathbf{S}$ is a function $h:R\rightarrow S$ that is a homomorphism: 

$h(x+y)=h(x)+h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(1)=1$

Remark: 
It follows that $h(0)=0$ and $h(-x)=-h(x)$.

## Examples
Example 1: $\langle\mathbb{Z},+,-,0,\cdot,1\rangle$, the ring of integers with addition, subtraction, zero, and multiplication is an integral domain.


## Basic results
Every finite integral domain is a [fields](fields.md).

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |Universal class |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  | |
|[Residual size](residual_size.md)  | |
|[Congruence distributive](congruence_distributive.md)  | |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
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
f(4)= &1\\
f(5)= &1\\
f(6)= &0\\
\end{array}$

## Subclasses
[Unique factorization domains](unique_factorization_domains.md) 

## Superclasses
[Commutative rings with identity](commutative_rings_with_identity.md) 


## References


)]