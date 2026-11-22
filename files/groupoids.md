# Groupoids

Abbreviation: **Grpd**

## Definition
A ***groupoid*** is a [category](categories.md) $\mathbf{C}=\langle C,\circ,\text{dom},\text{cod}\rangle$ such that

every morphism is an isomorphism: $\forall x\exists y\ x\circ y=\text{dom}(x)\text{ and }y\circ x=\text{cod}(x)$ 

### Morphisms
Let $\mathbf{C}$ and $\mathbf{D}$ be groupoids. A morphism from $\mathbf{C}$ to $\mathbf{D}$ is a function $h:C\rightarrow D$ that is a ***functor***: $h(x\circ y)=h(x)\circ h(y)$, $h(\text{dom}(x))=\text{dom}(h(x))$ and $h(\text{cod}(x))=\text{cod}(h(x))$.

Remark: These categories are also called ***Brandt groupoids***.

## Examples
Example 1: 

## Basic results


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |first-order class |
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
  f(2)= &2\\
  f(3)= &3\\
  f(4)= &7\\
  f(5)= &9\\
  f(6)= &16\\
  f(7)= &22\\
  f(8)= &42\\
  f(9)= &57\\
  f(10)= &90\\
\end{array}$

http://oeis.org/A140189

## Subclasses
[Groups](groups.md)

## Superclasses
[Categories](categories.md)

## References



