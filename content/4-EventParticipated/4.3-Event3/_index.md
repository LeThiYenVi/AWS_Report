---
title: "Event 3"
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# EVENT HARVEST REPORT
**Event:** AWS Cloud Mastery Series #2: From DevOps, IaC to Container & Observability

---

## 1. ATTENDANCE OBJECTIVES
Event participation focused on 4 core objectives to enhance technical capabilities and strategic thinking:
* **Shaping Mindset:** Grasp the essence of the Value Cycle and DevOps mission in ensuring continuous and reliable software flow.
* **Infrastructure Automation (IaC):** End the era of manual operations (ClickOps), transition to infrastructure management through code with three key tools: CloudFormation, Terraform, and CDK.
* **Containerization Strategy:** Deep understanding of architecture and criteria for selecting optimal Container operating platforms: App Runner for simplicity, ECS for efficiency, or EKS for flexibility.
* **Proactive Monitoring (Observability):** Establish comprehensive "eyes and ears" system to detect incidents and optimize performance through CloudWatch and X-Ray.

---

## 2. SPEAKER LIST
The event brought together top experts from AWS and Cloud Engineering:
* **AWS Experts & Cloud Engineers Team** – Engineers and solution architects sharing Platform Engineering models and hands-on technical demos.

---

## 3. TECHNICAL CONTENT HIGHLIGHTS

### 3.1. DevOps Mindset & CI/CD Pipeline (Foundation of Thinking)
The event redefined DevOps not just as tools, but as a culture optimizing value flow:
* **The Value Cycle:** A complete 5-stage cycle from Insights $\rightarrow$ Portfolio $\rightarrow$ CI $\rightarrow$ Testing $\rightarrow$ CD. The goal is balancing Release Speed and Stability.
* **Clearly distinguish automation levels:**
    * *Continuous Integration (CI):* Daily code merges, automatic Build and Test to detect errors early (Fail fast).
    * *Continuous Delivery:* Automatic deployment to Staging, but requires human approval (Manual Trigger) for Production.
    * *Continuous Deployment:* 100% automation of flow from Commit to Production.
* **Optimal Pipeline Strategy:**
    * *Centralized CI:* Build centralized CI for management but empower Self-service for Developers.
    * *Artifact Management:* Follow the principle **"Build Once, Deploy Anywhere"**. Package source code only once (Artifact) and use it for all environments to ensure consistency.
    * *Fail Conditions:* Pipeline must stop immediately if encountering compilation errors, code standard violations, security vulnerabilities, or slow tests.
    * *Metrics:* Use Heatmap and DORA metrics (Deploy frequency, Failure rate, MTTR) to measure process health.

### 3.2. Infrastructure as Code (IaC) - From ClickOps To Code
Journey to eliminate risks from manual operations (ClickOps) towards Accuracy, Scalability, and Collaboration:
* **AWS CloudFormation (Native):** Use YAML/JSON to define resources. Manage lifecycle through Stack concept (deleting Stack cleans up resources).
* **Terraform (Multi-Cloud):** Open-source power with HCL language. Standard workflow: Write $\rightarrow$ Plan (Preview changes) $\rightarrow$ Apply. Strength is multi-platform management capability (AWS, Azure, GCP) and state management through State File.
* **AWS CDK (Code-based):** Define infrastructure using programming languages (Python, TypeScript...).
    * *Constructs:* From L1 (Detailed configuration) to L3 (Pre-built architecture Patterns).
    * *Drift Detection:* Critical feature to detect configuration drift from manual edits, helping maintain system discipline.

### 3.3. Containerization - Application Running Strategy
Analysis of Orchestration and Compute choices:
* **Comparing ECS vs. EKS:**
    * *Amazon ECS:* Simple, tightly integrated with AWS ecosystem, suitable for teams wanting fast deployment and reduced operations.
    * *Amazon EKS:* Kubernetes standard, powerful and flexible, for complex Enterprise systems or Hybrid-cloud.
* **Compute Models:**
    * *EC2 Launch Type:* Maximum control but requires server management effort.
    * *AWS Fargate:* Serverless for containers, only need to care about CPU/RAM, AWS handles underlying infrastructure.
    * *AWS App Runner:* "Zero-ops" solution, turn code/image into Web App with HTTPS in just a few steps, no network/server configuration needed.

### 3.4. Observability - Monitoring & Optimization
Ensure deep and broad observability for stable operations:
* **Amazon CloudWatch:** Collect performance data (Metrics), centralized logs (Logs), and automatic response (Alarms) when system encounters issues.
* **AWS X-Ray:** Distributed Tracing tool, helps trace request journey through microservices to find Bottlenecks and root causes.
* **Best Practices:** Clearly distinguish roles of Logs (events) and Traces (journeys); use standard AWS Patterns to set up monitoring.

---

## 4. DETAILED EVENT EXPERIENCE

This topic completely changed my perspective on system operations:

### 4.1. Shift from "Ops" to "Platform Engineering"
I realized modern DevOps is not about running after Developers to deploy for them. DevOps is about building "Highways" (Pipeline & Platform). A good platform is where Developers can self-serve infrastructure needs within the safe framework (Governance) that the DevOps team has established.

### 4.2. Operational Discipline
The principles of **Artifact Management** and **Drift Detection** are valuable lessons. In enterprise environments, Consistency is a critical factor. Absolutely do not rebuild code in different environments and strictly prohibit manual configuration changes when IaC has been applied.

### 4.3. Smart Tool Selection Strategy
There is no "best" tool, only the "most suitable" choice:
* Need stability and native support: Choose **CloudFormation**.
* Multi-cloud enterprise: **Terraform** is mandatory.
* Team strong in programming, needs to reuse complex architecture: **AWS CDK** is the ultimate weapon.
* Simple Web App: Use **App Runner** instead of wasting resources operating Kubernetes.

---

## 5. CONCLUSION

The "DevOps & IaC Mastery" topic painted a complete roadmap for Cloud modernization journey:

* **About Mindset:** Complete transition from manual to automation and data-driven measurement.
* **About Infrastructure:** Master IaC to ensure scalability, reproducibility, and configuration control.
* **About Operations:** The combination of flexible Containerization and deep Observability is the key to a high-performance and sustainable system.

This is a solid knowledge foundation for me to confidently build and operate large-scale software systems on AWS.

---

