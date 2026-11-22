#  Monounary Algebras 

Abbreviation: **MonoUn**

## Definition
A ***monounary algebra*** is a structure $\mathbf{A}=\langle A,f\rangle$ of type $\langle 1\rangle$ such that
$f$ is a unary operation on $A$.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be monounary algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(f(x))=f(h(x))$.

## Examples
Example 1: The free unary algebra on one generator is isomorphic to the natural numbers $\mathbb N$. The number 0 is the generator $x$, and the operation $f$ is the successor function, i.e., $f(n)=n+1$.

The free unary algebra on $X$ generators is a union of $|X|$ disjoint copies of the one-generated free algebra.

## Basic results
Monounary algebras are equivalent to directed graphs in which every vertex has exactly one outgoing edge.

One-generated monounary algebras are either isomorphic to the free one-generated algebra or they are finite and contain a path of length $l$ from the generator to a cycle of length $k$ (where $l\geq 0$ and $k\geq 1$).

## Properties



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |variety |
|[Equational theory](equational_theory.md)                |decidable |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   |no |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          |no |
|[Congruence modular](congruence_modular.md)               |no |
|[Congruence n-permutable](congruence_n-permutable.md)        |no |
|[Congruence regular](congruence_regular.md)               |no |
|[Congruence uniform](congruence_uniform.md)               |no |
|[Congruence extension property](congruence_extension_property.md)    |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      |no |
|[Amalgamation property](amalgamation_property.md)            | |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |

## Finite members



## Subclasses

[Idempotent monounary algebras](idempotent_monounary_algebras.md) subvariety

The variety of monounary algebras has countably many subvarieties, each determined by an equation of the form $f^m(x)=f^n(x)$.

Let $j>k\ge 0$ and $m>n\ge 0$. Then
$\text{Mod}(f^j(x)=f^k(x)\subseteq\text{Mod}(f^m(x)=f^n(x)$ if and only if $k\le n$ and $(j-k)|(m-n)$.

Hence the lattice of nontrivial subvarieties of monounary algebras is isomorphic to $(\mathbb N,\le)\times (\mathbb N,|)$, which is itself isomorphic to the lattice of divisibility of the natural numbers. The variety $\text{Mod}(x=y)$ of trivial subvarieties is the unique element below the variety $\text{Mod}(f(x)=x)$ (which is term-equivalent to the variety of sets).

## Superclasses

[Duo-unary algebras](duo-unary_algebras.md) subreduct


## References

