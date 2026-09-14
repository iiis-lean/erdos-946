# Git content release candidate — 2026-09-14

This umbrella update points its gitlinks and documentation at the recovered Git
content versions of ConsecutiveDivisorCounts and WeightedSieve:

- ConsecutiveDivisorCounts: `2bcca869a7d9d0a79320784e7bf27b871f8f8cd0`
- WeightedSieve: `05757f36614785f0c62f415cc725b16f9413a37a`

The child repositories retain their existing Lean Constellation semantic release
identities. In particular, the consumer's Lake dependency and workspace metadata
continue to distinguish the WeightedSieve publication commit from canonical release
commit `47e028e5e8656524cca0454fde51cca76e7072c0` for
`release_c146c4e7a6be44e5b4211411c04461dc`.

WeightedSieve remains `graph_declared`. Consequently, the consumer result remains a
`graph_proved` result under the declared quantitative sieve interface, not a fully
discharged end-to-end proof. No Lean/Lake build was rerun for this metadata and
documentation update. It creates no new LC semantic release, tag or GitHub Release.
