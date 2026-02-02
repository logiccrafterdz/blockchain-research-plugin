# Skill: causal-proof-design

For causal behavioral proofs and nonce-ordered structures:

Core principles:
- Causality must be cryptographically enforced, not just informally logged.
- Nonce or sequence ordering must be unforgeable and verifiable off-chain.
- Proofs should be atomic: either fully valid or rejected.

When designing:
1. Specify the event ingestion flow (on-chain trigger → behavioral event → proof generation).
2. Define the verification interface (inputs, outputs, invariants).
3. Outline failure modes: nonce reuse, reordering attacks, storage bloat, DoS.
4. Propose minimal test vectors (e.g., 3–5 events with explicit causal dependencies).
