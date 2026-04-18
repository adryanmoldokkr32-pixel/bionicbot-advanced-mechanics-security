---
name: automated-knowledge-graph
description: Build and maintain a live knowledge graph of project data and learnings.
---

# Automated Knowledge Graph Engine

This skill focuses on 'Institutional Memory', ensuring the team (and the AI) never forgets an important detail.

## Instructions

1. Extract 'Entities' (Users, Projects, Tech) from chat and documents.
2. Map 'Relationships' (Project X uses Tech Y, User Z is expert in A).
3. Use Mermaid or specialized DBs (Neo4j) to store the graph.
4. Periodically update the graph with new learnings or project shifts.
5. Use the graph to provide deep context for complex queries.

## Examples

- "Update our project knowledge graph with the new tech stack decisions."
- "Show me a map of how our 5 microservices depend on each other."