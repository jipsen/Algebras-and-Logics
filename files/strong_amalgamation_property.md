# Strong Amalgamation Property

An ***amalgam*** is a tuple 
$\langle \mathbf{A},f,\mathbf{B},g,\mathbf{C}\rangle$ such that 
$\mathbf{A},\mathbf{B},\mathbf{C}$ are structures of the same 
signature, and $f:\mathbf{A}\to\mathbf{B}$, $g:\mathbf{A}\to\mathbf{C}$
are embeddings (injective morphisms).

A class $\mathcal{K}$ of structures is said to have the
***strong amalgamation property***, or SAP for short, if for every amalgam $\langle \mathbf{A},f,\mathbf{B},g,\mathbf{C}\rangle$ with 
$\mathbf{A},\mathbf{B},\mathbf{C}\in\mathcal{K}$ and $A\ne\emptyset$
there exists a structure $\mathbf{D}\in\mathcal{K}$ and embeddings 
$f':\mathbf{B}\to\mathbf{D}$, $g':\mathbf{C}\to\mathbf{D}$ such that
$f'\circ f=g'\circ g$ and $\text{Im}(f ')\cap \text{Im}(g')=\text{Im}(f'\circ f)$,
where $\text{Im}(f ')=\{f '(x) | x\in B\}$.

### Properties that imply the SAP
[Amalgamation property](amalgamation_property.md) and [Epimorphisms are surjective](epimorphisms_are_surjective.md)

[Superamalgamation property](superamalgamation_property.md)

### Properties implied by the SAP
[Amalgamation property](amalgamation_property.md)

