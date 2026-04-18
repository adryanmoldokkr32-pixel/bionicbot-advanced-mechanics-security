---
name: sast-dast-analysis
description: Scan source code and running apps for logical security vulnerabilities.
---

# Static & Dynamic Analysis (SAST/DAST)

This skill focuses on finding vulnerabilities both in the 'Written Code' and the 'Running App'.

## Instructions

1. Configure SAST tools (SonarQube, Snyk, CodeQL) in the CI/CD pipeline.
2. Analyze 'Data Flow' to find where untrusted user input reaches a sensitive sink.
3. Run DAST scanners against a staging environment to find runtime issues.
4. Implement 'Dependency Scanning' for known CVEs in third-party libraries.
5. Prioritize fixes based on 'Reachability' and 'Exploitability'.

## Examples

- "Scan my GitHub repo with Snyk and tell me which npm packages are insecure."
- "Use CodeQL to find a potential 'Buffer Overflow' in this C++ code."