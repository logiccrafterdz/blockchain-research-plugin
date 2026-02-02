# Skill: research-gap-analysis

## EXECUTION CONTROL - READ THIS FIRST
**CRITICAL: This orchestrator follows a SIMPLE START approach:**
1. **Ask user to confirm the research topic** - Wait for explicit confirmation.
2. **Jump directly into Full Workflow Logic** - Automatically run subtasks sequentially.
3. **Do NOT pre-read sub-steps** - Load logic on-demand only when needed.

## Overview
This skill guides the formalization of unaddressed gaps in blockchain identity and behavior-attestation systems using a **modular, waypoint-based architecture**.

## Workflow Modes
**  Rapid Analysis Mode (Steps 1-2):**
1. **Problem Boundary Definition** - Scope the gap precisely (what it is vs what it isn't).
2. **Prior Art Scan** - Identify why existing ERC/EIPs fail to solve this specific gap.

** Deep Specification Mode (Steps 1-4):**
3. **Primitive Design** - Propose a minimal cryptographic/protocol primitive.
4. **Validation Vectors** - Define concrete test cases (valid/invalid sequences).

## Waypoint State Management
This skill uses **Waypoints** to store state between steps.
- **`01_boundary.md`**: Stores the defined problem scope and boundary analysis.
- **`02_prior_art.md`**: Stores the analysis of existing standards and their limitations.
- **`03_design_spec.md`**: Stores the proposed primitive and validation vectors.

## Execution Logic
1. **Step 1: Boundary** -> Ask user for the core problem. Generate `01_boundary.md`.
2. **Step 2: Prior Art** -> Read `01_boundary.md`. Search/Recall standards. Generate `02_prior_art.md`.
3. **Step 3: Design** -> Read previous waypoints. Propose solution. Generate `03_design_spec.md`.

Always ground analysis in existing ERC/EIP standards.
