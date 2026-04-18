---
name: traffic-shaping-rate-limiting
description: Implement advanced traffic control to protect services from overload.
---

# Rate Limiting & Traffic Shaping

This skill focuses on 'Leaky Bucket' and 'Token Bucket' algorithms to ensure system stability under heavy load.

## Instructions

1. Implement global vs per-IP rate limiting.
2. Use 'Traffic Shaping' to smooth out bursty traffic patterns.
3. Design 'Graceful Degradation' (e.g., disable non-essential features during load).
4. Implement 'Load Shedding' to reject requests when resources are critical.
5. Provide clear feedback to users/clients during throttling events.

## Examples

- "Protect my search API from being scraped by a single aggressive bot."
- "Implement load shedding logic that prioritizes 'Checkout' over 'Search'."