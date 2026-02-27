# Deploying Compute Engine (ACE Lab)

## Objective
Deploy and manage a virtual machine using best practices.

---

## Steps Covered

1. Create VM instance
2. Select appropriate machine type
3. Configure firewall rules
4. Attach service account
5. Enable logging

---

## Security Considerations

- Avoid public IP if not required
- Use least privilege service account
- Restrict firewall rules
- Enable OS Login

---

## Commands (gcloud example)

gcloud compute instances create my-vm \
  --zone=us-central1-a \
  --machine-type=e2-medium

---

## Key Exam Skills Demonstrated

- Compute deployment
- Resource configuration
- Basic networking
- CLI familiarity