# Algebraic posets

Abbreviation: **APos**

## Definition
An ***algebraic poset*** is a [directed complete partial order](directed_complete_partial_orders.md) $\mathbf{P}=\langle P,\leq \rangle$
such that

the set of compact elements below any element is directed and

every element is the join of all compact elements below it.

An element $c\in P$ is ***compact*** if for every subset $S\subseteq P$ such that $c\le\bigvee S$, there exists
a finite subset $S_0$ of $S$ such that $c\le\bigvee S_0$.

The set of compact elements of $P$ is denoted by $K(P)$.

### Morphisms
Let $\mathbf{P}$ and $\mathbf{Q}$ be algebraic posets. A morphism from $\mathbf{P}$ to 
$\mathbf{Q}$ is a function $f:P\rightarrow Q$ that is ***Scott-continuous***, which means that $f$ preserves all directed joins: 

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
[Algebraic semilattices](algebraic_semilattices.md) 


## Superclasses
[Directed complete partial orders](directed_complete_partial_orders.md) 


## References


)]