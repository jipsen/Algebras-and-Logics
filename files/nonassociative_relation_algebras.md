# Nonassociative relation algebras

Abbreviation: **NA**
## Definition
A ***nonassociative relation algebra*** is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,\circ,^{\smile},e\rangle$ such that


$\langle A,\vee,0,
\wedge,1,\neg\rangle$ is a [Boolean algebra](boolean_algebras.md)


$e$ is an ***identity*** for $\circ$:  $x\circ e=x$, $e\circ x=x$


$\circ$ is ***join-preserving***:  
$(x\vee y)\circ z=(x\circ z)\vee (y\circ z)$


$^{\smile}$ is an ***involution***:  
${x^\smile}^\smile=x$, $(x\circ y)^{\smile} z=y^{\smile}\circ x^{\smile}$


$^{\smile}$ is ***join-preserving***:  
$(x\vee y)^{\smile} z=x^{\smile}\vee y^{\smile}$


$\circ$ is residuated:  $x^{\smile}\circ(\neg (x\circ y))\le\neg y$


Remark: 

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be relation algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a Boolean homomorphism and preserves $\circ$, $^{\smile}$, $e$:

$h(x\circ y)=h(x)\circ h(y)$, $h(x^{\smile})=h(x)^{\smile}$, $h(e)=e$
## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Discriminator variety](discriminator_variety.md)  |no |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &\\
f(3)= &\\
f(4)= &\\
f(5)= &\\
f(6)= &\\
\end{array}$

## Subclasses
[Weakly associative relation algebras](weakly_associative_relation_algebras.md) 

## Superclasses
[Nonassociative sequential algebras](nonassociative_sequential_algebras.md) 


## References

R. Maddux: Some varieties containing relation algebras. Trans. Amer. Math. Soc., 272 (1982), pp. 501-526. https://www.jstor.org/stable/pdf/1998710.pdf









