# ☁️ Cloud Infrastructure & Web Application Deployment Portfolio

This repository contains documentation, configurations, and visual proofs for cloud infrastructure setup, security management, and web application deployment.

---

## 1. Cloud Core Concepts & Infrastructure Services
Explore compute services, object storage, managed databases, virtual networking, IAM policies, and cloud monitoring.

* **Virtual Networking (VPC):** Configured a secure and isolated cloud networking environment using Amazon VPC[cite: 1].
  <div align="center">
    <img src="assets/vpc-dashboard.png" alt="VPC Dashboard" width="800px" />
    <p><i>Figure 1.1: Active VPC Dashboard and Details[cite: 1]</i></p>
  </div>

* **Object Storage (Amazon S3):** Stored and managed application notes and files securely in an Amazon S3 bucket[cite: 2].
  <div align="center">
    <img src="assets/s3-storage.png" alt="Amazon S3 Storage" width="800px" />
    <p><i>Figure 1.2: Amazon S3 Bucket Containing cloud-notes.txt[cite: 2]</i></p>
  </div>

---

## 2. Cloud Security, Logging & Resource Management
Manage environment variables, secrets, application logging, and resource quotas securely in the cloud.

* **Environment Variables:** Configured runtime variables (`APP_ENV=production`) in the Linux cloud environment[cite: 3, 10].
  <div align="center">
    <img src="assets/env-variables.png" alt="Environment Variables" width="750px" />
    <p><i>Figure 2.1: Setting and Verifying Environment Variables[cite: 3, 10]</i></p>
  </div>

* **Secrets Management:** Stored sensitive credentials securely using AWS Secrets Manager[cite: 9].
  <div align="center">
    <img src="assets/secrets-manager.png" alt="Secrets Manager" width="800px" />
    <p><i>Figure 2.2: Stored Secrets in AWS Secrets Manager[cite: 9]</i></p>
  </div>

* **Application Logging & Monitoring:** Set up centralized CloudWatch log groups for application monitoring[cite: 8].
  <div align="center">
    <img src="assets/cloudwatch-logs.png" alt="CloudWatch Logs" width="800px" />
    <p><i>Figure 2.3: Application Log Groups in AWS CloudWatch[cite: 8]</i></p>
  </div>

* **Resource Quotas & Scaling:** Monitored auto-scaling and service quotas via AWS Service Quotas[cite: 7].
  <div align="center">
    <img src="assets/service-quotas.png" alt="Service Quotas" width="800px" />
    <p><i>Figure 2.4: EC2 Auto Scaling Service Quotas[cite: 7]</i></p>
  </div>

---

## 3. Deploying a Web Application Workflow
**Workflow:** Application Code → Cloud Compute → Database/Storage → Networking → Live Web Application.

* **Step 1: Application Code Development**  
  Created the HTML structure and CSS style configurations for the web application[cite: 4, 6].
  <div align="center">
    <img src="assets/html-code-structure.png" alt="HTML Structure" width="600px" />
    &nbsp;&nbsp;
    <img src="assets/html-code-style.png" alt="CSS Style" width="600px" />
    <p><i>Figure 3.1 & 3.2: Web Application HTML Structure and Styling[cite: 4, 6]</i></p>
  </div>

* **Step 2 & 3: Cloud Compute & Web Server Setup**  
  Deployed code to an Ubuntu EC2 instance and ran the Nginx web server[cite: 3].
  <div align="center">
    <img src="assets/nginx-status.png" alt="Nginx Status" width="800px" />
    <p><i>Figure 3.3: Nginx Web Server Active (Running) Status[cite: 3]</i></p>
  </div>

* **Step 4: Live Web Application**  
  Successfully accessed the live application globally via the EC2 instance's Public IP address[cite: 5].
  <div align="center">
    <img src="assets/live-website.png" alt="Live Website" width="750px" />
    <p><i>Figure 3.4: Live Web Application Running on Public IP (54.79.66.170)[cite: 5]</i></p>
  </div>
