---
name: secret-rotation-vault
description: Securely manage and automatically rotate API keys, passwords, and tokens.
---

# Secret Rotation & Vault Management

This skill ensures that even if a secret is stolen, it is only valid for a short time.

## Instructions

1. Integrate with Vault managers (HashiCorp Vault, AWS Secrets Manager).
2. Set up automated rotation for DB passwords and third-party API keys.
3. Use 'Dynamic Secrets' that are generated per-request and expire quickly.
4. Audit access logs for every time a secret is retrieved.
5. Implement 'Emergency Revocation' (The 'Red Button' to kill all keys).

## Examples

- "Set up an AWS Lambda to rotate my RDS password every 30 days."
- "How do I provide a 'One-time' use API key to a specific agent?"