---
name: service-mesh-coordinator
description: Manage service-to-service communication, security, and metrics using a Service Mesh.
---

# Service Mesh Coordinator

This skill manages the 'Sidecar' proxy layer (Istio, Linkerd) to handle mTLS, retries, and observability automatically.

## Instructions

1. Configure sidecar proxies for all service deployments.
2. Implement Mutual TLS (mTLS) for secure internal communication.
3. Set up 'Traffic Splitting' for A/B testing and Canary releases.
4. Define 'Timeout' and 'Retry' policies at the mesh level.
5. Use mesh metrics to build a global service dependency map.

## Examples

- "Enforce mTLS across all microservices in my Kubernetes cluster."
- "Route 10% of traffic to a new service version using Istio."