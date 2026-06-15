# Supply Chain Inventory Optimization Analysis
### Inventory Risk, Lead Time Performance & Quality Analysis

## Project Overview

This project analyses inventory health across products and suppliers to identify stock risks, operational bottlenecks, and opportunities for inventory optimization.

The objective was to determine whether inventory imbalances were driven primarily by supplier performance, manufacturing delays, product quality issues, or a combination of operational factors.

## Business Questions

- How balanced are current inventory levels?
- Which products are at risk of overstocking or understocking?
- Which product categories show the highest concentration of inventory risk?
- Do supplier lead times contribute to inventory imbalances?
- Are manufacturing delays associated with stock shortages?
- Is there a relationship between product quality issues and inventory risk?
- Where should the business prioritise inventory improvement efforts?

## Data Source

**Dataset:**
Supply Chain Inventory Dataset

The analysis used product, supplier, inventory, manufacturing, and quality data to evaluate inventory performance across the supply chain.

### Key Fields Used

- SKU
- Product Type
- Stock Levels
- Number of Products Sold
- Availability
- Supplier Name
- Supplier Lead Time
- Manufacturing Lead Time
- Defect Rates
- Inspection Results
- Revenue Generated
- Manufacturing Costs
- Shipping Costs

### Engineered Fields

- Stock-to-Order Ratio
- Stock Risk Classification
- Understock Flag
- Overstock Flag
- Inventory Risk Indicators

## Methodology

### 1. Data Preparation (Google Sheets)

Data was cleaned and validated to:

- Identify and remove duplicate records
- Check for missing values
- Standardise field formatting
- Validate category values
- Review numerical outliers
- Create inventory risk classifications
- Calculate stock-to-order ratios

### 2. Exploratory Analysis

The analysis focused on five core areas:

- **Inventory Health** → evaluating overall inventory balance
- **Product Category Risk** → identifying high-risk product groups
- **Supplier Performance** → analysing supplier lead times and inventory risk
- **Lead Time Impact** → comparing supplier and manufacturing delays
- **Quality Analysis** → examining defect rates and inspection results

### 3. Dashboard Development

Insights were visualised in Tableau through an interactive dashboard designed to communicate inventory risks, operational performance, and improvement opportunities.

## Key Findings

- 90% of products were classified as normal inventory levels
- Only 10% of products were identified as overstock or understock risks
- Cosmetics contained the highest concentration of inventory risk flags
- Supplier lead times alone did not explain inventory imbalances
- Understocked products exhibited the longest manufacturing lead times
- Understocked products also showed the highest average defect rates
- Manufacturing and quality issues appeared more closely associated with inventory shortages than supplier performance

## Strategic Recommendations

### Improve Inventory Planning

Review forecasting and replenishment strategies for products with recurring inventory imbalances, particularly within the Cosmetics category.

### Reduce Manufacturing Bottlenecks

Investigate production delays contributing to extended manufacturing lead times and inventory shortages.

### Strengthen Quality Control

Prioritise quality improvement initiatives for products with elevated defect rates and inspection failures.

### Monitor Inventory Risk Proactively

Implement ongoing inventory risk monitoring to identify overstock and understock situations before they become operational issues.

## Visualisation

The interactive dashboard was built in Tableau Public.

**View Interactive Dashboard:**
https://public.tableau.com/app/profile/tony.deehan/viz/SupplyChainAnalysis_17805040530980/Dashboard1

## Tools and Technologies

- Google Sheets — Data cleaning and exploratory analysis
- Tableau Public — Dashboard creation and visualisation
- PDF Executive Summary — Stakeholder reporting

## Project Structure

```text
supply-chain-inventory-analysis/
│
├── assets/          # Dashboard images and screenshots
├── data/            # Dataset (if included)
├── reports/         # Executive summary PDF
└── README.md
```

## What This Project Demonstrates

- Translating business problems into analytical questions
- Cleaning and preparing operational data
- Creating inventory risk classifications
- Identifying drivers of inventory imbalances
- Building interactive Tableau dashboards
- Communicating findings through executive-level reporting
- Delivering actionable operational recommendations

## Notes

This project uses a publicly available supply chain dataset for portfolio purposes.

All analysis, calculations, dashboard design, and recommendations were developed independently to demonstrate end-to-end data analysis skills.
