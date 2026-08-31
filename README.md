# Sales Performance & Profitability Dashboard | Power BI
> An interactive Power BI sales dashboard that provides a consolidated view of sales performance, profitability, customer activity,
regional performance, shipping modes, and product-level metrics to support data-driven business decisions.

## The Business Question
The objective of this project was to analyse overall sales performance and identify the key factors influencing revenue and profitability across regions, products, customer segments, and shipping modes.

The dashboard is designed for business stakeholders and sales teams who need a single view of key performance indicators and the ability to filter results by year, region, category, segment, and product. The analysis helps answer questions such as:

- Which regions generate the highest sales?
- How does sales performance change over time?
- Which products contribute most to revenue?
- How does profitability vary across shipping modes?
- What are the overall sales, customer, order, and profitability metrics?


## Dataset
- **Source:** Sales dataset provided for analytics and dashboard development
- **Size:** [5000 rows,400 customers, 15 columns]
- **Time period:** [01-01-2023 - 31-12-2025]
- **Key columns:** - `order_id`
  - `order_date`
  - `ship_date`
  - `ship_mode`
  - `customer_id`
  - `customer_name`
  - `segment`
  - `region`
  - `category`
  - `product_name`
  - `quantity`
  - `unit_price`
  - `discount`
  - `sales`
  - `profit`
### Data Grain
Each row in the dataset represents an individual order-level sales transaction containing customer, product, shipping, revenue, and profit information.
---

## Tools Used

- **Power BI** — Dashboard development and interactive data visualisation
- **Power Query** — Data cleaning and transformation
- **DAX** — Creation of business measures and KPIs
- **Excel / CSV** — Source data storage and preparation
- 
## What I Did

1. **Reviewed and prepared the sales dataset** by validating date, customer, product, sales, and profit fields before importing the data into Power BI.

2. **Created a data model and calculated business metrics** including:
   - Total Orders
   - Total Revenue
   - Total Customers
   - Average Order Value
   - Profit Margin %

3. **Developed DAX measures** to calculate aggregated sales, profit, customer, and order metrics dynamically based on report filters.

4. **Built an interactive Power BI dashboard** with slicers for:
   - Year
   - Region
   - Category
   - Segment
   - Product
   - ---

## Dashboard Overview

The dashboard provides the following high-level KPIs:

| KPI | Value |
|---|---:|
| Total Orders | **5K** |
| Total Revenue | **12.49M** |
| Profit Margin | **14.60%** |
| Total Customers | **400** |
| Average Order Value | **31.23K** |

### Visualisations

- **Sales Trend by Year and Month** — Tracks changes in monthly sales performance over time.
- **Sales by Region** — Compares total sales across geographic regions.
- **Profit Margin by Ship Mode** — Evaluates profitability across different shipping methods.
- **Product Performance Table** — Provides product-level sales and profit margin analysis.
- **Interactive Filters** — Allow stakeholders to drill into specific years, regions, categories, segments, and products.

---

## Key Findings

### 1. Sales performance is relatively balanced across regions, with the South leading

The **South region generated approximately 2.6M in sales**, making it the highest-performing region. Central, West, and East each generated approximately **2.5M**, while North generated approximately **2.4M**.

This indicates that sales are relatively well distributed geographically, with no single region dominating overall revenue.
---

### 2. Overall sales reached 12.49M across approximately 5K orders

The business generated **12.49M in total revenue** from approximately **5,000 orders**, resulting in an average order value of **31.23K**.

This provides a baseline for evaluating future sales growth, customer purchasing behaviour, and order value trends.

---

### 3. Profitability varies across shipping modes

Profit margins differ across shipping methods, with the dashboard showing margins of approximately:

- **Same Day:** 25.8%
- **Standard Class:** 25.3%
- **First Class:** 24.7%
- **Second Class:** 24.1%

Same Day shipping shows the highest profit margin among the shipping modes displayed, although the differences are relatively narrow.

---

### 4. Sales fluctuate over time with noticeable monthly peaks

Monthly sales generally fluctuate between approximately **0.25M and 0.45M**, with several periods showing strong sales peaks.

The highest sales period occurs toward the end of the available time series, reaching approximately **0.45M+**, indicating a potential opportunity to investigate seasonal demand patterns and the drivers behind high-performing months.

---

### 5. Product-level performance varies significantly

The product performance table highlights differences in both sales contribution and profit margin across products.

For example, products such as **Binder, Bookcase, and Chair** are among the stronger contributors to total sales, while profit margins vary across individual products.

This suggests that revenue performance alone should not be used to evaluate product success; sales and profitability should be analysed together.

---
## Recommendations

### 1. Investigate high-performing months and replicate successful drivers

Analyse the periods with the highest sales to identify potential drivers such as:

- Seasonal demand
- Product mix
- Customer segment behaviour
- Regional performance
- Promotional activity

Successful patterns can then be used to inform future sales and inventory planning.

---

### 2. Optimise product strategy using both revenue and profit margin

High-revenue products should be evaluated alongside their profitability.

Products with:

- High sales and high margins should be prioritised for growth.
- High sales but low margins should be reviewed for pricing or discount optimisation.
- Low sales but strong margins may represent opportunities for targeted promotion.

---

### 3. Investigate regional opportunities

Although regional sales are relatively balanced, the **North region generates the lowest sales** among the regions shown.

Further analysis could investigate whether this is driven by:

- Lower customer volume
- Lower average order value
- Product mix
- Customer segments
- Shipping preferences

---

### 4. Continue monitoring shipping profitability

Since profit margins vary across shipping modes, shipping strategy should be monitored alongside customer demand and delivery costs.

A deeper analysis could examine whether higher-margin shipping modes also have sufficient order volume to materially impact total profitability.

---


