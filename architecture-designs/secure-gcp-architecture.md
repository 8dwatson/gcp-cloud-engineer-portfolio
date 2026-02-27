# Secure GCP Architecture Design

## Scenario
Design a secure web application architecture in Google Cloud.

## Architecture Components

- VPC with private subnets
- Load balancer for public access
- Compute instances without public IPs
- Private database tier
- IAM roles with least privilege
- Centralized logging enabled

## Security Controls

- No public IP addresses on backend systems
- Firewall rules restricted to required ports only
- Service accounts separated by function
- Audit logging enabled
- Encryption at rest and in transit

## Threat Mitigation

| Threat | Mitigation |
|--------|------------|
| Privilege escalation | Role separation and IAM review |
| Data exfiltration | Private networking |
| DDoS | Load balancing |
| Insider threat | Audit logs |

## Why This Design Is Secure

The design minimizes attack surface and enforces strong identity and access controls.