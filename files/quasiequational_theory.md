# Quasiequational theory

A ***quasiequation*** is a universal formula of the form $\phi_1 \text{ and } \phi_2 \text{ and }\cdots\text{ and } \phi_m\ \Longrightarrow\ \phi_0$,
where the $\phi_i$ are atomic formulas. Note that for an algebraic language, the $\phi_i$ are simply equations. For $m=0$, a quasiequation
is just a universal atomic formula.

The ***quasiequational theory*** of a class of structures is the set of quasiequations that hold in all members of the class.

The ***decision problem*** for the quasiequational theory of a class of structures is the problem with input: a quasiequation
of length $n$ (as a string) and output: "true" if the quasiequation holds in all members of the class, and "false" otherwise.

The quasiequational theory is ***decidable*** if there is an algorithm that solves the decision problem, otherwise it is ***undecidable***.

The complexity of the decision problem (if known) is one of PTIME, NPTIME, PSPACE, EXPTIME, ...

A complete deductive system for quasiequations is given in [A. Selman, ***Completeness of calculi for axiomatically defined classes of algebras***, 
Algebra Universalis, **2**, 1972, 20--32 [MRreview](http://www.ams.org/mathscinet-getitem?mr=47:1725).
Additional information on quasiequations can be found e.g. in
[Stanley N. Burris and H.P. Sankappanavar, A Course in Universal Algebra](http://www.thoralf.uwaterloo.ca/htdocs/ualg.html).

