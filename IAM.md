---

##  **IAM (Identity and Access Management)**

###  List IAM Users

```bash
aws iam list-users
```

###  Create a New IAM User

```bash
aws iam create-user --user-name newuser
```

###  Create Access Key for a User

```bash
aws iam create-access-key --user-name newuser
```

###  Attach Policy to a User

```bash
aws iam attach-user-policy --user-name newuser \
--policy-arn arn:aws:iam::aws:policy/AdministratorAccess
```

###  List Attached Policies for a User

```bash
aws iam list-attached-user-policies --user-name newuser
```

###  Delete IAM User

```bash
aws iam delete-user --user-name newuser
```
