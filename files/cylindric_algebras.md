# Cylindric algebras

Abbreviation: **CA$_\alpha$**

## Definition
A ***cylindric algebra*** of dimension $\alpha$ is a [Boolean algebra with operators](boolean_algebra_with_operators.md) $\mathbf{A}=\langle A,
\vee, 0, \wedge, 1, -, c_i, d_{ij}: i,j<\alpha\rangle$ such that for all $i,j<\alpha$

the $c_i$ are increasing: $x\le c_i x$

the $c_i$ semi-distribute over $\wedge$: $c_i(x\wedge c_i y) = c_i x\wedge c_i y$

the $c_i$ commute: $c_ic_j x=c_jc_i x$

the diagonals $d_{ii}$ equal the top element:  $d_{ii}=1$

$d_{ij}=c_k(d_{ik}\wedge d_{kj})$ for $k\ne i,j$

$c_i(d_{ij}\wedge x)\wedge c_i(d_{ij}\wedge -x)=0$ for $i\ne j$

Remark: This is a template.
Click on the 'Edit text of this page' link at the bottom to add some information to this page.

It is not unusual to give several (equivalent) definitions. Ideally, one of the definitions would give an irredundant axiomatization that does not refer to other classes.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be ... . A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x ... y)=h(x) ... h(y)$

## Examples
Example 1: 

## Basic results


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |variety  |
|[Equational theory](equational_theory.md)                |undecidable for $\alpha\ge 3$, decidable otherwise |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   |no |
|[Residual size](residual_size.md)                    |unbounded |
|[Congruence distributive](congruence_distributive.md)          |yes |
|[Congruence modular](congruence_modular.md)               |yes |
|[Congruence n-permutable](congruence_n-permutable.md)        |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)               |yes |
|[Congruence uniform](congruence_uniform.md)               |yes |
|[Congruence extension property](congruence_extension_property.md)    |yes |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      | |
|[Amalgamation property](amalgamation_property.md)            | |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |

## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |

## Subclasses
  [Representable cylindric algebras](representable_cylindric_algebras.md) subvariety


## Superclasses
  [Diagonal free cylindric algebras](diagonal_free_cylindric_algebras.md) subreduct

  [Two-dimensional cylindric algebras](two-dimensional_cylindric_algebras.md) subreduct


## References


Roger Maddux, ***Introductory course on relation algebras, finite-dimensional cylindric algebras, and their interconnections***, Algebraic Logic (Proc. Conf. Budapest 1988) ed. by H. Andreka, J. D. Monk, and I. Nemeti, Colloq. Math. Soc. J. Bolyai 54 North-Holland Amsterdam, 1991, 361--392 
see also http://www.math.iastate.edu/maddux/papers/raca.ps




