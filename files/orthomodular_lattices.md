# Orthomodular lattices

Abbreviation: **OMLat**
## Definition
An ***orthomodular lattice*** is an [ortholattice](ortholattices.md) $\mathbf{L}=\langle L,\vee,0,\wedge,1,'\rangle$ such that

the orthomodular law holds:  $x\le y \implies x\vee(x'\wedge y)=y$.

This law is equivalent to satisfying the identity $x\vee(x'\wedge (x\vee y))=x\vee y$.

### Morphisms
Let $\mathbf{L}$ and $\mathbf{M}$ be orthomodular lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x')=h(x)'$

## Examples
Example 1: The closed subspaces of (countably dimensional) Hilbert Space form an orthomodular lattice that is not modular (for finite dimensional vector spaces all subspaces are closed, hence the lattice of closed subspaces is modular).

Example 2: The smallest nonmodular orthomodular lattice has 10 elements and is isomorphic to a parallel sum of a 4-element Boolean algebra and an 8-element Boolean algebra. A failure of the modular law $x\vee(y\wedge(x\vee z))=(x\vee y)\wedge(x\vee z)$ occurs when $x$, $z$ are atoms of the 8-element algebra and $y$ is an atom of the 4-element algebra.

<html>
<script>
function initcanvas(id,u,lflag,r){
  c=document.getElementById(id).getContext('2d');c.translate(10,-10);
  unit=u; radius=r?r:6;
  labelnode=lflag;
  labelcolor="black";
  nodes=new Array;
}

function node(x,y,t,r,nodecolor){
  nodes[t]=[];nodes[t][0]=x;nodes[t][1]=y;if(r==undefined)r=radius;nodes[t][2]=r;
  if(nodecolor==undefined)nodecolor="black";nodes[t][3]=nodecolor;
}

function edge(i,j,edgecolor){
  if(edgecolor==undefined)edgecolor="black";nodecolor=nodes[i][3];
  x=nodes[i][0];y=nodes[i][1];z=nodes[j][0];w=nodes[j][1];r=nodes[i][2];
  c.strokeStyle=edgecolor;c.beginPath();c.moveTo(unit*x,c.canvas.height-unit*y);c.lineTo(unit*z,c.canvas.height-unit*w);c.stroke();
  c.strokeStyle=nodecolor;c.fillStyle="white";c.beginPath();c.arc(unit*x,c.canvas.height-unit*y,r,0,6.3,true);c.fill();c.stroke();
  if(labelnode){c.fillStyle=nodecolor=="white"?labelcolor:nodecolor;c.fillText(i,unit*x-2.7,c.canvas.height-unit*y+3.5);}
}
function edges(lst,edgecolor){for (i=0;i<lst.length-1;i++) edge(lst[i],lst[i+1],edgecolor);edge(lst[i],lst[i],edgecolor);}
</script>

<canvas id="oml" width="140" height="110"></canvas>
<script>
initcanvas("oml",30,false,4);
node(2,3,"7");
node(0,2,"4");node(1,2,"5");node(2,2,"6");node(3,1.5,"8");node(4,1.5,"9");
node(0,1,"1");node(1,1,"2");node(2,1,"3");
node(2,0,"0");
edges([0,1,6,7,4,3,0,2,4]);
edges([1,5,7]);
edges([5,3]);edges([2,6]);
edges([0,8,7,9,0]);
</script>
</html>

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  |undecidable |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  | |
|[Congruence regular](congruence_regular.md)  | |
|[Congruence uniform](congruence_uniform.md)  | |
|[Congruence extension property](congruence_extension_property.md)  |no |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong.md)  |no |
|[Amalgamation property](amalgamation_property.md)  |no |
|[Strong amalgamation property](strong_amalgamation_property.md)  |no |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members |
|--:|--:|
| 1 | 1 |
| 2 | 1 |
| 3 | 0 |
| 4 | 1 |
| 5 | 0 |
| 6 | 1 |
| 7 | 0 |
| 8 | 2 |

Many Greechie diagrams of orthomodular lattices with blocks containing 3 atoms have been computed at http://cs.anu.edu.au/~Brendan.McKay/nauty/greechie.html

## Subclasses
[Modular ortholattices](modular_ortholattices.md) 


## Superclasses
[Ortholattices](ortholattices.md) 


## References



