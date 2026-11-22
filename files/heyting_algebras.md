# Heyting algebras

Abbreviation: **HA**


## Definition
A ***Heyting algebra*** is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\to \rangle$ such that


$\langle A,\vee ,0,\wedge ,1\rangle$ is a bounded distributive
lattice


$\to$ gives the residual of $\wedge$:  $x\wedge y\leq z\Longleftrightarrow y\leq x\to z$

## Definition
A ***Heyting algebra*** is a FLew-algebra $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\cdot ,\to \rangle$ such that


$x\wedge y=x\cdot y$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Heyting algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(0)=0$, 
$h(x\wedge y)=h(x)\wedge h(y)$, $h(1)=1$, 
$h(x\to y)=h(x)\to h(y)$

## Examples
Example 1: The open sets of any [topological space](topological_spaces.md) $\mathbf X$ form a Heyting algebra under the operations of union $\cup$, 
empty set $\emptyset$, intersection $\cap$, whole space $X$, and the operation $U\to V=$ interior of $(X - U)\cup V$.

Example 2: Any [frame](frames.md) can be expanded to a unique Heyting algebra by defining $x\to y = \bigvee\{z:x\wedge z\le y\}$.

## Basic results
Any finite distributive lattice is the reduct of a unique Heyting algebra. More generally the same result holds for any complete and completely distributive lattice.

A Heyting algebra is subdirectly irreducible if and only if it has a unique coatom.

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
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

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 1 |
| 4 | 2 |
| 5 | 3 |
| 6 | 5 |
| 7 | 8 |
| 8 | 15 |
| 9 | 26 |
| 10 | 47 |
| 11 | 82 |
| 12 | 151 |
| 13 | 269 |
| 14 | 494 |
| 15 | 891 |
| 16 | 1639 |
| 17 | 2978 |
| 18 | 5483 |
| 19 | 10006 |
| 20 | 18428 |

Values known up to size 49  Marcel Ern\'e;, Jobst Heitzig and J\"urgen Reinhold,***On the number of distributive lattices***,
Electron. J. Combin.,
**9**2002,Research Paper 24, 23 pp. (electronic)

## Subclasses
[Goedel algebras](goedel_algebras.md) 

## Superclasses
[Bounded distributive lattices](bounded_distributive_lattices.md) 


## References


)]