# Command: /blockchain-research:extend-erc6551

Orchestrates ERC-6551 extension design using security-review-erc6551 skill waypoints.

Execution flow:
1. Require precise behavior invariant: "What MUST be enforced? (e.g., X before Y)"
2. Guide through waypoints 01→02→03 to establish security boundaries
3. Only after waypoint 03: Propose extension interface
4. Final output: Composable extension spec with migration path

Critical rule: NEVER propose interface before ownership/attribution boundary is clarified (waypoint 01).
