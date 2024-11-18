### REG NUMBER: 212222110045
### NAME: Sowmya V

# CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS

## AIM
To Create S3 bucket and EC2 Instances for Linux and Windows.

## PROBLEM STATEMENT
This experiment highlights the steps to set up cloud infrastructure using AWS, focusing on creating an S3 bucket for scalable storage and deploying EC2 instances for Linux and Windows environments.

## Algorithm

**Step 1: Log in to AWS Management Console**  
- Open the [AWS Management Console](https://aws.amazon.com/console/).  
- Log in using your credentials (IAM user or Root user).  

**Step 2: Access the S3 Service**  
- Navigate to **Services** > **S3**.  
- Click on **Create Bucket**.  

**Step 3: Configure the S3 Bucket**  
- Provide a unique **Bucket Name**.  
- Choose the **Region** closest to your users for better performance.  
- Configure optional settings like versioning, encryption, and access control.  

**Step 4: Finalize the S3 Bucket Creation**  
- Review the settings and click **Create Bucket**.  
- Verify the bucket appears in the list of S3 buckets.  


**Step 5: Access the EC2 Service**  
- Navigate to **Services** > **EC2**.  
- Click on **Launch Instance**.  

**Step 6: Configure EC2 Instance (Linux)**  
- Select an Amazon Machine Image (AMI), such as **Amazon Linux 2**.  
- Choose an instance type (e.g., **t2.micro** for free tier).  
- Configure instance details, such as VPC, subnet, and IAM role if needed.  
- Add storage (default is 8 GB).  
- Configure a security group to allow **SSH (port 22)**.  

**Step 7: Launch Linux Instance**  
- Review the settings and click **Launch**.  
- Choose or create a key pair for SSH access.  
- Download the key file (.pem) and securely save it.  
- Launch the instance and verify its status.  

**Step 8: Configure EC2 Instance (Windows)**  
- Follow the same steps as the Linux instance, but choose a **Windows AMI** (e.g., **Windows Server 2019**).  
- Adjust the security group to allow **RDP (port 3389)** for remote access.  

**Step 9: Launch Windows Instance**  
- Review the settings and click **Launch**.  
- Choose or create a key pair and save it.  
- Launch the instance and verify its status.  


## OUTPUT

![image](https://github.com/user-attachments/assets/d9e82bbf-83d7-4c9c-a188-50144fc44cdd)

![image](https://github.com/user-attachments/assets/4c159798-8458-4e9d-a01c-116bab91df83)

![image](https://github.com/user-attachments/assets/823b8dec-1770-41f0-8040-90ddcc834d45)

![image](https://github.com/user-attachments/assets/d1cf4ce7-e6c2-412f-b5dd-ab5a431d1360)

![image](https://github.com/user-attachments/assets/405f6e6a-3ab9-4ae1-839f-7983be28fa9a)

![image](https://github.com/user-attachments/assets/2385e377-c9e4-482e-bb77-a4f2b77ee040)


## RESULT
Successfully created an S3 bucket and EC2 instances for both Linux and Windows.

  


