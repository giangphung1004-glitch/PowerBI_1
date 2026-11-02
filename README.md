# Adventure Works's Report | Power BI

**An interactive Power BI report analyzing sales performance, product trends, and manufacturer-level contributions across the Adventure Works dataset.**

## Project Overview

Adventure Works's Report is a Power BI portfolio project that explores sales performance across manufacturers, geographic markets, products, and time periods. It provides an overall view of revenue, sales volume, and product performance. **VanArsdel is one of the manufacturers represented in the dataset**, and a dedicated dashboard page examines its performance and contribution relative to total market revenue.

**Key business questions:**
- How do revenue, units sold, and average order value change over time?
- Which manufacturers, countries, and product categories contribute the most revenue?
- How much revenue and sales volume does VanArsdel, as one of the manufacturers, contribute compared with the overall market?
- Which products and segments drive sales, and how do results compare with the previous year?
- What factors help explain differences in revenue across locations and product groups?

## Dashboard Pages

| Page | What it covers |
| --- | --- |
| **Market Overview** | Revenue, quantity sold, average order value (AOV), year-over-year changes, revenue trends, and comparisons by manufacturer, country, and category. |
| **VanArsdel Performance** | A closer look at one manufacturer: VanArsdel revenue, units sold, revenue share compared with the overall market, trends over time, country breakdowns, and product-level details. |
| **Product & Segment Analysis** | Product and segment comparisons, top-five products by revenue, current-versus-prior-year revenue, and revenue by category. |
| **Further Analysis** | Interactive exploration using Power BI Q&A, a Decomposition Tree, and Key Influencers to investigate revenue-related patterns. |

The report also includes a navigation/landing page and an additional city-level revenue chart.

## Key Metrics

The report uses measures and comparisons including:

- **Revenue** and **Total Quantity** — overall sales value and units sold.
- **Average Order Value (AOV)** — sales value per order, as defined in the report model.
- **Year-over-Year (YoY) Growth** — changes in revenue, quantity, and AOV versus the prior year.
- **Previous-Year Revenue** — a reference point for monthly and product performance comparisons.
- **VanArsdel Revenue & Quantity** — sales performance for VanArsdel, one manufacturer in the dataset.
- **VanArsdel Revenue Share** — the proportion of total revenue attributable to VanArsdel.

## Data Model & Power BI Features

The report references six tables: `Facts`, `Sales`, `Product`, `Manufacturer`, `Geography`, and `Date`.

**Power BI capabilities demonstrated:**
- KPI cards and DAX-based measures
- Line, bar, column, combo, pie, donut, and treemap visuals
- Product-level tables and hierarchical matrix analysis
- Interactive slicers for year, manufacturer, category, product, and segment
- Page navigation and cross-filtering
- Q&A, Decomposition Tree, and Key Influencers visuals

## View the Project

**[Download the Power BI report (.pbix)](HW12%20-%20Ph%C3%B9ng%20Th%E1%BB%8B%20H%C6%B0%C6%A1ng%20Giang.pbix)**

1. Download the `.pbix` file from this repository.
2. Open it using **Microsoft Power BI Desktop**.
3. Use the page navigation and slicers to explore the dashboard.

> **Note:** The report's connection metadata references a remote Power BI dataset. Depending on the environment, refreshing or reconnecting to that dataset may require appropriate access permissions. The repository contains the report file, not a separate export of its underlying data.

## Dashboard Screenshots

Screenshots of the report pages can be added to this repository to provide a quick preview without requiring Power BI Desktop.

<!-- Once you upload dashboard.png to the repository root, remove these HTML comment markers to show the screenshot in GitHub:
![Adventure Works's Report dashboard](dashboard.png)
-->

## Tools

**Microsoft Power BI Desktop** · **DAX** · **Data Modeling** · **Business Intelligence & Visualization**
