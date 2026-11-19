
# E-Commerce Sales Performance Analysis

**Excel-Based Sales Reporting | Shopee vs TikTok Shop**

## Overview

This portfolio project demonstrates an Excel-based e-commerce sales reporting workflow using **500 synthetic transactions** from **July–September 2026**. It covers data validation, marketplace performance, monthly revenue, SKU analysis, and dashboard reporting.

> **Dataset disclosure:** All transactions are simulated for educational and portfolio purposes. They are not actual Shopee or TikTok Shop sales.

## Business Objectives

- Compare revenue and completed orders between Shopee and TikTok Shop.
- Monitor net revenue, valid completed orders, and Average Order Value (AOV).
- Analyze monthly sales trends and product/SKU contribution.
- Identify transaction records requiring validation before reporting.

## Dataset

The dataset contains order IDs, dates, marketplaces, SKUs, quantities, unit prices, discounts, and order statuses. A separate product master provides SKU, product name, category, and reference price.

| Attribute | Description |
| --- | --- |
| Reporting period | July–September 2026 |
| Transaction count | 500 |
| Marketplaces | Shopee and TikTok Shop |
| Dataset type | Synthetic |

## Excel Workbook Structure

| Worksheet | Purpose |
| --- | --- |
| README | Project overview and instructions |
| Raw Sales Data | Original synthetic transactions |
| Product Master | SKU and product reference data |
| Data Cleaning | Product lookups, validation, and revenue eligibility |
| Sales Analysis | Marketplace, monthly, and SKU-level summaries |
| Dashboard | KPI summary and sales charts within Excel |
| Insights | Business questions and analytical recommendations |

## Methodology

### 1. Data Preparation

Organized raw marketplace transactions and maintained a separate product master for consistent SKU references.

### 2. Data Cleaning and Validation

Used Excel functions such as **VLOOKUP**, **IF**, and **COUNTIF** to retrieve product information, flag repeated order IDs, and identify records requiring review. Only valid completed transactions contribute to eligible net revenue.

### 3. Sales Analysis

Used **SUMIFS** and **COUNTIFS** to summarize revenue and order counts by marketplace and reporting month, alongside SKU-level sales performance.

### 4. Dashboard Reporting

The workbook includes an Excel dashboard summarizing revenue, valid completed orders, AOV, flagged records, and marketplace performance. **Open the Excel workbook to view the dashboard; no image files are required.**

## Reported KPIs

| Metric | Workbook value |
| --- | ---: |
| Total transactions | 500 |
| Valid completed orders | 414 |
| Net revenue | Rp55,339,000 |
| Average Order Value | Rp133,669 |
| Flagged records | 7 |

### Marketplace Performance

| Marketplace | Completed orders | Net revenue |
| --- | ---: | ---: |
| Shopee | 225 | Rp31,721,000 |
| TikTok Shop | 189 | Rp23,618,000 |
| **Total** | **414** | **Rp55,339,000** |

### Monthly Net Revenue

| Month | Shopee | TikTok Shop | Total |
| --- | ---: | ---: | ---: |
| July 2026 | Rp9,448,000 | Rp8,049,000 | Rp17,497,000 |
| August 2026 | Rp8,509,000 | Rp7,278,000 | Rp15,787,000 |
| September 2026 | Rp13,764,000 | Rp8,291,000 | Rp22,055,000 |

*Figures are the reported workbook values and should be recalculated and verified in Microsoft Excel before formal use.*

## Key Findings

- Shopee contributes more reported eligible revenue and completed orders than TikTok Shop.
- September records the highest net revenue of the three reporting months.
- Seven records are flagged for further validation.
- SKU-level summaries support identification of product revenue contribution.

## Business Recommendations

1. Monitor marketplace-level revenue and completed orders regularly.
2. Review high-performing and underperforming SKUs for inventory and promotional planning.
3. Track cancelled and refunded orders separately from eligible sales.
4. Validate duplicate IDs, SKU references, and quantities before producing reports.

These are analytical recommendations, not measured business improvements.

## Tools and Techniques

**Microsoft Excel:** VLOOKUP, IF, COUNTIF, COUNTIFS, SUMIFS, data validation, sales reporting, and Excel dashboard.

## Repository Structure

```text
E-Commerce-Sales-Performance-Analysis/
├── README.md
└── Ecommerce_Sales_Analysis_Portfolio.xlsx
```

The project **does not require an `images/` folder, screenshots, or exported dashboard pictures**.

## How to Use

1. Download the Excel workbook from this repository.
2. Open it in Microsoft Excel.
3. Read the `README` worksheet.
4. Inspect `Raw Sales Data`, `Product Master`, and `Data Cleaning`.
5. Explore `Sales Analysis`, `Dashboard`, and `Insights` for results.

## Limitations

- Synthetic data, not actual marketplace transactions.
- Three-month reporting period.
- No shipping fees, commissions, advertising costs, or product costs.
- Net revenue is not profit or official marketplace GMV.
- Flagged transactions require further review.

## Future Improvements

- Power Query imports and automated cleaning.
- Cancellation and refund trend analysis.
- Profitability reporting using costs and marketplace fees.
- Automated monthly reporting.

---

**Project:** E-Commerce Sales Performance Analysis  
**Category:** Data Analytics / Sales Reporting  
**Tool:** Microsoft Excel  
