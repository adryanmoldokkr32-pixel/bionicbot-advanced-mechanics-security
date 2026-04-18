---
name: canary-deployment-orchestrator
description: Manage safe, incremental software releases using Canary and Blue-Green patterns.
---

# Canary & Blue-Green Deployments

This skill focuses on 'Risk Mitigation' during launches, ensuring errors only affect a tiny fraction of users.

## Instructions

1. Set up dual environments (Blue for current, Green for new).
2. Configure traffic routing to send 1%, 5%, 10% of users to 'Green'.
3. Monitor 'Health Metrics' (Error rates, Latency) on the Canary version.
4. Automatically 'Roll Back' if health metrics drop below a threshold.
5. Fully switch traffic to 'Green' only after successful verification.

## Examples

- "Perform a canary release of our new auth service for 5% of traffic."
- "Set up a blue-green deployment strategy for our production API."