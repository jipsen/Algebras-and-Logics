# Bilattices

Abbreviation: **Bilat**

## Definition
A ***bilattice*** is a structure $\mathbf{L}=\langle L,\vee,\wedge,\oplus,\otimes,\neg\rangle$ such that

$\langle L,\vee,\wedge\rangle$ is a [lattice](lattices.md),

$\langle L,\oplus,\otimes\rangle$ is a [lattice](lattices.md),

$\neg$ is a De Morgan operation for $\vee$, $\wedge$: $\neg(x\vee y)=\neg x\wedge\neg y$, $\neg\neg x=x$ and

$\neg$ commutes with $\oplus$, $\otimes$: $\neg(x\oplus y)=\neg x\oplus\neg y$, $\neg(x\otimes y)=\neg x\otimes\neg y$.

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be bilattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\oplus y)=h(x)\oplus h(y)$, $h(x\otimes y)=h(x)\otimes h(y)$, $h(\neg x)=\neg h(x)$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |

## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 0 |
| 3 | 0 |
| 4 | 1 |
| 5 | 3 |
| 6 | 32 |
| 7 | 284 |

## Subclasses
[Interlaced bilattices](interlaced_bilattices.md) 

## Superclasses
[pre-bilattices](pre-bilattices.md) 


## References



