# Categories

Abbreviation: **Cat**

## Definition
A ***category*** is a structure $\mathbf{C}=\langle C,\circ,\text{dom},\text{cod}\rangle$ of type $\langle 2,1,1\rangle$ such that
$C$ is a class,

$\langle C,\circ\rangle$ is a (large) [partial semigroup](partial_semigroups.md)

dom amd cod are total unary operations on $C$ such that

$\text{dom}(x)$ is a left unit:  $\text{dom}(x)\circ x=x$

$\text{cod}(x)$ is a right unit:  $x\circ\text{cod}(x)=x$

if $x\circ y$ exists then $\text{dom}(x\circ y)=\text{dom}(x)$ and $\text{cod}(x\circ y)=\text{cod}(y)$

$x\circ y$ exists iff $\text{cod}(x)=\text{dom}(y)$

Remark: The members of $C$ are called ***morphisms***, $\circ$ is the partial operation of ***composition***,
dom is the ***domain*** and cod is the ***codomain*** of a morphism.

The set of objects of $C$ is the set $\mathbf{Obj}C=\{\text{dom}(x)|x\in C\}$. For $a,b\in C$ the set of homomorphism from $a$ to $b$ is
$\text{Hom}(a,b)=\{c\in C|\text{dom}(c)=a\text{ and }\text{cod}(c)=b\}$.

### Morphisms
Let $\mathbf{C}$ and $\mathbf{D}$ be categories. A morphism from $\mathbf{C}$ to $\mathbf{D}$ is a function $h:C\rightarrow D$ that is a homomorphism: 
$h(\text{dom}(c))=\text{dom}h(c)$, $h(\text{cod}(c))=\text{cod}h(c)$ and
$h(c\circ d)=h(c) \circ h(d)$ whenever $c\circ d$ is defined.

Morphisms between categories are called ***functors***.

## Examples
Example 1: The category of function on sets with composition.

In fact, most of the classes of mathematical structures in this database are categories.

## Basic results

$\text{dom}(\text{dom}(x))=\text{dom}(x)=\text{cod}(\text{dom}(x))$

$\text{cod}(\text{cod}(x))=\text{cod}(x)=\text{dom}(\text{cod}(x))$

## Properties



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |many-sorted variety  |
|[Equational theory](equational_theory.md)                | |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   | |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          | |
|[Congruence modular](congruence_modular.md)               | |
|[Congruence n-permutable](congruence_n-permutable.md)        | |
|[Congruence regular](congruence_regular.md)               | |
|[Congruence uniform](congruence_uniform.md)               | |
|[Congruence extension property](congruence_extension_property.md)    | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      | |
|[Amalgamation property](amalgamation_property.md)            | |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |

## Finite members

$\begin{array}{lr}
  f(1)= &1\\
  f(2)= &3\\
  f(3)= &11\\
  f(4)= &55\\
  f(5)= &329\\
  f(6)= &2858\\
  f(7)= &\\
  f(8)= &\\
  f(9)= &\\
  f(10)= &\\
\end{array}$

http://oeis.org/A125696

## Subclasses
[Schroeder categories](schroeder_categories.md)

[Closed categories](closed_categories.md)

[Compact categories](compact_categories.md)


## Superclasses
[Partially ordered categories](partially_ordered_categories.md)

[Partial semigroups](partial_semigroups.md)


## References





