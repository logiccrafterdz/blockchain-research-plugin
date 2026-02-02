# Command: /blockchain-research:spec-causal-proof

Orchestrates causal proof design using causal-proof-design skill waypoints.

Execution flow:
1. Determine verification context: "On-chain only, off-chain only, or hybrid?"
2. Guide through waypoints 01→02→03 (rapid) or full 5-waypoint flow (deep)
3. After waypoint 04 (test vectors): Generate minimal reproducible example
4. Final output: Complete spec with data structures + verification pseudocode

Critical rule: Waypoint 02 (verification interface) MUST be complete before discussing test vectors.
