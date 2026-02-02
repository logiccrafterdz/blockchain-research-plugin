# blockchain-research-plugin

Claude plugin for applied blockchain research: formalizing behavior gaps, designing causal proofs, and extending standards like ERC-6551.

## Philosophy

- **Minimal scope**: Only research workflows — no generic task management.
- **Standards-first**: Always ground proposals in existing ERCs/EIPs before extending.
- **Atomic proofs**: Causal claims must be cryptographically verifiable, not just logged.

## Workflows supported

- `/blockchain-research:audit-behavior-gap` — Formalize unaddressed behavior attestation problems.
- `/blockchain-research:spec-causal-proof` — Design nonce-ordered causal structures with test vectors.
- `/blockchain-research:extend-erc6551` — Propose composable extensions without breaking compatibility.

## Install (local development)

```bash
git clone https://github.com/LogicCrafterDz/blockchain-research-plugin.git
cd blockchain-research-plugin
claude plugins add .
```

> Requires `GITHUB_TOKEN` in environment for GitHub MCP integration.

## Architecture notes

- No external APIs beyond GitHub MCP.
- Skills and commands are stateless — no database or persistent storage required.
- Designed for longevity: independent of Comet/Antigravity changes.
