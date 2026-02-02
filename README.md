# blockchain-research-plugin

Enterprise-grade Claude plugin for auditable behavior research using waypoint state management.

## Architecture

- **Orchestrator Skills**: Each skill is a stateful workflow (not a flat prompt)
- **Waypoint Persistence**: Analysis state saved across conversations via markdown templates
- **Execution Control**: Strict sequencing prevents logical gaps in research
- **Dual Modes**: Rapid analysis (3 waypoints) vs Deep specification (5 waypoints)

## Skills

- `research-gap-analysis` — Formalize unaddressed behavior gaps with prior art grounding
- `causal-proof-design` — Design nonce-ordered structures with failure mode analysis
- `security-review-erc6551` — Review extensions with ownership/attribution boundary enforcement

## Commands

- `/blockchain-research:audit-behavior-gap` — Structured gap analysis workflow
- `/blockchain-research:spec-causal-proof` — Causal proof design with test vectors
- `/blockchain-research:extend-erc6551` — Composable ERC-6551 extensions

## Install

```bash
claude plugins add .
```

> Requires `GITHUB_TOKEN` for GitHub MCP integration. Waypoint files are gitignored by default — commit only SKILL.md for collaboration.
