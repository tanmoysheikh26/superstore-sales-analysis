# Superstore Sales Analysis 

An end-to-end Excel and Power Query business analysis of Superstore sales data from 2014–2017, focused on sales performance, profitability, products, regions, customer segments, and discount impact.


##  Project Overview

This project analyzes Superstore sales data to understand overall business performance and identify areas of strong and weak profitability.

The analysis follows a structured workflow:

**Raw Data → Power Query → Data Cleaning → PivotTable Analysis → Dashboard → Business Insights**

The goal is to transform raw transactional data into actionable business insights that can support decisions related to products, regions, customer segments, and discount strategies.


##  Business Problem

Although the business generates strong overall sales, profitability varies significantly across products, categories, regions, customer segments, and discount levels.

The analysis aims to answer:

- How is the business performing overall?
- How are sales and profit changing over time?
- Which categories generate the most profit?
- Which products and sub-categories are loss-making?
- Which regions perform best and worst?
- Which customer segments are most valuable?
- How are different discount levels associated with profitability?



##  Tools & Techniques

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Slicers
- Data Cleaning & Transformation
- KPI Analysis
- Business Analysis
- Data Visualization

---

## Data Cleaning

The raw dataset was processed using Power Query before analysis.

Key cleaning and preparation steps included:

- Validating and correcting date formats
- Setting appropriate data types
- Checking missing values
- Checking duplicate records
- Preparing the dataset for PivotTable analysis
- Creating analysis-ready fields
- Validating the final cleaned dataset

After cleaning:

- **9,994** data records
- **0** duplicate rows
- **0** missing values identified in the audited fields

  ##  Data Source

The analysis uses the **Superstore Sales Dataset**, a sample retail dataset containing transactional information such as orders, customers, products, sales, quantity, discounts, and profit.

**Source:** Kaggle – Superstore Dataset by Vivek Chowdhury  
**Dataset:** Superstore Sales Dataset  
**Time Period:** 2014–2017  
**Records:** 9,994  
**Columns:** 21  
**Purpose:** Educational and portfolio analysis

🔗 [View the original dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

> The dataset was used for educational and portfolio purposes. The original dataset is not redistributed separately in this repository

##  Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | $2.30M |
| Total Profit | $286.40K |
| Profit Margin | 12.47% |
| Total Orders | 5,009 |
| Total Customers | 793 |
| Total Quantity | 37.87K |



##  Key Insights

### 1. Overall Performance

The business generated approximately **$2.30M in sales** and **$286.40K in profit**, resulting in an overall profit margin of **12.47%**.

### 2. Growth Over Time

Sales increased substantially from 2015 onward.

- 2015 Sales YoY: **-2.83%**
- 2016 Sales YoY: **+29.47%**
- 2017 Sales YoY: **+20.36%**

2017 recorded the highest annual sales and profit.

### 3. Category Performance

**Technology** generated the highest profit among the three categories.

**Furniture**, despite generating significant sales, produced considerably lower profit, indicating weaker profitability.

### 4. Product Profitability

Several products generated significant losses.

The largest loss among the analyzed products was:

**Cubify CubeX 3D Printer Double Head Print → approximately -$8.88K profit**

Loss-making products require further investigation of pricing, discounting, costs, and product economics.

### 5. Regional Performance

The **West** region generated the highest sales and profit.

The **Central** region had the lowest profit margin among the four regions, suggesting an opportunity for deeper investigation into its product mix and discount patterns.

### 6. Customer Segments

**Consumer** generated the highest overall sales.

However, **Home Office** had the highest profit margin among the three customer segments.

### 7. Discount & Profitability

Higher discount ranges were associated with negative aggregated profit.

Profit by discount range:

| Discount Range | Profit |
|---|---:|
| No Discount | +$320.99K |
| Low (1–20%) | +$100.79K |
| Medium (21–40%) | -$35.82K |
| High (41–60%) | -$28.94K |
| Very High (61%+) | -$70.61K |

This indicates that heavily discounted transactions deserve closer examination.

> Note: The analysis identifies an association between discount levels and profitability; it does not establish that discounts alone caused the losses.



##  Business Recommendations

Based on the analysis:

1. **Review high-discount transactions**  
   Evaluate whether discounts above 20–30% are generating sufficient business value.

2. **Investigate loss-making products**  
   Review pricing, discounting, costs, and demand for consistently loss-making products.

3. **Improve Furniture profitability**  
   Analyze problematic sub-categories such as Tables and Bookcases.

4. **Investigate Central region performance**  
   Examine its product mix, discount levels, and customer behavior.

5. **Prioritize profitable product categories**  
   Technology and Office Supplies demonstrate stronger overall profit contribution.


##  Dashboard Features

The interactive Excel dashboard includes:

- KPI cards
- Monthly Sales & Profit Trend
- Profit by Category
- Sales & Profit by Region
- Sales & Profit by Customer Segment
- Top Loss-Making Products
- Profit by Discount Range
- Year slicer
- Region slicer
- Segment slicer
- Category slicer

The slicers allow users to interactively filter the dashboard and explore different business dimensions.

### 6.	Screenshots 
Example: ![Dashboard Preview](https://github.com/tanmoysheikh26/superstore-sales-analysis/blob/main/Dashboard.png)


