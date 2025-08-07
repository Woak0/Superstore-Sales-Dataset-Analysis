# Superstore Sales Performance Analysis (2015-2018)

### Live Dashboard Demonstration
*(Since a public Power BI link requires a work/school account, this GIF demonstrates the report's full interactivity, including slicers, tooltips, and drill-down features.)*

![Dashboard Demo](dashboard_demo.gif)

---

### Project Overview
This end-to-end data analytics project provides a comprehensive analysis of the Superstore's sales data. The goal was to move beyond simple reporting to identify key drivers of performance and provide actionable, data-driven recommendations to guide strategic business decisions.

### Tools & Technologies
*   **Data Cleaning & Preparation:** Python (Pandas)
*   **Data Modeling & Visualization:** Power BI
*   **Data Analysis Language:** DAX (Data Analysis Expressions)
*   **Version Control & Hosting:** Git & GitHub

### The Analytical Process
1.  **Data Preparation (Python):** The raw dataset was cleaned and processed using Pandas. This involved correcting data types, handling missing values through logical imputation, and engineering new features like `Days_to_Ship`.
2.  **Data Modeling (Power BI):** A professional-grade **Star Schema** data model was constructed to ensure analytical integrity and report performance. This involved creating separate Dimension tables for Customers, Products, Geography, and Orders connected to a central Fact table.
3.  **Data Analysis (DAX):** Advanced DAX measures were created to answer complex business questions, including time intelligence calculations (YoY Growth) and customer loyalty metrics (Repeat Customers).
4.  **Dashboarding (Power BI):** A 3-page interactive dashboard was built to visualize the findings, covering a KPI Summary, a Customer Deep-Dive, and a Product Analysis.

### Key Findings & Recommendations
*   **Finding:** The business is healthy, with a **20.3% YoY growth** in its most recent year.
*   **Finding:** The **Consumer segment** (50.8% of sales) and two key states (**California & New York**, 33% of sales) are the primary drivers of revenue.
*   **Finding:** Customer loyalty is exceptionally high at **98.3%**, but a "long tail" of underperforming products creates operational drag.
*   **Recommendation 1:** Launch targeted marketing campaigns for the Consumer segment in top states.
*   **Recommendation 2:** Conduct a profitability review of the Furniture category.
*   **Recommendation 3:** Delist the bottom 50 SKUs to optimize inventory.

### How to View
1.  **The Final Report:** For a full narrative of the findings and recommendations, please view the **`Superstore_Sales_Analysis_Report.pdf`**.
2.  **The Power BI File:** The **`.pbix`** file can be opened with Power BI Desktop to explore the full data model, DAX measures, and interactive report.
3.  **The Python Script:** The data preparation process is documented in the Jupyter Notebook **`.ipynb`** file.