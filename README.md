# HR Analytics Dashboard – Power BI

## 1. Project Overview
This HR Analytics Dashboard provides a data-driven view of employee attrition and workforce demographics. It enables HR teams to monitor key HR metrics, identify attrition patterns, and support strategic decision-making for improving employee retention and workforce planning.

## 2. Business Problem
Organizations face challenges in understanding why employees leave and what factors influence attrition. Without data-based insights, HR teams struggle to design effective retention strategies.  
This dashboard addresses the problem by analyzing workforce data and highlighting key drivers of attrition across demographics, job roles, salary levels, and experience.

## 3. Tech Stack
- **Power BI** – Data modelling, dashboard design, visualization
- **Power Query (M Language)** – Data cleaning and transformation
- **MS Excel** – Initial data exploration and validation

## 4. Dataset Summary
- **Data Source:** HR employee dataset (single table)
- **Records:** 1,470 employee records
- **Features:** Employee demographics, job roles, salary, experience, education, and attrition status

### Key Columns:
`Employee ID, Age, Gender, Education, Job Role, Department, Salary, YearsAtCompany, Attrition`

## 5. Data Preparation & Cleaning (Power Query)
Data was cleaned and transformed using Power Query before building the dashboard.

Key steps performed:
- Removed duplicates and irrelevant columns
- Standardized data types (e.g., numeric, text, date)
- Created calculated columns for analysis (e.g., Age Group, Salary Band, Years of Service Band)
- Handled missing values and formatting issues

## 6. Key HR KPIs
The dashboard displays the following HR metrics at a glance:

| KPI | Description |
|------|----------------|
| **Employee Count** | Total active employees |
| **Attrition Count** | Number of employees who left |
| **Attrition Rate (%)** | % of employees who left the organization |
| **Average Age** | Avg age of employees |
| **Average Salary** | Avg monthly salary |
| **Average Years at Company** | Avg tenure |

## 7. Dashboard Features
- Single-page interactive HR analytics dashboard
- Visual breakdowns of attrition by:
  - Age Group
  - Gender
  - Education Level
  - Salary Band
  - Job Role
  - Department
  - Years of Service
- Trend-based comparisons to identify high-risk employee segments
- Executive-level overview with key KPIs displayed at the top

## 8. Slicers / Filters Used
The report includes interactive slicers to enable dynamic analysis:

- Department  
- Job Role  
- Education  
- Gender  
- Age Group  
- Salary Range  
- Years at Compa

## 9. Dashboard Preview
Below is a preview of the HR Analytics Dashboard:

![HR Dashboard Overview](https://github.com/Nikita05-dot/HR-Analytics-PowerBI/blob/main/Screenshot%202025-11-04%20192722.png)


