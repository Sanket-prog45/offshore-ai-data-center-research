# Reproducibility Guide

## Goal

A reader should be able to trace each modeled result from input assumptions to the final figure or table.

## Workflow

1. Review `data/scenario_inputs_template.csv`.
2. Review criterion definitions and weights in `analysis/decision_model_template.csv`.
3. Apply the normalization rules described in the manuscript.
4. Calculate the weighted composite score for each scenario.
5. Run alternative priority-weight profiles.
6. Record how often each scenario ranks first.
7. Run one-at-a-time perturbations to identify high-sensitivity assumptions.
8. Generate figures from the resulting tables.

## Evidence hierarchy

The manuscript separates:
- published empirical evidence
- modeled scenario inputs
- analytical judgments

Do not merge these categories.

## Validation priorities

Future empirical work should prioritize thermal performance, lifecycle cost, corrosion/biofouling, marine heat discharge, maintenance logistics, and local infrastructure conditions.
