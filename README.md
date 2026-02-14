# Software Quality Management Case Study  
## Netflix Streaming Platform  


## 1. Project Overview

This project presents a structured Software Quality Management (SQM) framework for the Netflix Online Streaming Platform.

Netflix is a global subscription-based video-on-demand service that relies heavily on distributed cloud-native software systems. Due to its massive scale and business dependency on continuous availability, software quality is a critical success factor.

This case study applies recognized quality frameworks including:

- ISO/IEC 25010 Software Quality Model
- CMMI Process Maturity Model
- Defect Analysis and Classification
- Risk Management Framework
- GitHub-based Quality Governance Workflow

The objective is to demonstrate how theoretical software quality models can be practically implemented using modern development tools.


## 2. System Background

### Organization
Netflix, Inc.

### System Type
- Web-based platform  
- Mobile applications (Android & iOS)  
- Smart TV & embedded device applications  
- Cloud-native microservices backend  

### Stakeholders
- Global subscribers  
- Content licensors  
- Developers and QA teams  
- Business executives  
- Cloud service providers  

### Business Impact
Software quality directly affects:
- Service availability
- Customer retention
- Revenue stability
- Data security compliance


## 3. Quality Objectives (ISO/IEC 25010)

The following quality characteristics were selected:

### 3.1 Functional Suitability
Ensures core features (search, playback, personalization) function correctly.  
**Monitoring:** Functional testing, defect density tracking.

### 3.2 Performance Efficiency
Ensures fast startup times and minimal buffering.  
**Monitoring:** Load testing, latency metrics, stress testing.

### 3.3 Reliability
Ensures continuous service availability.  
**Monitoring:** Uptime %, MTBF, incident frequency.

### 3.4 Usability
Ensures intuitive navigation and accessibility across devices.  
**Monitoring:** Usability testing, user feedback surveys.

### 3.5 Security
Protects personal and financial data.  
**Monitoring:** Penetration testing, vulnerability scans, compliance audits.


## 4. Defect Management Framework

A total of 9 defects (D1–D9) were identified and classified based on:

- Severity (Critical / Major / Minor)
- Priority (High / Medium / Low)
- Root Cause (Process / Infrastructure / Security Policy / UX Design)

Defects are tracked using:
- GitHub Issues
- Labels
- Milestones
- Project Board workflow


## 5. CMMI Process Maturity Assessment

### Current Level: CMMI Level 2 – Managed

Justification:
- Project-level planning exists
- Defect tracking is implemented
- Testing processes are structured
- Risk management is reactive

### Improvement Plan (Towards Level 3 – Defined)

1. Standardize quality processes organization-wide
2. Implement formal peer reviews
3. Establish centralized metrics dashboard
4. Proactive risk monitoring framework


## 6. Risk Management Strategy

Five quality-related risks were identified (R1–R5), analyzed using:

- Likelihood
- Impact
- Risk Exposure Level

Mitigation strategies include:
- Change management procedures
- Multi-region redundancy
- Security audits & MFA
- Automated CI/CD testing
- Continuous performance monitoring

All risks are documented and tracked using GitHub Issues.


## 7. GitHub Quality Governance Workflow

This repository demonstrates:

- Structured Issue tracking
- Label-based classification
- Milestone-based lifecycle management
- Project Board workflow:
  - Backlog
  - In Progress
  - Review
  - Done

This ensures traceability between:
Quality Objectives → Defects → Risks → Process Improvements


## Conclusion

This case study demonstrates the structured application of Software Quality Management principles to a real-world large-scale distributed system.

By integrating ISO 25010, CMMI, defect analysis, and risk management into GitHub governance, a measurable and controlled quality framework is established.
