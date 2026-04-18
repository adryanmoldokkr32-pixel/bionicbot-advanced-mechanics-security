---
name: edge-computing-optimizer
description: Optimize latency by moving logic and data to the network edge.
---

# Edge Computing Optimizer

This skill focuses on using Cloudflare Workers, Vercel Edge, or Lambda@Edge to run code closest to the user.

## Instructions

1. Identify logic that can run without a central database (Geo-detection, Auth checks).
2. Use Edge KV or Durable Objects for fast, low-latency data access.
3. Implement 'Stale-While-Revalidate' (SWR) patterns at the edge.
4. Optimize asset delivery based on the user's device and connection.
5. Handle edge-to-origin failover scenarios.

## Examples

- "Rewrite this auth-check to run on Cloudflare Workers for 50ms faster response."
- "Implement A/B testing logic entirely at the network edge."