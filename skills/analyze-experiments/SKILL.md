---
name: analyze-experiments
description: "Analyzes experiment data to extract key metrics and performance indicators"
allowed-tools: Read Write
---

# Analyze Experiments

## Instructions

1. Parse the provided experiment dataset.
   Each experiment may include:
   - parameters (hyperparameters / configurations)
   - metrics (accuracy, loss, etc.)
   - timestamps or run identifiers

2. Extract key metrics:
   - best performing experiment
   - worst performing experiment
   - average performance

3. Identify:
   - parameter variations
   - metric differences across runs

4. Output:
   - summary of all experiments
   - top 3 best runs
   - key differences between high and low performers