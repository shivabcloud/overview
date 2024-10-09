🌐 Cloud Native Web Application

Architecture Diagram

test drawio

🚀 Project Overview

This project is a comprehensive demonstration of cloud application development and deployment, emphasizing robust security, availability and scalability:

RESTful Application Development & Enhanced CI:
Developed a scalable RESTful application, with Continuous Integration via GitHub Actions ensuring code reliability and quality
Integrated detailed logging and metrics for effective monitoring and performance analysis
Application Scaling and Event-Driven Architecture:
Implemented AutoScaling for dynamic capacity management targetting CPU utilization
Used Google Cloud Pub/Sub for an efficient, event driven architecture
Robust Infrastructure Deployment with Security:
Deployed a secure GCP infrastructure, with a focus on network and resource isolation
Utilized IAM roles and security groups to enforce strict access controls and security best practices
Configured the Application Load Balancer to only accept HTTPS requests, enhancing data security in transit, with SSL/TLS certificates managed through GCP managed Certificate
Employed Cloud DNS for reliable domain registration and DNS management
Cloud Functions for Automation:
Integrated GCP Cloud functions for automated responses to specific events, streamlining operations and increasing efficiency
Encryption
Used Customer Managed Encryption Keys to manage encryption for the Cloud Database, Instance Templates and Bucket Storage
☁️ List of Cloud services used:

🌐 VPC (Virtual private cloud)
⚖️ External Application Load Balancer (ALB)
⚖️ Auto Scaler for Managed Group Instances (MIG)
🔍 Ops Agent (Logs and metrics)
🔑 Cloud Key Management Service
☁️ Cloud DNS
💻 Virtual Machines
🗄️ Cloud SQL
🛠️ Code

For more specific implementation details, visit the repos :

Application and REST APIs : https://github.com/shivabcloud/webapp
Infrastructure: https://github.com/shivabcloud/tf-gcp-infra
Cloud Function: https://github.com/shivabcloud/serverless
