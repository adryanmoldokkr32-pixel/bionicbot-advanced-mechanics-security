---
name: circuit-breaker-resilience
description: Implement resilience patterns to prevent cascading failures in distributed systems.
---

# Circuit Breaker & Resilience Patterns

This skill focuses on the 'Self-Healing' nature of a system, ensuring it doesn't crash when one part is struggling.

## Instructions

1. Implement Circuit Breakers for all external service calls (e.g., using Hystrix or Resilence4j patterns).
2. Define thresholds for 'Open', 'Closed', and 'Half-Open' states.
3. Design 'Fallback' mechanisms (e.g., show cached data if the DB is slow).
4. Implement 'Bulkheading' to isolate failures to a single component.
5. Set up 'Retry' logic with exponential backoff and jitter.

## Examples

- "Protect my app from a slow Payment API using a circuit breaker."
- "Implement a fallback strategy for our recommendation engine."