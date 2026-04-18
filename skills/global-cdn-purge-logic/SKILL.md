---
name: global-cdn-purge-logic
description: Manage complex global content caching and invalidation strategies.
---

# Global Content Delivery (CDN) Purge Logic

This skill focuses on the balance between high-cache-hit rates and fresh data delivery.

## Instructions

1. Set up 'Surrogate Keys' or 'Tags' for granular cache invalidation.
2. Implement 'Atomic Purging' to ensure related assets are cleared together.
3. Optimize Cache-Control headers (max-age, s-maxage, stale-while-revalidate).
4. Monitor CDN logs to identify 'Cache Misses' and optimize hit rates.
5. Design failover patterns between multiple CDN providers.

## Examples

- "Configure a Cloudflare cache purge trigger for a specific blog post update."
- "Optimize cache headers for a global e-commerce product catalog."