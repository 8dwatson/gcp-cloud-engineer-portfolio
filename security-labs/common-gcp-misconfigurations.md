# Common Google Cloud Misconfigurations

## 1. Over-Permissioned IAM Roles
Using Owner or Editor roles unnecessarily increases risk.

## 2. Public Storage Buckets
Unrestricted access can expose sensitive data.

## 3. Public IP on Compute Instances
Increases attack surface.

## 4. Disabled Audit Logs
Prevents detection and investigation.

## 5. Unrestricted Firewall Rules
Allowing 0.0.0.0/0 on sensitive ports exposes services.

---

## Prevention Strategy

- Enforce least privilege
- Restrict public access
- Use private networking
- Enable logging
- Conduct regular security reviews