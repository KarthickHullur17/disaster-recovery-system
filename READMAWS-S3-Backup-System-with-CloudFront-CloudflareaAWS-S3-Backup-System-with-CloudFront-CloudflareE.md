# AWS-S3-Backup-System-with-CloudFront-Cloudflare

## Overview
This project demonstrates a secure disaster recovery system using AWS services with global content delivery and HTTPS access.

## Architecture
User → CloudFront → S3 (Private) → Lambda

## Technologies Used
- AWS Lambda
- Amazon S3 (Private Bucket with Versioning)
- Amazon CloudFront (CDN with HTTPS)
- GitHub (Version Control)

## Features
- Automated backup creation using Lambda
- Secure file storage in private S3 bucket
- Global file access via CloudFront CDN
- HTTPS enabled secure delivery
- High availability and scalable design

## Live Demo
[View Demo](https://d2q6kc2jtbdmc.cloudfront.net/file2.PNG)
Live Demo
Check out the live deployment here: [Disaster Recovery System](https://disaster-recovery-system.karthickhullur1010.workers.dev/)

## Screenshots

### CloudFront Output
![CloudFront Output](cloudfront-output.png)

### S3 Bucket
![S3 Bucket](s3.png)

### Lambda Function
![Lambda Function](lambda.png)

### CloudFront Distribution
![CloudFront Distribution](cloudfront.png)

## Project Structure
