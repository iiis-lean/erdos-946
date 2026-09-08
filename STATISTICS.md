# Formalization statistics

Current active declarations are counted once; historical revisions and Lean/Mathlib dependency files are excluded.

| Metric | ConsecutiveDivisorCounts | WeightedSieve | Total |
| --- | ---: | ---: | ---: |
| Declarations | 56 | 28 | 84 |
| Public declarations | 13 | 26 | 39 |
| Private declarations | 43 | 2 | 45 |
| Main exports | 1 | 26 | 27 |
| Owned Lean files | 66 | 54 | 120 |
| Physical lines | 12,543 | 809 | 13,352 |
| Code lines | 10,973 | 349 | 11,322 |
| Comment-only lines | 1,226 | 328 | 1,554 |
| Blank lines | 344 | 132 | 476 |

Lean comments are excluded while preserving string literals; mixed code/comment lines count as code. Nonblank lines containing only Lean comments are comment-only. Imports count as code. These three line categories partition the physical lines; generated declaration docstrings are included in the comment count.

## Consumer nodes

| Content node | Lean files | Physical lines | Code lines |
| --- | ---: | ---: | ---: |
| (import aggregators) | 4 | 15 | 4 |
| Main.FiniteSieveSelection | 16 | 938 | 715 |
| Main.KeyLemma | 26 | 5,508 | 4,891 |
| Main.ConsecutiveEqualDivisorCounts | 20 | 6,082 | 5,363 |

## Proof boundary

The consumer has 48 proved theorems and eight definitions (all 56 declarations committed). The provider has nine declared theorems, 17 definitions and two structures (all 28 declarations committed). Consumer graph_proved is conditional on its declared provider contract.

The consumer references 11 provider interfaces from 14 private declarations: 41 Statement uses and 43 Proof uses. Ten used interfaces have proved availability; SevenAffineFormsQuantitativeAlmostPrime remains declared.

Machine-readable per-file counts and declaration categories: [statistics.json](statistics.json). Exact public commit and local Release mapping: [workspace.json](workspace.json).
