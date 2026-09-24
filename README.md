# ShopEasy — Cloud-Based E-Commerce Project

## 🚀 Project Overview

ShopEasy is a simple e-commerce website created to understand
how a real product can be designed, deployed and scaled using
cloud concepts.

The project focuses on both **Product Management** and
**Cloud Infrastructure**.

---

## 🎯 Product Goal

Build a simple shopping experience where users can:

- Browse products
- View product prices
- Add products to cart

The project is designed as a practical PM + Cloud portfolio project.

---

## 🌐 Live Demo

The frontend website is deployed using GitHub Pages.

**Live Website:**  
https://nk3067678-tech.github.io/shopeasy-cloud-project/

---

## ☁️ Cloud Architecture

The planned cloud architecture uses:

- **AWS S3** — Website and product file storage
- **AWS EC2** — Backend/API
- **AWS RDS** — Database
- **AWS CloudWatch** — Monitoring

Architecture diagram:

![ShopEasy Cloud Architecture](shopeasy-cloud-architecture%20%281%29.png)

---

## 📈 Scalability Plan

The system is designed to support growth from:

**10,000 users/day → 100,000 users/day**

Future scalability improvements include:

- Load Balancer
- Multiple EC2 instances
- Auto Scaling
- Database read replicas
- Caching
- CDN
- CloudWatch monitoring

Details:  
[Scalability Plan](scalability-plan.md)

---

## 💰 Cost Planning

The project identifies the major cloud cost components:

- EC2
- RDS
- S3
- CloudWatch

Cost decisions are based on traffic, infrastructure usage,
performance and business requirements.

Details:  
[Cost Estimate](cost-estimate.md)

---

## 🔐 Security

The security plan covers:

- HTTPS
- Authentication
- API validation
- Database access control
- Least-privilege permissions
- S3 access control
- Monitoring
- Backup and recovery

Details:  
[Security Checklist](security-checklist.md)

---

## 🚀 Launch Readiness

Before launching a major feature, the project checks:

- Product functionality
- Performance
- Security
- Monitoring
- Scalability
- Backup and recovery

Details:  
[Launch Checklist](launch-checklist.md)

---

## 📁 Project Structure

```text
shopeasy-cloud-project/
│
├── index.html
├── products.json
├── cloud-architecture.md
├── scalability-plan.md
├── cost-estimate.md
├── security-checklist.md
├── launch-checklist.md
├── shopeasy-cloud-architecture (1).png
└── README.md
