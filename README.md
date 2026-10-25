# Insurance Data Analysis | Power BI & MS SQL Server

##  Project Overview

This project focuses on analyzing insurance data using **Microsoft SQL Server, Power BI, and Power Query Editor** to transform raw data into meaningful insights through an interactive dashboard.

The project covers the complete data analysis workflow, starting with importing data into a SQL Server database and connecting it to Power BI, followed by data transformation, dashboard development, and visualization of key insurance metrics.

The interactive dashboard helps analyze insurance premiums, coverage amounts, claim amounts, policy types, claim statuses, and customer demographics.

## 🎯 Project Objectives

- Store and manage insurance data using Microsoft SQL Server.
- Connect SQL Server with Power BI for data analysis.
- Clean and transform data using Power Query Editor.
- Validate data types and create conditional columns.
- Build an interactive dashboard using Power BI visuals.
- Analyze policy distribution, insurance premiums, coverage, and claims.
- Present business insights through clear and interactive visualizations.

## 🛠️ Tools & Technologies

- **Microsoft SQL Server** — Database creation and data storage.
- **Microsoft Power BI** — Data visualization and dashboard development.
- **Power Query Editor** — Data cleaning and transformation.
- **CSV** — Source data format.

## 📂 Dataset Description

The dataset contains **10,004 records and 13 columns** related to insurance policies, customers, premiums, coverage, and claims.

### Key Columns

| Column | Description |
|---|---|
| PolicyNumber | Unique policy identifier |
| CustomerID | Customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| PolicyType | Type of insurance policy |
| PolicyStartDate | Policy start date |
| PolicyEndDate | Policy end date |
| PremiumAmount | Insurance premium amount |
| CoverageAmount | Insurance coverage amount |
| ClaimNumber | Claim identifier |
| ClaimDate | Date of the claim |
| ClaimAmount | Amount associated with the claim |
| ClaimStatus | Claim status: Pending, Rejected, or Settled |

## 🔄 Project Workflow

### 1. Database Creation & Data Import

- Created a database in Microsoft SQL Server.
- Imported the insurance dataset into the database.
- Reviewed the dataset structure and available columns.
- Established a data source for Power BI reporting.

### 2. Connecting SQL Server to Power BI

- Connected Microsoft SQL Server to Power BI.
- Imported the insurance data for further analysis.
- Prepared the data for transformation and visualization.

### 3. Data Transformation in Power Query Editor

- Checked and corrected data types for appropriate columns.
- Reviewed the dataset for data quality issues.
- Created conditional columns to categorize data and support analysis.
- Prepared the transformed data for report development.

### 4. Interactive Dashboard Development

Designed an interactive insurance dashboard using Power BI's Report View.

The dashboard includes the following visuals:

- **Slicers:** Filter data by Policy Number, Claim Number, and Customer ID.
- **KPI Cards:** Display Premium Amount, Coverage Amount, and Claim Amount.
- **Multi-row Card:** Show gender-related summary information and the count of gender records.
- **Ribbon/flow-style chart:** Visualize the number of claims by claim status.
- **Horizontal Bar Chart:** Compare premium amounts across different policy types.
- **Doughnut Chart:** Show the count and proportion of active and inactive policies.
- **Line Chart:** Analyze claim amounts across different age groups.
- **Matrix Visual:** Compare Pending, Rejected, and Settled claim amounts across policy types.

## 📊 Dashboard Preview

![Insurance Data Analysis Dashboard](Insurance%20Dashboard.png)

*Interactive Power BI dashboard for exploring insurance policies, premiums, coverage amounts, and claims.*

## 🔍 Key Metrics & Analysis

The dashboard presents the following metrics and analytical views:

- **Premium Amount:** Total premium value across the insurance records.
- **Coverage Amount:** Total insurance coverage represented in the dataset.
- **Claim Amount:** Total claim amount across the records.
- **Policy Type Analysis:** Comparison of premium amounts for Auto, Health, Home, Life, and Travel insurance.
- **Policy Status Analysis:** Distribution of active and inactive policies.
- **Claim Status Analysis:** Comparison of rejected, settled, and pending claims.
- **Age Group Analysis:** Comparison of claim amounts across Adult, Elder, and Young Adult categories.
- **Claim Status Matrix:** Breakdown of claim amounts by policy type and claim status.
- **Customer Filtering:** Interactive filtering using policy, claim, and customer identifiers.

##  Key Learnings

Through this project, I gained practical experience in:

- Creating and managing databases in Microsoft SQL Server.
- Connecting a relational database to Power BI.
- Cleaning and transforming data using Power Query Editor.
- Working with data types and conditional columns.
- Designing interactive dashboards with slicers and KPI cards.
- Selecting appropriate charts for different analytical requirements.
- Using matrix visuals to compare multiple categories.
- Presenting insurance data in a structured and business-friendly format.

## 📁 Repository Structure

```text
Insurance-Data-Analysis/
│
├── InsuranceData.csv
├── Insurance Dashboard.png
├── Insurance Data Analysis.pbix
└── README.md
```

*Note: Update the filenames above to match the actual files you upload to your GitHub repository. Include the Power BI `.pbix` file and dashboard screenshot if you intend to share them.*

## 🚀 How to Explore the Project

1. Clone or download this repository.
2. Open the Power BI `.pbix` file using Microsoft Power BI Desktop.
3. If required, update the SQL Server connection settings to match your environment.
4. Refresh the data after configuring the appropriate data source.
5. Use the dashboard slicers to explore insurance records and analyze different metrics.

## 👨‍💻 Project Purpose

This project was developed as a hands-on exercise to strengthen my skills in **SQL Server, Power BI, data transformation, and interactive dashboard development**.

It demonstrates my understanding of the end-to-end data analysis process, from database setup and data preparation to reporting and visualization.

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.

**Skills Demonstrated:** SQL Server | Power BI | Power Query | Data Cleaning | Data Transformation | Data Visualization | Dashboard Development
