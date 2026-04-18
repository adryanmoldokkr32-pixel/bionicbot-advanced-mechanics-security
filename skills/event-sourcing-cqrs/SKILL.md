---
name: event-sourcing-cqrs
description: Design systems that use event logs as the source of truth.
---

# Event Sourcing & CQRS Architect

This skill focuses on high-audit, high-performance architectures where every change is recorded as an immutable event.

## Instructions

1. Define 'Command' vs 'Query' models (CQRS separation).
2. Design an immutable 'Event Store' to capture every state change.
3. Implement 'Projections' to build optimized read-models from the event log.
4. Handle 'Event Versioning' to allow for schema evolution over time.
5. Use 'Snapshots' to improve performance when rebuilding current state.

## Examples

- "Design an event-sourced banking system where every transaction is an event."
- "Create a read-optimized projection for a complex social media feed."