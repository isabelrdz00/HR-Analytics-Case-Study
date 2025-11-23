**📊 Atlas Labs – HR Analytics Dashboard (Power BI Case Study)**

This project is an end-to-end Power BI report development case study using fictitious HR datasets from a tech company called Atlas Labs.
The goal is to design a reusable, interactive HR analytics report that helps the company monitor employee performance, hiring trends, diversity metrics, and attrition factors.

**⭐ Report Summary**
This case study walks through the complete Power BI report development lifecycle, focusing on:
- requirements gathering
- connecting to multiple data sources
- transforming and modeling the data
- creating a Kimball-style snowflake schema
- writing DAX measures
- defining branding and layout
- designing interactive charts and insights

The final report provides Atlas Labs’ HR team with a clear, intuitive overview of employee metrics.

**Power BI Report Development Workflow**
This project follows the four-step Power BI report development process, focusing on the first two steps.

Step 1: Build Your Data Model & Analyze Data

This step includes five key activities:
- 1. Requirements Gathering
 - Identified HR questions: hiring, diversity, performance, attrition
 - Defined KPIs and metrics needed by the HR stakeholders

- 2. Connecting to Data Sources
 - Loaded FactPerformanceRating and supporting dimension tables
 - Connected employee, education, satisfaction, and rating datasets
 - Prepared to build a date dimension table

- 3. Data Transformation
 - Cleaned and structured all tables in Power Query
 - Standardized column names
 - Ensured consistent keys across dimensions
 - Created the Date table with Year, Quarter, Month, and Day fields

- 4. Data Modeling
 - Built a snowflake schema with:
 - FactPerformanceRating (central fact table)
 - DimEmployee
 - DimEducationLevel
 - DimRatingLevel
 - DimSatisfiedLevel
 - DimDate
 - Defined one-to-many relationships
 - Ensured referential integrity

- 5. Write Initial DAX Measures
 - Created measures for:
 - Total Employees
 - Active Employees
 - Inactive Employees
 - Attrition Rate
 - Performance metrics
 - Year-over-year comparisons

Step 2: Report Design

This step includes three key activities:

- 1. Branding
 - Chose colors, typography, and layout consistent with Atlas Labs’ theme
 - Added navigation bar and sections for readability

- 2. Defining Report Layout
Structured multiple pages for:
 - Overview
 - Demographics
 - Performance
 - Attrition
 - Allocated space for KPIs, filters, charts, and drilldowns

- 3. Building Visuals
 - Added clean, intuitive charts including:
 - Hiring trends
 - Diversity distribution
 - Attrition breakdown
 - Employee performance ratings
 - Active employees by department and job role
 - Built interactions and slicers for exploration

**Final Data Model (Snowflake Schema)**
The final schema uses:
- FactPerformanceRating (central table)
- 5 dimension tables providing entity context
- One dimension not directly linked to the fact (as expected in snowflake schema)
- This structure increases flexibility and data clarity for reporting.

**Final Dashboard**
The final dashboard enables Atlas Labs HR team to:
- monitor hiring trends
- explore diversity and inclusion data
- analyze employee performance
- identify factors influencing attrition
- track active vs inactive employees
- drill into departments and job roles
- It is reusable, interactive, and ready for long-term organizational use.


Throughout this case study, the following concepts and skills were applied:
- Data modeling (Kimball methodology)
- Snowflake schema design
- Power Query transformations
- DAX functions and KPIs
- Layout and report design principles
- Interactive dashboard creation

This project demonstrates how to build a professional, stakeholder-ready Power BI report from scratch.

