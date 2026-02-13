# Parking Optimization & Utilization Analytics Dashboard

## Overview
This project presents an **end-to-end data analytics solution** designed to analyze parking access activity, utilization trends, and future demand forecasting for a university parking system.

The objective was to transform raw transactional parking data into **actionable operational insights** that support:

- Capacity planning  
- Peak-hour demand management  
- Resource allocation decisions  
- Future parking volume forecasting  

The final deliverable is an **interactive Power BI dashboard** (shared here as a PDF export for public viewing).

---

## Key Business Questions Addressed
- How many total parking transactions occurred over the analysis period?
- How many **unique access cards/users** utilized parking facilities?
- What is the **average parking duration**?
- Which parking lots experience the **highest utilization**?
- What are the **hourly and daily usage patterns**?
- How will parking demand evolve over the **next six months**?

---

## Dataset Summary
The dataset contains **multi-year parking transaction records** including:

- Entry and exit timestamps  
- Parking lot identifiers  
- Access card/user identifiers  
- Duration of stay  
- Activity timestamps for trend analysis  

This enables **time-series, utilization, and behavioral analytics** across several years of operations.

---

## End-to-End Analytics Workflow

### 1. Data Cleaning & Preparation
- Removed incomplete and duplicate transaction records  
- Standardized **date/time formats** for temporal analysis  
- Derived calculated fields:
  - Parking duration (hours)  
  - Entry hour, day, month, and term  
- Validated data consistency across years  

**Tools used:** Power Query, DAX transformations

---

### 2. Data Modeling
- Built a **star-schema-style semantic model**
- Created relationships between:
  - Transaction fact table  
  - Date dimension  
  - Parking lot dimension  
- Optimized model for **fast aggregation and filtering**

---

### 3. Analytical Calculations (DAX)
Key measures developed:

- Total Transactions  
- Unique Cards Used  
- Average Parking Duration  
- Lot-level utilization ranking  
- Hourly usage heatmap metrics  
- Time-series trend measures  
- Forecasted parking volume with **95% confidence interval**

---

### 4. Dashboard Design & Visualization
The dashboard was designed for **operational decision-makers** with:

- KPI summary tiles for quick monitoring  
- Top-10 busiest parking lots ranking  
- Hour-by-hour utilization heatmap by weekday  
- Access-group contribution analysis  
- Multi-year trend visualization  
- **Forward-looking demand forecast**  

**Design principles followed:**

- Clear visual hierarchy  
- Minimal cognitive load  
- Actionable insight over decorative visuals  

---

## Key Insights Generated
- Parking demand is **highly concentrated in specific lots**, indicating optimization opportunities.  
- Weekday mornings show **sharp utilization spikes**, useful for staffing and traffic planning.  
- Average parking duration suggests **long-stay dominance**, impacting turnover.  
- Forecasting indicates **continued demand variability**, with widening uncertainty beyond mid-2025.  

---

## Tools & Technologies
- **Power BI Desktop** – data modeling, DAX, visualization  
- **Power Query** – ETL and transformation  
- **Time-series forecasting** – built-in analytics with confidence intervals  
- **GitHub** – project documentation and portfolio hosting  

---

## Project Deliverables
- Power BI analytical dashboard (**PDF export included in repository**)  
- End-to-end documentation of analytics workflow  
- Business insights for operational planning  

---

## Business Impact
This solution demonstrates the ability to:

- Convert raw operational data into **decision-ready intelligence**  
- Apply **data modeling, DAX, and visualization best practices**  
- Deliver **forecast-driven planning insights**  
- Communicate findings clearly to **non-technical stakeholders**  

---

## About Me
**Sagar Mallappa Naduvinkeri**  
*Data Analyst | Business Intelligence | Analytics Engineering*

- Focused on **data-driven decision support and dashboarding**  
- Experienced in **Power BI, SQL, Python, and analytics storytelling**

🔗 LinkedIn:  
https://www.linkedin.com/in/sagar-naduvinkeri/

---

⭐ *If you found this project useful, feel free to star the repository.*
