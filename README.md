# EduFin Crisis Analytics — Education Loan Portfolio Risk Investigation
#### Description

EduFin Crisis Analytics is a comprehensive SQL-based financial risk analysis project designed to investigate a ₹12 Crore discrepancy in student loan disbursements affecting 15,000+ accounts.
The project simulates a real-world fintech crisis scenario where a Data Analyst must deliver board-level insights within 48 hours before a federal compliance audit.
Using portfolio, customer, geographic, institutional, and payment data, this project performs a 5-phase investigative analysis to identify:

• Portfolio health deterioration
• Geographic default hotspots
• High-risk borrower segments
• Poor-performing institutional partners
• Timeline of the crisis escalation

The project focuses on transforming raw financial data into executive-ready dashboards, risk classifications, and strategic recommendations using advanced SQL analytics.

#### 🛠️ Tech Stack
• SQL (MySQL / PostgreSQL compatible)
• Window Functions
• CTEs (Common Table Expressions)
• Conditional Aggregation
• Date & Time Intelligence
• Risk Segmentation Logic
• Business KPI Analysis
• Financial Reporting Standards
• Excel / CSV Datasets
GitHub for Documentation & Version Control
#### 📂 Data Source

The analysis is based on EduFin’s simulated enterprise loan database containing 4 years of education lending data (2021–2025).
• Core Datasets
• loans.csv → Loan lifecycle & transactional data
• customers.csv → Borrower demographics & financial profiles
• institutions.csv → University & college partnerships
• payments.csv → EMI & repayment history
• defaults_collections.csv → Recovery & collection activity
• geographic_demographics.csv → Regional intelligence
• dim_city.csv → City & state mapping

#### Business Context
• ₹12 Crore loan discrepancy
• 15,000+ impacted student accounts
• Rising default rates beyond industry thresholds
• Compliance audit scheduled within one month
• Potential timestamp inconsistencies after Oracle → Salesforce migration (Jan 2024)

#### ✨ Features / Highlights
📊 Phase 1 — Portfolio Health Check

Executive-level analysis of:

• Total loan book size
• Portfolio valuation
• Default rate calculation
• Active vs Defaulted vs Overdue distribution
• Portfolio-at-risk exposure
• Automated health classification system
• Board-ready crisis summary

Key Insights
✔ Financial impact assessment/
✔ Risk category breakdown/
✔ Portfolio viability analysis
✔ Executive dashboard generation

🌍 Phase 2 — Geographic Risk Analysis

Regional performance analysis to identify:

• High-default cities
• Geographic concentration of losses
• Market-level financial exposure
• Regional lending risk classification

Key Insights
✔ City-wise default rates
✔ Geographic crisis hotspots
✔ Capital-at-risk mapping
✔ Strategic halt-lending recommendations

👥 Phase 3 — Customer Risk Segmentation

Advanced borrower profiling for collections prioritization.

Key Insights
✔ High-value defaulter identification
✔ Multi-loan default behavior
✔ CIBIL score risk correlation
✔ Income & employment default trends
✔ Priority-based collections target list

🏫 Phase 4 — Institutional Partnership Risk

Institution-level underwriting performance evaluation.

Key Insights
✔ University-wise default rates
✔ Financial loss attribution
✔ Partnership risk classification
✔ Blacklist candidate identification
✔ Partner scorecards for renegotiation decisions

📈 Phase 5 — Crisis Timeline & Time Intelligence

Time-series analysis to identify:
• Exact onset of the lending crisis
• Default trend acceleration
• Vintage cohort deterioration
• Rolling financial loss accumulation

Advanced SQL Concepts Used
✔ LAG() Window Functions
✔ Cohort Analysis
✔ Month-over-Month Default Velocity
✔ Rolling Aggregations
✔ Crisis Heatmaps
✔ Vintage Risk Tracking

#### 🚦 Portfolio Health Classification System
Classification	    Default Rate	        Action Required
🟢                 HEALTHY	≤ 5%	        Standard monitoring
🟠                 MODERATE RISK	5–10%	  Enhanced monitoring
🟡                 HIGH RISK	10–15%	    Collection escalation
🔴                 CRITICAL	>15%	        Crisis management activation
#### 📌 Business Problems Solved
• Quantified total financial exposure
• Identified highest-risk borrowers
• Detected failing geographic markets
• Measured institutional partner quality
• Pinpointed crisis onset timeline
• Generated board-level risk intelligence
• Supported compliance audit preparation
#### 📚 SQL Concepts Demonstrated
• Joins & Multi-table Analysis
• Aggregate Functions
• CASE Statements
• Window Functions
• Ranking Functions
• Cohort Analysis
• Risk Classification Logic
• Financial KPI Calculations
• Time-Series Analysis
• Business Intelligence Reporting
#### 🎯 Project Outcome

This project demonstrates how data analytics and SQL can be used in high-pressure fintech crisis environments to:

• Uncover hidden financial risks,
• Support executive decision-making,
• Improve underwriting strategy,
• Optimize collections operations,
and 
• Strengthen regulatory compliance readiness.
