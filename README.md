**💊 Pharma Drug Sales Report Dashboard – Power BI Project**

**📊 Overview:**
This project focuses on developing a comprehensive and interactive Power BI dashboard to present the sales performance of 8 pharmaceutical drugs across different time frames—hourly, daily, monthly, and weekly. The primary goal is to transform raw CSV data into meaningful visual insights for stakeholders to support data-driven decision-making.


**📁 Project Files:**
The project is based on the following four CSV datasets:
  - saleshourly.csv
  - salesdaily.csv
  - salesmonthly.csv
  - salesweekly.csv
Each file contains time-based sales data for 8 different drugs.


**⚙️ Tools & Technologies Used**
  - Power BI – Data visualization and dashboard design
  - DAX (Data Analysis Expressions) – For calculated columns and custom measures
  - Power Query Editor – For data cleaning and transformation
  - Data Modeling – For establishing relationships between tables


**🔧 Data Preparation**
  - Data Import
        - All four CSV files were imported into Power BI.
  - Data Cleaning & Transformation:
        - Removed duplicates
        - Handled missing/null values
        - Adjusted and standardized data types
        - Renamed columns where needed for clarity
  - Data Modeling (Model View)
        - Established many-to-one relationships between the four tables using appropriate keys
        - Ensured model integrity and optimized performance


**📈 Dashboard Features:**
The Power BI dashboard includes:
  - Cards – To show key KPIs (e.g., Total Sales, Average Sales)
  - Slicers – For dynamic filtering by drug name, time period, etc.
  - Pie Chart – For proportional distribution of sales
  - Tables – To show granular-level data
  - Stacked Bar Chart – To compare sales across drugs and time
  - Combo Chart – To combine line and bar views for trends
  - Stacked Column Chart – To show breakdowns by category
  - Stacked Area Chart – For visualizing trends over time
All visuals are thoughtfully arranged for a clean and insightful user experience.


**🧮 DAX Calculations:**
Custom DAX formulas were used to:
  - Create calculated columns (e.g., Week Num)
  - Generate measures (e.g., Total Monthly Sales, Average Monthly Sales, Daily Sales, Weekly Sales)
  - Perform conditional formatting and custom KPIs


**🧾 Final Output:**
A complete Power BI Report (Pharma Sales PowerBI Report.pbix) is generated, offering stakeholders a comprehensive view of drug sales trends over time, facilitating better strategy and business planning.


**📸 Screenshots:**
Images of PowerBI Dashboard and Model View is attached for reference.

![Data Modeling Image](https://github.com/user-attachments/assets/707eac81-fcce-48c9-b7d2-a9f4e700be59)

![PowerBI Dashboard Image](https://github.com/user-attachments/assets/54a1c5b8-1725-4c16-b946-84745cf58a81)
