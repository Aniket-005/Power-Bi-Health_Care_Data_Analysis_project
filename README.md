<img src=Health_Care_logo.png alt="Example Image" width="500">

# Power BI Healthcare Data Analysis Project

# Project Overview:

This Power BI project focuses on analyzing healthcare data to extract meaningful insights. The goal is to visualize key healthcare metrics, identify trends, and support data-driven decision-making.

# Key Objectives:

# 1. Data Integration: 
Connect Power BI with multiple data sources (SQL Server, Excel, CSV, etc.).

# 2. Data Cleaning & Transformation:

Handle missing values.

Convert data types for consistency.

Remove duplicate records.

# Dashboard Development:

Create interactive dashboards to track patient data, hospital performance, and resource utilization.

Use key visualizations such as bar charts, line graphs, KPI indicators, and heatmaps.

# Performance Analysis:

Identify trends in patient admissions, treatment effectiveness, and disease patterns.

Monitor hospital performance metrics such as bed occupancy rate and patient wait time.

# Predictive Insights:

Utilize Power BI AI capabilities to forecast future healthcare demands.

# Data Sources:

Electronic Health Records (EHRs)

Hospital Management Systems

Public Health Databases (WHO, CDC, etc.)

Manually entered hospital data

# About Data
The data contains 21 columns and 10000 rows:
| Column                 | Description                                   | Data Type        |
|------------------------|-----------------------------------------------|------------------|
| Name                   | Gives patient name                            | object           |        
| Age                    | Gives patient age                             | float64          |
| Gender                 | Gives patient gender                          | object           |
| Blood_Type             | Gives patient blood type                      | object           |
| Medical_Condition      | Gives patient Medical Condition               | object           |
| Admission_Date         | Gives patient Admission date                  | datetime64       |
| Doctor_Name            | Gives doctor Name                             | object           |
| Hospital_Name          | Gives hospital Name                           | object           |
| Insurance_Provider     | Gives insurance provider Company Name         | object           |
| Billing_Amount         | Gives patient billing amount                  | float64          |
| Room_Number            | Gives patient admit room number               | int64            |
| Admission_Type         | Gives patient admission type                  | object           |
| Discharege_Date        | Gives patient discharge date                  | datetime64       |
| Medication             | Gives patient medication                      | object           |
| Age_Group              | Group the patient based on age group          | object           |
| Length_of_Hospital_Stay| Gives patient hospital stay days              | object           |
| Admit_Month_Name       | Gives patient admit month                     | object           |
| Admit_Year             | Gives patient admit year                      | int32            |
| Admit_Day_Of_week      | Gives patient admit week                      | object           |

# Revenue DashBoard

<img src= "revenue Dashboard.png" alt="Example Image" width="700">

# Patient DashBoard

<img src= "patient analysis dashboard.png" alt="Example Image" width="700">

# Technologies Used:

Power BI (Data visualization and reporting)

SQL Server / MySQL (Database connection and query execution)

Excel / CSV (Raw data sources)

DAX & Power Query (Data transformation and calculations)

# Dashboard Features:

# Patient Demographics Overview: 
Age, gender, region-based patient analysis.

# Hospital Performance Metrics: 
Patient wait time, treatment success rate, hospital occupancy.

# Disease Trends: 
Common diseases, seasonal trends, and outbreak predictions.

# Financial Analysis: 
Revenue, cost per patient, insurance claims.

# How to Use the Dashboard:

Open the Power BI file (.pbix) in Power BI Desktop.

Ensure data sources are correctly linked and refreshed.

Navigate through different report pages to explore insights.

Use interactive filters and slicers to customize the analysis.

Export reports as needed for further analysis.

# Future Enhancements:

Integration with real-time data sources (API connections).

Advanced AI-powered predictive analytics.

Enhanced security measures for sensitive healthcare data.

# Conclusion
This Power BI healthcare project provides a comprehensive view of patient care, hospital efficiency, and health trends. The dashboards enable data-driven decision-making, improving overall healthcare management and patient outcomes.
