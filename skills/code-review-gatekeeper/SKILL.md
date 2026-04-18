---
name: code-review-gatekeeper
description: Implement automated code quality and security gates for every PR.
---

# Code Review & Quality Gatekeeper

This skill focuses on the 'Standard of Excellence', ensuring no low-quality code ever reaches production.

## Instructions

1. Set up linters and formatters (Prettier, ESLint) as mandatory CI checks.
2. Enforce minimum 'Test Coverage' percentages (Ex. 80%).
3. Use AI to perform a first-pass review of logic and potential bugs.
4. Block merges if security scans (SAST) find high-severity issues.
5. Automate 'Vibe' checks for variable naming and architectural consistency.

## Examples

- "Configure a GitHub Action that blocks PRs with less than 90% test coverage."
- "Audit this PR: find 3 logical bugs and suggest better variable names."