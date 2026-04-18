---
name: async-task-queue-manager
description: Manage high-volume background processing using message queues.
---

# Asynchronous Task Queue Management

This skill focuses on moving heavy work (emails, reports, video processing) out of the main request-response cycle.

## Instructions

1. Select a message broker (Redis/BullMQ, RabbitMQ, SQS).
2. Design 'Workers' that are stateless and horizontally scalable.
3. Implement 'Dead Letter Queues' (DLQ) for failing tasks.
4. Set up task prioritization and delayed execution logic.
5. Monitor queue depth and worker throughput to prevent lag.

## Examples

- "Scale my image processing workers to handle a sudden burst of 100k uploads."
- "Set up a retry policy for failed webhook deliveries in BullMQ."