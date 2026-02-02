# Command: /blockchain-research:audit-behavior-gap

Orchestrates a structured gap analysis using the research-gap-analysis skill waypoints.

Execution flow:
1. Determine mode: "Rapid analysis or deep specification?" 
2. If rapid: Guide through waypoints 01→02→03 only
3. If deep: Guide through all 5 waypoints with strict sequencing
4. After completion: Output consolidated gap analysis report referencing all waypoints

Critical rule: NEVER allow skipping waypoints. Enforce sequential progression.
