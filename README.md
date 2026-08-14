# SafeX Solutions – AI Report Generator Prototype

## Week 2 Internship Contribution

**Intern:** Ali Ammar Haider  
**University:** COMSATS University Islamabad  
**Internship Domain:** Artificial Intelligence & Machine Learning (AI/ML)  
**Role:** Group Member – Individual Module Contributor  

---

## Project

**Business Automation Research – AI Report Generator Prototype**

This project is my individual Week 2 contribution to the SafeX Solutions Business Automation Research group project.

The module processes a sample business project dataset, calculates key performance metrics, generates visual analytics, uses Google Gemini 2.5 Flash to produce AI-powered business insights, and generates downloadable weekly business reports.

> **Note:** This repository contains my individual `report_generator` module contribution to the group project, not the complete group project.

---

## My Contribution

As an individual module contributor, I developed the **AI Report Generator** component responsible for:

- Processing structured business project data using Pandas
- Calculating project performance KPIs
- Calculating an overall operational health score
- Generating business performance visualizations
- Sending summarized business metrics to Google Gemini 2.5 Flash
- Generating AI-powered business analysis and recommendations
- Creating a weekly text-based business report
- Generating a professional PDF business report
- Providing a Streamlit-based interface for viewing results
- Providing PDF and TXT report download functionality

---

## Key Features

### Data Analysis

The module analyzes a sample dataset containing **40 business projects** and calculates metrics including:

- Total projects
- Completed projects
- In-progress projects
- Pending projects
- Average project completion
- Total and average hours worked
- Total budget
- Actual project cost
- Budget difference
- Client satisfaction
- Project delays
- Risk levels
- Department-level performance

### Operational Health Score

An overall project health score is calculated using:

- Average project completion
- Client satisfaction
- On-time project performance

The resulting score provides a high-level indicator of overall operational performance.

### AI Business Analysis

Google Gemini **2.5 Flash** is used to analyze the calculated business metrics and generate structured insights covering:

- Executive Summary
- Performance Analysis
- Financial Analysis
- Risk Analysis
- Client Satisfaction Analysis
- Business Recommendations

### Data Visualizations

The module automatically generates eight performance charts:

1. Project Status Distribution
2. Projects by Department
3. Risk Level Distribution
4. Budget vs Actual Cost
5. Average Client Satisfaction
6. Completion Percentage Distribution
7. Total Hours Worked by Department
8. Average Completion by Department

### Report Generation

The system generates:

- Weekly business report in `.txt` format
- Professional business report in `.pdf` format
- Automatically generated performance charts

### Streamlit Dashboard

The Streamlit interface provides:

- KPI metric cards
- Weekly report summary
- Interactive performance chart display
- AI-generated business insights
- PDF report download
- Plain-text report download
- Refresh / re-run functionality

---

## Project Structure

```text
safex-week2-ai-report-generator/
│
├── report_generator/
│   ├── data/
│   │   └── weekly_projects_40_enhanced.csv
│   │
│   ├── outputs/
│   │   ├── charts/
│   │   │   ├── budget_vs_cost.png
│   │   │   ├── client_satisfaction.png
│   │   │   ├── completion_by_department.png
│   │   │   ├── completion_distribution.png
│   │   │   ├── hours_worked.png
│   │   │   ├── projects_by_department.png
│   │   │   ├── project_status_pie.png
│   │   │   └── risk_levels.png
│   │   │
│   │   └── reports/
│   │       ├── Weekly_Business_Report.pdf
│   │       └── weekly_report.txt
│   │
│   ├── engine.py
│   ├── ui.py
│   └── __init__.py
│
├── README.md
├── requirements.txt
└── .gitignore