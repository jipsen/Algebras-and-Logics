# Modular lattices

Abbreviation: **MLat**

## Definition
A ***modular lattice*** is a [lattice](lattices.md) $\mathbf{L}=\langle L, \vee, \wedge\rangle$ that satisfies the

***modular identity***:  $((x\wedge z) \vee y) \wedge z = (x\wedge z) \vee (y\wedge z)$

## Definition
A ***modular lattice*** is a [lattice](lattices.md) $\mathbf{L}=\langle L, \vee, \wedge\rangle$ that satisfies the

***modular law***: $x\le z\Longrightarrow (x\vee y) \wedge z\le x\vee (y\wedge z)$

## Definition
A ***modular lattice*** is a lattice $\mathbf{L}=\langle L,\vee,\wedge\rangle$ such that $\mathbf{L}$ has no sublattice isomorphic
to the pentagon $\mathbf{N}_{5}$ <html><canvas id="c1" width="60" height="60"></canvas>
<script>
unit=20;
labelnodes=false;
function node(x,y,t,r,nodecolor){
  nodes[t]=[];nodes[t][0]=x;nodes[t][1]=y;if(r==undefined)r=(labelnodes?6:3);nodes[t][2]=r;
  if(nodecolor==undefined)nodecolor="black";nodes[t][3]=nodecolor;
}
function edge(i,j,edgecolor){
  if(edgecolor==undefined)edgecolor="black";nodecolor=nodes[i][3];
  x=nodes[i][0];y=nodes[i][1];z=nodes[j][0];w=nodes[j][1];r=nodes[i][2];
  c.strokeStyle=edgecolor;c.beginPath();c.moveTo(unit*x,c.canvas.height-unit*y);c.lineTo(unit*z,c.canvas.height-unit*w);c.stroke();
  c.strokeStyle=nodecolor;c.fillStyle="white";c.beginPath();c.arc(unit*x,c.canvas.height-unit*y,r,0,6.3,true);c.fill();if(r!=0)c.stroke();
  if(labelnodes){c.fillStyle=nodecolor;c.fillText(i,unit*x-2.7,c.canvas.height-unit*y+3.5);}
}
nodes=new Array;c=document.getElementById('c1').getContext('2d');c.translate(10,-4);
node(1,2,"4");
node(0,0.66,"1");node(0,1.33,"2");node(2,1,"3");
node(1,0,"0");
edge(4,2);edge(4,3);
edge(2,1);
edge(1,0);edge(3,0);
edge(0,0);
</script>
</html>

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be modular lattices. 
A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$

## Examples
Example 1: $M_3$ <html><canvas id="c2" width="60" height="60"></canvas>
<script>
nodes=new Array;c=document.getElementById('c2').getContext('2d');c.translate(10,-4);
node(1,2,"4");
node(0,1,"1");node(1,1,"2");node(2,1,"3");
node(1,0,"0");
edge(4,1);edge(4,2);edge(4,3);
edge(1,0);edge(2,0);edge(3,0);
edge(0,0);
</script></html>
is the smallest nondistributive modular lattice. By a result of [Dedekind1900]
this lattice occurs as a sublattice of every nondistributive
modular lattice.


## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |undecidable [Freese1980] [Herrmann1983] |
|[Quasiequational theory](quasiequational_theory.md)  |undecidable [Lipshitz1974] |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |no |
|[Congruence regular](congruence_regular.md)  |no |
|[Congruence uniform](congruence_uniform.md)  |no |
|[Congruence extension property](congruence_extension_property.md)  |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |no |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |no |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 1 |
| 4 | 2 |
| 5 | 4 |
| 6 | 8 |
| 7 | 16 |
| 8 | 34 |
| 9 | 72 |
| 10 | 157 |
| 11 | 343 |
| 12 | 766 |
| 13 | 1718 |
| 14 | 3899 |
| 15 | 8898 |
| 16 | 20475 |
| 17 | 47321 |
| 18 | 110024 |
| 19 | 256791 |
| 20 | 601991 |
| 21 | 1415768 |
| 22 | 3340847 |
| 23 | 7904700 |
| 24 | 18752942 |

[(Peter Jipsen, Nathan Lawless, ***Generating all finite modular lattices of a given size***, 
Algebra Universalis, **74**, 2015, 253--264

## Subclasses
[Distributive lattices](distributive_lattices.md) 

[Complete modular lattices](complete_modular_lattices.md) 

## Superclasses
[Semimodular lattices](semimodular_lattices.md) 

[Geometric lattices](geometric_lattices.md) 


## References


Richard Dedekind, ***\"Uber die von drei Moduln erzeugte Dualgruppe***,
Math. Ann., **53**, 1900, 371--403


Ralph Freese, ***Free modular lattices***,
Trans. Amer. Math. Soc., **261**, 1980, 81--91


Christian Herrmann, ***On the word problem for the modular lattice with four free generators***,
Math. Ann., **265**, 1983, 513--527


L. Lipshitz, ***The undecidability of the word problems for projective geometries and modular lattices***,
Trans. Amer. Math. Soc., **193**, 1974, 171--180
