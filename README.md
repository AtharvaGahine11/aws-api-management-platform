# 🚀 API Gateway Developer Platform Cloud

<div align="center">

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws)
![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-API-black?style=for-the-badge&logo=flask)
![MySQL](https://img.shields.io/badge/MySQL-RDS-blue?style=for-the-badge&logo=mysql)
![CloudWatch](https://img.shields.io/badge/CloudWatch-Monitoring-red?style=for-the-badge&logo=amazoncloudwatch)
![GitHub Repo stars](https://img.shields.io/github/stars/yourusername/api-gateway-developer-platform-cloud?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/yourusername/api-gateway-developer-platform-cloud?style=for-the-badge)

<h3>☁️ Enterprise API Management & Developer Platform on AWS ☁️</h3>

<p>
Centralized API Management • Developer Operations • Monitoring • Analytics • Workflow Automation
</p>

</div>

---

## 🌟 Project Overview

The **API Gateway Developer Platform Cloud** is an enterprise-grade cloud-native platform built using AWS services. It centralizes API Management, Developer Operations, Monitoring, Analytics, Workflow Automation, and Secure Access Control.

This project demonstrates modern cloud architecture practices using:

- Amazon EC2
- Amazon RDS MySQL
- Amazon API Gateway
- Amazon CloudWatch
- Amazon IAM
- Amazon VPC
- Python Flask

---

# 🎯 Problem Statement

Organizations often manage APIs through disconnected systems, spreadsheets, and manual workflows. This project provides a centralized cloud platform capable of:

✅ Managing APIs

✅ Managing Developers

✅ Workflow Automation

✅ Analytics Reporting

✅ Monitoring & Alerting

✅ Secure Access Control

✅ High Availability Architecture

✅ Cloud Scalability

---

# 🏗️ Architecture Diagram

```text
                        Users
                          │
                          ▼
                  Amazon API Gateway
                          │
                          ▼
                Flask Application (EC2)
                          │
                          ▼
                   Amazon RDS MySQL
                          │
                          ▼
                 Amazon CloudWatch

VPC
├── Public Subnet
│    └── EC2 Instance
│
└── Private Subnet
     └── RDS Database

IAM
├── Admin
├── Developer
└── Monitoring User
```

---

# ☁️ AWS Services Used

| Service | Purpose |
|----------|----------|
| Amazon EC2 | Application Hosting |
| Amazon RDS | MySQL Database |
| API Gateway | API Management |
| CloudWatch | Monitoring & Metrics |
| IAM | Identity Management |
| VPC | Network Isolation |
| Security Groups | Access Control |

---

# ⚡ Features

## 👨‍💻 Developer Management

- Developer Registration
- Developer Listing
- Role Management
- Secure Access

---

## 🔌 API Management

- API Catalog
- API Monitoring
- API Health Checks
- Endpoint Management

---

## 📊 Analytics Dashboard

- Developer Statistics
- API Statistics
- Workflow Statistics
- Approval Statistics

---

## 📈 Monitoring Dashboard

CloudWatch Metrics:

- API Request Count
- API Latency
- CPU Utilization
- Error Monitoring
- Database Connections
- Storage Monitoring

---

## 🔐 Security

- IAM User Management
- Security Groups
- Private Database Access
- Controlled API Access

---

## 🤖 Automation

- Deployment Automation
- Backup Automation
- Monitoring Automation

---

# 📂 Project Structure

```bash
api-gateway-developer-platform-cloud/
│
├── app.py
├── deploy.sh
├── backup.sh
├── monitor.sh
│
├── docs/
│   ├── Project_Report.pdf
│   ├── Architecture_Diagram.png
│
├── screenshots/
│   ├── ec2.png
│   ├── rds.png
│   ├── apigateway.png
│   ├── cloudwatch.png
│
└── README.md
```

---

# 🗄️ Database Tables

```sql
developers
apis
workflows
approvals
analytics
```

---

# 🚀 API Endpoints

## Health API

### Request

```http
GET /health
```

### Response

```json
{
  "status":"healthy"
}
```

---

## Developers API

### Request

```http
GET /developers
```

### Response

```json
[
 {
  "id":1,
  "name":"Atharva",
  "email":"atharva@example.com",
  "role":"Admin"
 }
]
```

---

## Dashboard API

### Request

```http
GET /dashboard
```

### Response

```json
{
  "platform":"API Gateway Developer Platform",
  "total_developers":2,
  "total_apis":0,
  "total_workflows":0,
  "total_approvals":0,
  "status":"Running"
}
```

---

# 🛠️ Deployment Steps

## Clone Repository

```bash
git clone https://github.com/yourusername/api-gateway-developer-platform-cloud.git
```

## Move to Project

```bash
cd api-gateway-developer-platform-cloud
```

## Install Dependencies

```bash
pip install flask pymysql
```

## Run Application

```bash
python3 app.py
```

---

# 📋 Infrastructure Setup

### Step 1

Create IAM Users

### Step 2

Create VPC

### Step 3

Create Public & Private Subnets

### Step 4

Launch EC2 Instance

### Step 5

Configure Security Groups

### Step 6

Create RDS MySQL Database

### Step 7

Connect EC2 to RDS

### Step 8

Deploy Flask Application

### Step 9

Configure API Gateway

### Step 10

Configure CloudWatch Dashboard

---

# 📊 CloudWatch Dashboard

The monitoring dashboard includes:

✅ API Request Count

✅ API Latency

✅ 4XX Errors

✅ 5XX Errors

✅ EC2 CPU Utilization

✅ RDS Connections

✅ Free Storage Space

---

# 📸 Project Screenshots

## EC2 Instance

Add Screenshot

```html
<img src="screenshots/ec2.png" width="900">
```

---

## Amazon RDS

```html
<img src="screenshots/rds.png" width="900">
```

---

## API Gateway

```html
<img src="screenshots/apigateway.png" width="900">
```

---

## CloudWatch Dashboard

```html
<img src="screenshots/cloudwatch.png" width="900">
```

---

# 🎓 Learning Outcomes

✔ Cloud Architecture

✔ AWS Networking

✔ EC2 Deployment

✔ RDS Administration

✔ API Gateway Integration

✔ Cloud Monitoring

✔ IAM Security

✔ Flask API Development

✔ DevOps Fundamentals

---

# 🔮 Future Enhancements

- Docker Containerization
- Kubernetes Deployment
- CI/CD Pipeline
- Multi-Region Deployment
- Load Balancing
- Auto Scaling
- JWT Authentication

---

# 👨‍🎓 Academic Project

**Course:** AWS Cloud Computing

**University:** ITM Skills University

**Program:** B.Tech Computer Science Engineering

**Semester:** IV

---

# 👨‍💻 Author

## Atharva Gahine

Cloud Computing • AWS • Python • DevOps

---

<div align="center">

### ⭐ If you like this project, please give it a star ⭐

🚀 Built with AWS Cloud Services

</div>
