#  Superstore Sales Performance Dashboard (Power BI)

##  Project Overview

This project focuses on **Data Visualization and Storytelling** using the **Sample Superstore Dataset**. The objective is to transform raw sales data into meaningful business insights through interactive visualizations and dashboards created in **Microsoft Power BI**.

The dashboard provides a comprehensive analysis of sales performance across different regions, product categories, customer segments, and discount levels, helping stakeholders make informed business decisions.

---

##  Objectives

- Create interactive visualizations using Power BI.
- Analyze sales and profit performance.
- Identify high-performing and low-performing categories.
- Evaluate regional sales distribution.
- Understand the impact of discounts on profitability.
- Present findings through effective storytelling and business insights.

---

##  Tools & Technologies Used

- Microsoft Power BI Desktop
- Sample Superstore Dataset (CSV)
- Data Visualization
- Business Intelligence (BI)
- Dashboard Design
- Data Storytelling

---

## Dataset Information

**Dataset Name:** Sample Superstore Dataset

The dataset contains information related to:

- Order ID
- Order Date
- Ship Date
- Customer ID
- Customer Name
- Segment
- Region
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

---

## Data Preparation

The following preprocessing steps were performed before visualization:

### 1. Data Import
- Imported the CSV dataset into Power BI Desktop.

### 2. Date Conversion
- Converted **Order Date** and **Ship Date** columns to Date format.

### 3. Data Validation
- Verified data types and column consistency.
- Checked numerical fields such as Sales, Profit, Quantity, and Discount.

### 4. Measure Creation

Created the following DAX measures:

```DAX
Total Sales = SUM([Sales])

Total Profit = SUM([Profit])

Total Orders = DISTINCTCOUNT([Order ID])

Total Quantity = SUM([Quantity])
```

---

## Dashboard Components

### KPI Cards

The dashboard includes four Key Performance Indicators (KPIs):

| KPI | Description |
|------|------------|
| Total Sales | Total revenue generated |
| Total Profit | Total profit earned |
| Total Orders | Number of unique orders |
| Total Quantity | Total quantity sold |

---

### Visualization 1: Sales Trend Over Time

**Chart Type:** Line Chart

**Purpose:** Analyze sales growth over time.

**Insight:** Sales showed a generally increasing trend, indicating business growth and rising customer demand.

---

### Visualization 2: Sales by Category

**Chart Type:** Clustered Column Chart

**Purpose:** Compare revenue generated across product categories.

**Insight:** Technology contributes the highest sales among all categories.

---

### Visualization 3: Profit by Category

**Chart Type:** Clustered Bar Chart

**Purpose:** Analyze category-wise profitability.

**Insight:** Technology generates the highest profit, making it the most profitable category.

---

### Visualization 4: Sales by Region

**Chart Type:** Donut Chart

**Purpose:** Visualize regional contribution to overall sales.

**Insight:** West and East regions contribute the largest share of total sales.

---

### Visualization 5: Profit by Region

**Chart Type:** Bar Chart

**Purpose:** Compare profits generated across different regions.

**Insight:** The West region records the highest profitability.

---

### Visualization 6: Sales by Segment

**Chart Type:** Pie Chart

**Purpose:** Analyze customer segment contributions.

**Insight:** The Consumer segment contributes the largest share of total sales.

---

### Visualization 7: Profit vs Discount

**Chart Type:** Scatter Plot

**Purpose:** Evaluate the relationship between discount and profitability.

**Insight:** Higher discounts generally lead to lower profits, negatively affecting profit margins.

---

## Interactive Features

The dashboard includes slicers for:

- Region
- Category
- Segment

These filters allow users to interactively explore and analyze the data.

---

## Storytelling Approach

The dashboard was designed to answer the following business questions:

### How has sales performance changed over time?
Sales have consistently increased, indicating growing demand and business expansion.

### Which category performs best?
Technology is the leading category in terms of both sales and profit.

### Which region is most profitable?
The West region contributes the highest overall profit.

### Which customer segment drives revenue?
The Consumer segment generates the largest share of sales.

### What affects profitability?
Higher discount percentages negatively impact profit margins.

---

## Key Business Insights

1. Total sales exceeded **$2.3 Million**.
2. Technology is the most profitable category.
3. Consumer segment contributes the highest sales volume.
4. West region generates the highest profit.
5. Excessive discounting reduces profitability.
6. Business growth remained consistent throughout the analysis period.

---

## Recommendations

- Focus marketing efforts on Technology products.
- Optimize discount strategies to improve profit margins.
- Expand operations in high-performing regions.
- Investigate low-profit categories and products.
- Strengthen customer retention strategies for the Consumer segment.

---

## Dashboard Pages

### Page 1: Superstore Sales Dashboard

Contains:
- KPI Cards
- Sales Trend Analysis
- Category Performance Analysis
- Regional Analysis
- Segment Analysis
- Profit vs Discount Analysis

### Page 2: Executive Summary

Contains:
- Key Findings
- Business Insights
- Business Recommendations

---

## Project Structure

```text
Superstore-Sales-Dashboard/
│
├── Sample - Superstore.csv
├── Superstore_Sales_Dashboard.pbix
├── Dashboard_Screenshot.png
├── Executive_Summary.png
└── README.md
```

---

## Learning Outcomes

Through this project, I learned:

- Data visualization best practices
- Dashboard design using Power BI
- Business storytelling techniques
- KPI creation using DAX
- Interactive report development
- Insight generation from business data

---



## ⭐ Conclusion

This project demonstrates the use of Power BI to convert raw business data into actionable insights through interactive dashboards and storytelling. The analysis highlights sales trends, profitability patterns, customer behavior, and strategic recommendations that can support data-driven business decision-making.
