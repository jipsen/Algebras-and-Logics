# Kleene lattices

Abbreviation: **KLat**


## Definition
A ***Kleene lattice*** is a structure $\mathbf{A}=\langle A,\vee
,\wedge ,0,\cdot ,1,^{\ast }\rangle$ of type $\langle
2,2,0,2,0,1\rangle$ such that


$\langle A,\vee ,0,\cdot ,1,^{\ast }\rangle$ is a Kleene algebra


$\langle A,\vee ,\wedge \rangle$ is a lattice


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Kleene lattices. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)\ 
\text{and}  h(x\cdot y)=h(x)\cdot h(y)$, $h(x^{\ast
})=h(x)^{\ast }$, $h(0)=0$, $h(1)=1$


## Examples
Example 1: 


## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |Quasivariety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  |Undecidable |
|[First-order theory](first-order_theory.md)  |Undecidable |
|[Locally finite](locally_finite.md)  |No |
|[Residual size](residual_size.md)  |Unbounded |
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


## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &3\\
f(4)= &16\\
f(5)= &149\\
f(6)= &1488\\
\end{array}$


## Subclasses
[Action lattices](action_lattices.md) 


## Superclasses
[Kleene algebras](kleene_algebras.md) 

[Multiplicative lattices](multiplicative_lattices.md) 


## References
