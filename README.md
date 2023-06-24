# Terraform-AWS
Terraform code to run AWS Cloud using CLI by automation. Launch instance, S3 bucket, Cloud Front, and many more services without using GUI!

## Problem Statement:
- Create the private key and security group which allows port 80.
- Launch Amazon AWS EC2 instance.
- In this EC2 instance use the key and security group which we have created in Step 1 to log in remotely or locally.
- Launch one Volume (EBS) and mount that volume into /var/www/html.
- The developer has uploaded the code into the GitHub repo also the repo has some images.
- Copy the GitHub repo code into /var/www/html.
- Create an S3 bucket, copy/deploy the images from the GitHub repo into the S3 bucket and change the permission to public readable.
- Create a Cloudfront using an S3 bucket(which contains images) and use the Cloudfront URL to update in code in /var/www/html.
