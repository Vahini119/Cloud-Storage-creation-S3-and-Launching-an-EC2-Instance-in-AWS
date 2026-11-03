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
<img width="1920" height="1080" alt="Screenshot (412)" src="https://github.com/user-attachments/assets/2f0ceb55-5cee-4d29-b713-901fbe7c7a9b" />
<img width="1920" height="1080" alt="Screenshot (415)" src="https://github.com/user-attachments/assets/f0180766-c2b7-401e-a519-2163bf3856a5" />
<img width="1920" height="1080" alt="Screenshot (416)" src="https://github.com/user-attachments/assets/018a4bde-f9ee-4aad-8f04-9a778319ed8b" />
<img width="1920" height="1080" alt="Screenshot (417)" src="https://github.com/user-attachments/assets/7fc7e89b-efe1-4974-a4d4-494c2e344a34" />
<img width="1920" height="1080" alt="Screenshot (418)" src="https://github.com/user-attachments/assets/7ace7b51-7b1e-4a8b-81e0-e2bf794d2304" />
<img width="1920" height="1080" alt="Screenshot (419)" src="https://github.com/user-attachments/assets/d4e411be-af57-4fb4-82f3-ebcf4f96c66d" />
<img width="1920" height="1080" alt="Screenshot (422)" src="https://github.com/user-attachments/assets/2b1c4fe1-4768-4f81-a952-4ea9c4502f91" />
<img width="1920" height="1080" alt="Screenshot (429)" src="https://github.com/user-attachments/assets/9f6262d1-d2e9-4d42-82d3-1350a6512936" />
<img width="1920" height="1080" alt="Screenshot (431)" src="https://github.com/user-attachments/assets/587e6db0-63ed-458c-b9ef-5e0a44e2ad94" />
<img width="1920" height="1080" alt="Screenshot (432)" src="https://github.com/user-attachments/assets/71022486-1316-4993-802f-a98a22120250" />
<img width="1920" height="1080" alt="Screenshot (433)" src="https://github.com/user-attachments/assets/59c92b00-5601-4c2e-9575-aae1bd3ae459" />
<img width="1920" height="1080" alt="Screenshot (435)" src="https://github.com/user-attachments/assets/0c566812-5874-4b7d-9ef6-a169d09eeea8" />
 






















Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
