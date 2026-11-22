# Lattices

Abbreviation: **Lat**


## Definition
A ***lattice*** is a structure $\mathbf{L}=\langle L,\vee ,\wedge
\rangle$, where $\vee$ and $\wedge$ are infix binary operations
called the ***join*** and ***meet***, such that

$\vee ,\wedge$ are associative:  $(x\vee y)\vee z=x\vee (y\vee z)$, $(x\wedge y)\wedge z=x\wedge (y\wedge z)$

$\vee ,\wedge$ are commutative:  $x\vee y=y\vee x$, $x\wedge y=y\wedge x$

$\vee ,\wedge$ are absorbtive:  $(x\vee y)\wedge x=x$, $(x\wedge y)\vee x=x$.

Remark: 
It follows that $\vee$ and $\wedge$ are idempotent: $x\vee x=x$, $x\wedge x=x$.

This definition shows that lattices form a variety.

A partial order $\leq$ is definable in any lattice by 
$x\leq y\Longleftrightarrow x\wedge y=x$, or equivalently by 
$x\leq y\Longleftrightarrow x\vee y=y$.

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be lattices. A morphism from $\mathbf{L}$
to $\mathbf{M}$ is a function $h:L\to M$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$


## Definition
A ***lattice*** is a structure $\mathbf{L}=\langle L,\vee ,\wedge
\rangle$ of type $\langle 2,2\rangle$ such that

$\langle L,\vee \rangle$ and $\langle L,\wedge
\rangle$ are 
[semilattices](semilattices.md), and

$\vee ,\wedge$ are absorbtive:  $(x\vee y)\wedge x=x$, $(x\wedge y)\vee x=x$


## Definition
A ***lattice*** is a structure $\mathbf{L}=\langle L,\leq
\rangle$ that is a 
[partially ordered set](partially_ordered_sets.md) in which all elements $x,y\in L$ have a

least upper bound:  $z=x\vee y\Longleftrightarrow x\leq z$, $y\leq z\ \text{and}\ \forall w\ (x\leq w$, $y\leq w\Longrightarrow z\leq w)$ and a

greatest lower bound:  $z=x\wedge y\Longleftrightarrow z\leq x$, $z\leq y\ \text{and}\ \forall w\ (w\leq x$, $w\leq y\Longrightarrow w\leq z)$


## Definition
A ***lattice*** is a structure $\mathbf{L}=\langle L,\vee ,\wedge
,\leq \rangle$ such that $\langle L,\leq \rangle$ is a 
[partially ordered set](partially_ordered_sets.md) and the following quasiequations hold:

$\vee$-left:  $x\leq z$ and $y\leq z\ \Longrightarrow x\vee y\leq z$

$\vee$-right:  $z\leq x\Longrightarrow z\leq x\vee y$, $\quad z\leq y\Longrightarrow z\leq x\vee y$

$\wedge$-right:  $z\leq x$ and $z\leq y\Longrightarrow z\leq x\wedge y$

$\wedge$-left:  $x\leq z\Longrightarrow x\wedge y\leq z$, $\quad y\leq z\Longrightarrow x\wedge y\leq z$

Remark: 
These quasiequations give a cut-free Gentzen system to decide the equational
theory of lattices.


## Examples
Example 1: $\langle P(S),\cup ,\cap ,\subseteq \rangle$, the collection of
subsets of a sets $S$, ordered by inclusion.

/*Lattices (mace)*/


## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable in polynomial time |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes [(Nenosuke Funayama,Tadasi Nakayama,***On the distributivity of a lattice of lattice-congruences***,
Proc. Imp. Acad. Tokyo,
**18** 1942, 553--554)] |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes [(Bjarni J\'onsson,***Universal relational systems***,
Math. Scand., **4** 1956, 193--208)] |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 1 |
| 4 | 2 |
| 5 | 5 |
| 6 | 15 |
| 7 | 53 |
| 8 | 222 |
| 9 | 1078 |
| 10 | 5994 |
| 11 | 37622 |
| 12 | 262776 |
| 13 | 2018305 |
| 14 | 16873364 |
| 15 | 152233518 |
| 16 | 1471613387 |
| 17 | 15150569446 |
| 18 | 165269824761 |
| 19 | 1901910625578 |

[(Jobst Heitzig, J\"urgen Reinhold, ***Counting finite lattices***,
Algebra Universalis,
**48**, 2002, 43--53)][(Peter Jipsen, Nathan Lawless, ***Generating all finite modular lattices of a given size***, 
Algebra Universalis, **74**, 2015, 253--264

[Diagrams of lattices of size 2 to 7](http://math.chapman.edu/~jipsen/posets/lattices77.html)

/*[Finite lattices](finite_lattices.md) of size $\le 7$

[Subdirectly irreducible lattices](subdirectly_irreducible_lattices.md) of size $\le 7$

[Lattices not in some subclasses](lattices_not_in_some_subclasses.md) of size $\le 7$
*/

## Subclasses
[Modular lattices](modular_lattices.md) 

[Semidistributive lattices](semidistributive_lattices.md) 

[Neardistributive lattices](neardistributive_lattices.md) 

[Join-complete lattices](join-complete_lattices.md) 

[Meet-complete lattices](meet-complete_lattices.md) 

## Superclasses
[Semilattices](semilattices.md) 

[Weakly associative lattices](weakly_associative_lattices.md) 


## References
