# Monadic algebras

Abbreviation: **MonA**

## Definition
A ***monadic algebra*** is a structure $\mathbf{A}=\langle A, \vee, 0, \wedge, 1, \neg, f\rangle$ of type $\langle 2, 0, 2, 0, 1, 1\rangle$ such that

$\langle A, \vee, 0, \wedge, 1, \neg\rangle$ is a [Boolean algebra](boolean_algebras.md)

$f$ is a ***unary closure operator***:  $f(x\vee y)=f(x)\vee f(y)$, $f(0)=0$, $x\le f(x)=f(f(x))$

$f$ is ***self conjugated***:  $f(x)\wedge y=0\iff x\wedge f(y)=0$

Remark: This is a template.
If you know something about this class, click on the 'Edit text of this page' link at the bottom and fill out this page.

It is not unusual to give several (equivalent) definitions. Ideally, one of the definitions would give an irredundant axiomatization that does not refer to other classes.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be monodic algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$,
$h(\neg x)=\neg h(x)$, 
$h(f(x))=f(h(x))$.

## Examples
Example 1: 

## Basic results


## Properties
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.



|Property|Value|
|---|---|
|[Classtype](classtype.md)                        |variety  |
|[Equational theory](equational_theory.md)                |decidable |
|[Quasiequational theory](quasiequational_theory.md)           | |
|[First-order theory](first-order_theory.md)               | |
|[Locally finite](locally_finite.md)                   | |
|[Residual size](residual_size.md)                    | |
|[Congruence distributive](congruence_distributive.md)          |yes |
|[Congruence modular](congruence_modular.md)               |yes |
|[Congruence n-permutable](congruence_n-permutable.md)        |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)               |yes |
|[Congruence uniform](congruence_uniform.md)               |yes |
|[Congruence extension property](congruence_extension_property.md)    |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |yes |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)      |yes |
|[Amalgamation property](amalgamation_property.md)            |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)     | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)      | |

## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |

## Subclasses



## Superclasses
  [Boolean algebras](boolean_algebras.md) reduced type

  [Closure algebras](closure_algebras.md)


## References





