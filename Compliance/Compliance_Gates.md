# Compliance Gates

## Gate 1 - SAST
Tool: SonarQube
Threshold: 0 Critical Vulnerabilities

## Gate 2 - Dependency Scan
Tool: Trivy
Threshold: 0 Critical CVEs

## Gate 3 - DAST
Tool: OWASP ZAP
Threshold: 0 High Vulnerabilities

## Gate 4 - Policy Check
Tool: OPA
Threshold: 100% Pass

## Gate 5 - License Scan
Threshold: No GPL Licenses

## Gate 6 - Infrastructure Scan
Tool: Checkov
Threshold: Pass