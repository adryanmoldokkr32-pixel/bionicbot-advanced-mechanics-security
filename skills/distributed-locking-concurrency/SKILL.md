---
name: distributed-locking-concurrency
description: Manage shared resources safely in a scaled, multi-instance environment.
---

# Distributed Locking & Concurrency

This skill prevents data corruption and race conditions when multiple server instances try to modify the same resource simultaneously.

## Instructions

1. Use distributed lock managers like Redis (Redlock) or ZooKeeper.
2. Implement 'Leasing' to ensure locks are released if a process crashes.
3. Use Optimistic Concurrency Control (OCC) with version numbers or timestamps.
4. Design 'Idempotent' operations to safely retry failed requests.
5. Audit code for shared-state bottlenecks that limit horizontal scaling.

## Examples

- "Prevent two users from booking the same seat using a Redis distributed lock."
- "Make this 'Increment Balance' function idempotent for safe retries."