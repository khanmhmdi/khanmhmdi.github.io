---
title: "Experiment 001 — Baseline Prompt Sensitivity"
date: 2026-02-06
model: GPT-4.x
task: Reasoning Robustness
tags: [prompting, evaluation, rlhf]
status: completed
---

## Objective
Evaluate sensitivity of model reasoning to minimal prompt perturbations.

## Hypothesis
Minor syntactic variations cause non-trivial reasoning drift.

## Setup
- Model: GPT‑4.x
- Temperature: 0.7
- Task type: Logical reasoning
- Evaluation: Qualitative + error categorization

## Procedure
1. Construct baseline prompt
2. Generate perturbations
3. Compare outputs manually

## Results
~35% of outputs showed reasoning divergence.

## Failure Modes
- Assumption injection
- Step omission

## Notes
Prompt canonicalization may improve stability.

## Next Steps
- Test with lower temperature
- Apply instruction hierarchy constraints
