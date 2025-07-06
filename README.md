# Static Website Hosting with AWS S3 and CloudFront

This project demonstrates how to host a static website on AWS using **S3** for storage and **CloudFront** as a content delivery network (CDN) to improve global performance.

## 🛠️ Features

- Static file hosting using Amazon S3
- CloudFront distribution for low-latency content delivery
- Public access control via S3 bucket policy
- Versioning and lifecycle rules for backup and storage optimization
- (Optional) Custom domain with Route 53 and HTTPS

## 📁 Project Structure


## 🚀 Deployment Steps

1. Create an S3 bucket (enable static website hosting & public access).
2. Upload HTML/CSS files.
3. Create a CloudFront distribution pointing to the S3 bucket.
4. (Optional) Configure custom domain and SSL via Route 53 and ACM.
5. Test site at:  
   `http://<bucket-name>.s3-website-<region>.amazonaws.com`

## 🌍 Architecture

