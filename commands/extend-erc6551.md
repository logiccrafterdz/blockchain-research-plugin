# Command: /blockchain-research:extend-erc6551

Use when proposing an ERC-6551-compatible extension for behavioral proofs.

Steps:
1. Require: the specific behavior or invariant to be enforced (e.g., "agent must execute X before Y under condition Z").
2. Output:
   - Extension interface (new functions/events; avoid breaking changes).
   - How it composes with standard ERC-6551 flows.
   - Security implications and new attack surfaces.
   - Migration path or compatibility notes for existing token-bound accounts.
3. Emphasize composability over replacement.
