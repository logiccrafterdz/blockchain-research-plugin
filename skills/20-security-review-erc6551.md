# Skill: security-review-erc6551

When reviewing ERC-6551-based designs and extensions:

Critical checks:
- Distinguish token-bound account ownership from behavioral attribution.
- Check whether causal history can be manipulated via proxies, account migration, or upgradeability patterns.
- Analyze gas costs of proof generation vs. verification and their impact on UX.

Always ask: which behaviors are being attested, who can forge them, and under what assumptions?
