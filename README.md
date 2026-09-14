# Prime-gap admissibility

Recovered original Lean sources for finite residue admissibility counting. No asymptotic prime-gap theorem is claimed. The universal permutation/bijection boundary remains open in this packet.

The eleven source modules are copied byte-for-byte from `EG203-KILLSHOT-ROUND-044-SOURCE-PREDICATE-AUDIT.zip`. See [PROVENANCE.md](PROVENANCE.md), [fresh audit](AUDIT.md), and [historical subject account](archive/README.md). The old headline of 74 theorems / 8 modules is not adopted.

Build with Lean/mathlib 4.29.1:

```sh
lake update
lake exe cache get
lake build
```

**Build status:** this recovery includes a fresh source count and compiler attempt, but a clean mathlib build has not been certified; see the audit receipt.
