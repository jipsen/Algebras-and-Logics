# Complete lattices

Abbreviation: **CLat**
## Definition
A ***complete lattice*** is a structure $\mathbf{L}=\langle L,\bigvee,\bigwedge\rangle$ such that $\bigvee,\bigwedge$ map
subsets of $L$ to elements of $L$ and

$\langle L,\vee,\wedge\rangle$ is a [lattice](lattices.md) where $x\vee y=\bigvee\{x,y\}$, $x\wedge y=\bigwedge\{x,y\}$ and

$\bigvee S$ is the least upper bound of $S$,

$\bigwedge S$ is the greatest lower bound of $S$.

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be complete lattices. 
A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a complete homomorphism: 

$h(\bigvee S)=\bigvee h[S] \text{ and } h(\bigwedge S)=\bigwedge h[S]$

## Examples
Example 1: $\langle \mathcal{P}(X),\bigcup,\bigcap\rangle$, the set of all subsets of a set $X$, with union and intersection of families of sets.

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |Second-order |
|[Amalgamation property](amalgamation_property.md)  |Yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |Yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |Yes |

## Subclasses
[Algebraic lattices](algebraic_lattices.md) 

## Superclasses
[Lattices](lattices.md) 


## References






