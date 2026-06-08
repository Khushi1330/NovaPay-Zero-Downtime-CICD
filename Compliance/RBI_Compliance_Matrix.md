# RBI Compliance Matrix

| RBI Requirement          | Pipeline Control                  |
| ------------------------ | --------------------------------- |
| Change Management        | GitHub Actions Approval Workflow  |
| Segregation of Duties    | Pull Request Review Process       |
| Vulnerability Assessment | SonarQube + Trivy + OWASP ZAP     |
| Audit Logging            | GitHub Commit History             |
| Incident Management      | Automated Rollback Strategy       |
| Business Continuity      | Blue-Green Deployment             |
| Secure Deployment        | OPA Compliance Gates              |
| Traceability             | Git SHA Based Deployment Tracking |

## Compliance Objective

The NovaPay CI/CD pipeline enforces automated controls aligned with RBI technology governance expectations and provides traceability from code commit to production deployment.
