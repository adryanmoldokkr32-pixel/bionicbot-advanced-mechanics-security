---
name: chaos-engineering-tester
description: Test system resilience by intentionally injecting failures.
---

# Load Testing & Chaos Engineering

This skill focuses on 'Breaking things on purpose' to ensure they don't break in production when it matters.

## Instructions

1. Run high-volume load tests using k6, Locust, or JMeter.
2. Inject failures: Kill random containers, drop network packets, slow down DBs.
3. Measure 'Recovery Time Objective' (RTO) and 'Recovery Point Objective' (RPO).
4. Monitor how the 'Circuit Breakers' and 'Auto-scalers' react to stress.
5. Document 'Weak Points' and prioritize hardening tasks.

## Examples

- "Run a k6 test to see if our site can handle 50k concurrent users."
- "What happens to the frontend if the 'Search' microservice is down?"