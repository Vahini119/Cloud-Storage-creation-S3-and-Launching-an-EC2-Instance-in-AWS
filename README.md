# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


Snap Shots:
 


<img width="1920" height="1080" alt="Screenshot (381)" src="https://github.com/user-attachments/assets/012097d8-d914-4a6d-a18a-b7e29201c38b" />

<img width="1920" height="1080" alt="Screenshot (382)" src="https://github.com/user-attachments/assets/817c9b40-a003-4313-8251-f450be438312" />

<img width="1920" height="1080" alt="Screenshot (383)" src="https://github.com/user-attachments/assets/1a81c411-c4ed-4ce0-9348-0406630beeb5" />

<img width="1920" height="1080" alt="Screenshot (406)" src="https://github.com/user-attachments/assets/5e7960ce-4757-4543-9ac4-d283fbe1177e" />

<img width="1920" height="1080" alt="Screenshot (407)" src="https://github.com/user-attachments/assets/4d0a0291-b148-4a76-89a6-471d75f0ee32" />

<img width="1920" height="1080" alt="Screenshot (408)" src="https://github.com/user-attachments/assets/d1379147-bee3-4d20-9ade-64a355315bfe" />

<img width="1920" height="1080" alt="Screenshot (410)" src="https://github.com/user-attachments/assets/6e278df8-c1f8-4976-9d69-a983c2fb0b64" />

<img width="1920" height="1080" alt="Screenshot (411)" src="https://github.com/user-attachments/assets/01a0d52e-8a4e-47f2-8772-ca5ee421955a" />



























Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
