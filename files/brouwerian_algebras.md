# Brouwerian algebras

Abbreviation: **BrA**

## Definition
A ***Brouwerian algebra*** is a structure $\mathbf{A}=\langle A, \vee, \wedge, 1, \rightarrow\rangle$ such that


$\langle A, \vee, \wedge, 1\rangle$ is a distributive lattice
with top


$\rightarrow$ gives the residual of $\wedge$:  $x\wedge y\leq z\Longleftrightarrow y\leq x\rightarrow z$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Brouwerian algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(1)=1$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$

## Definition
A ***Brouwerian algebra*** is a BL-algebra $\mathbf{A}=\langle A, \vee, \wedge, 1, \cdot, \rightarrow\rangle$ such that

$x\wedge y=x\cdot y$

## Examples
Example 1: 

## Basic results


## Properties
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence e-regular](congruence_e-regular.md)  |yes, $e=1$ |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |yes |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |yes |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &3\\
f(6)= &5\\
f(7)= &8\\
f(8)= &15\\
f(9)= &26\\
f(10)= &47\\
f(11)= &82\\
f(12)= &151\\
f(13)= &269\\
f(14)= &494\\
f(15)= &891\\
f(16)= &1639\\
f(17)= &2978\\
f(18)= &5483\\
f(19)= &10006\\
f(20)= &18428\\
Values known up to size 49 [Erne, Heitzig, Reinhold (2002
\end{array}$


## Subclasses
[Generalized Boolean algebras](generalized_boolean_algebras.md) 

[Heyting algebras](heyting_algebras.md) 


## Superclasses
[Distributive lattices](distributive_lattices.md) 

[Basic logic algebras](basic_logic_algebras.md) 


## References


)]