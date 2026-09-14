# Fresh recovery audit — 2026-09-14

Recovered 11 original source modules containing 104 named theorem/lemma declarations, including private lemmas and finite specializations. The generated root import module is counted separately in the machine-readable inventory. This is a lexical count, not a count of independent mathematical results.

Sorry/admit tokens outside comments/strings: 0. Explicit axiom declarations: 0. See [per-file declarations and SHA-256 hashes](audit/source-inventory.json). `native_decide` occurs in the historical sources; its presence should be distinguished from a small-kernel proof term when assessing theorem authority.

The first isolated compiler attempt, preserved in [compiler-attempt.json](audit/compiler-attempt.json), could not build because Mathlib was absent from that environment. That historical attempt is now superseded for **build status** by a clean GitHub Actions replay on 2026-09-14: the pinned Lean 4.29.1 toolchain installed, `lake update` completed, the Mathlib cache was fetched, and `lake build` completed successfully.

Accordingly, the recovered project is now **BUILD VERIFIED** in the pinned CI environment. This does not imply that the 104 lexical declarations are 104 independent theorems, does not remove the source's use of `native_decide`, and does not close the general first-cover permutation/bijection theorem.

The old 74-theorem / 8-module headline remains superseded by the explicit 11-module source inventory.
