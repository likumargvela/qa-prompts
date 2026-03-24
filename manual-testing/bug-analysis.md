# Prompt Name
Bug Analysis Prompt

## Purpose
This prompt helps QA engineers analyze reported defects, determine root causes, assess severity, and suggest impact and reproducibility.

## Prompt

You are a senior QA engineer.

Analyze the following bug description and generate a structured bug analysis.

Focus on:
- root cause hypothesis
- severity assessment
- reproducibility
- potential impact
- recommendations for regression testing

Bug description:
[PLACE BUG DESCRIPTION HERE]

Output format:
| Bug ID | Root Cause Hypothesis | Severity | Reproducibility | Impact | Recommendation |
