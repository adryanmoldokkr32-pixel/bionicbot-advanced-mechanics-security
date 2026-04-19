---
name: chaos-mesh-orchestrator
description: Intentionally inject failures into the system to test and improve resilience.
---

# Chaos Mesh Orchestrator

This skill enables bionicbot to act as a 'Security Destroyer', purposefully killing servers, dropping database connections, and spiking latency to see how the system recovers.

## Instructions
1. Schedule 'Chaos Days' where random components are disabled.
2. Monitor the 'Self-Healing' response time of each module.
3. Identify 'Cascade Failures' where one small bug crashes the entire platform.
4. Propose architectural changes to harden the points of failure identified during chaos.

## Examples
- "Inject 50% packet loss into our 'Market Sentinel' to test its retry logic."