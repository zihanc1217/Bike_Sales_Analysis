1. Overview

   This project analyzes a dataset of 1,000+ potential bike customers, cleaning and preparing the raw data, performing exploratory analysis with         pivot tables, and building an interactive dashboard to identify buyer patterns. The final Excel file includes fully organized sheets for raw data,    cleaning steps, pivot summaries, and a dashboard suitable for business decision-making.

   This project demonstrates Excel skills including:
    - Data cleaning
    - Conditional logic & formula-driven transformations
    - Pivot Tables (segmentation, aggregation, comparisons)
    - Dashboard design (charts, slicers, KPI summaries)
---

2. Repo Structure
```text
  excel-bike-buyers-project/
  │
  ├── data/
  │   └── Excel Project Dataset.xlsx       # Full workbook with raw data, cleaning, pivot tables, dashboard
  │
  ├── outputs/ (optional)
  │   └── dashboard_screenshot.png         
  └── README.md
  ```
---

3. Workbook Structure and Description

   3.1 bike_buyers (Raw Data)

   Contains demographic and behavioral variables such as:
    - Marital Status, Gender, Income, Education
    - Occupation, Home Ownership, Cars Owned
    - Commute Distance, Region, Age
    - Purchased Bike (Yes/No)

    This raw dataset is the foundation for all subsequent cleaning and analysis.

   3.2 Working Sheet (Data Cleaning & Preprocessing)
  
   This sheet applies all preprocessing steps, including:
  
     1) Recoding categorical fields
     2) Normalizing inconsistent labels
     3) Checking for missing values
     4) Preparing fields for pivot analysis
     5) Creating clean analytical features

    Typical Excel skills demonstrated here:

    - IF(), IFS(), VLOOKUP()

    - TRIM(), PROPER() standardization
  
    - Conditional Formatting

    - Derived metrics for analysis

    3.3 Pivot Table (Exploratory Analysis)
    The pivot table sheet summarizes buyer patterns and uncovers segments such as:

     - Income vs. Purchase Likelihood

     - Age group trends

     - Commute distance effects

     - Regional differences

     - Household structure & car ownership patterns

     These insights support the dashboard’s visualizations.

     3.4 Dashboard
     A clean, interactive dashboard including:

      - Bar & column charts for buyer demographics

      - Purchase distribution across income, age, and region

      - Slicers for dynamic filtering

      - Summary indicators for quick interpretation

     The dashboard showcases Excel BI capabilities and turns raw data into actionable insight.
---

4. Key Insights
   - Higher-income groups show significantly stronger purchase rates.
   - Shorter commute distances correlate with higher likelihood of buying a bike.
   - Certain regions (e.g., Pacific) show stronger buyer interest.
   - Customers who are in the Middle Age group show stronger purchase rates.
   - Professionals and skilled workers are more likely to purchase compared to clerical roles.
   - Home ownership and car ownership patterns provide additional segmentation.
---

5. How to use the file
   1) Download Excel Project Dataset.xlsx from the data/ folder.
   2) Open the Dashboard tab to explore interactive visuals.
   3) Use slicers to filter by region, age, marital status, commute distance, etc.
   4) Review Pivot Table and Working Sheet to see the analytical process.
---

6. Skills Demonstrated
   - Data cleaning and preprocessing
   - Categorical recodingPivot tables & aggregations
   - Dashboard design
   - Data visualization
   - Analytical thinking
---

7. Future Improvement
   If expanded, the project could include:
   - Predictive modeling using Python (purchase likelihood)
   - A fully interactive Power BI version
   - Additional demographic segmentation
   - Automated Excel formulas for repeatable analysis
