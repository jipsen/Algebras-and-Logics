### Varieties of universal algebras

A ***variety*** is a class of structures of the same signature that is defined by a set of identities, i.e., universally quantified
equations or, more generally, atomic formulas.

Varieties are also called ***equational classes***.

By a fundamental result of [Garrett Birkhoff: ***On the structure of abstract algebras***, 
Proceedings of the Cambridge Philosophical Society, 31:433--454, 1935] a class $\mathcal{K}$ of algebras of the same signature is a 
variety iff it is closed under the operators $H$, $S$, $P$ (i.e., $H\mathcal{K}\subseteq\mathcal{K}$, $S\mathcal{K}\subseteq\mathcal{K}$, and $P\mathcal{K}\subseteq\mathcal{K}$), where

$H\mathcal{K}=\{$homomorphic images of members of $\mathcal{K}\}$

$S\mathcal{K}=\{$subalgebras of members of $\mathcal{K}\}$

$P\mathcal{K}=\{$direct products of members of $\mathcal{K}\}$.

Equivalently, $\mathcal K$ is a variety iff $\mathcal K=HSP\mathcal K$.

In particular, given any class $\mathcal K$ of algebras, $V\mathcal K=HSP\mathcal K$ is the smallest variety that contains $\mathcal K$, and is called the ***variety generated by $\mathcal K$***.

See [http://www.thoralf.uwaterloo.ca/htdocs/ualg.html| Stanley N. Burris and H.P. Sankappanavar,  A Course in Universal Algebra](http://www.thoralf.uwaterloo.ca/htdocs/ualg.html|_stanley_n._burris_and_h.p._sankappanavar,__a_course_in_universal_algebras.md) for
more details.

Show all pages on [http://math.chapman.edu/~jipsen/structures/doku.php/?do=search&id=variety&fulltext=Search| varieties](http://math.chapman.edu/~jipsen/structures/doku.php/?do=search&id=variety&fulltext=search|_varieties.md)

A picture of some [http://www.chapman.edu/~jipsen/PCP/theoriesPO1.html| theories ordered by interpretability](http://www.chapman.edu/~jipsen/pcp/theoriespo1.html|_theories_ordered_by_interpretabilitys.md)

### Some varieties and quasivarieties listed by signature and (first) subclass relation
Proper quasivarieties are marked by a *

$\langle \rangle$ [Sets](sets.md)

$\langle 0\rangle$ [Pointed sets](pointed_sets.md)

$\langle 1\rangle$ [Mono-unary algebras](mono-unary_algebras.md)

$\langle 1,0\rangle$ [Pointed mono-unary algebras](pointed_mono-unary_algebras.md)

$\langle 1,1\rangle$ [Duo-unary algebras](duo-unary_algebras.md)

$\langle 1,1,\ldots\rangle$ [Unary algebras](unary_algebras.md)
  *[M-sets](m-sets.md)
    *[G-sets](g-sets.md)

$\langle 2\rangle$ [Groupoids](groupoids.md)
  *[Semigroups](semigroups.md)
    *[Commutative semigroups](commutative_semigroups.md)
      *[Semilattices](semilattices.md)
    *[Bands](bands.md)
      *[Normal bands](normal_bands.md)
        *[Rectangular bands](rectangular_bands.md)
  *[Commutative groupoids](commutative_groupoids.md)
    *[Idempotent commutative groupoids](idempotent_commutative_groupoids.md)
  *[Idempotent groupoids](idempotent_groupoids.md)

$\langle 2,0\rangle$ [Pointed groupoids](pointed_groupoids.md)
  *[Monoids](monoids.md)
    *[Commutative monoids](commutative_monoids.md)
      *[Bounded semilattices](bounded_semilattices.md)
    *[Idempotent monoids](idempotent_monoids.md)
  *[BCI-algebras](bci-algebras.md)*
    *[BCK-algebras](bck-algebras.md)*
      *[Commutative BCK-algebras](commutative_bck-algebras.md)

$\langle 2,1\rangle$ [Groupoids with a unary operation](groupoids_with_a_unary_operations.md)
  *[Inverse semigroups](inverse_semigroups.md)
    *[Commutative inverse semigroups](commutative_inverse_semigroups.md)

$\langle 2,1,0\rangle$ [Pointed groupoids with a unary operation](pointed_groupoids_with_a_unary_operations.md)
  *[Groups](groups.md)
    *[Abelian groups](abelian_groups.md)
      *[Boolean groups](boolean_groups.md)

$\langle 2,1,0,1,1,\ldots\rangle$ [Pointed groupoids with a unary operations](pointed_groupoids_with_a_unary_operations.md)
  *[Modules over a ring](modules_over_a_rings.md)
    *[Vector spaces over a field](vector_spaces_over_a_fields.md)

$\langle 2,2\rangle$ [Duo-groupoids](duo-groupoids.md)
  *[Weakly associative lattices](weakly_associative_lattices.md)
    *[Lattices](lattices.md)
      *[Modular lattices](modular_lattices.md)
        *[Distributive lattices](distributive_lattices.md)
      *[Neardistributive lattices](neardistributive_lattices.md)
        *[Almost distributive lattices](almost_distributive_lattices.md)
  *[Semirings](semirings.md)
    *[Idempotent semirings](idempotent_semirings.md)
  *[Skew_lattices](skew_lattices.md)

$\langle 2,2,0\rangle$ [Pointed duo-groupoids](pointed_duo-groupoids.md)
  *[Semirings with identity](semirings_with_identitys.md)
  *[Semirings with zero](semirings_with_zeros.md)

$\langle 2,2,1\rangle$
  *[Lattices with a unary operation](lattices_with_a_unary_operations.md)
    *[Distributive lattices with a unary operation](distributive_lattices_with_a_unary_operations.md)
      *[Distributive lattices with a unary operator](distributive_lattices_with_a_unary_operators.md)
    *[Lattices with a unary operator](lattices_with_a_unary_operators.md)

$\langle 2,2,\ldots\rangle$
  *[Lattices with additional operations](lattices_with_additional_operations.md)
    *[Distributive lattices with additional operations](distributive_lattices_with_additional_operations.md)
      *[Distributive lattices with operators](distributive_lattices_with_operators.md)
    *[Lattices with operators](lattices_with_operators.md)

$\langle 2,0,2,0\rangle$
  *[Shells](shells.md)
    *[Bounded lattices](bounded_lattices.md)
      *[Bounded modular lattices](bounded_modular_lattices.md)
        *[Bounded distributive lattices](bounded_distributive_lattices.md)
  *[Semirings with identity and zero](semirings_with_identity_and_zeros.md)
    *[Boolean rings](boolean_rings.md)

$\langle 2,1,0,2\rangle$
  *[Near-rings](near-rings.md)
    *[Rings](rings.md)
      *[Commutative rings](commutative_rings.md)

$\langle 2,1,0,2,0\rangle$
  *[Rings with identity](rings_with_identitys.md)
    *[Commutative rings with identity](commutative_rings_with_identitys.md)

$\langle 2,0,2,0,1\rangle$
  *[Kleene algebras](kleene_algebras.md)*
  *[Bounded lattices with a unary operation](bounded_lattices_with_a_unary_operations.md)
    *[Bounded distributive lattices with a unary operation](bounded_distributive_lattices_with_a_unary_operations.md)
      *[Bounded distributive lattices with a unary operator](bounded_distributive_lattices_with_a_unary_operators.md)
    *[Bounded lattices with a unary operator](bounded_lattices_with_a_unary_operators.md)
    *[p-algebras](p-algebras.md)
      *[distributive p-algebras](distributive_p-algebras.md)
        *[Stone algebras](stone_algebras.md)
          *[Double Stone algebras](double_stone_algebras.md)
            *[Boolean algebras](boolean_algebras.md)
    *[dual p-algebras](dual_p-algebras.md)
      *[distributive dual p-algebras](distributive_dual_p-algebras.md)

$\langle 2,0,2,0,1,1\rangle$
  *[Boolean algebras with a unary operation](boolean_algebras_with_a_unary_operations.md)
    *[Modal algebras](modal_algebras.md)
      *[Closure algebras](closure_algebras.md)
        *[Monadic algebras](monadic_algebras.md)

$\langle 2,0,2,0,1,1\rangle$
  *[Boolean algebras with two unary operations](boolean_algebras_with_two_unary_operations.md)
    *[Boolean algebras with two unary operators](boolean_algebras_with_two_unary_operators.md)
      *[Tense algebras](tense_algebras.md)

$\langle 2,0,2,0,1,2\rangle$
  *[Boolean algebras with a binary operation](boolean_algebras_with_a_binary_operations.md)
    *[Boolean algebras with a binary operator](boolean_algebras_with_a_binary_operators.md)
      *[Boolean semigroups](boolean_semigroups.md)
        *[Commutative Boolean semigroups](commutative_boolean_semigroups.md)
          *[Boolean semilattices](boolean_semilattices.md)

$\langle 2,0,2,0,1,2,0\rangle$
  *[Boolean monoids](boolean_monoids.md)
    *[Commutative Boolean monoids](commutative_boolean_monoids.md)
      *[Symmetric relation algebras](symmetric_relation_algebras.md)

$\langle 2,0,2,0,1,2,1,0\rangle$
  *[Nonassociative relation algebras](nonassociative_relation_algebras.md)
    *[Weakly associative relation algebras](weakly_associative_relation_algebras.md)
      *[Semiassociative relation algebras](semiassociative_relation_algebras.md)
        *[Relation algebras](relation_algebras.md)
          *[Representable relation algebras](representable_relation_algebras.md)
            *[Group relation algebras](group_relation_algebras.md)
              *[Abelian group relation algebras](abelian_group_relation_algebras.md)

$\langle 2,0,2,0,1,2,0,2,2\rangle$
  *[Sequential algebras](sequential_algebras.md)
    *[Representable sequential algebras](representable_sequential_algebras.md)

$\langle 2,0,2,0,1,\ldots\rangle$
  *[Boolean algebras with additional operations](boolean_algebras_with_additional_operations.md)
    *[Boolean algebras with operators](boolean_algebras_with_operators.md)
      *[Boolean modules over a relation algebra](boolean_modules_over_a_relation_algebras.md)
      *[Cylindric algebras of dimension n](cylindric_algebras_of_dimension_ns.md)
        *[Representable cylindric algebras of dimension n](representable_cylindric_algebras_of_dimension_ns.md)

$\langle 2,0,2,0,\ldots\rangle$
  *[Heyting algebras](heyting_algebras.md)

$\langle 2,0,2,0,\ldots\rangle$
  *[Bounded lattices with additional operations](bounded_lattices_with_additional_operations.md)
    *[Bounded distributive lattices with additional operations](bounded_distributive_lattices_with_additional_operations.md)
      *[Bounded distributive lattices with operators](bounded_distributive_lattices_with_operators.md)
    *[Bounded lattices with operators](bounded_lattices_with_operators.md)

$\langle 2,2,2\rangle$
  *[Quasigroups](quasigroups.md)

$\langle 2,2,2,0\rangle$
  *[Loops](loops.md)
  *[BCK-lattices](bck-lattices.md)
  *[Brouwerian lattices](brouwerian_lattices.md)

$\langle 2,2,2,1,0\rangle$
  *[Lattice-ordered groups](lattice-ordered_groups.md)
    *[Abelian lattice-ordered groups](abelian_lattice-ordered_groups.md)

$\langle 2,2,2,0,2\rangle$
  *[Commutative residuated lattices](commutative_residuated_lattices.md)
    *[Commutative distributive residuated lattices](commutative_distributive_residuated_lattices.md)
      *[Commutative generalized BL-algebras](commutative_generalized_bl-algebras.md)
        *[Commutative generalized MV-algebras](commutative_generalized_mv-algebras.md)

$\langle 2,2,2,0,2,2\rangle$
  *[Residuated lattices](residuated_lattices.md)
    *[Cancellative residuated lattices](cancellative_residuated_lattices.md)
    *[Distributive residuated lattices](distributive_residuated_lattices.md)
      *[Generalized BL-algebras](generalized_bl-algebras.md)
        *[Generalized MV-algebras](generalized_mv-algebras.md)

$\langle 2,0,2,0,2,2\rangle$
  *[Basic logic algebras](basic_logic_algebras.md)

$\langle 2,0,2,0,2,0,2\rangle$
  *[FLe-algebras](fle-algebras.md)
    *[FLec-algebras](flec-algebras.md)
    *[FLew-algebras](flew-algebras.md)

$\langle 2,0,2,0,2,0,2,2\rangle$
  *[FL-algebras](fl-algebras.md)
    *[FLc-algebras](flc-algebras.md)
    *[FLw-algebras](flw-algebras.md)

$\langle 2,0,2,0,1,2,2\rangle$
  *[Action algebras](action_algebras.md)

$\langle 2,2,0,2,0,1,2,2\rangle$
  *[Action lattices](action_lattices.md)
