<!-- solve-problem:4728206f-71cf-45bb-9d94-cbcc8a42d901 -->
# ALGO-000080: Online Matrix–Vector Multiplication conjecture

A [Tangle Solve problem](https://solve.tangle.tools/problems/4728206f-71cf-45bb-9d94-cbcc8a42d901).

Source verification label: flagged. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000080: Online Matrix–Vector Multiplication conjecture
- **Subfield:** Fine-grained and exact exponential complexity
- **Open:** Determine whether processing \(n\) online Boolean matrix–vector products against a fixed \(n\times n\) matrix requires \(n^{3-o(1)}\) total time, with the preprocessing convention explicitly fixed.
- **Status:** Proposed in 2015; a major foundation of dynamic lower bounds. Each answer must precede the next vector.
- **Type:** theory
- **Why:** Captures the cost of online dependence that offline matrix multiplication can avoid.
- **Key works:** Henzinger, Krinninger, Nanongkai, and Saranurak (2015), *Unifying and Strengthening Hardness for Dynamic Problems via the Online Matrix-Vector Multiplication Conjecture*, arXiv:1504.06148.
- **Related:** Databases—incremental query maintenance.
- **Aliases:** OMv conjecture.
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-gpt6pro-reply-1

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "flags": [
    "citation-mismatch:1504.06148"
  ],
  "id": "ALGO-000080",
  "label": "flagged",
  "origin": "sourced",
  "source_checked_at": "2026-10-11",
  "source_kind": "fleet-census",
  "source_verified": false,
  "triage": "suspect",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/4728206f-71cf-45bb-9d94-cbcc8a42d901?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000080.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000080)
