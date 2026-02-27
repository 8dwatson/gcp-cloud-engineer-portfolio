# Cloud Logging & Detection Strategy

## Objective
Design a monitoring strategy to detect suspicious activity in Google Cloud.

---

## Logs to Enable

- Admin Activity Logs
- Data Access Logs
- System Event Logs
- VPC Flow Logs

---

## High-Risk Events to Monitor

- IAM role changes
- Service account key creation
- Failed login attempts
- Public bucket exposure
- Firewall rule changes

---

## Alerting Strategy

- Create log-based alerts for IAM policy changes
- Alert on Owner role assignment
- Alert on service account key creation
- Alert on excessive failed authentication attempts

---

## Why This Matters

Early detection reduces impact of privilege escalation and data breaches.