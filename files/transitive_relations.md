# Transitive relations

Abbreviation: **TransRel**

## Definition
A ***transitive relation*** is a structure $\mathbf{X}=\langle X,R\rangle$ such that $R$ is a ***binary relation on*** $X$ 
(i.e. $R\subseteq X\times X$) that
is

transitive:  $xRy\text{ and }yRz\Longrightarrow xRz$

### Morphisms
Let $\mathbf{X}$ and $\mathbf{Y}$ be transitive relations. A morphism from $\mathbf{X}$ to $\mathbf{Y}$ is a function $h:X\rightarrow Y$ that is a homomorphism: 
$xR_{\mathbf X} y\Longrightarrow h(x)R_{\mathbf Y}h(y)$

## Definition
A ***transitive relation*** is a structure $\mathbf{X}=\langle X,R\rangle$ with $R\subseteq X\times X$ such that $R\circ R\subseteq R$, where $R\circ S=\{\langle x,z\rangle\mid \exists y\,(xRy\text{ and }ySz)\}$.

## Examples
Example 1: $\langle\mathbb{N},<\rangle$, and more generally every strict partial order.

Example 2: Every [preordered set](preordered_sets.md), e.g. $\langle\mathbb{Z},\mid\rangle$ (divisibility), and every [partially ordered set](partially_ordered_sets.md) or [equivalence relation](equivalence_relations.md).

Example 3: $\langle X,\emptyset\rangle$ and $\langle X,X\times X\rangle$ for any set $X$.

## Basic results
The intersection of any family of transitive relations on $X$ is transitive, so every relation $R$ has a smallest transitive extension, its ***transitive closure*** $R^+=\bigcup_{n\ge 1}R^n$.

A transitive relation is a preorder if and only if it is reflexive, and a strict partial order if and only if it is irreflexive (strict partial orders are then also asymmetric). A transitive relation that is symmetric is a ***partial equivalence relation***, i.e. an equivalence relation on $\{x\mid xRx\}$.

Strong amalgamation: if $\mathbf{A}$ is a substructure of $\mathbf{B}$ and $\mathbf{C}$ with $B\cap C=A$, then the transitive closure of $R_{\mathbf B}\cup R_{\mathbf C}$ restricts to $R_{\mathbf B}$ on $B$ and to $R_{\mathbf C}$ on $C$. Indeed, a path in $R_{\mathbf B}\cup R_{\mathbf C}$ between elements of $B$ splits into segments inside $C$ that start and end in $A$; by transitivity of $R_{\mathbf C}$ each such segment can be replaced by a single $R_{\mathbf A}$-edge, so the path lies in $B$.

Epimorphisms are surjective: if $h:\mathbf X\to\mathbf Y$ is not onto, take two copies of $\mathbf Y$ glued along $h[X]$, with the transitive closure of the union of their relations; the two inclusions of $\mathbf Y$ agree on $h[X]$ but are different.

## Properties

|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |quasivariety  |
|[Quasiequational theory](quasiequational_theory.md)           |decidable |
|[First-order theory](first-order_theory.md)               |undecidable |
|[Locally finite](locally_finite.md)                   |yes |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          | |
|[Congruence modular](congruence_modular.md)               | |
|[Congruence n-permutable](congruence_n-permutable.md)        | |
|[Congruence regular](congruence_regular.md)               | |
|[Congruence uniform](congruence_uniform.md)               | |
|[Congruence extension property](congruence_extension_property.md)    | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      | |
|[Amalgamation property](amalgamation_property.md)            |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)     |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      |yes |

The quasiequational (universal Horn) theory is decidable since the language is finite and purely relational: deciding whether a universal sentence follows from the axioms reduces to satisfiability of an $\exists^*\forall^*$ sentence (Bernays–Schönfinkel class). The first-order theory is undecidable, since the theory of partially ordered sets, which is undecidable [ELTT1965], is a finitely axiomatized extension of it.

## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 2 |
| 2 | 8 |
| 3 | 39 |
| 4 | 242 |
| 5 | 1895 |
| 6 | 19051 |
| 7 | 246895 |
| 8 | 4145108 |
| 9 | 90325655 |
| 10 | 2555630036 |
| 11 | 93810648902 |
| 12 | 4461086120602 |
| 13 | 274339212258846 |
| 14 | 21775814889230580 |
| 15 | 2226876304576948549 |

Sequence: [OEIS A091073](https://oeis.org/A091073) (transitive relations on $n$ unlabeled points). The values for $n\le 4$ were also checked by direct enumeration. The number of transitive relations on a fixed $n$-element set (labelled count) is [OEIS A006905](https://oeis.org/A006905).

## Subclasses
  [Preordered sets](preordered_sets.md) subquasivariety

## Superclasses
  [Directed graphs](directed_graphs.md) supervariety


## References

[ELTT1965] Yu. L. Ershov, I. A. Lavrov, A. D. Taimanov, M. A. Taitslin, ***Elementary theories***, Russian Math. Surveys, **20**, 1965
