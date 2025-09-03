# 🌐 AWS S3 Static Website Hosting with CloudFront

## 📖 Project Overview
This project demonstrates hosting a static website using **Amazon S3** and distributing it globally with **Amazon CloudFront**.

---

## 🏗️ Architecture
1. Create an **S3 bucket** with static website hosting enabled.
2. Upload `index.html` file.
3. Make the bucket objects public (or use OAC for CloudFront).
4. Create a **CloudFront distribution** with the S3 bucket as origin.
5. Access the website via CloudFront domain.

---

## 🛠️ AWS Services Used
- Amazon S3
- Amazon CloudFront
- IAM
- Hosted a static website on **Amazon S3** with **CloudFront** distribution.  
- Configured IAM policies for secure bucket access.  
- Implemented a **global content delivery solution** using CDN.  

