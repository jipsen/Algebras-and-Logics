# Quandles

Abbreviation: **Qnd**

## Definition
A ***quandle*** is a structure $\mathbf{Q}=\langle Q,\triangleright,\triangleleft\rangle$ of type $\langle 2,2\rangle$ such that

$\triangleright$ is ***left-selfdistributive***:  $x\triangleright(y\triangleright z)=(x\triangleright y)\triangleright(x\triangleright z)$

$\triangleleft$ is ***right-selfdistributive***:  $(x\triangleleft y)\triangleleft z=(x\triangleleft z)\triangleleft(y\triangleleft z)$

$(x\triangleright y)\triangleleft x=y$

$x\triangleright (y\triangleleft x)=y$

$\triangleright$ is ***idempotent***: $x\triangleright x=x$

Remark: The last identity can equivalently be replaced by $\triangleleft$ is ***idempotent***: $x\triangleleft x=x$


### Morphisms
Let $\mathbf{Q}$ and $\mathbf{R}$ be quandles. A morphism from $\mathbf{Q}$ to $\mathbf{R}$ is a function $h:Q\rightarrow R$ that is a homomorphism: 
$h(x \triangleright y)=h(x) \triangleright h(y)$ and $h(x \triangleleft y)=h(x) \triangleleft h(y)$.

## Examples
Example 1: If $\langle G,\cdot,^{-1},1\rangle$ is a [group](groups.md) and $x\triangleright y=xyx^{-1}$, $x\triangleleft y=x^{-1}yx$ (conjugation) then 
$\langle G,\triangleright,\triangleleft\rangle$ is a quandle.

## Basic results


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        | [variety](varieties.md) |
|[Equational theory](equational_theory.md)                | |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   | |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          | No |
|[Congruence modular](congruence_modular.md)               | No |
|[Congruence n-permutable](congruence_n-permutable.md)        | Yes, $n=2$ |
|[Congruence regular](congruence_regular.md)               | |
|[Congruence uniform](congruence_uniform.md)               | |
|[Congruence extension property](congruence_extension_property.md)    | |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      | |
|[Amalgamation property](amalgamation_property.md)            | |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |

## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 3 |
| 4 | 7 |
| 5 | 22 |
| 6 | 73 |
| 7 | 298 |
| 8 | 1581 |
| 9 | 11079 |

## Subclasses
[Involutory quandles](involutory_quandles.md)

[Symmetric quandles](symmetric_quandles.md)

[Abelian quandles](abelian_quandles.md)

## Superclasses
[Racks](racks.md)

## References





