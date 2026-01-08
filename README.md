# AWS Serverless Contact Form

## 📌 Project Overview
A fully serverless contact form application built using AWS services. 
The frontend is hosted on Amazon S3 and distributed via CloudFront. 
The backend is implemented using AWS Lambda and user submissions are stored in DynamoDB.

## 🛠️ Tech Stack
- AWS S3
- AWS CloudFront
- AWS Lambda (Python)
- AWS DynamoDB
- IAM
- HTML, CSS, JavaScript

## 🏗️ Architecture
User → CloudFront → S3 → Lambda → DynamoDB

## 🚀 Features
- Serverless backend
- Global CDN delivery
- Secure data storage
- No server management
- Scalable and cost-efficient

## 🧪 How It Works
1. User submits contact form
2. JavaScript sends POST request to Lambda Function URL
3. Lambda processes data
4. Data stored in DynamoDB
5. Success message returned

## 🔐 Security Notes
- No AWS credentials stored in code
- IAM role-based access
- CORS configured

## 📷 Screenshots
See `/Screenshots` folder
