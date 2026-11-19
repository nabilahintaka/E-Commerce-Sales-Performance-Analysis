
# E-Commerce Sales Performance Analysis

**Excel-Based Sales Reporting | Shopee vs TikTok Shop**

## Overview

This project analyzes **500 synthetic e-commerce transactions** from Shopee and TikTok Shop covering **July–September 2026**. Using Microsoft Excel, the analysis combines data preparation, transaction validation, sales performance analysis, and dashboard reporting to evaluate marketplace performance, monthly revenue trends, and product-level sales.

The goal is to demonstrate how structured sales reporting and data quality checks can support reliable performance monitoring and data-driven business decisions.

## Executive Summary

The analysis reports **Rp55,339,000 in net revenue** from **414 valid completed orders**, with an Average Order Value (AOV) of **Rp133,669**.

Shopee contributes the largest share of net revenue at **Rp31,721,000 (57.3%)**, compared with TikTok Shop at **Rp23,618,000 (42.7%)**. September records the highest monthly revenue at **Rp22,055,000**.

The validation process also identifies **7 flagged records**, highlighting the importance of transaction quality checks before reporting sales performance.

All findings are based on synthetic data created for educational and portfolio purposes.

---

## Business Objectives

- Compare net revenue and completed orders between Shopee and TikTok Shop.
- Monitor sales KPIs, including net revenue, valid completed orders, and Average Order Value (AOV).
- Analyze monthly sales trends and product-level performance.
- Identify transaction records requiring validation before reporting.

---

## Dataset

The dataset contains synthetic marketplace transactions, including order IDs, dates, marketplaces, SKUs, quantities, unit prices, discounts, and order statuses.

A separate Product Master provides SKU references, product names, categories, and reference prices.

| Attribute | Description |
| --- | --- |
| Reporting Period | July–September 2026 |
| Total Transactions | 500 |
| Marketplaces | Shopee and TikTok Shop |
| Dataset Type | Synthetic |
| Main Dimensions | Date, Marketplace, SKU, Order Status |
| Main Measures | Quantity, Unit Price, Discount, Net Revenue |

---

## Data Processing & Methodology

### 1. Data Preparation

- Organized synthetic transactions across Shopee and TikTok Shop.
- Structured order identifiers, SKUs, quantities, prices, discounts, and order statuses.
- Maintained a Product Master for consistent product references.

### 2. Data Cleaning & Validation

- Used VLOOKUP to retrieve product information from the Product Master.
- Applied Excel validation formulas to identify duplicate Order IDs and unmapped SKUs.
- Separated cancelled and refunded transactions from completed orders.
- Identified 7 flagged records requiring review.
- Included only valid completed transactions in eligible net revenue calculations.

### 3. Sales Analysis

- Used SUMIFS and COUNTIFS to calculate marketplace revenue and completed order counts.
- Calculated Average Order Value (AOV).
- Compared monthly sales performance from July to September 2026.
- Analyzed SKU-level revenue contribution and units sold.

### 4. Dashboard Reporting

- Developed an Excel dashboard to summarize sales KPIs.
- Visualized marketplace performance and monthly revenue trends.
- Presented sales results and transaction quality indicators for reporting.

---

## Sales Performance

### Key Performance Indicators

| Metric | Value |
| --- | ---: |
| Total Transactions | 500 |
| Valid Completed Orders | 414 |
| Net Revenue | Rp55,339,000 |
| Average Order Value | Rp133,669 |
| Flagged Records | 7 |

### Marketplace Performance

| Marketplace | Valid Completed Orders | Net Revenue | Revenue Share |
| --- | ---: | ---: | ---: |
| Shopee | 225 | Rp31,721,000 | 57.3% |
| TikTok Shop | 189 | Rp23,618,000 | 42.7% |
| **Total** | **414** | **Rp55,339,000** | **100%** |

### Monthly Net Revenue

| Month | Shopee | TikTok Shop | Total |
| --- | ---: | ---: | ---: |
| July 2026 | Rp9,448,000 | Rp8,049,000 | Rp17,497,000 |
| August 2026 | Rp8,509,000 | Rp7,278,000 | Rp15,787,000 |
| September 2026 | Rp13,764,000 | Rp8,291,000 | Rp22,055,000 |

---

## Key Findings

### 1. Marketplace Performance

**Shopee generates higher net revenue and completed order volume than TikTok Shop.**

Shopee contributes Rp31.72 million (57.3%) in net revenue across 225 valid completed orders, compared with TikTok Shop's Rp23.62 million (42.7%) across 189 orders.

### 2. Order Status & Validation

**Transaction validation reduces the number of orders eligible for revenue reporting.**

Out of 500 transactions, 420 are marked Completed, 50 Cancelled, and 30 Refunded. After validation, 414 completed orders remain eligible for revenue reporting.

Seven records are flagged for review.

### 3. Product Performance

**The Home category leads revenue contribution, while product performance differs by revenue and units sold.**

Mini Diffuser generates Rp9.77 million, followed by Tumbler Stainless at Rp9.46 million. Serum Niacinamide leads unit volume with 86 units sold.

### 4. Monthly Revenue Performance

**September records the highest net revenue of the reporting period.**

Net revenue reaches Rp22.06 million in September, compared with Rp17.50 million in July and Rp15.79 million in August.

The increase is primarily reflected in Shopee's September sales performance.

---

## Business Recommendations

### Marketplace Monitoring

Monitor sales performance across Shopee and TikTok Shop to identify differences in revenue contribution, completed order volume, and Average Order Value.

### SKU Optimization

Review high-performing and underperforming SKUs to support inventory allocation and promotional planning, prioritizing products with strong revenue and unit sales performance.

### Order Status Monitoring

Track cancelled and refunded orders separately from valid completed transactions to improve sales reporting accuracy and identify potential operational issues.

### Data Quality Improvement

Implement consistent transaction validation checks to identify duplicate Order IDs, unmapped SKUs, and other data quality issues before generating reports.

---

## Tools & Technologies

| Tool / Technique | Purpose |
| --- | --- |
| Microsoft Excel | Data processing, analysis, and reporting |
| VLOOKUP | Product reference lookup |
| IF & IFERROR | Conditional logic and error handling |
| COUNTIF & COUNTIFS | Validation and transaction counting |
| SUMIFS | Revenue aggregation |
| Excel Charts | Sales performance visualization |
| Excel Dashboard | KPI monitoring and reporting |

---

## Excel Workbook Structure

| Worksheet | Purpose |
| --- | --- |
| README | Project overview and instructions |
| Raw Sales Data | Original synthetic transactions |
| Product Master | SKU and product reference data |
| Data Cleaning | Product lookups and transaction validation |
| Sales Analysis | Marketplace, monthly, and SKU-level summaries |
| Dashboard | Sales KPI reporting and charts |
| Insights | Business findings and recommendations |

---

## Repository Structure

    E-Commerce-Sales-Performance-Analysis/
    ├── README.md
    └── Ecommerce_Sales_Analysis_Portfolio.xlsx

## How to Use

1. Download the Excel workbook from this repository.
2. Open the workbook in Microsoft Excel.
3. Review the README and Raw Sales Data worksheets.
4. Explore the Product Master and Data Cleaning worksheets.
5. Review Sales Analysis for marketplace, monthly, and SKU-level results.
6. Open the Dashboard worksheet to view the Excel sales dashboard.
7. Read the Insights worksheet for analytical findings and recommendations.

---

## Limitations

- The dataset contains synthetic transactions and does not represent actual marketplace sales.
- The analysis covers only July–September 2026.
- Shipping fees, commissions, advertising costs, and product costs are not included.
- Net revenue should not be interpreted as profit or official marketplace GMV.
- Flagged records require additional review.

---

## Future Improvements

- Automate data imports and cleaning using Power Query.
- Develop Pivot Tables and slicers for more flexible reporting.
- Expand cancellation and refund analysis.
- Incorporate marketplace fees and product costs for profitability analysis.
- Automate recurring sales performance reporting.


---

**Project:** E-Commerce Sales Performance Analysis  
**Category:** Data Analytics / Sales Reporting  
**Tool:** Microsoft Excel  
