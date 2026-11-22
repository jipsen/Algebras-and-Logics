# Relation algebras

Abbreviation: **RA**
## Definition
A ***relation algebra*** is a algebra $\mathbf{A}=\langle A,\vee,0,\wedge,1,\neg,\circ,^{\smile},e\rangle$ such that

$\langle A,\vee,0,\wedge,1,\neg\rangle$ is a [Boolean algebra](boolean_algebras.md)

$\langle A,\circ,e\rangle$ is a [monoid](monoids.md)

$\circ$ is ***join-preserving***: $(x\vee y)\circ z=(x\circ z)\vee (y\circ z)$

$^{\smile}$ is an ***involution***: $x^{\smile\smile}=x$, $(x\circ y)^{\smile}=y^{\smile}\circ x^{\smile}$

$^{\smile}$ is ***join-preserving***: $(x\vee y)^{\smile}=x^{\smile}\vee y^{\smile}$

$\circ$ is residuated: $x^{\smile}\circ(\neg (x\circ y))\le\neg y$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be relation algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a Boolean homomorphism and preserves $\circ$, $^{\smile}$, $e$:

$h(x\circ y)=h(x)\circ h(y)$, $h(x^{\smile})=h(x)^{\smile}$, $h(e)=e$

## Examples
Example 1: $\langle \mathcal P(U^2), \cup, \emptyset, \cap, U^2, -, \circ, ^\smile, id_U \rangle$ the full relation algebra of binary relations on a set $U$.

Example 2: $\langle \mathcal P(G), \cup, \emptyset, \cap, G, -, \circ, ^\smile, \{e\} \rangle$ the group relation algebra of a [group](groups.md) $\langle G, *, ^{-1}, e \rangle$, where $X\circ Y=\{x*y : x\in X, y\in Y\}$ and $X^\smile=\{x^{-1} : x\in X\}$.

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
|[Discriminator variety](discriminator_variety.md)  |yes |
|[Amalgamation property](amalgamation_property.md)  |no |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |no |


## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 0 |
| 4 | 3 |
| 5 | 0 |
| 6 | 0 |

[Small relation algebras](https://www1.chapman.edu/~jipsen/gap/ramaddux.html)

## Subclasses
[n-dimensional relation algebras](n-dimensional_relation_algebras.md) 

[Representable relation algebras](representable_relation_algebras.md) 

[Commutative relation algebras](commutative_relation_algebras.md) 

[Square-increasing relation algebras](square-increasing_relation_algebras.md) 


## Superclasses
[Sequential algebras](sequential_algebras.md) 

[Semiassociative relation algebras](semiassociative_relation_algebras.md) 


## References
B. Jónsson: Varieties of relation algebras. Algebra Universalis, 15, 273–298 (1982). https://doi.org/10.1007/BF02483728