# Managing IAM (ACE Lab)

## Objective
Assign and manage roles using least privilege.

---

## Tasks Practiced

- Add user to project
- Assign predefined role
- Remove excessive permissions
- Review IAM policy

---

## gcloud Example

gcloud projects add-iam-policy-binding PROJECT_ID \
  --member=user:user@email.com \
  --role=roles/viewer

---

## Key Concepts

- Principle of least privilege
- Role hierarchy
- Project-level vs resource-level roles