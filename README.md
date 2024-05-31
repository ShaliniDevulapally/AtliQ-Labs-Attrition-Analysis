# **Employee Attrition Analysis**

## **Project Overview**
This project aims to analyze employee attrition using Power BI. The analysis covers various aspects such as overall attrition trends, demographics, performance tracking, and key factors contributing to employee turnover. The dashboard consists of four pages: Overview, Demographics, Performance Tracker, and Attrition.

## **Table of Contents**
1. [Introduction](#introduction)
2. [Data Sources](#data-sources)
3. [Data Preparation](#data-preparation)
4. [Dashboard Pages](#dashboard-pages)
   - [Overview](#overview)
   - [Demographics](#demographics)
   - [Performance Tracker](#performance-tracker)
   - [Attrition](#attrition)
5. [Findings and Recommendations](#findings-and-recommendations)
6. [How to Use](#how-to-use)
7.  [Conclusion](#conclusion)

## **Introduction**
The Employee Attrition Analysis project provides insights into employee turnover within a company. By using Power BI, we have created an interactive dashboard that helps in identifying trends, understanding demographic factors, tracking performance, and pinpointing key drivers of attrition.

## **Data Sources**
The data used in this project includes:
- Employee records with details such as age, gender, marital status, job role, department, hire date, and attrition status.
- Performance data including job satisfaction, relationship satisfaction, employment satisfaction, self-rating, and work-life balance.
- Additional fields created for date-related data and calculated measures.

## **Data Preparation**
- **Data Cleaning:** Verified data types, removed null values, and established relationships between tables.
- **DimDate Table:** Extracted and managed date-related data such as day, quarter, month, year, month name, fiscal year, day of the week, and day number.
- **Measures Table:** Organized all calculated measures in a dedicated table named "_measures".

## **Dashboard Pages**

### **Overview**
The Overview page provides a high-level summary of employee statistics, including:
- Total number of employees, active and inactive employees, and the company's attrition rate.
- Employee hiring trends over time with a hierarchical view (quarter, month, year).
- Visuals showing active employees by department and job role.

![Overview Page](path/to/overview_screenshot.png)

### **Demographics**
The Demographics page offers insights into the age distribution and other demographic factors:
- Youngest and oldest employee ages.
- Visualizations of employees by age bins, marital status, ethnicity, age and gender.

![Demographics Page](path/to/demographics_screenshot.png)

### **Performance Tracker**
The Performance Tracker page monitors individual employee performance:
- Key performance indicators include job satisfaction, relationship satisfaction, employment satisfaction, self-rating, and work-life balance.
- Last review date, next review date, and earliest hire date.

![Performance Tracker Page](path/to/performance_tracker_screenshot.png)

### **Attrition**
The Attrition page analyzes the factors contributing to employee turnover:
- Attrition percentage by various factors such as tenure, travel frequency, overtime, job role, and department.
- Visualizations of attrition trends and insights.

![Attrition Page](path/to/attrition_screenshot.png)

## **Findings and Recommendations**

### **Key Findings**
1. High attrition rate associated with frequent travel.
2. Significant attrition among employees working overtime.
3. Elevated attrition rates for employees with 1-5 years of tenure.
4. High turnover in specific roles: Sales Representative, Recruiter, Data Scientist.
5. Sales department has the highest attrition percentage.

### **Recommendations**
1. Revise travel frequency policies to align with employee convenience.
2. Address issues related to overtime to improve retention.
3. Implement targeted interventions for roles and departments with high attrition.

## **How to Use**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ShaliniDevulapally/employee-attrition-analysis.git
