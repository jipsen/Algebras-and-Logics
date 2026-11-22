# Complete semilattices

Abbreviation: **CSlat**
## Definition
A ***complete semilattice*** is a [directed complete partial orders](directed_complete_partial_orders.md) $\mathbf{P}=\langle P,\leq \rangle$
such that every nonempty subset of $P$ has a greatest lower bound: 
$\forall S\subseteq P\ (S\ne\emptyset\Longrightarrow \exists z\in P(z=\bigwedge S))$.
### Morphisms
Let $\mathbf{P}$ and $\mathbf{Q}$ be complete semilattices. A morphism from $\mathbf{P}$ to 
$\mathbf{Q}$ is a function $f:P\rightarrow Q$ that preserves all nonempty meets and all directed joins: 

$z=\bigwedge S\Longrightarrow f(z)=\bigwedge f[S]$ for all nonempty $S\subseteq P$ and 
$z=\bigvee D\Longrightarrow f(z)= \bigvee f[D]$

## Examples
Example 1: 

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
[Complete lattices](complete_lattices.md) 

## Superclasses
[Directed complete partial orders](directed_complete_partial_orders.md) 


## References


)]