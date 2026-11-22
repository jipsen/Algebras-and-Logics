# Equational Theory

The ***equational theory*** of a class of structures is the set of universal atomic formulas that hold in all members of the class.
For a class of algebras, this is simply the collection of all equations that hold in all members of the class.

The equational theory of a class of one-element structures consists of all universal atomic formulas in the language of the class.
The equational theory for the class of all structures of a given language contains only equations of the form $t=t$.

The ***decision problem*** for the equational theory of a class of structures is the problem with input: a universal atomic formula
of length $n$ and output: "true" if the formula holds in all members of the class, and "false" otherwise.

The equational theory is ***decidable*** if there is an algorithm that solves the decision problem, otherwise it is ***undecidable***.

The complexity of the decision problem (if known) is one of PTIME, NPTIME, PSPACE, EXPTIME, ...

G. Birkhoff showed that for classes of algebras, equational theories are precisely the sets of equations that are closed
under the standard rules of equational logic, see [Stanley N. Burris and H.P. Sankappanavar, A Course in Universal Algebra](http://www.thoralf.uwaterloo.ca/htdocs/ualg.html).
