# Pocrims

Abbreviation: **Pocrim**

## Definition
A ***pocrim*** (short for ***partially ordered commutative residuated integral monoid***) is a structure $\mathbf{A}=\langle A,\oplus,\ominus,0\rangle$ of type $\langle 2,2,0\rangle$ such that

(1):  $((x \ominus y) \ominus (x \ominus z)) \ominus (z \ominus y) = 0$

(2):  $x\ominus 0 = x$

(3):  $0\ominus x = 0$

(4):  $(x \ominus y) \ominus z = x \ominus (z \oplus y)$

(5):  $x\ominus y = y \ominus x = 0 \Longrightarrow x=y$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be pocrims. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \oplus y)=h(x) \oplus h(y)$,
$h(x \ominus y)=h(x) \ominus h(y)$,
$h(0)=0$.

## Definition
A ***pocrim*** is a structure $\mathbf{A}=\langle A,\oplus,\ominus,0\rangle$ such that

$\langle A,\ominus,0\rangle$ is a [BCK-algebra](bck-algebras.md)

$(x \ominus y) \ominus z = x \ominus (z \oplus y)$

## Examples
Example 1: 

## Basic results


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |quasivariety [Higgs1984]  |
|[Equational theory](equational_theory.md)                | |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   | |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          | |
|[Congruence modular](congruence_modular.md)               | |
|[Congruence n-permutable](congruence_n-permutable.md)        | |
|[Congruence regular](congruence_regular.md)               | |
|[Congruence uniform](congruence_uniform.md)               | |
|[Congruence extension property](congruence_extension_property.md)    | |
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
| 2 | 1 |
| 3 | 2 |
| 4 | 7 |
| 5 | 26 |
| 6 | 129 |

1,1,2,7,26,129

## Subclasses
[Hoops](hoops.md)


## Superclasses
[Polrims](polrims.md)

[Commutative residuated partially ordered monoids](commutative_residuated_partially_ordered_monoids.md)

[BCK-algebras](bck-algebras.md) reduced type


## References


D. Higgs, ***Dually residuated commutative monoids with identity element as least element do not form an equational class***, Math. Japon., 
**29**, 1984, no. 1, 69--75 



