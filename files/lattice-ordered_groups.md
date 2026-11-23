# Lattice-ordered groups

Abbreviation: **LGrp**


## Definition
A ***lattice-ordered group*** (or $\ell$***-group***) is a structure $\mathbf{L}=\langle L, \vee, \wedge, \cdot, ^{-1}, e\rangle$ such that 

$\langle L, \vee, \wedge\rangle$ is a [lattice](lattices.md)

$\langle L, \cdot, ^{-1}, e\rangle$ is a [group](groups.md)

$\cdot$ is order-preserving:  $x\leq y\Longrightarrow uxv\leq uyv$

Remark: 
$xy=x\cdot y$, $x\leq y\Longleftrightarrow x\wedge y=x$ and $x\leq y\Longleftrightarrow x\vee y=y$


## Definition
A ***lattice-ordered group*** (or $\ell$***-group***) is a structure $\mathbf{L}=\langle L,\vee ,\cdot ,^{-1},e\rangle$ such that

$\langle L,\vee\rangle$ is a [semilattice](semilattices.md)

$\langle L,\cdot,^{-1},e\rangle$ is a [group](groups.md)

$\cdot$ is join-preserving:  $u(x\vee y)v=uxv\vee uyv$

Remark: $x\wedge y=( x^{-1}\vee y^{-1}) ^{-1}$


## Definition
A ***lattice-ordered group*** (or $\ell$***-group***) is a residuated
lattice $\mathbf{L}=\langle L,\vee ,\wedge ,\cdot ,\backslash
,/,e\rangle$ that satisfies the identity $x(e/x)=e$.

Remark: $x^{-1}=e/x=x\backslash e$, $x/y=xy^{-1}$ and $x\backslash y=x^{-1}y$

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be $\ell$-groups. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $f:L\to M$ that is a
homomorphism: $f(x\vee y)=f(x)\vee f(y)$, $f(x\wedge y)=f(x)\wedge f(y)$, $f(x\cdot y)=f(x)\cdot f(y)$, $f(x^{-1})=f(x)^{-1}$, and $f(e)=e$.


## Examples
$\langle Aut(\mathbf{C}),\text{max},\text{min},\circ,^{-1},id_{\mathbf{C}}\rangle$, 
the group of order-automorphisms of a [chain](chains.md) $\mathbf{C}$, with $\text{max}$ and $\text{min}$ 
(applied pointwise), composition, inverse, and identity automorphism.


## Basic results
The lattice reducts of lattice-ordered groups are [distributive lattices](distributive_lattices.md).


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable[HollandMcCleary1979] |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable[GlassGurevich1983] |
|[First-order theory](first-order_theory.md)  |hereditarily undecidable[Gurevic1967] [Burris1985] |
|[Congruence distributive](congruence_distributive.md)  |yes, see [lattices](lattices.md) |
|[Congruence extension property](congruence_extension_property.md)  | |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$, see [groups](groups.md) |
|[Congruence regular](congruence_regular.md)  |yes, see [groups](groups.md) |
|[Congruence uniform](congruence_uniform.md)  |yes, see [groups](groups.md) |
|[Definable principal congruences](definable_principal_congruences.md)  | |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  | |
|[Amalgamation property](amalgamation_property.md)  |no |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |

## Finite nontrivial members

None 

## Subclasses
[Normal valued lattice-ordered groups](normal_valued_lattice-ordered_groups.md) 

## Superclasses
[Cancellative residuated lattices](cancellative_residuated_lattices.md) 


## References

Stanley Burris, ***A simple proof of the hereditary undecidability of the theory of lattice-ordered abelian groups***,
Algebra Universalis,
**20**, 1985, 400--401, http://www.math.uwaterloo.ca/~snburris/htdocs/MYWORKS/PAPERS/HerUndecLOAG.pdf


A. M. W. Glass, Yuri Gurevich,
***The word problem for lattice-ordered groups***,
Trans. Amer. Math. Soc., **280** 1983, 127--138
[MRreview](http://www.ams.org/mathscinet-getitem?mr=85d:06015)[ZMATH](http://www.emis.de/MATH-item?0586.03037)


Yuri Gurevic, ***Hereditary undecidability of a class of lattice-ordered Abelian groups***,
Algebra i Logika Sem.,
**6**, 1967, 45--62


W. Charles Holland, Stephen H. McCleary,
***Solvability of the word problem in free lattice-ordered groups***,
Houston J. Math., **5** 1979, 99--105
[MRreview](http://www.ams.org/mathscinet-getitem?mr=80f:06018)[ZMATH](http://www.emis.de/MATH-item?0404.06009)
[http://www.chapman.edu/~jipsen/lgroups/lgroupDecisionProc.html implementation]


Keith R. Pierce,
***Amalgamations of lattice ordered groups***,
Trans. Amer. Math. Soc., **172** 1972, 249--260
[MRreview](http://www.ams.org/mathscinet-getitem?mr=48:3835)[ZMATH](http://www.emis.de/MATH-item?0259.06017)
