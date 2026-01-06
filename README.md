
 📊 Executive Sales Performance Dashboard | Power BI Dashboard
 

This project showcases an executive-level sales analytics dashboard built in Power BI to evaluate revenue growth, profitability, and year-on-year (YoY) performance across regions, product categories, and customer segments.
The objective was to transform raw transactional data into clear, decision-ready insights that senior stakeholders can understand and act on quickly.
 🖥 Executive Dashboard Overview
 <img width="891" height="684" alt="image" src="https://github.com/user-attachments/assets/5e44975f-a368-4bfe-9952-0708e6dcf727" />

 
Single-page executive view displaying KPIs, YoY growth indicators, profit margin, and interactive slicers for rapid decision-making.
 🔍 Key Highlights

- $2.30M total revenue analysed across multiple years  
- 46.88% YoY sales growth calculated using robust time intelligence  
- Technology identified as the most profitable product category  
- Exposed discount-driven margin risks in specific regions  
- Implemented slicer-safe YoY growth indicators (▲ ▼) for executive clarity  


 📈 Sales Trend Analysis (Year-on-Year)
 <img width="975" height="465" alt="image" src="https://github.com/user-attachments/assets/a4084415-d553-457a-bbdb-9ffc60171d74" />

 
Line chart showing multi-year sales trends, enabling leadership to quickly identify growth patterns, slowdowns, and recovery periods.

 🧹 Data Cleaning & Preparation
Prior to analysis, structured data cleaning and transformation were performed to ensure data accuracy, consistency, and reliability:
- Removed duplicates and corrected inconsistent category naming  
- Standardised date formats and validated transaction timelines  
- Handled missing values in sales, discount, and profit fields  
- Created calculated columns for profit and margin validation  
- Built a dedicated Date Table to support accurate time intelligence  
- Modelled clean relationships using a star schema design

These steps ensured all insights were trustworthy, scalable, and audit-ready.
 📊 Category-Level Performance
 <img width="975" height="483" alt="image" src="https://github.com/user-attachments/assets/cc9a1bc1-d72d-4347-9213-88b764c5ec76" />

 
Comparison of sales and profit by product category, highlighting Technology as the strongest contributor to profitability.
 🧠 What I Did
- Designed a proper Date Table to support accurate YoY and trend analysis  
- Built a star schema data model optimised for performance  
- Created advanced DAX measures using `SAMEPERIODLASTYEAR`  
- Implemented growth indicators (▲ ▼) for rapid executive interpretation  
- Designed an interactive dashboard with region, category, and segment slicers  


 🌍 Regional Sales vs Profit Analysis
 <img width="975" height="483" alt="image" src="https://github.com/user-attachments/assets/5bc6b021-a915-493b-b236-38a7c048ce1d" />

Sales and profit comparison by region, revealing areas with strong revenue but weaker margins due to discounting.
 📊 YoY KPI Indicators
 <img width="975" height="166" alt="image" src="https://github.com/user-attachments/assets/e49ca5a6-c5c6-4692-ab4b-95fce8469599" />


 
Executive KPI cards displaying YoY growth with clear directional indicators (▲ ▼), remaining accurate under all slicer selections.
 📈 Business Impact
- Highlighted high-performing regions and customer segments  
- Identified profit leakage caused by excessive discounting  
- Enabled leadership to track growth and profitability at a glance  
- Improved decision-making through clear visual storytelling 

 🛠 Tools & Skills
Power BI • DAX • Time Intelligence • Data Modelling • Data Cleaning • Business Analytics • Dashboard Design


 📋 Challenges
- Ensuring data accuracy and consistency  
- Optimising performance for interactive dashboards  
- Designing clear, actionable insights for executives

 📋 Solutions
- Employed a robust data model and time intelligence to ensure accurate analysis  
- Implemented slicer-safe indicators for executive clarity  
- Optimised dashboard performance for interactive use

 📋 References
- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)  
- [DAX Documentation](https://docs.microsoft.com/en-us/dax/)  
- [Time Intelligence Documentation](https://docs.microsoft.com/en-us/power-bi/desktop-time-intelligence)  
- [Data Modelling Documentation](https://docs.microsoft.com/en-us/power-bi/developer/modeling-overview)  
- [Data Cleaning Documentation](https://docs.microsoft.com/en-us/power-bi/desktop-data-cleaning)  
- [Business Analytics Documentation](https://docs.microsoft.com/en-us/power-bi/visuals/power-bi-visuals-business-analytics)  
 
 📁 Repository Structure
 
 │Sales Dashboard
 
├── screenshots/

│ ├── dashboard-overview.png

│ ├── yearly-sales-trends.png

│ ├── sales-by-category.png

│ ├── sales-vs-profit-region.png

│ └── yoy-kpi-cards.png

├── dataset

├── Executive_Sales_Dashboard.pbix
└── README.md
