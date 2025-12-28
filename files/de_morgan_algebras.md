# De Morgan algebras

Abbreviation: **DeMA**
## Definition
A ***De Morgan algebra*** is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\neg\rangle$ such that


$\langle A,\vee ,0,\wedge ,1\rangle$ is a bounded distributive
lattice


$\neg$ is a De Morgan involution:  $\neg( x\wedge
y) =\neg x\vee \neg y$, $\neg\neg x=x$


Remark: 
It follows that $\neg ( x\vee y) =\neg x\wedge \neg y$, $\\neg 1=0$ and $\neg 0=1$ (e.g. $\neg 1=\neg 1\vee 0=\neg 1\vee\neg\neg 0=
\neg(1\wedge\neg 0)=\neg\neg 0=0$). Thus $\neg$ is a dual automorphism.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be De Morgan algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(\neg x)=\neg h(x)$
## Examples
Example 1: Let $\{0<a,b<1\}$ be the 4-element lattice with $a,b$ incomparable, and define $\neg$ by $\neg0=1,\neg a=a,\neg b=b$.
## Basic results

The algebra in Example 1 generates the variety of De Morgan algebras, see e.g. http://www.math.uic.edu/~kauffman/DeMorgan.pdf

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong..md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  | 4 |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &3\\
f(5)= &1\\
f(6)= &4\\
f(7)= &2\\
f(8)= &9\\
f(9)= &5\\
f(10)= &14\\
\end{array}$

## Subclasses
[Kleene logic algebras](kleene_logic_algebras.md) 

## Superclasses
[Ockham algebras](ockham_algebras.md) 


## References


)]
