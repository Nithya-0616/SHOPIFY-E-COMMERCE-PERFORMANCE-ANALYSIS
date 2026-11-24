# Analysis Methodology – Shopify E-commerce Performance Analysis

## 1. Project Overview

Shopify Performance Pulse is an e-commerce performance analysis project developed using Microsoft Power BI.

The project analyses sales transactions across product categories, geographical markets, payment methods and customer ratings. It also examines revenue trends, order volumes and product returns.

The objective is to transform transactional data into meaningful business insights through data preparation, analytical calculations and interactive dashboard visualisations.

## 2. Dataset Overview

The project uses a Shopify e-commerce dataset containing **60,000 transaction records and 17 columns**.

**Analysis period:** January 2023 – June 2025

### Dataset Attributes

| Attribute | Description |
|---|---|
| order_id | Unique order identifier |
| order_date | Date of the transaction |
| customer_id | Customer identifier |
| product_id | Product identifier |
| product_category | Category of the purchased product |
| product_price | Original product price |
| discount_percent | Discount applied |
| quantity | Quantity purchased |
| customer_country | Customer's geographical location |
| traffic_source | Source through which the customer arrived |
| payment_method | Payment method used |
| shipping_cost | Shipping cost associated with the order |
| rating | Customer rating |
| is_returned | Indicates whether the order was returned |
| discounted_price | Price after discount |
| revenue | Revenue generated |
| profit | Profit recorded in the dataset |

### Dataset Dimensions

- Total records: 60,000
- Total columns: 17
- Product categories: 7
- Countries: 7
- Payment methods: 5
- Traffic sources: 5
- Unique customers: 31,154

## 3. Data Preparation and Quality Checks

The dataset was reviewed before performing the analysis.

The following checks were conducted on the source CSV:

- Verified the dataset dimensions and column structure.
- Checked for missing values across all 17 columns.
- Checked for duplicate records.
- Reviewed date formats and the analysis period.
- Examined the distinct values in categorical fields.
- Reviewed numerical fields used for sales and performance analysis.

### Data Quality Observations

| Validation | Result |
|---|---|
| Total records | 60,000 |
| Missing values | 0 |
| Duplicate rows | 0 |
| Unique order IDs | 60,000 |
| Date coverage | Jan 2023 – Jun 2025 |

The source dataset contained no missing values or duplicate rows during the validation checks.

## 4. Tools and Technologies

**Primary Tool:** Microsoft Power BI

**Technologies and Techniques:**

- Power Query
- Data Cleaning and Transformation
- Data Modelling
- DAX Measures
- KPI Development
- Interactive Dashboard Design
- Data Visualisation
- Slicers and Filters

## 5. Key Performance Indicators

The dashboard presents six major business KPIs.

| KPI | Result | Business Meaning |
|---|---:|---|
| Total Revenue | 59.65M | Overall revenue generated |
| Return Rate | 14.8% | Percentage of orders marked as returned |
| Total Orders | 60K | Total number of orders |
| Total Quantity Sold | 181K | Total units sold |
| Average Order Value | 994.10 | Average revenue per order |
| Top Category | Electronics | Highest revenue-generating category |

### KPI Calculation Logic

The following calculation logic describes the metrics represented in the dashboard.

**Total Revenue**

Sum of the revenue field.

**Total Orders**

Distinct count of order IDs.

**Total Quantity Sold**

Sum of the quantity field.

**Average Order Value**

Total Revenue divided by Total Orders.

**Return Rate**

Number of returned orders divided by total orders, multiplied by 100.

**Top Category**

Product category with the highest total revenue.

## 6. Dashboard Design and Analysis

The dashboard, titled **Shopify Performance Pulse: Comprehensive E-commerce Performance Insights**, contains six major analytical visualisations.

### 6.1 Monthly Revenue and Orders

A combination chart displaying monthly revenue and order trends.

**Purpose:**
- Monitor monthly sales performance.
- Compare revenue and order volume.
- Identify fluctuations in business activity.

### 6.2 Top 5 Categories by Revenue

A pie chart comparing the revenue contribution of the leading product categories.

**Purpose:**
- Identify high-performing product categories.
- Understand category-level revenue contribution.
- Compare the relative performance of product segments.

### 6.3 Return Rate by Product Category

A horizontal bar chart comparing return percentages across product categories.

**Purpose:**
- Identify categories with higher return rates.
- Highlight potential product or customer satisfaction issues.
- Support category-level return management.

### 6.4 Orders by Payment Method

A doughnut chart showing the distribution of orders across payment methods.

The methods include:
- Apple Pay
- Cash on Delivery
- Credit Card
- Debit Card
- PayPal

**Purpose:** Understand customer payment preferences and order distribution.

### 6.5 Customer Rating Distribution

A column chart showing the distribution of orders across four customer rating bands.

**Purpose:**
- Understand the distribution of customer ratings.
- Identify rating patterns.
- Support customer experience analysis.

### 6.6 Top 5 Countries by Revenue

A horizontal bar chart comparing revenue across the five leading countries.

**Purpose:**
- Identify major geographical revenue contributors.
- Compare market performance.
- Support regional business planning.

## 7. Interactive Dashboard Features

The dashboard includes interactive slicers for:

- Product Category
- Country
- Year

These filters allow users to explore performance across different product segments, geographical markets and reporting periods.

## 8. Key Business Insights

Based on the dataset and dashboard analysis:

1. **Revenue Performance:** The business generated approximately 59.65 million in total revenue.
2. **Order Volume:** A total of 60,000 orders were recorded, with 180,574 units sold.
3. **Category Performance:** Electronics is the highest revenue-generating category, contributing approximately 8.72 million.
4. **Geographical Performance:** Australia leads the displayed country comparison with approximately 8.70 million in revenue.
5. **Product Returns:** The overall return rate is approximately 14.8%.
6. **Category Returns:** Sports records the highest category return rate at approximately 15.2%.
7. **Payment Preferences:** Apple Pay has the highest order count among the five payment methods.
8. **Customer Ratings:** The dashboard shows a relatively distributed pattern across the four rating bands.

## 9. Business Recommendations

Based on the observed performance, the following actions can be considered:

- Investigate the reasons behind higher return rates in categories such as Sports and Fashion.
- Review product quality, descriptions and customer expectations to identify possible causes of returns.
- Analyse the factors contributing to Electronics' leading revenue performance.
- Evaluate regional opportunities in high-performing markets such as Australia.
- Monitor monthly revenue and order fluctuations to improve sales planning.
- Review payment method preferences to optimise the checkout experience.
- Analyse customer ratings alongside product categories and return behaviour to identify potential areas for improvement.

## 10. Limitations and Opportunities for Further Analysis

The current dashboard focuses primarily on revenue, orders, product returns, payment methods and customer ratings.

Further analysis could explore:

- Customer segmentation using customer IDs.
- Repeat purchase behaviour.
- Revenue and profit comparisons.
- Discount impact on revenue and profitability.
- Traffic source performance.
- Shipping cost analysis.
- Customer rating patterns by product category.
- Return behaviour by country and product category.

These additional analyses could provide a more comprehensive understanding of e-commerce business performance.

## 11. Project Files

| File | Description |
|---|---|
| `SHOPIFY DATA SET.csv` | Original Shopify transaction dataset |
| `SHOPIFY.pbix` | Power BI project file |
| `SHOPIFY_DASHBOARD.png` | Dashboard preview |
| `README.md` | Project overview and key findings |

## 12. Skills Demonstrated

**Technical Skills**
- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning and Transformation
- Data Analysis
- KPI Development
- Data Visualisation
- Interactive Dashboard Development

**Analytical and Business Skills**
- E-commerce Performance Analysis
- Revenue Analysis
- Sales Trend Analysis
- Product Category Analysis
- Customer Rating Analysis
- Return Rate Analysis
- Business Insight Generation
- Data-Driven Recommendations

## 13. Conclusion

This project demonstrates how Power BI can be used to transform e-commerce transaction data into an interactive business intelligence dashboard.

By analysing revenue, order volumes, product categories, geographical performance, payment methods and product returns, the project provides a consolidated view of e-commerce performance.

The findings highlight opportunities to improve product performance, understand customer behaviour and support data-driven business decisions.

---

**Created by:** Nithya Sreenath

**Project:** Shopify E-commerce Performance Analysis using Power BI

[GitHub Profile](https://github.com/nithya16-sql) · [LinkedIn](https://www.linkedin.com/in/nithyasreenath/) · [Writing Portfolio](https://nithyasreenath.blogspot.com/)
