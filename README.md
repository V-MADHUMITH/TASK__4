TASK 4->CLOUD SECURITY IMPLEMENTATION
COMPANY: CODTECH IT SOLUTION 
NAME: V. MADHUMITHA
INTERN ID: CITSOD393
DOMAIN: CLOUD COMPUTING 
DURATION: 4 WEEKS 
MENTOR: NEELA SANTOSH

->Introduction:
*This project involves implementing cloud security using Amazon Web Services (AWS). The task covers creating IAM users, assigning group-level permissions, securing S3 buckets, and enabling default encryption to protect data stored in the cloud.

 
->Objective:
*To implement IAM policies, secure storage, and data encryption on a cloud platform (AWS) as part of Task 4 for the CODTECH internship.

->Tools Used:

*AWS Management Console

*IAM (Identity and Access Management)

*Amazon S3

*Incognito Browser (for testing IAM user access)

->Step-by-Step Implementation:

*Step 1: Created IAM User
Created an IAM user named intern-user with AWS Console access.

*Step 2: Created IAM Group
Created a group InternGroup and attached the AmazonS3FullAccess policy.

*Step 3: Attached User to Group
Added intern-user to InternGroup to inherit group permissions.

*Step 4: Created S3 Bucket
Created a bucket named codtech-secure-bucket and enabled block all public access.

*Step 5: Enabled Default Encryption
Enabled SSE-S3 encryption using Amazon S3-managed keys for default encryption.

*Step 6: Uploaded Encrypted File
Uploaded a test file to the bucket and confirmed encryption was automatically applied.

*Step 7: Tested IAM User Access
Logged in as intern-user in a private browser and successfully accessed and interacted with the S3 bucket.

->output:

<img width="940" height="141" alt="Image" src="https://github.com/user-attachments/assets/80c7a4b0-bd98-4595-b870-63331460b076" />

<img width="940" height="911" alt="Image" src="https://github.com/user-attachments/assets/5f7ff7a4-9c73-4ee9-96b0-5c9aee5be6bb" />

<img width="940" height="937" alt="Image" src="https://github.com/user-attachments/assets/94e55d4d-7e84-4d63-a4ca-ac7263c711a0" />

<img width="940" height="178" alt="Image" src="https://github.com/user-attachments/assets/aa29e42d-e61f-47ec-95e7-89ac0d43ba2b" />

<img width="940" height="341" alt="Image" src="https://github.com/user-attachments/assets/901f7cf4-2793-4238-935e-a4db9c5b4d79" />


