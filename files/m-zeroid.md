# m-zeroids

Abbreviation: **MZrd**


## Definition
An ***m-zeroid*** is a
algebra $\mathbf{A}=\langle A, \wedge, \vee, +, 0, -\rangle$ such that

$\langle A, +\rangle$ is a [commutative semigroup](commutative_semigroups.md)

$\langle A, \wedge, \vee\rangle$ is a [lattice](lattices.md)

$-x=x$

$x+ 0 = 0$

$x+ -x = 0$

$x\le y\iff 0=-x+y$

$x+ (y\vee z) = (x+y)\vee(x+z)$


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be MV-algebras. A morphism from $\mathbf{A}
$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x+y)=h(x)+h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x\vee y)=h(x)\vee h(y)$, $h(-x)=-h(x)$, $h(0)=0$

## Examples
Example 1: 


## Basic results

All subdirectly irreducible algebras are linearly ordered. 

The lattice is always bounded, with top element $0$. 

The bottom element $-0$ is the identity of $+$.

The dual operation $x\cdot y=-(-y+-x)$ is the fusion of a commutative integral involutive semilinear residuated lattice. In fact, m-zeroids are precisely the duals of these residuated lattices, which are also known as involutive IMTL algebras.

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Universal theory](universal_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence e-regular](congruence_e-regular.md)  |yes, $e=1$ |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |


## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members | subdirectly irreducible |
|--:|--:|--:|
| 1 | 1 | 0 |
| 2 | 1 | 1 |
| 3 | 1 | 1 |
| 4 | 3 | 2 |
| 5 | 3 | 3 |
| 6 | 8 | 7 |
| 7 | 12 | 12 |
| 8 | 35 | 31 |
| 9 | 61 | 59 |
| 10 | 167 | 161 |
| 11 |  | 329 |
| 12 |  | 944 |
| 13 |  | 2067 |
| 14 |  | 6148 |
| 15 |  | 14558 |
| 16 |  | 44483 |
| 17 |  | 116372 |

see [OEIS A030453](https://oeis.org/A030453)

## Subclasses
TBD 


## Superclasses
TBD 


## References

J. B. Palmatier and F. Guzman,
***M-zeroids structure and categorical equivalence***,
Studia Logica,
**100**(5) 2012, 975--1000