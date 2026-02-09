# Module 9: Security, IAM, and Encryption (AWS)

---

## Question 1

**Which are characteristics of an AWS Identity and Access Management (IAM) group? (Select TWO.)**

* ⛔ A group can have security credentials.
* ⛔ A group can belong to another group.
* ✅ **New users added to a group inherit the group's permissions.**
* ✅ **A user can belong to more than one group.**
* ⛔ Permissions in a group policy always override permissions in a user policy.

---

## Question 2

**What is an advantage of using attribute-based access control (ABAC) over role-based access control (RBAC)?**

* ⛔ ABAC permissions are more secure than RBAC permissions.
* ⛔ ABAC permissions explicitly identify the resources that they protect.
* ⛔ ABAC requires less testing than RBAC.
* ✅ **ABAC will likely require fewer policies than RBAC.**

---

## Question 3

**A developer is a member of an IAM group. The group policy allows access to Amazon S3 and Amazon EC2 and denies access to Amazon ECS. The developer also has a user policy that allows access to Amazon ECS and Amazon CloudFront. Which option describes the user's access?**

* ⛔ Access to Amazon S3, Amazon EC2, and Amazon CloudFront, but no access to Amazon ECS
* ⛔ Access to Amazon ECS and Amazon CloudFront, but no access to Amazon S3 and Amazon EC2
* ⛔ Access to Amazon S3 and Amazon EC2, but no access to Amazon ECS and Amazon CloudFront
* ✅ **Access to Amazon S3, Amazon EC2, Amazon ECS, and Amazon CloudFront**

---

## Question 4

**What is a benefit of identity federation with the AWS Cloud?**

* ✅ **It enables the use of an external identity provider to authenticate workforce users and give them access to AWS resources.**
* ⛔ It centralizes the storage and management of user identities inside the AWS Cloud.
* ⛔ It assigns roles to authenticated users to control their access to AWS resources.
* ⛔ It eliminates the need for defining permissions in IAM.

---

## Question 5

**Which service enables identity federation for accessing a web application running in the AWS Cloud?**

* ⛔ AWS CloudHSM
* ⛔ AWS WAF
* ⛔ AWS Key Management Service (AWS KMS)
* ✅ **Amazon Cognito**

---

## Question 6

**Which service helps centrally manage billing, control access, compliance, and security, and share resources across multiple AWS accounts?**

* ⛔ AWS Identity and Access Management (IAM)
* ⛔ AWS Systems Manager
* ⛔ Amazon Cognito
* ✅ **AWS Organizations**

---

## Question 7

**A company wants to prevent all IAM users in production accounts from deleting AWS CloudTrail logs. How should this restriction be enforced?**

* ⛔ Create an S3 bucket policy and associate it with all buckets containing CloudTrail logs.
* ⛔ Create an IAM policy and attach it to each IAM user.
* ⛔ Create a tag policy and attach it to the production accounts.
* ✅ **Create a service control policy (SCP) and attach it to the production OU.**

---

## Question 8

**A client encrypts sensitive data with a data key before sending it to a server. The data key is sent to the server so it can decrypt the data. Which encryption type should be used to protect the data if the key is stolen?**

* ⛔ Symmetric encryption
* ⛔ Server-side encryption
* ⛔ Asymmetric encryption
* ✅ **Envelope encryption**

---

## Question 9

**Which functions does AWS Key Management Service (AWS KMS) provide? (Select TWO.)**

* ✅ **Rotate keys**
* ✅ **Create symmetric and asymmetric keys**
* ⛔ Create IAM access keys
* ⛔ Authenticate external users
* ⛔ Store encrypted data

---

## Question 10

**Which AWS service discovers and protects sensitive information stored on Amazon S3?**

* ⛔ Amazon Detective
* ⛔ AWS Resource Access Manager (AWS RAM)
* ⛔ AWS Audit Manager
* ✅ **Amazon Macie**

---

📌 *Module 9 – Ready for GitHub (Markdown format)*
