# Vorgentia Research Post-Review Release Gates

Release: `vorgentia-research-site-2026.08.16`

Code Review status: COMPLETE

| Gate | Requirement | Current status | Evidence required |
|---|---|---:|---|
| EM-01 | Intended Conveyance Response identified, captured and sealed | BLOCKED | Sealed response, version, UTC time and digest |
| EM-02 | Exact source and corresponding application sealed | PREPARED | Frozen `index.html`, size and SHA-256 recorded; formal sealed record pending |
| EM-03 | Blind toolset response captured and sealed | BLOCKED | Clean-context response and digest |
| EM-04 | Pre-sealed semantic comparison completed | BLOCKED | Comparison record and evidence matrix |
| EM-05 | Emergence score is 75–100% | BLOCKED | Final non-placeholder score and classification |
| EM-06 | Signing artifact is byte-identical to Emergence artifact | BLOCKED | Matching SHA-256 digest |
| CS-06 | Dedicated Ed25519 key initialized under keyholder custody | BLOCKED | Public fingerprint; private key remains outside package |
| CS-07 | Signed Git commit verified | BLOCKED | Full commit SHA and verified signature |
| CS-08 | Release manifest signed | BLOCKED | Detached signature and public verification key |
| CS-09 | Signature and hashes independently verified | BLOCKED | Verification record |
| CS-10 | Signed annotated release tag verified | BLOCKED | Tag verification record |
| CS-11 | Deployed artifact is byte-identical and HTTPS enforced | BLOCKED | Deployed digest and HTTPS verification |
| CS-12 | Release closed and announcement boundary observed | BLOCKED | Append-only closure record; no announcement before 2026-08-16 |

No private signing action may begin until EM-01 through EM-06 are complete.

