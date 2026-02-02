# Skill: causal-proof-design

For causal behavioral proofs and nonce-ordered structures:
- Causality must be cryptographically enforced, not just informally logged
- Nonce or sequence ordering must be unforgeable and verifiable off-chain
- Proofs should be atomic: either fully valid or rejected

1. Specify the event ingestion flow, starting from the on-chain trigger through the behavioral event to the final proof generation.
2. Define the verification interface, including all required inputs, expected outputs, and maintenance of critical invariants.
3. Outline failure modes, focusing on vulnerabilities such as nonce reuse, reordering attacks, storage bloat, and potential denial-of-service vectors.
4. Propose minimal test vectors, utilizing three to five events with explicit causal dependencies to verify logic.
