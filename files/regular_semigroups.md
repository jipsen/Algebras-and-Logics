# Regular semigroups

Abbreviation: **RSgrp**
## Definition
An element $x$ of a semigroup $S$ is said to be ***regular*** if exists $y$ in $S$ such that $xyx=x$. 

## Definition
A ***regular semigroup*** is a [semigroups](semigroups.md) $\mathbf{S}=\langle
S,\cdot \rangle$ such that
each element is regular.


## Definition
A ***regular semigroup*** is a structure $\mathbf{S}=\langle
S,\cdot \rangle$, where $\cdot$ is an infix binary operation, called
the ***semigroup product***, such that


$\cdot$ is associative:  $(xy)z=x(yz)$


each element is ***regular***:  $\exists y(xyx=x)$

## Definition
We say that $y$ is an ***inverse*** of an element $x$ in a semigroup $S$ if $x=xyx$ and $y=yxy$.  


### Morphisms
Let $\mathbf{S}$ and $\mathbf{T}$ be regular semigroups. A morphism from 
$\mathbf{S}$ to $\mathbf{T}$ is a function $h:Sarrow T$ that is a
homomorphism: 

$h(xy)=h(x)h(y)$

## Examples
Example 1: $\langle T_X,\circ\rangle$, the ***full transformation semigroup*** of functions on $X$, with composition.

$\langle End(V),\circ\rangle$, the ***endomorphism monoid*** of a vector space $V$, with composition.



## Basic results
If $x$ is a regular element of a semigroup (say $x=xyx$), then $x$ has an inverse, namely $yxy$, since $x=x(yxy)x$ and $yxy=(yxy)x(yxy)$. 

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |First-order |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |No |
|[Residual size](residual_size.md)  | |
|[Congruence distributive](congruence_distributive.md)  |No |
|[Congruence modular](congruence_modular.md)  | |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |No |
|[Amalgamation property](amalgamation_property.md)  |No |
|[Strong amalgamation property](strong_amalgamation_property.md)  |No |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism and anti-isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 3 |
| 3 | 9 |
| 4 | 42 |
| 5 | 206 |
| 6 | 1352 |
| 7 | 10168 |
| 8 | 91073 |
| 9 | 925044 |

(the opposite of a semigroup $S$ is identified with $S$ in the table above, see [OEIS A001427](https://oeis.org/A001427))

## Subclasses
[Bands](bands.md) 

[Inverse semigroups](inverse_semigroups.md) 

[Completely regular semigroups](completely_regular_semigroups.md) 

## Superclasses
[Semigroups](semigroups.md) 


\begin{bibdiv}
\begin{biblist}

\bib{MR1455373}{book}{
   author={Howie, John M.},
   title={Fundamentals of semigroup theory},
   series={London Mathematical Society Monographs. New Series},
   volume={12},
   note={Oxford Science Publications},
   publisher={The Clarendon Press Oxford University Press},
   place={New York},
   date={1995},
   pages={x+351},
   isbn={0-19-851194-9},
   review={\MR{1455373 (98e:20059)}},
}

\end{biblist}
\end{bibdiv}

