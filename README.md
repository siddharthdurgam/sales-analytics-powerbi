# Sales Analytics Dashboard — SQL + Power BI

> End-to-end sales analytics project combining SQL analysis, Power BI data transformation, and interactive dashboarding to turn 150,000+ sales transactions into actionable business insights.

## 📊 Project Overview

This project analyzes **150,000+ transactions across 4 years** and provides stakeholders with a consolidated view of sales performance and market trends.

The workflow follows a practical Business Analyst / Data Analyst process:

**SQL Analysis → Data Cleaning & ETL → Power BI Data Model → Dashboard Development → Business Insights**

## 🎯 Business Objectives

- Track overall revenue and sales performance
- Analyze revenue and sales quantity by market
- Identify top-performing customers and products
- Monitor revenue trends over time
- Compare market performance across regions
- Reduce manual reporting effort through dashboard automation

## 💼 Business Impact

Based on the project documentation:

- Reduced analysis time by **80%** through automated reporting
- Enabled faster access to sales insights for stakeholders
- Improved market performance tracking across regions

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| **SQL / MySQL** | Initial data analysis and metric exploration |
| **Power BI** | Data cleaning, transformation, modeling and visualization |
| **Power Query** | ETL and data preparation |
| **DAX** | Dashboard KPIs and analytical calculations |

## 🔄 Project Workflow

### Phase 1 — Data Analysis & ETL

- Analyzed the sales dataset using SQL/MySQL
- Used Power BI transformation tools for data preparation
- Removed blank rows
- Removed sales records with values ≤ 0
- Normalized currency to INR
- Removed duplicate transactions

### Phase 2 — Dashboard Development

Built an interactive Power BI dashboard containing:

- Total revenue tracking
- Revenue by market
- Sales quantity by market
- Year and month filtering
- Top 5 customers
- Top 5 products
- Revenue trend analysis

## 🎥 Video Demonstration

A project demonstration is available in the original project documentation.

## 📁 Repository Structure

```text
sales-analytics-powerbi/
├── README.md
├── db_dump.sql
├── sales_dashboard.pbix
└── docs/
    └── project-notes.md
```

## 🚀 Setup & Usage

1. Install **Power BI Desktop**.
2. Clone this repository or download `sales_dashboard.pbix`.
3. Open `sales_dashboard.pbix` in Power BI Desktop.
4. If a live database connection is required, configure the appropriate database connection settings in Power BI.

> Never commit passwords, API keys, or private database credentials to this public repository.

## 🔐 Public Repository Safety

Before publishing SQL/database files, remove machine-specific connection information, credentials, and other private configuration details. The public repository should contain only sanitized project assets.

## 💼 Business Analyst Relevance

This project demonstrates practical skills relevant to Data Analyst and Business Analyst roles:

- SQL analysis
- Data cleaning and ETL
- KPI definition
- Power BI dashboard development
- Business performance analysis
- Trend analysis
- Stakeholder-focused reporting
- Data-driven decision support

## 👤 Author

**Siddharth Patel**  
Data Analyst | Business Analyst | Python Developer

- LinkedIn: https://www.linkedin.com/in/siddharth-durgam-878632263
- GitHub: https://github.com/siddharthdurgam
