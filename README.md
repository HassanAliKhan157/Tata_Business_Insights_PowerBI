# TATA Retail Store Business Insights

This project was completed as part of the **TATA Data Visualization with Effective Business Insights Job Simulation.** The goal was to help TATA’s executive team (CEO and CMO) gain critical business insights from the retail store data, enabling data-driven decisions and supporting their expansion strategy.

## Project Overview

The CEO and CMO of TATA Retail Store provided four key business questions they wanted answered through data visualization. They were interested in understanding:

- Revenue trends and seasonality
- Country-level sales opportunities (excluding the UK)
- Customer-level revenue insights
- Geographic regions with high sales demand for expansion planning

All analysis and visualizations were performed in **Power BI.** Each question was visualized on a separate report sheet.

---

## Data Cleaning

Before analysis, the raw dataset required cleaning to ensure accurate results. The following steps were performed:

- **Removed records** where quantity was below 1 (returns or errors).
- **Removed records** where unit price was below $0.
- Used conditional logic and data transformation techniques in Power BI to exclude bad data from the analysis.

---

## Analysis & Visualizations

### Question 1

**CEO Request:**  
_View the time series of revenue data for 2011, broken down monthly, to identify seasonality._

**Insights:**  
My analysis shows that for the first eight months of 2011, revenue was relatively stable, averaging around \$685,000 per month. However, beginning in September, revenue increased by 40% compared to August. This upward trend continued through November, where revenue peaked at \$1.5 million — the highest in the year. December’s data is incomplete, so no definitive conclusion can be drawn for that month. Overall, the retail store’s sales display significant seasonality, with stronger performance in the last four months of the year.

**Visualization Type:** Line Chart

![Question 1 Visualization](https://github.com/HassanAliKhan157/Tata_Business_Insights_PowerBI/blob/main/Question%201%20Visual.png)

---

### Question 2

**CMO Request:**  
_View the top 10 countries (excluding the UK) generating the highest revenue, and also show the quantity sold._

**Insights:**  
Countries such as the Netherlands, Ireland, Germany, and France emerged as strong performers with high revenue and sales volumes. These markets should be prioritized for further marketing and sales efforts to boost market share and revenue.

**Visualization Type:** Column Chart

![Question 2 Visualization](https://github.com/HassanAliKhan157/Tata_Business_Insights_PowerBI/blob/main/Question%202%20Visual.png)

---

### Question 3

**CMO Request:**  
_View the top 10 customers by revenue, showing the highest revenue-generating customer first._

**Insights:**  
The analysis reveals minimal difference in revenue between the top 10 customers. The highest revenue-generating customer purchased only 17% more than the second-highest, indicating the business is not overly reliant on a small group of customers. This reflects low customer bargaining power, which is favorable for the business.

**Visualization Type:** Column Chart

![Question 3 Visualization](https://github.com/HassanAliKhan157/Tata_Business_Insights_PowerBI/blob/main/Question%203%20Visual.png)

---

### Question 4

**CEO Request:**  
_View a global map of all countries (excluding the UK) to identify regions with the highest demand, supporting expansion strategy._

**Insights:**  
Aside from the UK, countries like the Netherlands, Ireland, Germany, France, and Australia generate significant revenue. Most sales are concentrated in Europe, with minimal sales in the Americas, and virtually none in Africa, Asia, or Russia. This indicates potential growth opportunities in underdeveloped regions, warranting new strategies to expand the company’s global footprint.

**Visualization Type:** Map Chart

![Question 4 Visualization](https://github.com/HassanAliKhan157/Tata_Business_Insights_PowerBI/blob/main/Question%204%20Visual.png)

---

## Tools Used

- Power BI Desktop
- Power Query for data cleaning and transformations
- DAX for calculations and measures
- Various visualization charts including Line, Column, and Map charts
