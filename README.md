# Product Sales Analysis & Dashboard

A data analysis project examining product-level performance, customer purchasing trends, regional revenue distributions, and payment channel efficiency using Excel.

---

## Project Overview

This project provides an end-to-end evaluation of commercial sales data. By cleaning, structuring, and analyzing order-level transaction records, this project highlights key operational drivers—such as top-performing product categories, high-value customer demographics, peak sales channels, and profit margin distributions.

The repository includes the complete dataset along with dynamic analytical breakdowns designed to support data-driven decision-making for inventory management, marketing strategy, and financial forecasting.

---

## Dataset Structure

The dataset (`Product_Sales_Analysis.xlsx`) comprises individual transaction records with the following core attributes:

| Field Name | Description | Data Type |
| :--- | :--- | :--- |
| **Order ID** | Unique identifier for each customer transaction | String / Text |
| **Order Date** | Date the transaction was placed | Date (`YYYY-MM-DD`) |
| **Customer ID / Name** | Unique identifier and name of the buyer | Text |
| **Region / Location** | Geographical market segment | Categorical |
| **Product Category** | High-level classification of products | Categorical |
| **Sub-Category / Product** | Specific item purchased | Text |
| **Unit Price** | Cost per single unit sold | Currency / Decimal |
| **Quantity** | Number of units purchased per order | Integer |
| **Total Revenue** | Gross revenue generated (`Unit Price` × `Quantity`) | Currency / Decimal |
| **Discount / Cost** | Associated promotional discounts or item cost basis | Currency / Percentage |
| **Net Profit** | Bottom-line earnings generated per order | Currency / Decimal |
| **Payment Method** | Channel used for settlement (e.g., Credit Card, Bank Transfer, MoMo) | Categorical |

---

## Key Analytical Highlights

### 1. Financial Performance Metrics
* **Gross Revenue vs. Net Profit:** Comparison of top-line sales performance against actual profit margins across product lines.
* **Average Order Value (AOV):** Identification of customer spending patterns per transaction segment.
* **Discount Impact Analysis:** Evaluation of how promotional pricing affects net profit margins.

### 2. Regional & Channel Insights
* **Geographic Distribution:** Mapping total sales density across targeted regional markets to identify key revenue hubs.
* **Payment Preference:** Breakdown of customer payment methods to highlight conversion pathways and preferred payment gateways.

### 3. Product & Inventory Trends
* **Top-Selling Categories:** Volume vs. value comparison to identify high-margin items vs. fast-moving inventory.
* **Seasonality & Growth:** Time-series tracking of daily, monthly, and quarterly revenue trends to support stock planning.

---

## How to Use the Excel Workbook

1. **Raw Data Sheet (`Sales_Data`):** Contains the sanitized, structured master transaction log.
2. **Pivot Summary Tables (`Pivot_Summaries`):** Aggregated metrics summarizing sales by region, category, date, and payment channel.
3. **Interactive Dashboard (`Dashboard`):** Includes visual KPI cards, chart visualizations, and slicers (interactive filters) allowing dynamic filtering by:
   * **Date Range / Quarter**
   * **Product Category**
   * **Geographic Region**

---

## Key Recommendations & Strategic Takeaways

* **Inventory Optimization:** Focus procurement capital on high-margin, high-demand sub-categories while reviewing slow-moving SKUs.
* **Targeted Marketing:** Direct promotional spend toward high-performing geographic regions during peak purchasing periods.
* **Payment Integration:** Prioritize seamless checkout options for the dominant payment methods identified in the analysis to reduce cart abandonment.

---

## Tools & Technologies Used

* **Microsoft Excel / Google Sheets:**
  * Advanced Formulas (`SUMIFS`, `XLOOKUP`, `INDEX/MATCH`, `LET`)
  * Data Cleaning & Formatting
  * Pivot Tables & Pivot Charts
  * Interactive Slicers & Dynamic Dashboards

---

## Contact & Connect

* **Author:** Emmanuel Atta Opoku
* **LinkedIn:** www.linkedin.com/in/opoku-emmanuel-atta
