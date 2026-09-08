# IAM-Builder-Lab
My IAM Builder Lab walkthrough and policies
# IAM Builder Lab

This is my walkthrough of the AWS IAM Builder Lab.

---

## What I Did

### Task 1: Explored the Setup
- Looked at IAM users: user-1, user-2, user-3
- Looked at groups: EC2-Admin, EC2-Support, S3-Support
- Viewed JSON policies

**Screenshots:**
- [S3 support policy.png](./S3%20support%20policy.png)
- [EC2 support policy.png](./EC2%20support%20policy.png)
- [EC2 admin policy.png](./EC2%20admin%20policy.png)

---

### Task 2: Assigned Users to Groups
- user-1 → S3-Support
- user-2 → EC2-Support
- user-3 → EC2-Admin

**Screenshots:**
- [Before: user list](./user%20list%20before.png)
- [user-1 to S3-Support](./user-1%20to%20s3%20support.png)
- [user-2 to EC2-Support](./user-2%20to%20EC2%20support.png)
- [user-3 to EC2-Admin](./user%203%20to%20EC2%20admin.png)

---

### Task 3: Tested Permissions
- user-1: S3 works ✅, EC2 denied ❌
- user-2: EC2 view works ✅, stop denied ❌
- user-3: EC2 stop works ✅

**Screenshots:**
- [user-1 S3 success](./user%201%20suc%20s3%20bucket.png)
- [user-1 EC2 denied](./User%201%20access%20denied%20for%20EC2.png)
- [user-2 EC2 view](./user%202%20EC2%20access.png)
- [user-2 stop error](./user%202%20not%20authorized%20to%20stop%20instance.png)
- [user-3 stop success](./user%203%20stop%20instance.png)

---

## What I Learned
- Managed policies = reusable, Inline policies = one entity only
- JSON structure: Effect, Action, Resource, Condition
- Least privilege = minimum permissions needed

---

## Link to My Medium Article
(Add your Medium link here after you publish)
