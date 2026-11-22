# Lattice-ordered rings

Abbreviation: **LRng**
## Definition
A ***lattice-ordered ring*** (or $\ell$***-ring***) is a structure $\mathbf{L}=\langle L,\vee,\wedge,+,-,0,\cdot\rangle$ such that 


$\langle L,\vee,\wedge\rangle$ is a [lattice](lattices.md)


$\langle L,+,-,0,\cdot\rangle$ is a [ring](rings.md)


$+$ is order-preserving:  $x\leq y\Longrightarrow x+z\leq y+z$


${\uparrow}0$ is closed under $\cdot$:  $0\leq x,y\Longrightarrow 0\leq x\cdot y$


Remark: 

## Definition
### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be $\ell$-rings. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $f:L\rightarrow M$ that is a
homomorphism: $f(x\vee y)=f(x)\vee f(y)$, $f(x\wedge y)=f(x)\wedge f(y)$, $f(x\cdot y)=f(x)\cdot f(y)$, $f(x+y)=f(x)+f(y)$.
## Examples


## Basic results
The lattice reducts of lattice-ordered rings are [distributive lattices](distributive_lattices.md).

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Congruence distributive](congruence_distributive.md)  |yes, see [lattices](lattices.md) |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$, see [groups](groups.md) |
|[Congruence regular](congruence_regular.md)  |yes, see [groups](groups.md) |
|[Congruence uniform](congruence_uniform.md)  |yes, see [groups](groups.md) |

|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |

## Finite members

$\begin{array}{lr}
None
\end{array}$

## Subclasses
[Commutative lattice-ordered rings](commutative_lattice-ordered_rings.md) 

## Superclasses
[Abelian lattice-ordered groups](abelian_lattice-ordered_groups.md) 


## References


)]