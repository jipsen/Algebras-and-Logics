# Pseudo MV-algebras

Abbreviation: **psMV**


## Definition
A ***pseudo MV-algebra***[GI2001] (or ***psMV-algebra*** for short) is a
structure $\mathbf{A}=\langle A, \oplus, ^-, ^\sim, 0, 1\rangle$ such that

$(x\oplus y)\oplus z = x\oplus(y\oplus z)$

$x\oplus 0 = x$

$x\oplus 1 = 1$

$(x^-\oplus y^-)^\sim = (x^\sim\oplus y^\sim)^-$

$(x\oplus y^\sim)^-\oplus x = y\oplus (x^-\oplus y)^\sim$

$x\oplus (y^-\oplus x)^\sim = y\oplus (x^-\oplus y)^\sim$

$x^{-\sim}=x$

$0^- = 1$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be pseudo MV-algebras. A morphism from $\mathbf{A}
$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x\oplus y)=h(x)\oplus h(y)$, $h(x^-)=h(x)^-$, $h(0)=0$ ($h(x^\sim)=h(x)^\sim$ and $h(1)=1$ follow from these).


## Examples


## Basic results
$0+x=x$, $1+x=1$, $x^{\sim-}=x$, $0^\sim=1$ and axiom A7 in[GI2001] follow from the above axioms.

Pseudo MV-algebras are term-equivalent to divisible [involutive residuated lattices](involutive_residuated_lattices.md).

Every psMV-algebra is obtained from an interval in a [lattice-ordered group](lattice-ordered_groups.md)[Dvu2002].

Every finite psMV-algebra is commutative.

Every commutative psMV-algebra is an [MV-algebra](mv-algebras.md).

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
|[Congruence n-permutable](congruence_n-permutable.md)  |yes |
|[Congruence e-regular](congruence_e-regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  |  |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |


## Finite members

^$n$       | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 |
^# of algs | 1 | 1 | 1 | 2 | 1 | 2 | 1 | 3 | 2 |  2 |  1 |  4 |  1 |  2 |  2 |  5 |  1 |  4 |  1 |  4 |  2 |  2 |  1 |  7 |  2 |
^# of si's | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |

## Subclasses
[MV-algebras](mv-algebras.md) 


## Superclasses

[Involutive residuated lattices](involutive_residuated_lattices.md)

## References


S. Georgescu and A. Iorgulescu, 
***Pseudo-MV algebras***, 
Multiple Valued Logic, **6**, 2001, 95--135


A. Dvurecenskij,
***Pseudo MV-algebras are intervals in $\ell$-groups***, Journal of the Australian Mathematical Soc.
Ser. 72, (2002), 427-–445)]