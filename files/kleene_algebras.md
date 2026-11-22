# Kleene algebras

Abbreviation: **KA**
## Definition
A ***Kleene algebra*** is a structure $\mathbf{A}=\langle A,\vee
,0,\cdot ,1,^{\ast }\rangle$ of type $\langle
2,0,2,0,1\rangle$ such that
$\langle A,\vee ,0,\cdot ,1\rangle$ is an [idempotent semiring with identity and zero](idempotent_semirings_with_identity_and_zero.md)

$e\vee x\vee x^{\ast }x^{\ast }=x^{\ast }$

$xy\leq y\Longrightarrow x^{\ast }y=y$

$yx\leq y\Longrightarrow yx^{\ast }=y$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Kleene algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a
homomorphism: $h(x\vee y)=h(x)\vee h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x^{\ast })=h(x)^{\ast }$, $h(0)=0$,
and $h(1)=1$.

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |quasivariety |
|[Equational theory](equational_theory.md)  |decidable, PSPACE complete [StoMey1973] |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |no |
|[Congruence modular](congruence_modular.md)  |no |
|[Congruence meet-semidistributive](congruence_meet-semidistributive.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |


## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 3 |
| 4 | 20 |
| 5 | 149 |
| 6 | 1488 |

## Subclasses
[Action algebras](action_algebras.md) 

[Kleene lattices](kleene_lattices.md) 


## Superclasses
[Idempotent semirings with identity and zero](idempotent_semirings_with_identity_and_zero.md) 

## References


L. J. Stockmeyer, A. R. Meyer, ***Word problems requiring exponential time: preliminary report***,
Fifth Annual ACM Symposium on Theory of Computing (Austin, Tex., 1973),
Assoc. Comput. Mach., New York, 1973, 1--9 ZMATH
)]