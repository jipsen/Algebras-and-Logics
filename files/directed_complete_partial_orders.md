# Directed complete partial orders

Abbreviation: **DCPO**
## Definition
A ***directed complete partial order*** is a poset $\mathbf{P}=\langle P,\leq \rangle$
such that every directed subset of $P$ has a least upper bound: 
$\forall D\subseteq P\ (D\ne\emptyset\text{and}\forall x,y\in D\ \exists z\in D
(x,y\le z)\Longrightarrow \exists z\in P(z=\bigvee D))$.
### Morphisms
Let $\mathbf{P}$ and $\mathbf{Q}$ be directed complete partial orders. A morphism from $\mathbf{P}$ to 
$\mathbf{Q}$ is a function $f:Parrow Q$ that is ***Scott-continuous***, which means that $f$ preserves all directed joins: 

$z=\bigvee D\Longrightarrow f(z)= \bigvee f[D]$

## Examples
Example 1: $\langle \mathbb{R},\leq \rangle$, the real numbers with the standard order.
Example 1: $\langle P(S),\subseteq \rangle$, the collection of subsets of a
sets $S$, ordered by inclusion.


## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |second-order |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |

## Subclasses
[Complete semilattices](complete_semilattices.md) 

## Superclasses
[Directed partial orders](directed_partial_orders.md) 


## References


)]