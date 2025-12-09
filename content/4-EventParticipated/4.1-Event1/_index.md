---
title: "Event 1"
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# EVENT HARVEST REPORT
**Event:** Vietnam Cloud Day 2025: Ho Chi Minh City Connect Edition for Builders  
**Track 1:** GenAI & Data

---

## 1. ATTENDANCE OBJECTIVES
Event participation focused on 4 core objectives to enhance technical capabilities and strategic thinking:
* **GenAI Security:** Understanding security mechanisms in GenAI and AI Agents to ensure enterprise data safety.
* **Development Process (AI-DLC):** Exploring the *AI-Driven Development Lifecycle* model and how to integrate it into current DevOps processes.
* **Data Platform:** Methods for building a Unified Data Platform optimized for Analytics and AI.
* **Trend Updates:** Grasping strategies, vision, and latest GenAI technologies on AWS.

---

## 2. SPEAKER LIST (AWS EXPERTS)
The event brought together top experts from Amazon Web Services:
* **Jun Kai Loke** – AI/ML Specialist SA
* **Kien Nguyen** – Solutions Architect
* **Tamelly Lim** – Storage Specialist SA
* **Binh Tran** – Senior Solutions Architect
* **Taiki Dang** – Solutions Architect
* **Michael Armentano** – Principal WW GTM Specialist

---

## 3. TECHNICAL CONTENT HIGHLIGHTS

### 3.1. Unified Data Platform
Data is the core foundation ("Data is the fuel") for successful AI deployment.
* **End-to-End Architecture:** Complete workflow from Ingestion $\rightarrow$ Storage $\rightarrow$ Processing $\rightarrow$ Access $\rightarrow$ Governance.
* **Objective:** Eliminate "Silos" (isolation) in data, people, and processes. Moving towards Self-service and standardized Governance.
* **Key AWS Services:** S3, Glue, Redshift, Lake Formation, OpenSearch, Kinesis/MSK.
* **Featured Technology:** **Zero-ETL integration** (connecting S3 $\leftrightarrow$ Redshift, Aurora, DynamoDB...) helps minimize latency and complexity in data transfer.

### 3.2. GenAI Strategy & Tools on AWS
* **Amazon Bedrock:** Primary service allowing Foundation Models (FM) selection, RAG integration, Guardrails, optimization between cost and latency.
* **Amazon SageMaker Unified Studio:** Unified platform for Data, Analytics & AI. Comprehensive MLOps support (Pipelines, Registry, Deployment, Monitoring).
* **AI Agents - Productivity Enhancement:** Transition from single Assistant to Multi-agent systems (like AgentCore, Amazon Nova). Supporting frameworks: CrewAI, LangGraph, LlamaIndex.
* **Real-world Applications:** Customer service (CS), Business Intelligence (BI) with Amazon Q (in QuickSight), business process automation.

### 3.3. GenAI Security & Trust
* **Multi-layer Security Model:** Protection from Infrastructure $\rightarrow$ Model $\rightarrow$ Application.
* **5 Security Pillars:** Compliance, Privacy, Controls, Risk Management, Resilience.
* **Hallucination Mitigation:** Combining Prompt Engineering, RAG (Retrieval-Augmented Generation), and Fine-tuning.
    * *RAG Workflow:* Input $\rightarrow$ Embedding $\rightarrow$ Context $\rightarrow$ LLM $\rightarrow$ Output.
* **Control Tools:** Bedrock Guardrails, Human-in-the-loop, Observability (OpenTelemetry) to prevent risks according to OWASP LLM standards.

### 3.4. AI-Driven Development Lifecycle (AI-DLC)
A new concept in software development lifecycle:
* **Evolution:** AI-Assisted $\rightarrow$ AI-Driven $\rightarrow$ AI-Managed.
* **Stages:** Inception $\rightarrow$ Construction $\rightarrow$ Operation.
* **Implementation:** Integrating Infrastructure as Code (IaC), automated testing, monitoring, and risk management directly into the process.

---

## 4. KEY TAKEAWAYS & NEW THINKING

After the event, I synthesized important changes in thinking and strategy:

1.  **System Design Thinking:**
    * Must design Data & AI systems in an **End-to-end** approach, firmly eliminating Data Silos.
    * Apply **Self-service** and **Governance** principles from the early stages.

2.  **Technical Architecture:**
    * Leverage the power of **Zero-ETL** and **Lakehouse** for sustainable, easily scalable system operations.
    * Combine service pieces (S3, Glue, Bedrock...) into a unified platform instead of disparate tools.

3.  **Development Strategy:**
    * **Business-first:** All technology decisions must originate from business problems. Data and Security are the "Foundation" - without this foundation, AI cannot deliver value.
    * **Balance:** Between innovation speed and cost/security.
    * **AI-DLC:** Standardize development processes with AI participation at every stage (Code, Review, Test, Doc).

---

## 5. APPLICATION PLAN FOR WORK

Based on learned knowledge, I propose specific application plans:

**In Real Projects:**
* Pilot **AI Agent** for Login/Registration module and Customer Support (Chatbot).
* Integrate **Validation/Guardrails** to ensure GenAI input/output data safety.

**In Learning & Teamwork:**
* Apply **AI-DLC** model: Use AI to assist in writing boilerplate code and creating technical documentation; humans focus on Review and Approve.
* Clearly analyze when to use **Serverless (Lambda)** (for short tasks, events) and when to use **Containers (ECS/Fargate)** (for long-term, complex applications).

**In Personal Role:**
* Practice documentation thinking and requirements gathering in a Business-first approach.
* Focus on building a solid Data Foundation before deploying complex AI models.

---

## 6. EVENT & WORKSHOP EXPERIENCE
*(Recording actual experience at the event)*

The most memorable highlight was the **"GenAI-powered App-DB Modernization"** Workshop. This was a valuable opportunity to practice modernizing applications and databases:
* **Technical Experience:** Hands-on designing end-to-end data pipelines and accessing latest tools like Amazon Bedrock, AgentCore.
* **RAG Practice:** Deep understanding of how to minimize Hallucination through coordinating Prompt Engineering and RAG workflow.
* **Expert Connection:** Direct exchanges with AWS engineers about real Case Studies, helping strengthen confidence in Multi-agent models and AI-DLC.

> **Conclusion:** GenAI is not just a trend tool, but requires a comprehensive strategy from Infrastructure Architecture, Data to Security to truly bring value to enterprises.

---

