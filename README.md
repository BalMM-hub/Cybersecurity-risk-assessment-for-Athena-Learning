# Cybersecurity risk assessment for Athena Learning Inc.

A structured qualitative cybersecurity risk assessment conducted for **Athena Learning Inc.**, a fictional cloud-based education technology company. This project demonstrates practical cybersecurity risk assessment skills, including asset identification, threat and vulnerability analysis, qualitative risk rating, and security control recommendations.

**Author:** Kehinde Oyewumi

---

## Project overview

This project documents a cybersecurity risk assessment performed for Athena Learning Inc., a fictional organization that delivers online courses, certification programs, and virtual learning services through a cloud-hosted learning platform.

The objective of the assessment was to identify the organization's most critical assets, evaluate the cybersecurity threats affecting those assets, determine the potential business impact of identified risks, and recommend security controls to reduce operational and information security exposure.

Unlike a vulnerability assessment or penetration test, this project focuses on **risk identification, prioritization, and risk treatment planning**, following a structured qualitative assessment methodology.

---

## Project objective

The assessment was designed to:

* identify critical business assets,
* analyze relevant cybersecurity threats,
* assess vulnerabilities affecting those assets,
* evaluate likelihood and business impact,
* determine overall risk severity,
* recommend appropriate security controls.

---

## Business scenario

Athena Learning Inc. operates a cloud-based Learning Management System (LMS), processes online payments, stores student and employee records, and supports a remote workforce using corporate and personally owned devices.

Because the organization relies heavily on cloud services, web applications, and remote access, it faces risks related to:

* unauthorized access to sensitive student data,
* payment system compromise,
* web application attacks,
* cloud misconfiguration,
* and endpoint security weaknesses.

This assessment evaluates those risks and prioritizes them based on **likelihood and business impact**.

---

## Repository contents

| File | Description |
| ---- | ------------ |
| [`risk-assessment-report.pdf`](risk-assessment-report.pdf) | Comprehensive assessment report containing the business context, assessment scope, methodology, asset inventory, risk analysis, prioritized findings, and recommended security controls. |
| [`risk-register.xlsx`](risk-register.xlsx) | Structured risk register documenting identified assets, threats, vulnerabilities, likelihood, impact, overall risk ratings, and mitigation recommendations. |
| [`assets/risk-matrix.png`](assets/risk-matrix.png) | Qualitative likelihood × impact matrix used to prioritize identified cybersecurity risks. |
| [`assets/network-overview.png`](assets/network-overview.png) | High-level network and asset architecture illustrating the organization's systems, cloud services, and critical infrastructure. |

---

## Assessment methodology

A qualitative risk assessment methodology was used throughout the project.

1. Asset identification
2. Threat identification
3. Vulnerability assessment
4. Likelihood evaluation
5. Business impact evaluation
6. Risk rating (Low / Medium / High / Critical)
7. Security control recommendation

Risk ratings were determined using a **likelihood × impact model**, allowing identified risks to be prioritized for remediation.

---

## Key findings

The assessment identified several high-priority cybersecurity risks affecting Athena Learning Inc.

### Critical risks

* **Student data exposure** — risk of unauthorized access, identity theft, credential compromise, and data leakage.
* **Learning Management System compromise** — risk of SQL injection, authentication bypass, and web application exploitation.

### High risks

* **Payment processing systems** — risk of financial fraud, database theft, and transaction manipulation.
* **Cloud security weaknesses** — excessive permissions, exposed cloud storage, insecure identity management, and monitoring gaps.

### Medium risks

* **Remote workforce and BYOD** — increased risk of credential theft, malware infection, and insecure endpoint configurations.

The complete risk register and detailed control recommendations are documented in the assessment report.

---

## Recommended security controls

The assessment recommends security improvements across multiple domains.

### Identity and access management

* Multi-factor authentication (MFA)
* Role-based access control (RBAC)
* Privileged account monitoring
* Strong password policies

### Data protection

* Encryption at rest
* Encryption in transit
* Secure key management
* Data classification

### Network security

* Network segmentation
* Firewall hardening
* VPN protection
* DNS security monitoring

### Application security

* Secure software development practices
* Input validation
* Parameterized queries
* Web Application Firewall (WAF)

### Endpoint security

* Full disk encryption
* Endpoint protection
* Mobile device management
* Automated patch management

### Monitoring and detection

* Centralized logging
* SIEM monitoring
* Security alert correlation
* Audit log review

---

## Skills demonstrated

This project demonstrates practical cybersecurity and GRC skills, including:

* cybersecurity risk assessment,
* asset classification,
* threat and vulnerability analysis,
* qualitative risk evaluation,
* risk prioritization,
* security control selection,
* technical documentation,
* and security reporting.

---

## What I learned

This project reinforced that cybersecurity risk assessment is not simply identifying threats; it is a structured process of evaluating business impact, prioritizing risks, and recommending practical controls that align with organizational objectives.

Conducting this assessment strengthened my understanding of asset classification, qualitative risk analysis, security control selection, and professional cybersecurity documentation.

---

## Disclaimer

Athena Learning Inc. is a fictional organization created for educational and portfolio purposes. This assessment was independently developed to demonstrate cybersecurity risk assessment methodology and documentation practices commonly used in cybersecurity, governance, risk, and compliance (GRC) environments.
