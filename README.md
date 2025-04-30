# Week-9-Assignment

Infrastructure Bootcamp Assignment
AWS Web Application Deployment with ALB + ASG + S3

## Clarusway Bootcamp Website Deployment Scenario:
 Deploying a highly available website using:
 1. S3 for static assets
 2. Auto Scaling Group for NGINX web servers
 3. Application Load Balancer for traffic distribution

 # 🔧 Assignment Tasks
 ## Part 1: S3 Setup (Static Assets)
   1. Created a bucket mafaz-clarusway-assets in eu-north-1
   2. Uploaded the provided (index.html) and Logo files (logo.png, sda.png)
   3. Configured:
     - Static website hosting
     - Bucket policy for public read access

 ## Part 2: Auto Scaling Group
   1. Created a Launch Template
   2. Configured ASG with the desired configuration details
 
 ## Part 3: Application Load Balancer
 1. Created an internet-facing ALB with:
   - HTTP listener on port 80
   - Target group with health checks (/)
 2. Verified the Round-robin traffic distribution

 ## ✅ Cleanup:
 - S3 bucket deleted
 - ASG Terminated
 - ALB Removed
