# Bounded distributive lattices

Abbreviation: **BDLat**

## Definition
A ***bounded distributive lattice*** is a structure $\mathbf{L}=\langle L,\vee ,0,\wedge ,1\rangle$ such that

$\langle L,\vee ,\wedge \rangle$ is a 
[distributive lattice](distributive_lattices.md)

$0$ is the least element:  $0\leq x$

$1$ is the greatest element:  $x\leq 1$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be bounded distributive lattices. A morphism from 
$\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\to M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(0)=0$, $h(1)=1$

## Examples
Example 1: $\langle \mathcal P(S), \cup, \emptyset, \cap, S\rangle$, the collection
of subsets of a set $S$, with union, empty set, intersection, and the whole
set $S$.



## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |no |
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  |2 |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &3\\
\end{array}$     
$\begin{array}{lr}
f(6)= &5\\
f(7)= &8\\
f(8)= &15\\
f(9)= &26\\
f(10)= &47\\
\end{array}$     
$\begin{array}{lr}
f(11)= &82\\
f(12)= &151\\
f(13)= &269\\
f(14)= &494\\
f(15)= &891\\
\end{array}$     
$\begin{array}{lr}
f(16)= &1639\\
f(17)= &2978\\
f(18)= &5483\\
f(19)= &10006\\
f(20)= &18428\\
\end{array}$

Values known up to size 49 [EHR2002].

## Subclasses
[Boolean algebras](boolean_algebras.md) 

[Complete distributive lattices](complete_distributive_lattices.md) 

## Superclasses
[Distributive lattices](distributive_lattices.md) 

[Bounded modular lattices](bounded_modular_lattices.md) 


## References


Marcel Erne, Jobst Heitzig and J\"urgen Reinhold, ***On the number of distributive lattices***, Electron. J. Combin.,
**9**, 2002, Research Paper 24, 23 pp. (electronic)
)]