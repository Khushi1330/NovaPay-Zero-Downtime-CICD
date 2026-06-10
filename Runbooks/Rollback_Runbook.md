# NovaPay Rollback Runbook

## Purpose

This document defines the rollback process for failed deployments.

---

## Rollback Triggers

### Immediate Rollback

Conditions:

* HTTP 5xx Error Rate > 5%
* Application CrashLoopBackOff
* Health Check Failure
* Database Connection Pool Exhaustion

Response Time:
Less than 60 seconds.

---

### Escalated Rollback

Conditions:

* Latency exceeds 2x baseline
* Transaction success rate decreases
* Resource utilization exceeds thresholds

Response Time:
Less than 15 minutes.

---

## Rollback Procedure

### Step 1

Identify deployment version.

### Step 2

Verify rollback target version.

### Step 3

Redirect traffic to stable deployment.

### Step 4

Disable failed deployment.

### Step 5

Validate service recovery.

### Step 6

Notify stakeholders.

---

## Validation Checklist

* Application healthy
* Error rates normalized
* Database healthy
* Monitoring dashboards normal
* Customer transactions successful

---

## Post Rollback Activities

* Root Cause Analysis
* Incident Report
* Corrective Action Plan
* Compliance Documentation
