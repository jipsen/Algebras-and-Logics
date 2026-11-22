# Sequential algebras

Abbreviation: **SeA**
## Definition
A ***sequential algebra*** is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,\circ,e,\triangleright,\triangleleft\rangle$ such that


$\langle A,\vee,0,
\wedge,1,\neg\rangle$ is a [Boolean algebra](boolean_algebras.md)


$\langle A,\circ,e\rangle$ is a [monoid](monoids.md)


$\triangleright$ is the ***right-conjugate*** of $\circ$:  
$(x\circ y)\wedge z=0 \iff (x\triangleright z)\wedge y=0$


$\triangleleft$ is the ***left-conjugate*** of $\circ$:  
$(x\circ y)\wedge z=0 \iff (z\triangleleft y)\wedge x=0$


$\triangleright,\triangleleft$ are ***balanced***:  
$x\triangleright e=e\triangleleft x$


$\circ$ is ***euclidean***:  
$x\cdot(y\triangleleft z)\leq (x\cdot y)\triangleleft z$


Remark: 

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be sequential algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a Boolean homomorphism and preserves $\circ$, $\triangleright$, $\triangleleft$, $e$:

$h(x\circ y)=h(x)\circ h(y)$, $h(x\triangleright y)=h(x)\triangleright h(y)$, $h(x\triangleleft y)=h(x)\triangleleft h(y)$, $h(e)=e$
## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |undecidable |
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
|[Definable principal congruences](definable_principal_congruences.md)  |yes |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |yes |
|[Discriminator variety](discriminator_variety.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |no |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |no |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |

## Subclasses
[Relation algebras](relation_algebras.md) 

[Representable sequential algebras](representable_sequential_algebras.md) 

## Superclasses
[Distributive residuated lattices](distributive_residuated_lattices.md) 

[Semiassociative sequential algebras](semiassociative_sequential_algebras.md) 


## References








