# Normal valued lattice-ordered groups

Abbreviation: **NVLGrp**


## Definition
A ***normal valued lattice-ordered group*** (or ***normal valued*** $\ell$***-group***) is a 
[lattice-ordered group](lattice-ordered_groups.md)
$\mathbf{L}=\langle L, \vee, \wedge, \cdot, ^{-1}, e\rangle$ that satisfies

$(x\vee x^{-1})(y\vee y^{-1}) \le (y\vee y^{-1})^2(x\vee x^{-1})^2$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be $\ell$-groups. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $f:L\rightarrow M$ that is a
homomorphism: $f(x\vee y)=f(x)\vee f(y)$ and $f(x\cdot y)=f(x)\cdot f(y)$.

Remark: It follows that $f(x\wedge y)=f(x)\wedge f(y)$, $f(x^{-1})=f(x)^{-1}$, and $f(e)=e$


## Examples


## Basic results
The variety of normal valued $\ell$-groups is the largest proper subvariety of [lattice-ordered groups](lattice-ordered_groups.md) [Holland1976].


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
|[Amalgamation property](amalgamation_property.md)           | |
|[Strong amalgamation property](strong_amalgamation_property.md)    | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)     | |


## Finite nontrivial members
None


## Subclasses
[Representable lattice-ordered groups](representable_lattice-ordered_groups.md) 


## Superclasses
[Lattice-ordered groups](lattice-ordered_groups.md) 


## References

Stanley Burris, ***A simple proof of the hereditary undecidability of the theory of lattice-ordered abelian groups***,
Algebra Universalis,
**20**, 1985, 400--401, http://www.math.uwaterloo.ca/~snburris/htdocs/MYWORKS/PAPERS/HerUndecLOAG.pdf


Yuri Gurevic, ***Hereditary undecidability of a class of lattice-ordered Abelian groups***,
Algebra i Logika Sem.,
**6**, 1967, 45--62


W. Charles Holland, ***The largest proper variety of lattice-ordered groups***,
Proceedings of the AMS, **57**(1), 1976, 25--28)]