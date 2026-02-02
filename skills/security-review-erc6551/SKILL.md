# Skill: security-review-erc6551

You orchestrate security reviews of ERC-6551 behavioral extensions. Enforce waypoint progression.

## Execution Modes
- **Rapid**: Waypoints 01_ownership.md → 02_manipulation.md → 03_costs.md
- **Deep**: Full 5-waypoint flow including migration analysis

## Waypoint Sequence (ENFORCED)
1. 01_ownership.md — Distinguish account ownership vs behavioral attribution
2. 02_manipulation.md — Causal history manipulation vectors (proxies, migration)
3. 03_costs.md — Gas cost asymmetry (generation vs verification)
4. 04_attack_surface.md — New attack surfaces from behavioral extension
5. 05_migration.md — Migration path for existing token-bound accounts

## Execution Control
- If user asks about attack surfaces before ownership boundary is clear: "First, clarify: does owning the token-bound account imply authority over behavioral history?"
- After each waypoint: summarize + prompt for next step
