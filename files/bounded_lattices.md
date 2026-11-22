# Bounded lattices

Abbreviation: **BLat**

## Definition
A ***bounded lattice*** is a structure $\mathbf{L}=\langle L,\vee,0,\wedge,1\rangle$ such that

$\langle L,\vee,\wedge\rangle$ is a [lattice](lattices.md)

$0$ is the least element:  $0\leq x$

$1$ is the greatest element:  $x\leq 1$
### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be bounded lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(0)=0$, $h(1)=1$

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
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |

## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &5\\
\end{array}$     
$\begin{array}{lr}
f(6)= &15\\
f(7)= &53\\
f(8)= &222\\
f(9)= &1078\\
f(10)= &5994\\
\end{array}$     
$\begin{array}{lr}
f(11)= &37622\\
f(12)= &262776\\
f(13)= &2018305\\
f(14)= &16873364\\
f(15)= &152233518\\
\end{array}$     
$\begin{array}{lr}
f(16)= &1471613387\\
f(17)= &15150569446\\
f(18)= &165269824761\\
f(19)= &\\
f(20)= &\\
\end{array}$

[HeiRei2002]


## Subclasses
[Bounded modular lattices](bounded_modular_lattices.md) 

[Complete lattices](complete_lattices.md) 


## Superclasses
[Lattices](lattices.md) 


## References


Jobst Heitzig and J\"urgen Reinhold, ***Counting finite lattices***,
Algebra Universalis,
**48**, 2002, 43--53

