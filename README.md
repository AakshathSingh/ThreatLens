<div align="center">

# 🛡️ ThreatLens

### Threat Detection & Incident Response Platform

*A Full-Stack Security Operations Center (SOC) Platform for Automated Threat Detection, Log Analysis, Incident Investigation, Threat Intelligence Enrichment and Security Reporting.*

<p>

![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?style=for-the-badge&logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-Framework-000000?style=for-the-badge&logo=express)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma)
![JWT](https://img.shields.io/badge/JWT-Secure%20Authentication-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</p>

*A cybersecurity internship capstone project that simulates the workflow of a modern Security Operations Center (SOC), enabling analysts to detect, investigate and respond to cyber threats through automated log analysis and interactive security dashboards.*

</div>

---

# 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [System Architecture](#-system-architecture)
- [Application Workflow](#-application-workflow)
- [Project Modules](#-project-modules)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Future Enhancements](#-future-enhancements)
- [Learning Outcomes](#-learning-outcomes)
- [Author](#-author)

---

# 📌 Project Overview

ThreatLens is a full-stack web application developed to simulate the workflow of a modern Security Operations Center (SOC). The platform provides a centralized environment where analysts can securely upload security logs, detect malicious activities, investigate incidents, visualize Indicators of Compromise (IOCs), and generate detailed security reports.

Modern organizations generate enormous volumes of logs every day, making manual investigation both time-consuming and error-prone. ThreatLens streamlines this process by combining automated log parsing, rule-based threat detection, threat intelligence enrichment, interactive dashboards, and investigation tools into a single platform.

Built using Node.js, Express.js, Prisma ORM, MySQL, and a responsive frontend, the application demonstrates secure software development practices while incorporating real-world cybersecurity concepts such as the MITRE ATT&CK framework, IOC correlation, risk scoring, and incident response.

The project was developed as an internship capstone to bridge the gap between theoretical cybersecurity knowledge and practical SOC operations by replicating how analysts investigate security events from initial detection through final reporting.

---

# 🎯 Problem Statement

Security analysts often work with data from multiple tools to investigate a single incident. Logs may reside in one system, threat intelligence in another, dashboards elsewhere, and reporting tools separately. This fragmented workflow increases investigation time and the likelihood of missing critical indicators.

ThreatLens addresses this challenge by providing a unified platform where log ingestion, detection, enrichment, visualization, investigation, and reporting are integrated into a seamless workflow. The application demonstrates how automation can reduce analyst workload while improving the speed and consistency of security investigations.

---

# ✨ Key Features

## 🔐 Secure Authentication

- User Registration
- Secure Login
- JWT Authentication
- Password Hashing using bcrypt
- Protected API Routes
- User-specific data isolation

---

## 📁 Log Management

- Upload security log files
- Drag-and-drop file upload
- Upload history
- Processing status tracking
- Secure file validation
- Multiple log format support

---

## ⚙️ Detection Engine

ThreatLens includes a rule-based detection engine capable of identifying common attack patterns from uploaded log files.

Implemented detection rules include:

- SQL Injection
- Cross-Site Scripting (XSS)
- Directory Traversal
- Suspicious User-Agent Detection
- Sensitive File Access

---

## 🌐 Threat Intelligence

Security events are enriched using external threat intelligence to improve investigation quality.

Features include:

- VirusTotal integration
- Reputation lookup
- IOC enrichment
- External threat validation

---

## 🎯 MITRE ATT&CK Mapping

ThreatLens automatically maps detected activities to the MITRE ATT&CK framework, helping analysts understand attacker tactics and techniques during investigations.

---

## 📊 Security Dashboard

The dashboard provides a real-time overview of platform activity through interactive charts and security metrics including:

- Alert Summary
- Severity Distribution
- Attack Trends
- Top Source Countries
- Recent Alerts
- MITRE ATT&CK Overview

---

## 🚨 Alert Management

Detected threats are automatically converted into alerts containing:

- Risk Score
- Severity Level
- Detection Rule
- Timestamp
- IOC Details
- Investigation Status

---

## 🔍 IOC Relationship Graph

ThreatLens visualizes relationships between Indicators of Compromise through an interactive graph, allowing analysts to quickly understand how malicious entities are connected during an investigation.

---

## 📅 Incident Investigation

The investigation module combines multiple sources of information into a single view including:

- Incident Timeline
- Threat Intelligence
- IOC Relationships
- MITRE ATT&CK Mapping
- Risk Assessment

---

## 📄 Security Reporting

The reporting module enables analysts to review completed investigations and generate structured security reports summarizing threats, findings, and recommended actions.

---

# 🚀 Why ThreatLens?

Unlike traditional log viewers, ThreatLens combines multiple stages of the incident response lifecycle into one integrated platform.

✔ Secure authentication

✔ Automated log parsing

✔ Rule-based threat detection

✔ Threat intelligence enrichment

✔ MITRE ATT&CK mapping

✔ IOC relationship visualization

✔ Dynamic risk assessment

✔ Interactive dashboards

✔ Incident investigation

✔ Security reporting

---

> **Next:** Part 2 will cover the Technology Stack, System Architecture (with Mermaid diagrams), Application Workflow, and the detailed Project Modules section with explanations of how each component works.
