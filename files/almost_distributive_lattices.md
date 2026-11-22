# Almost distributive lattices

Abbreviation: **ADLat**

## Definition
An ***almost distributive lattice*** is a [neardistributive lattice](neardistributive_lattices.md) $\mathbf{L}=\langle L,\vee,\wedge\rangle$ such that

AD$_{\wedge}$:  $v\wedge[u\vee (x\wedge[y\vee (x\wedge z)])]\le u\vee [x\wedge[y\vee (x\wedge z])\wedge(v\vee (x\wedge y)\vee (x\wedge z))]$

AD$_{\vee}$:  $v\vee[u\wedge (x\vee[y\wedge (x\vee z)])]\ge u\wedge [x\vee[y\wedge (x\vee z])\vee(v\wedge (x\vee y)\wedge (x\vee z))]$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be almost distributive lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function 
$h:L\rightarrow M$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$

## Examples
Example 1: $D[d]=\langle D\cup\{d'\},\vee ,\wedge\rangle$, where $D$ is any distributive lattice and $d$ is an element in it that
is split into two elements $d,d'$ using Alan Day's doubling construction.


## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  |no |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |

## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &4\\
f(6)= &\\
f(7)= &\\
\end{array}$


## Subclasses
[Distributive lattices](distributive_lattices.md) 


## Superclasses
[Neardistributive lattices](neardistributive_lattices.md) 


## References


)]