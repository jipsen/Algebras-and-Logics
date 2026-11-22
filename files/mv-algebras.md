# MV-algebras

Abbreviation: **MV**


## Definition
An ***MV-algebra*** (short for ***multivalued logic algebra***) is a
structure $\mathbf{A}=\langle A, +, 0, \neg\rangle$ such that

$\langle A, +, 0\rangle$ is a [commutative monoid](commutative_monoids.md)

$\neg \neg x=x$

$x+ \neg 0 = \neg 0$

$\neg(\neg x+y)+y = \neg(\neg y+x)+x$

Remark: This is the definition from [COM2000]


### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be MV-algebras. A morphism from $\mathbf{A}
$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x+y)=h(x)+h(y)$, $h(\neg x)=\neg h(x)$, $h(0)=0$


## Definition
An ***MV-algebra*** is a
structure $\mathbf{A}=\langle A, +, 0, \cdot, 1, \neg\rangle$ such that

$\langle A, \cdot, 1\rangle$ is a [commutative monoid](commutative_monoids.md)

$\neg$ is a DeMorgan involution for $+,\cdot$:  $\neg \neg x=x$, $x+y=\neg ( \neg x\cdot \neg y)$

$\neg 0=1$, $0\cdot x=0$, $\neg ( \neg x+y) +y=\neg ( \neg y+x) +x$


## Definition
An ***MV-algebra*** is a [basic logic algebra](basic_logic_algebras.md) $\mathbf{A}=\langle
A,\vee,0,\wedge,1,\cdot,\to\rangle$ that satisfies

MV:  $x\vee y=(x\to y)\to y$


## Definition
A ***Wajsberg algebra*** is an algebra $\mathbf{A}=\langle A, \to, \neg, 1\rangle$ such that

$1\to x=x$

$(x\to y)\to((y\to z)\to(x\to z) = 1$

$(x\to y)\to y = (y\to x)\to x$

$(\neg x\to\neg y)\to(y\to x)=1$

Remark: 
Wajsberg algebras are term-equivalent to MV-algebras via $x\to y=\neg x+y$, $1=\neg 0$ and $x+ y=\neg x\to y$, $0=\neg 1$.


## Definition
A ***bounded Wajsberg hoop*** is an algebra $\mathbf{A}=\langle A, \cdot, \to, 0, 1\rangle$ such that

$\langle A, \cdot, \to, 1\rangle$ is a [hoop](hoops.md)

$(x\to y)\to y = (y\to x)\to x$

$0\to x=1$

Remark: 
Bounded Wajsberg hoops are term-equivalent to Wajsberg algebras via $x\cdot y=\neg(x\to\neg y)$, $0=\neg 1$, and $\neg x=x\to 0$.
See [BP1994] for details.


## Definition
A ***lattice implication algebra*** is an algebra $\mathbf{A}=\langle A, \to, -, 1\rangle$ such that

$x\to (y\to z) = y\to (x\to z)$

$1\to x = x$

$x\to 1 = 1$

$x\to y = {-}y\to {-}x$

$(x\to y)\to y = (y\to x)\to x$

Remark: 
Lattice implication algebras are term-equivalent to MV-algebras via $x+ y = -x\to y$, $0= -1$, and $\neg x= - x$.

## Definition
A ***bounded commutative BCK-algebra*** is an algebra $\mathbf{A}=\langle A,\cdot, 0, 1\rangle$ such that

$\langle A,\cdot,0\rangle$ is a [commutative BCK-algebra](commutative_bck-algebras.md) and

$x\cdot 1 = 0$

Remark: 
Bounded commutative BCK-algebras are term-equivalent to MV-algebras via $\neg x=1\cdot x$, $x+ y = y\cdot \neg x$, and switching the role of $0$, $1$.

## Examples
Example 1: 


## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable |
|[Universal theory](universal_theory.md)  |decidable (FEP[BF2000])|
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence e-regular](congruence_e-regular.md)  |yes, $e=1$ |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |yes [Mu1987] |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |


## Finite members

^$n$       | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 |
^# of algs | 1 | 1 | 1 | 2 | 1 | 2 | 1 | 3 | 2 |  2 |  1 |  4 |  1 |  2 |  2 |  5 |  1 |  4 |  1 |  4 |  2 |  2 |  1 |  7 |  2 |
^# of si's | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |

The number of algebras with $n$ elements is given by the number of ways of factoring $n$ into a product with nontrivial factors,
see http://oeis.org/A001055

## Subclasses
[Boolean algebras](boolean_algebras.md) 


## Superclasses
[Generalized MV-algebras](generalized_mv-algebras.md) 

[Basic logic algebras](basic_logic_algebras.md) 

[Wajsberg hoops](wajsberg_hoops.md) 


## References


W. J. Blok, I. M. A. Ferreirim,
***On the structure of hoops***,
Algebra Universalis,
**43** 2000, 233--257


W. J. Blok, D. Pigozzi,
***On the structure of varieties with equationally definable principal congruences. III***,
Algebra Universalis,
**32** 1994, 545--608


Roberto L. O. Cignoli, Itala M. L. D'Ottaviano, Daniele Mundici,
***Algebraic foundations of many-valued reasoning***,
Trends in Logic---Studia Logica Library
**7** Kluwer Academic Publishers
2000, x+231


Daniele Mundici,
***Bounded commutative BCK-algebras have the amalgamation property***,
Math. Japon.,
**32** 1987, 279--282
