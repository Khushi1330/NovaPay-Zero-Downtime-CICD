# PCI-DSS Compliance Mapping

## Overview

NovaPay implements automated controls within the DevSecOps pipeline to support PCI-DSS compliance requirements.

---

## Requirement 1

### Install and Maintain Network Security Controls

Pipeline Control:

* Kubernetes Network Policies
* Security Groups
* Firewall Rules

---

## Requirement 2

### Secure Configuration Standards

Pipeline Control:

* Infrastructure as Code (Terraform)
* Configuration Reviews

---

## Requirement 3

### Protect Stored Account Data

Pipeline Control:

* Database Encryption
* Secrets Management via Vault

---

## Requirement 4

### Protect Cardholder Data in Transit

Pipeline Control:

* TLS Encryption
* Service Mesh Security

---

## Requirement 5

### Protect Systems Against Malware

Pipeline Control:

* Container Image Scanning
* Dependency Scanning using Trivy

---

## Requirement 6

### Develop and Maintain Secure Systems

Pipeline Control:

* SonarQube SAST
* OWASP ZAP DAST
* Automated Security Gates

---

## Requirement 7

### Restrict Access to System Components

Pipeline Control:

* Role-Based Access Control (RBAC)
* GitHub Branch Protection

---

## Requirement 8

### Identify Users and Authenticate Access

Pipeline Control:

* Multi-Factor Authentication
* Identity Federation

---

## Requirement 10

### Log and Monitor Access

Pipeline Control:

* Audit Logging
* Prometheus Monitoring
* Grafana Dashboards

---

## Compliance Objective

The NovaPay CI/CD pipeline integrates security and governance controls that align with PCI-DSS requirements and support continuous compliance verification.
