# Representable lattice-ordered groups

Abbreviation: **RLGrp**


## Definition
A ***representable lattice-ordered group*** (or ***representable*** $\ell$***-group***) is a 
[lattice-ordered group](lattice-ordered_groups.md)
$\mathbf{L}=\langle L, \vee, \wedge, \cdot, ^{-1}, e\rangle$ that satisfies the identity

$(x\wedge y)^2 = x^2\wedge y^2$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be $\ell$-groups. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $f:L\rightarrow M$ that is a
homomorphism: $f(x\vee y)=f(x)\vee f(y)$ and $f(x\cdot y)=f(x)\cdot f(y)$.

Remark: It follows that $f(x\wedge y)=f(x)\wedge f(y)$, $f(x^{-1})=f(x)^{-1}$, and $f(e)=e$


## Examples


## Basic results
Every representable $\ell$-group is a subdirect product of [totally ordered groups](ordered_groups.md).


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)                       |variety |
|[Equational theory](equational_theory.md)               | |
|[Quasiequational theory](quasiequational_theory.md)          | |
|[First-order theory](first-order_theory.md)              |hereditarily undecidable [Gurevic1967] [Burris1985] |
|[Locally finite](locally_finite.md)                  |no |
|[Residual size](residual_size.md)                   | |
|[Congruence distributive](congruence_distributive.md)         |yes (see [lattices](lattices.md)) |
|[Congruence modular](congruence_modular.md)              |yes |
|[Congruence n-permutable](congruence_n-permutable.md)         |yes, $n=2$ (see [groups](groups.md)) |
|[Congruence regular](congruence_regular.md)              |yes, (see [groups](groups.md)) |
|[Congruence uniform](congruence_uniform.md)              |yes, (see [groups](groups.md)) |
|[Congruence extension property](congruence_extension_property.md)   | |
|[Definable principal congruences](definable_principal_congruences.md) | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)     | |
|[Amalgamation property](amalgamation_property.md)           |no [GlassSaracinoWood1984] |
|[Strong amalgamation property](strong_amalgamation_property.md)    |no [CherriPowell1993] |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)     | |


## Finite members
None


## Subclasses
[Abelian lattice-ordered groups](abelian_lattice-ordered_groups.md) 


## Superclasses
[Normal valued lattice-ordered groups](normal_valued_lattice-ordered_groups.md) 


## References

Stanley Burris, ***A simple proof of the hereditary undecidability of the theory of lattice-ordered abelian groups***,
Algebra Universalis,
**20**, 1985, 400--401, http://www.math.uwaterloo.ca/~snburris/htdocs/MYWORKS/PAPERS/HerUndecLOAG.pdf


Mona Cherri and Wayne B. Powell,
***Strong amalgamation of lattice ordered groups and modules***,
International J. Math. & Math. Sci., Vol 16, No 1 (1993) 75--80, http://www.hindawi.com/journals/ijmms/1993/405126/abs/ doi:10.1155/S0161171293000080


A. M. W. Glass, D. Saracino and C. Wood,
***Non-amalgamation of ordered groups***,
Math. Proc. Camb. Phil. Soc. 95 (1984), 191--195


Yuri Gurevic, ***Hereditary undecidability of a class of lattice-ordered Abelian groups***,
Algebra i Logika Sem.,
**6**, 1967, 45--62
