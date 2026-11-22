# Groups

Abbreviation: **Grp**

## Definition
A ***group*** is a structure $\mathbf{G}=\langle G,\cdot
,^{-1},e\rangle$, where $\cdot$ is an infix binary operation, called
the ***group product***, $^{-1}$ is a postfix unary operation, called the 
***group inverse*** and $e$ is a constant (nullary operation), called the 
***identity element***, such that

$\cdot$ is associative: $(xy)z=x(yz)$

$e$ is a left-identity for $\cdot$: $ex=x$

$^{-1}$ gives a left-inverse: $x^{-1}x=e$.

Remark: 
It follows that $e$ is a right-identity and that $^{-1}$gives a right
inverse: $xe=x$, $xx^{-1}=e$.

### Morphisms
Let $\mathbf{G}$ and $\mathbf{H}$ be groups. A morphism from $\mathbf{G}$ to 
$\mathbf{H}$ is a function $h:Garrow H$ that is a homomorphism: 

$h(xy)=h(x)h(y)$, $h(x^{-1})=h(x)^{-1}$, $h(e)=e$

## Examples
Example 1: $\langle S_{X},\circ ,^{-1},id_{X}\rangle$, the collection of
permutations of a sets $X$, with composition, inverse, and identity map.

Example 2: The general linear group $\langle GL_{n}(V),\cdot
,^{-1},I_{n}\rangle$, the collection of invertible $n\times n$
matrices over a vector space $V$, with matrix multiplication, inverse, and
identity matrix.

## Basic results



## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable in polynomial time |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Congruence distributive](congruence_distributive.md)  |no ($\mathbb{Z}_{2}\times \mathbb{Z}_{2}$) |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, n=2, $p(x,y,z)=xy^{-1}z$ is a Mal'cev term |
|[Congruence regular](congruence_regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
|[Congruence types](congruence_types.md)  |1=permutational |
|[Congruence extension property](congruence_extension_property.md)  |no, consider a non-simple subgroup of a simple group |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &1\\
f(6)= &2\\
f(7)= &1\\
f(8)= &5\\
f(9)= &2\\
f(10)= &2\\
f(11)= &1\\
f(12)= &5\\
f(13)= &1\\
f(14)= &2\\
f(15)= &1\\
f(16)= &14\\
f(17)= &1\\
f(18)= &5\\
\end{array}$

Information about small groups up to size 2000: http://www.tu-bs.de/~hubesche/small.html

## Subclasses
[p-groups](p-groups.md) 

[nilpotent groups](nilpotent_groups.md) 

[solvable groups](solvable_groups.md) 

## Superclasses
[Monoids](monoids.md) 

[Inverse semigroups](inverse_semigroups.md) 


## References


)]