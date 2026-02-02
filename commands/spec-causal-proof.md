# Command: /blockchain-research:spec-causal-proof

Use when designing a new causal proof or behavioral attestation scheme.

Steps:
1. Ask the user for: event type, ordering constraints, and verification context (on-chain, off-chain, or hybrid).
2. Produce a spec with:
   - Data structure (tree layout, node contents, ordering field).
   - Ingestion protocol (how events enter the stream and are committed).
   - Verification function signature and pseudocode.
   - 2–3 minimal test cases (valid sequence, invalid reordering, invalid omission).
3. Explicitly call out trust assumptions (sequencers, oracles, signers).
