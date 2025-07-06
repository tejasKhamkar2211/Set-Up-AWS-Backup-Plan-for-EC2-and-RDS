# Set-Up-AWS-Backup-Plan-for-EC2-and-RDS

Objective: 
Learn how to configure and manage automated backup and recovery for AWS 
resources using AWS Backup. This project involves launching an EC2 and RDS 
instance, and creating a centralized backup plan to protect both.

1. . Infrastructure Setup
Launch one EC2 instance:
o Use Amazon Linux.
o Install a sample web server (e.g., Apache or Nginx).

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/a0ff816a-a7e9-4142-ade5-1e46878505d5" />

o Store some test data on the instance (e.g., a sample HTML page or text file).

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/79371709-8cd9-40ce-afb0-12d72296c54c" />

Launch one RDS instance:
o Choose MySQL or PostgreSQL engine.

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/3a9f3e7f-c800-40d3-afef-94a5a3accc49" />

o Create a test database and insert sample data into a table

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/04814540-2a05-43a0-8178-09b0cc1e8a46" />

2. AWS Backup Setup:
   Create a Backup Vault

   <img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/384ee5b4-ddb0-42df-9868-87739c88284e" />

   Create a Backup Plan:
<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/58a149cc-c99b-4373-9395-6ef86644cf40" />


Assign both:
o The EC2 instance
o The RDS databas

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/8e299795-80f5-4d49-8bd6-f15f39e80dd8" />

Validation & Reporting:

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/9532304a-edf0-4d74-ade3-3d4fdfcc8fcb" />

Recovery points for EC2 and RDS

ec2 instance AMI

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/25f212e3-5f90-4a62-87bb-672735be08ae" />

Rds instance recovery point 

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/04c7afd9-0bff-4324-8851-823547e56f96" />


   
