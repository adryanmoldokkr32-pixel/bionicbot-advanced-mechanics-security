---
name: db-sharding-partitioning
description: Scale massive databases by splitting data across multiple instances.
---

# Database Sharding & Partitioning

This skill focuses on 'Horizontal Scaling' of the data layer, handling datasets too large for a single machine.

## Instructions

1. Select a 'Shard Key' that ensures even data distribution.
2. Implement 'Directory-based' or 'Range-based' sharding logic.
3. Design a 'Query Router' to direct requests to the correct shard.
4. Implement 'Table Partitioning' (by Date, ID) within individual shards.
5. Manage cross-shard queries and data re-balancing over time.

## Examples

- "Design a sharding strategy for a chat app with 100 million users."
- "Partition a PostgreSQL 'logs' table by month for faster archiving."