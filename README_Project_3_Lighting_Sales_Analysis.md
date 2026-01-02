
# Australian Lighting Sales Analysis & Forecasting

## Project Overview
This project analyzes **13 years and 10 months of Australian lighting industry sales data** to uncover long-term trends, understand market behavior, and support data-driven business decision-making. The dataset spans multiple item types, customer districts, business areas, and business chains.

---

## Dataset Summary
- Industry: Australian Lighting
- Time Span: ~13 years 10 months
- Key fields include sales date, sales value, item type, light source, salesperson, district, business area, and business chain.

---

## Data Quality Assessment
Initial inspection revealed:
- Significant missing values
- Incorrect data types (dates and numeric fields)

These issues posed risks to forecasting accuracy, operational planning, and strategic decision-making.

---

## Data Cleaning & Standardization
Key steps:
- Removed records with missing sales dates and salesperson codes
- Converted sales to numeric and handled missing values using median imputation
- Standardized categorical fields such as light source, business area, and chain codes
- Converted sales dates to datetime format
- Verified no duplicate transactions

Result: a clean, consistent dataset ready for analysis.

---

## Exploratory Data Analysis
Key insights derived:
- Clear seasonal and long-term sales trends
- Identification of top-performing product categories
- Regional sales performance differences
- Business area and partner-level performance patterns

Outliers were treated using log transformation to improve analytical robustness.

---

## Business Insights
- Seasonal demand patterns support better inventory and staffing planning
- High-performing product categories guide product strategy
- Regional and partner performance insights inform targeted sales and expansion strategies

---

## Final Dataset
- 951,109 rows
- 11 columns
- Fully cleaned and analysis-ready

---

## Strategic Value
This project converts raw sales data into a reliable strategic asset, enabling:
- Data-driven planning
- Improved forecasting accuracy
- Better resource allocation
- Stronger competitive positioning

---

## Tools Used
- Python
- pandas, numpy
- matplotlib, seaborn
