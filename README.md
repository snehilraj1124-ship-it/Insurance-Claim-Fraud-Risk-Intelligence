# Insurance Claim Fraud & Risk Intelligence

An end-to-end insurance analytics and fraud intelligence system designed to analyze insurance claims, policyholder behavior, provider activity, suspicious claim patterns, and risk indicators.

The project combines **Python, Java, SQL, HTML, CSS, and JavaScript** to demonstrate a practical enterprise-oriented workflow for insurance claim analysis, anomaly detection, risk scoring, investigation, and visualization.

---

## 📌 Project Overview

Insurance organizations process a large number of claims every day. Identifying unusual claim behavior manually can be difficult when transaction volume increases.

This project provides an analytical prototype that processes insurance claim data and identifies potentially suspicious patterns using multiple risk indicators.

The system focuses on:

- Claim amount analysis
- Customer behavior analysis
- Claim frequency monitoring
- Provider risk profiling
- Duplicate claim investigation
- Anomaly detection
- Risk scoring
- Investigation prioritization
- Management-level KPI reporting
- Interactive dashboard visualization

The project is designed as a **decision-support and analytical prototype** rather than an automated system for making final fraud determinations.

---

## 🎯 Objectives

The main objectives of this project are:

1. Analyze historical insurance claim information.
2. Identify unusual claim amounts.
3. Detect customers with unusually frequent claims.
4. Analyze provider-level claim behavior.
5. Identify potentially duplicate claim patterns.
6. Generate transparent risk indicators.
7. Calculate an explainable claim risk score.
8. Prioritize cases for further investigation.
9. Provide SQL queries for fraud investigation.
10. Present analytical results through a web dashboard.

---

## 🏗️ System Architecture

```text
                 Insurance Claim Data
                         │
                         ▼
                Data Validation
                         │
                         ▼
                Data Preprocessing
                         │
                         ▼
                Feature Engineering
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
       Anomaly Detection       SQL Investigation
              │                     │
              └──────────┬──────────┘
                         ▼
                  Risk Indicators
                         │
                         ▼
                  Java Risk Engine
                         │
                         ▼
                 Risk Classification
                         │
                         ▼
              Investigation Dashboard
                         │
                         ▼
                  Analytical Report
