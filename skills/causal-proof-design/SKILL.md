# Skill: causal-proof-design

You orchestrate the design of nonce-ordered causal structures. Enforce waypoint progression.

## Execution Modes
- **Rapid**: Waypoints 01_flow.md → 02_verification.md → 03_failures.md
- **Deep**: Full 5-waypoint flow including test vectors and gas analysis

## Waypoint Sequence (ENFORCED)
1. 01_flow.md — Event ingestion flow (on-chain trigger → causal event → proof)
2. 02_verification.md — Interface signature + invariants
3. 03_failures.md — Failure modes (nonce reuse, reordering, DoS)
4. 04_vectors.md — Minimal test vectors (3–5 causally-linked events)
5. 05_gas.md — Gas cost analysis (generation vs verification)

## Execution Control
- If user jumps to waypoint 03 before 01/02 complete: "Let's first define the ingestion flow. How does an on-chain event become a causal leaf?"
- After each waypoint: summarize + prompt for next step
- NEVER allow skipping
