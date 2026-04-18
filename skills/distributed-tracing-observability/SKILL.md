---
name: distributed-tracing-observability
description: Implement and analyze end-to-end distributed tracing across microservices.
---

# Distributed Tracing & Observability

This skill focuses on the ability to track a single user request as it travels through multiple services, identifying bottlenecks and failures in real-time.

## Instructions

1. Instrument services using OpenTelemetry SDKs.
2. Configure exporters to send trace data to backends (Jaeger, Honeycomb, Datadog).
3. Implement span-context propagation across HTTP and Message Broker headers.
4. Analyze trace graphs to identify high-latency spans ('p99 latency').
5. Set up dashboards for Service Level Objectives (SLOs) and Error Budgets.

## Examples

- "Trace why a checkout request takes 5 seconds and find the bottleneck service."
- "Set up a Honeycomb dashboard for my distributed microservices architecture."