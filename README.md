# Pharmaceutical-Revenue-Product-Performance-Demand-Analytics

## Project Overview

This project delivers a data-driven analysis of pharmaceutical revenue performance, product contribution, and demand patterns.

Using pharmacy dispensing records collected through the Electronic Medical Record (EMR) system, the project examines product-level revenue, transaction volumes, dispensing demand, and demand consistency to support better procurement planning, inventory optimisation, restocking decisions, and resource allocation.

The analytical solution was compiled by **Waterside Tree Consultancy** to support the pharmacy's operational improvement initiative.

## Business Problem

Pharmacy departments must balance medicine availability, procurement expenditure, inventory holding costs, and patient demand.

Without structured analysis, procurement decisions may result in:

- Excess inventory and avoidable expiry.
- Stock-outs of high-priority medicines.
- Inefficient allocation of procurement budgets.
- Poor visibility into revenue-generating products.
- Reactive rather than planned replenishment.
- Uneven distribution of inventory resources.

This project addresses these challenges through revenue segmentation and demand classification.

## Project Objectives

1. Evaluate pharmaceutical revenue performance across the 2025 reporting period.
2. Identify products contributing the highest revenue.
3. Measure product demand and monthly dispensing patterns.
4. Apply ABC analysis to classify products according to revenue contribution.
5. Apply XYZ analysis to assess demand consistency.
6. Identify strategically important products through ABC-XYZ segmentation.
7. Translate analytical findings into practical procurement and inventory management recommendations.

## Analytical Framework

### 1. ABC Analysis – Revenue Classification

ABC analysis categorises pharmaceutical products according to their contribution to total revenue.

| Category | Business Meaning | Management Priority |
|---|---|---|
| A | High-revenue products | Highest financial oversight |
| B | Medium-revenue products | Moderate oversight |
| C | Low-revenue products | Simplified controls |

### 2. XYZ Analysis – Demand Consistency

XYZ analysis classifies products based on the consistency of their historical demand.

| Category | Demand Behaviour | Management Approach |
|---|---|---|
| X | Relatively consistent demand | Planned replenishment |
| Y | Variable demand | More frequent review |
| Z | Irregular demand | Cautious, needs-based purchasing |

### 3. ABC-XYZ Matrix

Combining both frameworks provides a more comprehensive understanding of product importance.

| Segment | Classification | Recommended Strategy |
|---|---|---|
| AX | High revenue, consistent demand | Strategic procurement priority |
| AY | High revenue, variable demand | Frequent demand review |
| AZ | High revenue, irregular demand | Controlled, case-by-case purchasing |
| BX | Medium revenue, consistent demand | Routine replenishment |
| BY | Medium revenue, variable demand | Periodic stock review |
| BZ | Medium revenue, irregular demand | Cautious procurement |
| CX | Low revenue, consistent demand | Economical replenishment |
| CY | Low revenue, variable demand | Controlled stock holding |
| CZ | Low revenue, irregular demand | Needs-based procurement |

## Key Business Findings

### Overall Revenue Performance

- Total pharmaceutical revenue: **₦996.09 million**
- Total products: **1,128**
- Total dispensing transactions: **327,000 approximately**

### Class A – High-Revenue Products

- Revenue contribution: **₦856.47 million**
- Number of products: **225**
- Share of total portfolio revenue: **Approximately 86%**

Class A products represent the most financially significant segment of the pharmacy portfolio and deserve stronger procurement and management oversight.

### Class X – Consistent-Demand Products

- Number of products: **94**
- Average demand indicator: **5.76**

These products demonstrate comparatively consistent historical demand, supporting more structured replenishment planning.

### AX – High-Revenue, Consistent-Demand Products

- Revenue contribution: **₦328.83 million**
- Number of products: **60**
- Share of total portfolio revenue: **Approximately 33%**
- Share of Class A revenue: **Approximately 38%**

The AX segment represents a strategic procurement priority because it combines substantial financial contribution with relatively predictable demand.

## Executive Recommendations

Five operational recommendations emerged from the analysis:

1. **Prioritise AX products in procurement planning.** Maintain an approved priority list and review stock availability, supplier lead times, and outstanding orders before each purchasing cycle.

2. **Establish minimum and maximum stock levels.** Define item-level reorder points, target stock quantities, and safety allowances using historical usage and supplier lead times.

3. **Implement scheduled replenishment.** Introduce regular procurement review cycles for AX products to reduce emergency purchases and improve medicine availability.

4. **Align budgets and storage with product priority.** Use Class A revenue contribution and AX classification to guide procurement budgets, storage planning, and management oversight.

5. **Monitor inventory exceptions and redistribute stock.** Track low-stock alerts, approaching expiry dates, unusual demand changes, and delayed deliveries. Consider approved stock transfers where appropriate.

## Dashboard Components

The Power BI reporting solution includes:

- Total pharmaceutical revenue.
- Number of products.
- Total dispensing transactions.
- Monthly revenue trends.
- Monthly total demand trends.
- Monthly average demand trends.
- Top revenue-generating products.
- Most in-demand products.
- ABC product classification.
- XYZ demand classification.
- Product-level filtering and interactive segmentation.

## Tools and Technologies

| Technology | Application |
|---|---|
| Electronic Medical Record (EMR) | Pharmacy dispensing data source |
| MySQL | Data extraction and transformation |
| SQL | Revenue aggregation and analytical queries |
| Python | Data analysis and preparation |
| Power BI | Interactive dashboards and reporting |
| ABC Analysis | Revenue-based product classification |
| XYZ Analysis | Demand consistency classification |

## Business Impact and Expected Value

The analytical framework provides pharmacy management with a structured basis for:

- Improving procurement prioritisation.
- Reducing avoidable inventory accumulation.
- Supporting timely restocking decisions.
- Improving allocation of procurement resources.
- Identifying products requiring closer monitoring.
- Strengthening inventory visibility and accountability.
- Supporting evidence-based operational decisions.

These are intended operational benefits. Their realised financial and service impacts should be measured through subsequent monitoring.

## Data Governance and Considerations

The analysis uses pharmacy data collected through the hospital's EMR system.

Patient-identifiable information was excluded from public repositories and GitHub uploads.

Demand classifications describe historical patterns and should not be interpreted as guaranteed future demand. Procurement decisions should also consider clinical importance, supplier reliability, lead times, expiry dates, current stock levels, and available budgets.

## Project Contributor

**Waterside Tree Consultancy**

Analytics, business intelligence, pharmaceutical revenue intelligence, demand analysis, and inventory optimisation.

## Conclusion

This project demonstrates how pharmacy dispensing data can be transformed into actionable business intelligence.

By combining revenue contribution with demand consistency, the ABC-XYZ framework provides a practical foundation for identifying high-priority pharmaceutical products and improving procurement, inventory management, replenishment, and resource allocation.

**The ultimate objective is to support better inventory decisions, improve medicine availability, and strengthen pharmacy operational efficiency.**

---
**Project:** FMCB Pharmaceutical Revenue, Product Performance & Demand Analytics  
**Reporting Period:** January – December 2025  
**Data Source:** Electronic Medical Record (EMR)  
**Compiled by:** Waterside Tree Consultancy
"""
