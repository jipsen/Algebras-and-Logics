# Action algebras

Abbreviation: **Act**
## Definition
An ***action algebra*** is a structure $\mathbf{A}=\langle A,\vee,\bot,\cdot,1,^*,\backslash,/\rangle$ of type 
$\langle 2,0,2,0,1,2,2\rangle$ such that


$\langle A,\vee,\bot,\cdot,1,^*\rangle$ is a [Kleene algebra](kleene_algebras.md)


$\backslash$ is the left residual of $\cdot$:  $y\leq x\backslash z\Longleftrightarrow xy\leq z$


$/$ is the right residual of $\cdot$:  $x\leq z/y\Longleftrightarrow xy\leq z$


Remark: These equivalences can be written equationally.


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be action algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 
$h(x\vee y)=h(x)\vee h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash y)=h(x)\backslash h(y)$,
$h(x/y)=h(x)/h(y)$, $h(x^* )=h(x)^*$, $h(\bot)=\bot$ and $h(1)=1$.

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety [Pratt1991] |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes [AltRaf2004] |
|[Congruence modular](congruence_modular.md)  |yes  |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=4$ [AltRaf2004] |
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
f(4)= &20\\
f(5)= &149\\
f(6)= &1488
\end{array}$


## Subclasses
[Action lattices](action_lattices.md) 

## Superclasses
[Kleene algebras](kleene_algebras.md) 

[Residuated join-semilattices](residuated_join-semilattices.md) 


## References


Vaughan Pratt, ***Action logic and pure induction***,
``Logics in AI (Amsterdam, 1990)'', Lecture Notes in Comput. Sci.,
478, 1991, 97--120, 92d:03016


C.J. van Alten and J.G. Raftery, ***Embedding Theorems and Rule Separation in Logics without Weakening***,
Studia Logica, 2004, ...--..., [preprint](preprints.md)

