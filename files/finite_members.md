# Finite members (format)

This page describes how the **Finite members** section of a class page records the number of finite members of each size. A uniform format keeps the pages readable, makes them easy to extend (adding a new value is a one-line change), and lets the numbers be checked by a script, e.g. against the [OEIS](https://oeis.org).

## Format

```
## Finite members

Number of members with $n$ elements, counted up to isomorphism.

| $n$ | members | subdirectly irreducible |
|--:|--:|--:|
| 1 | 1 | 0 |
| 2 | 1 | 1 |
| 3 | 2 | 1 |
| 4 | 5 | 2 |

Sequence: [OEIS A000000](https://oeis.org/A000000). Source: [Ref2001], computed with Mace4.
```

## Rules

1. **Counting convention.** The first line states what is counted. Use one of
   - *Number of members with $n$ elements, counted up to isomorphism.* (default)
   - *Number of members with $n$ elements, counted up to isomorphism and anti-isomorphism.* (e.g. for semigroups identified with their opposite)
   - *Number of members on a fixed $n$-element set (labelled count).*

   If the count is of something other than the universe size (e.g. number of morphisms of a category), say so here.
2. **One row per size $n$**, in increasing order, starting at $n=1$. Sizes are plain integers.
3. **First column** `members` is always present. Further columns are optional and use these headers when applicable: `subdirectly irreducible`, `simple`, `directly indecomposable`, `linearly ordered`. Columns are right-aligned (`--:`).
4. **Values** are plain decimal integers without separators (no `\,`, commas or spaces), so they can be copied and parsed directly.
   - `0` is written explicitly.
   - A lower bound is written `≥ 97`, optionally followed by a short note in parentheses, e.g. `≥ 97 (out of 104 candidates)`.
   - An unknown value in an optional column is left empty.
5. **Unknown sizes are omitted**, not listed with empty cells. The table ends at the largest known size; values for larger $n$ are simply added as new rows.
6. **Sparse classes.** If members exist only for some sizes (e.g. $n=2^k$), list only those sizes and add a sentence such as *For all other $n$ the number is 0.*
7. **Closed forms.** If a formula is known, state it in a sentence before the table (e.g. *The number equals the number of multiplicative partitions of $n$.*); the table still lists the first values.
8. **Sources** follow the table on one line:
   - OEIS: `[OEIS A000000](https://oeis.org/A000000)`; if the OEIS index is shifted relative to $n$, say so (e.g. *the value for $n$ is a(n+1)*).
   - References by their key in the References section, and/or the method used, e.g. *computed with Mace4*.
   - Links to lists of the finite members (e.g. the interactive *Finite ...* pages) go here as well.
9. Classes whose finite members are trivial or easily described (e.g. *only the one-element algebra*) may use a sentence instead of a table.
