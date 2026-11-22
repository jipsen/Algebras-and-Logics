
# Action lattices


Abbreviation: **ActLat**

## Definition
An ***action lattice*** is a structure $\mathbf{A}=\langle A,\vee,\wedge,0,\cdot,1,^*,\backslash ,/\rangle$ 
of type $\langle 2,2,0,2,0,1,2,2\rangle$ such that

$\langle A,\vee,0,\cdot,1,^*\rangle$ is a [Kleene algebra](kleene_algebras.md)

$\langle A,\vee,\wedge\rangle$ is a [lattice](lattices.md)

$\backslash$ is the left residual of $\cdot$:  $y\leq x\backslash z\Longleftrightarrow xy\leq z$

$/$ is the right residual of $\cdot$:  $x\leq z/y\Longleftrightarrow xy\leq z$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be action lattices. A morphism from $\mathbf{A}$ 
to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$,
$h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash
y)=h(x)\backslash h(y)$, $h(x/y)=h(x)/h(y)$, $h(x^*)=h(x)^*$, $h(0)=0$, $h(1)=1$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence e-regular](congruence_e-regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |

## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &3\\
f(4)= &20\\
f(5)= &149\\
f(6)= &1488\\
\end{array}$


## Subclasses
[Commutative action lattices](commutative_action_lattices.md) 


## Superclasses
[Action algebras](action_algebras.md) 

[Residuated lattices](residuated_lattices.md) 


## References


D. Kozen, ***On action algebras***, In J. van Eijck and A. Visser, editors,
***Logic and Information Flow***, MIT Press, 1994, 78--88 
see also http://www.cs.cornell.edu/kozen/papers/act.ps
)]