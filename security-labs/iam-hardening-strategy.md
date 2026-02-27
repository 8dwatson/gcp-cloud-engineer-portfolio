# IAM Hardening Strategy for Google Cloud

## Objective
Reduce risk caused by over-permissioned users and service accounts.

---

## Common IAM Risks

- Overuse of Owner role
- Service accounts with Editor permissions
- Unused service accounts
- Lack of periodic access reviews

---

## Hardening Strategy

### 1. Enforce Least Privilege
- Replace Owner with specific predefined roles
- Use Viewer for read-only access
- Use Security Reviewer for audit access

### 2. Separate Duties
- Admins manage infrastructure
- Security team audits IAM
- Developers deploy but do not manage IAM

### 3. Use Groups Instead of Direct User Roles
- Assign IAM roles to groups
- Add/remove users from groups

### 4. Monitor IAM Changes
- Enable audit logs
- Alert on role changes
- Review IAM policy quarterly

---

## Risk Reduction Impact

| Risk | Mitigation |
|------|------------|
| Privilege escalation | Remove broad roles |
| Data theft | Restrict service accounts |
| Insider abuse | Enable logging and alerts |

---

## Key Principle

IAM should always follow the Principle of Least Privilege.