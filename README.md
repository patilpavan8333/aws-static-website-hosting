# 🚀 AWS Static Website Hosting Project

## 🌐 Live Website

Visit the website here:

👉 https://mturkar.online

---

## 📖 Project Overview

This project demonstrates the deployment of a static website on AWS using a secure, scalable, and highly available architecture.

The website is hosted on Amazon S3, delivered through Amazon CloudFront, secured with SSL/TLS using AWS Certificate Manager (ACM), and connected to a custom domain through Amazon Route 53.

---

## 🏗️ Architecture

```text
+-------------------+
|   GitHub Repo     |
| HTML, CSS, JS     |
+---------+---------+
          |
          v
+-------------------+
|   Amazon S3       |
| Static Website    |
| Hosting Bucket    |
+---------+---------+
          |
          v
+-------------------+
| Amazon CloudFront |
|      CDN          |
+---------+---------+
          |
          | HTTPS
          v
+-------------------+
| Amazon Route 53   |
| Domain Management |
+---------+---------+
          |
          v
+-------------------+
|      Users        |
| mturkar.online    |
+-------------------+

AWS Certificate Manager (ACM)
          |
          +---- SSL/TLS Certificate
```

---

## ☁️ AWS Services Used

| Service | Purpose |
|----------|----------|
| Amazon S3 | Static Website Hosting |
| Amazon CloudFront | Content Delivery Network (CDN) |
| Amazon Route 53 | DNS Management |
| AWS Certificate Manager | SSL/TLS Certificate |
| GitHub | Source Code Repository |

---

## 🔒 Security Features

- HTTPS Enabled
- SSL/TLS Certificate via ACM
- Secure Content Delivery
- Custom Domain Configuration
- CloudFront CDN Protection

---

## 📂 Project Structure

```text
.
├── index.html
├── about.html
├── blog.html
├── locations.html
├── menu.html
├── css/
├── images/
└── fonts/
```

---

## 🚀 Deployment Steps

### 1. Create S3 Bucket

- Create an S3 bucket
- Upload website files
- Configure static website hosting

### 2. Configure CloudFront

- Create CloudFront distribution
- Select S3 bucket as origin
- Configure default root object

### 3. Configure SSL

- Request SSL certificate using ACM
- Validate domain ownership

### 4. Configure Route 53

- Create hosted zone
- Point domain to CloudFront distribution

### 5. Test Website

Verify:

- HTTPS access
- DNS resolution
- Website availability

---

## 📸 Project Screenshots

### Website

![Website Screenshot](screenshots/website.png)

### CloudFront Distribution

![CloudFront](screenshots/cloudfront.png)

### S3 Bucket

![S3](screenshots/s3.png)

### SSL Certificate

![ACM](screenshots/acm.png)

### Route 53

![Route53](screenshots/route53.png)

---

## 🎯 Key Learnings

- AWS Cloud Fundamentals
- Static Website Hosting
- DNS Configuration
- SSL/TLS Implementation
- CDN Configuration
- Cloud Security Best Practices

---

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript
- GitHub
- Amazon S3
- Amazon CloudFront
- Amazon Route 53
- AWS Certificate Manager

---

## 👨‍💻 Author

**Pavan Patil**

🌐 Website: https://mturkar.online

GitHub: https://github.com/patilpavan8333

LinkedIn: www.linkedin.com/in/pavan-patil8333

---

## ⭐ If you found this project useful, consider giving it a star!
