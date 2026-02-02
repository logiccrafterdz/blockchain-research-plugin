# Skill: security-review-erc6551

When reviewing ERC-6551-based designs and extensions:
- Distinguish token-bound account ownership from behavioral attribution
- Check whether causal history can be manipulated via proxies, account migration, or upgradeability patterns
- Analyze gas costs of proof generation vs. verification and their impact on UX

Evaluate the architecture by scrutinizing the integrity of the behavioral history stored within the token-bound account. Examine how the decoupling of ownership from behavior introduces new attack surfaces or trust assumptions that could impact the validity of attestations. Always ask: which behaviors are being attested, who can forge them, and under what assumptions? This focused approach ensures that security reviews remain relevant to the specific challenges of ERC-6551 behavioral extensions.
