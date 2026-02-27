# GCP Security Baseline Checklist

## Identity & Access Management
- [ ] No Owner roles assigned unnecessarily
- [ ] Service accounts follow least privilege
- [ ] MFA enabled
- [ ] IAM reviewed quarterly

## Logging & Monitoring
- [ ] Admin logs enabled
- [ ] Data access logs enabled
- [ ] Alerts configured for IAM changes

## Network Security
- [ ] No open firewall rules (0.0.0.0/0 on sensitive ports)
- [ ] Private IP for internal services
- [ ] VPC flow logs enabled

## Data Protection
- [ ] Encryption at rest enabled
- [ ] HTTPS enforced
- [ ] Backups configured

---

This checklist represents a basic cloud security posture baseline.