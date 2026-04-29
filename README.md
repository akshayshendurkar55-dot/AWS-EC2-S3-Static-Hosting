# AWS-EC2-S3-Static-Hosting
"Securely hosting web assets on AWS EC2 by fetching data from S3 using IAM Roles."
# AWS Cloud Hosting Project ☁️

## Overview
This project demonstrates how to set up a web server on **AWS EC2** that securely communicates with **Amazon S3** using **IAM Roles** to host an image.

## Services Used
- **EC2 (Ubuntu 24.04):** Web server hosting the site.
- **S3:** Object storage for the image file.
- **IAM Role:** Secure permission management (No access keys used).
- **Apache:** Web server software.

## Challenges Solved
- Handled Linux filenames with spaces using double quotes in CLI.
- Configured IAM Trust Relationships for secure EC2-S3 access.
- Debugged Apache pathing to serve the correct image file.
