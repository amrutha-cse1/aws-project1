#  AWS Static Website Deployment Project

This project demonstrates two deployment approaches for a static website using **Amazon Web Services (AWS)**:
1.  EC2-based deployment with Apache inside a **custom VPC**
2.  Serverless deployment using **Amazon S3 + CloudFront**

---

##  What I Learned

### Phase 1: EC2 Deployment
- Created a **custom VPC** with public/private subnets
- Launched an **EC2 instance** in the public subnet
- Installed and configured **Apache Web Server**
- Hosted a custom HTML site manually

### Phase 2: Serverless Architecture
- Created an **S3 bucket** to host a static website
- Enabled **public access + static hosting** configuration
- Connected the bucket to **CloudFront** for global CDN delivery
- Configured **HTTPS**, caching, and access control

---

##  Skills Applied
- VPC design and subnetting
- EC2 instance management (SSH, Apache, HTML)
- S3 bucket policy, static site hosting
- CloudFront distribution setup
- Domain configuration (GitHub Pages also explored)
- Git, GitHub, HTML, CSS, JS

---

##  Live Project
- CloudFront Link: https://d1eo49ry4vts3m.cloudfront.net/
-  EC2 Instance : http://3.105.227.200

---

##  Tech Stack
- AWS EC2, S3, CloudFront, VPC
- HTML5, CSS3, JavaScript
- Git, GitHub
