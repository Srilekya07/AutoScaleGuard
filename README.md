# 🚀 AutoScaleGuard

### Production-Grade Highly Available Web Application with Auto Scaling, Monitoring & Alerting on AWS

---

## 📌 Project Overview

**AutoScaleGuard** is a hands-on AWS project that demonstrates how to design and operate a **highly available, scalable, and observable web application** using core AWS services.  
The system automatically scales based on CPU utilization, monitors infrastructure health in real time, and sends alert notifications to DevOps teams.

This project follows **production best practices** and closely resembles real-world cloud architectures.

---

## 🎯 What This Project Demonstrates

- High availability using **Application Load Balancer**
- Automatic scale-out and scale-in using **Auto Scaling Group**
- Consistent EC2 configuration via **Launch Templates**
- Real-time monitoring with **Amazon CloudWatch**
- Email alerting using **Amazon SNS**
- Validation through **load testing**
- Operational visibility using **CloudWatch Dashboards**

---

## 🏗️ High-Level Architecture

User / Browser
   ↓
Internet Gateway
   ↓
Application Load Balancer
   ↓
Target Group
   ↓
Auto Scaling Group
   ↓
EC2 Instances
   ↓
CloudWatch Metrics
      ├─ Scale Out / Scale In (Auto Scaling)
      ├─ Dashboard Visualization
      └─ SNS Email Alerts


---

## 🔁 Request Flow (How It Works)

1. User sends an HTTP request to the application.
2. The Application Load Balancer distributes traffic to healthy EC2 instances.
3. EC2 instances serve the web application.
4. CPU utilization metrics are sent to Amazon CloudWatch.
5. Auto Scaling adjusts capacity based on thresholds.
6. CloudWatch alarms trigger SNS email notifications for DevOps teams.

---

## 🧩 AWS Services Used

- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Launch Template
- Amazon CloudWatch
- Amazon SNS
- Security Groups

---

## 🧪 Testing & Validation

- CPU stress testing used to simulate high load
- Verified automatic scale-out during load
- Verified scale-in after load reduction
- Confirmed CloudWatch metrics, alarms, and dashboard updates
- Confirmed SNS email alerts

---

## 📘 Key Learnings

- Designing **scalable and fault-tolerant** cloud systems
- Implementing **metric-driven auto scaling**
- Monitoring infrastructure using CloudWatch
- Separating **scaling alarms** from **human alert alarms**
- Following AWS **production best practices**

---

## 🔮 Future Enhancements

- Enable HTTPS using AWS Certificate Manager (ACM)
- Infrastructure as Code using Terraform
- Integrate alerts with Slack or PagerDuty
- Add custom application metrics

---

## 🏁 Conclusion

AutoScaleGuard showcases a practical, production-style AWS architecture that automatically scales, monitors itself, and alerts operators — reflecting real-world DevOps and cloud engineering practices.

---

## 👤 Author

**Nadella Srilekya**  
Cloud / DevOps Enthusiast  
