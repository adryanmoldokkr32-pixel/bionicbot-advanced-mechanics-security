---
name: identity-aware-proxy
description: Enforce access control based on user identity and device health.
---

# Identity-Aware Proxy (IAP)

This skill secures internal tools by verifying both the user and the specific device they are using (Zero-Trust).

## Instructions
1. Integrate with OIDC/SAML providers (Okta, Auth0).
2. Verify device security posture (e.g., iPhone 15 with latest iOS).
3. Implement context-aware access rules (e.g., No access from unknown IPs).
4. Log and audit all successful and failed access attempts.

## Examples
- "Secure the BionicSovereign admin dashboard with an Identity-Aware Proxy."