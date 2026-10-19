# Data Jobs Market Analysis Dashboard 
This project analyzes the global data job market using Power BI. The dashboard provides insights into salary trends, job demand, hiring locations, remote work opportunities, job types, and employer benefits across various data-related roles.

The objective of this project is to help job seekers, analysts, and recruiters understand the current data job landscape by exploring hiring patterns and compensation trends.

---------------------------------------------------------------------------------------------------------------------------------------------------------

## 1. Business Problem & Analytical Objective

With the increasing demand for data professionals, understanding job market trends, salary expectations, hiring patterns, and workforce requirements has become important for both job seekers and recruiters. However, job market data is often scattered across multiple platforms, making it difficult to extract meaningful insights.

This project aims to analyze 479K data-related job postings and transform raw recruitment data into actionable insights through an interactive Power BI dashboard. The analysis focuses on salary trends, job demand, employment types, remote work opportunities, hiring platforms, and geographic distribution of data jobs, enabling data-driven career and workforce decisions.

The primary objective of this project is to answer critical business and career-related questions, including:

- Which data-related roles offer the highest compensation?
- Which job titles are currently in highest demand?
- How do hourly and yearly salaries compare among different roles?
- What employment types dominate the data job market?

By answering these type of questions, the dashboard enables data professionals to better understand market conditions and career opportunities.

---------------------------------------------------------------------------------------------------------------------------------------------------------

## 2.🛠️ Tools & Technologies

| Layer | Technologies 
|---|---
| Data Source | Microsoft Excel
| Data Transformation | Power Query (M Language)
| Data Modeling | Relational Modeling
| Analytics Engine | DAX Measures
| Visualization| Microsoft Power Bi
| Maps & Geospatial Analytics | Bing Maps |
| Business Coverage| Job Market Analytics, Salary Analysis, Hiring Trends, Workforce Insights, Geographic Distribution 
--------------------------------------------------------------------------------------------------------------------------------------------------------

## 3. Data Engineering & Analytics Workflow

The project pipeline executes across four integrated analytical stages to convert raw e-commerce transaction records into optimized business intelligence outputs:

```text
[Phase 1: Data Extraction] ➔ [Phase 2: ETL Transformation] ➔ [Phase 3: KPI Modeling] ➔ [Phase 4: Interactive Dashboarding]
(Excel Data Source)          (Power Query Cleansing)         (DAX Measures & Metrics)   (Executive Visualization Layer)
```
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔹 Phase 1: Raw Data Acquisition

The platform utilizes transactional sales data stored inside the source workbook:

```text
job_posting_fact.xlsx
```
The dataset contains:

- Job information
- Compensation information
- Employment Benefits
- Recruitment Information

The dataset contains approximately 479K job postings spanning multiple countries and job categories.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔹 Phase 2: Power Query ETL & Data Transformation

The raw dataset was imported into Power BI and transformed using Power Query. Several data preparation activities were performed to improve data quality and ensure consistency before analysis.

Key Activities:

- Data profiling and quality checks
- Handling missing and null values
- Data type standardization
- Column transformations and formatting
- Removing unnecessary fields
- Creating analytical-ready datasets
  
-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔹 Phase 3: Data Modeling & KPI Development

After data transformation, the dataset was modeled within Power BI to support analytical reporting. DAX measures were created to calculate key business metrics used throughout the dashboard.

Key KPIs Developed:

- Total Job Count
- Median Yearly Salary
- Median Hourly Salary
- Work From Home Percentage
- Degree Mention Percentage
- Health Insurance Percentage
- Job Trend Metrics

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔹 Phase 4: Interactive Dashboard Development

Visualizations were created to help users explore salary trends, hiring demand, employment patterns, and geographic distribution of data jobs.

Dashboard Features:

- KPI Cards
- Salary Analysis
- Trend Analysis
- Geographic Mapping using Bing Maps
- Job Title Drill-Through Pages
- Interactive Filtering and Slicers
- Employment Type Analysis

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 4. Dashboard 1: Data Jobs Market Overview

This dashboard provides a macro-level analysis of the data job industry and serves as the entry point for users.




<img width="1367" height="787" alt="image" src="https://github.com/user-attachments/assets/c1ac79c4-16f3-4796-826f-04dc063d982b" />



## Key Metrics
-	Total Job Postings: 479K
-	Median Yearly Salary: $113K
-	Median Hourly Salary: $47.62
-	Salary Rating Indicator


## Visual Analysis

**1.** **Job Trend Analysis** (2024)
   
This **line chart** analyzes monthly hiring demand throughout the year.

Key Findings:

- High demand observed during the beginning of the year.
- Hiring activity experienced fluctuations throughout the year.
- Noticeable decline toward the final quarter.
- Partial recovery visible during the final month.

**2.** **Hourly Salary vs Annual Salary Analysis**

This **scatter plot** compares yearly compensation with hourly compensation across different job roles.

Key Findings:

- Machine Learning Engineers receive the highest compensation.
- Senior Data Scientists command premium salaries.
- Data Engineers consistently rank among top-paying positions.
- Data Analysts generally earn lower salaries compared to specialized engineering roles.

**3.** **Highest Paying Data Jobs**

The **ranking chart** identifies top-paying positions within the data industry.

Highest-paying roles include:

- Data Engineer
- Data Analyst
- Data Scientist
- Senior Data Engineer
- Business Analyst
- Software Engineer

**4.** **Job Role Summary Table**

Provides a consolidated overview including:

- Job Count
- Median Salary
- Median Hourly Pay
- Hiring Trend

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 4. Dashboard 2: Job Title Drill-Through Analysis

The drill-through functionality enables users to investigate individual job roles in greater detail.

The example demonstrated in this project focuses on the Data Scientist role:

<img width="1360" height="757" alt="image" src="https://github.com/user-attachments/assets/ffe36d5a-a3f6-4cc4-a362-8b88432d05da" />

## Key Metrics
- Median Annual Salary: $125K
- Median Hourly Salary: $43
- Remote Work Availability: 13.8%
- Degree Requirement Mention: 6.7%
- Health Insurance Mention: 15.9%

## Visual Analysis

**1-** **Geographic Analysis**

Countries Not Mentioning Degrees in Job Postings.
The map visual displays countries where employers frequently focus on skills and experience rather than explicitly requiring academic qualifications.

**2-** **Job Posting Source Analysis**

The bar chart highlights recruitment channels generating the highest number of opportunities.

Major Platforms Include:
- LinkedIn
- BeBee
- Indeed
- ZipRecruiter
- GrabJobs
- Jooble

**3-** **Employment Type Distribution**

The treemap highlights the distribution of employment categories.

**Dominant Categories**
- Full-Time (91%)
- Contractor
- Internship
- Part-Time

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 5. 📊 Key Business Insights

 **Compensation Insights**
- Data Engineer and Machine Learning Engineer roles offer the highest compensation packages.
- Most advanced data careers exceed $100K median annual salary.
- Senior-level positions demonstrate significantly higher earning potential.

**Hiring Insights**
- Demand for data professionals remains strong globally.
- Data Analyst, Data Scientist, and Data Engineer positions dominate the market.

**Remote Work Insights**
- Remote opportunities are available but remain a relatively small percentage of total postings.

**Education Insights**
- Employers increasingly emphasize practical skills and professional experience over formal degree requirements.

**Employment Insights**
- Full-time employment accounts for the vast majority of available opportunities.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## 6. 🚀 Skills Demonstrated

This project showcases:

**Power BI**
- Interactive Dashboard Design
- Drill-Through Functionality
- KPI Reporting
- Slicers & Filters
- Advanced Visualizations

**DAX**
- Measures
- KPIs
- Aggregations
- Dynamic Calculations

**Data Analytics**
- Trend Analysis
- Salary Benchmarking
- Workforce Analytics
- Market Research

**Data Modeling**
- Fact & Dimension Modeling
- Relationship Management
- Data Cleaning & Transformation


## Author

# Ved Amrita Dubey

----------------------------------------------------------------------------------------------------------------------------------------------------------------











