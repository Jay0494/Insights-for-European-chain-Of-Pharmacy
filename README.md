
---

##  Pharmacy Sales performance For 2025

Following an initial stakeholder meeting, the analytical objectives were clearly defined around three core questions:

1. How sales and profitability vary across Pharmaceutical Products, and individual pharmacies
2. Create a dashboard to monitor product categories and brands performance across different locations
3. How regional performance contributes to overall business results

With these objectives confirmed, the focus shifted to data assessment, preparation, and dashboard development in Power BI.

---

## Data Review & Preparation

The provided dataset included sales, pharmacy, product, and date-related tables. An initial data audit was conducted to assess structure, quality, and relevance.

Key preparation steps included:

* Dropping the provided date table in order to create a custom date dimension aligned to analytical needs
* Standardizing the sales, pharmacy, and product tables to ensure consistency
* Validating data quality by checking for duplicates, null values, and irrelevant fields
* Removing one non-essential column (`Discontinued Date`), as it did not support the defined business questions

After review, the dataset was deemed clean and analysis-ready. All tables were then loaded into Power BI via Power Query.

---

## Data Modeling

A custom date table was created using the `CALENDARAUTO()` function, with additional formatting and enrichment to support time-based analysis. This included:

* Year, month, and quarter fields
* A weekday vs. weekend classification column

Relationships were then established across the fact and dimension tables, resulting in a clean star-schema-style model optimized for performance and clarity.

To improve measure organization and maintainability, DAX measures were grouped into logical folders:

* Aggregates
* Statistics
* Time series measures

---

## Scope of Analysis

The analysis focuses specifically on **2025 performance**, providing a clear and consistent reporting period for stakeholders.

### Overall Performance (2025)

* **Total Revenue:** €4.41M
* **Total Profit:** €1.24M
* **COGS:** €3.17M
* **Units Sold:** 228K+
* **Transactions:** 32K
* **Profit Margin:** 28.1%

---

## Product Performance Insights

* Prescription products generated the highest revenue share (**16.6%**) but recorded the **lowest profit margin (22%)**
* OTC (10.5%), Wellness (10.2%), and Personal Care (8.7%) products demonstrated stronger margin performance relative to their revenue share
* Medical devices contributed 5% of revenue

This highlights a key trade-off between **revenue volume and profitability**, where high-margin categories are “punching above their weight.”

---

## Brand, Store & Location Performance

* **Non-generic products** dominated performance, contributing **85.7% of total revenue**
* **Medium-sized stores** performed best (23.2% of revenue), followed by large (18.4%) and small stores (9.6%)
* **Urban pharmacies** led performance (24.4%), followed by suburban (18.4%) and rural locations (8.3%)

---

## Geographic Performance

* Germany led revenue contribution (9%), followed by France (8.2%) and Italy (8.1%)
* Spain, Poland, and Austria were the lowest-performing countries at approximately 4% each

These insights highlight clear geographic performance gaps and opportunities for regional optimization.

---

## Time-Based Trends

* Revenue peaked in **May (8.7%)**, **July (8.9%)**, **October (8.7%)**, and **December (8.4%)**
* February recorded the lowest revenue contribution (7.6%)
* Profit margin peaked in March (28.2%), remained stable around 28%, dipped slightly in September (27.8%), and recovered to 28.1% by December
* Overall, the business demonstrated a **steady monthly revenue growth trend of approximately 1%**

---

## Key Business Insights

* High-revenue products do not always deliver the strongest margins
* Margin-strong categories such as OTC, Wellness, and Personal Care present optimization opportunities
* Urban, medium-sized pharmacies are key performance drivers
* Regional disparities suggest targeted commercial and operational strategies could improve results

---

## Dashboard Access

**Power BI Dashboard:**
[https://app.powerbi.com/view?r=eyJrIjoiMTBlYTBjMmItNzQ4ZC00OGQ0LTllY2YtMTg5YWVlMWRkZWMwIiwidCI6ImIyMTFiMjkwLWFkNzUtNGJlNC1iZDk3LWI5Y2MxZDlmMzdlZCJ9](https://app.powerbi.com/view?r=eyJrIjoiMTBlYTBjMmItNzQ4ZC00OGQ0LTllY2YtMTg5YWVlMWRkZWMwIiwidCI6ImIyMTFiMjkwLWFkNzUtNGJlNC1iZDk3LWI5Y2MxZDlmMzdlZCJ9)

---
---

## Recommendations & Business Impact

### 1. Optimize Product Mix to Improve Margins

**Insight:** Prescription products drive the highest revenue but deliver the lowest profit margin (22%), while OTC, Wellness, and Personal Care products generate stronger margins.

**Recommendation:**

* Maintain prescription products as volume drivers
* Increase promotional focus, shelf space, and cross-selling for OTC, Wellness, and Personal Care categories
* Bundle high-margin products with prescription purchases where feasible

**Business Impact:**

* Improved overall profit margin without sacrificing total revenue
* Better balance between revenue growth and profitability

---

### 2. Prioritize High-Performing Store Profiles

**Insight:** Medium-sized and urban pharmacies contribute the largest share of revenue.

**Recommendation:**

* Prioritize investment, inventory depth, and staffing optimization in medium-sized urban pharmacies
* Use high-performing stores as benchmarks for operational best practices
* Review underperforming small and rural stores for efficiency improvements

**Business Impact:**

* Higher return on operational investments
* More efficient resource allocation across the pharmacy network

---

### 3. Target Geographic Growth Opportunities

**Insight:** Germany, France, and Italy lead revenue contribution, while Spain, Poland, and Austria lag behind.

**Recommendation:**

* Replicate successful commercial strategies from top-performing countries into lower-performing regions
* Conduct localized analysis to identify country-specific product or pricing gaps
* Tailor promotions and assortments based on regional demand patterns

**Business Impact:**

* Reduced regional performance disparities
* Incremental revenue growth from underperforming markets

---

### 4. Leverage Seasonality for Sales Planning

**Insight:** Revenue peaks in May, July, October, and December, with a noticeable dip in February.

**Recommendation:**

* Increase inventory and marketing efforts ahead of peak months
* Introduce targeted promotions or campaigns during low-performing periods (e.g., February)
* Align staffing and supply chain planning with seasonal demand trends

**Business Impact:**

* Improved stock availability during high-demand periods
* Smoother revenue distribution across the year

---

### 5. Protect and Stabilize Profit Margins

**Insight:** Profit margins remained relatively stable around 28% but showed sensitivity during certain months.

**Recommendation:**

* Closely monitor cost drivers and discounting strategies during margin-sensitive periods
* Use high-margin categories to cushion margin fluctuations
* Introduce margin-based performance tracking at regional and pharmacy levels

**Business Impact:**

* Sustained margin performance despite sales volatility
* Greater visibility into profitability drivers at granular levels

---

## Overall Business Value

By combining geographic, product, and time-based insights, this Power BI solution enables stakeholders to:

* Make informed pricing and assortment decisions
* Focus investments on the most profitable stores and regions
* Balance revenue growth with margin sustainability
* Improve strategic planning through data-driven insights

---


---

## What I Would Do Next With More Data.

**Customer & Basket Insights**
• Analyse repeat customers and basket composition
• Identify cross-sell and upsell opportunities

**Pricing & Promotions**
• Measure promotional uplift and ROI by region
• Optimise discount levels to protect margins

**Operational & Cost Efficiency**
• Assess true store-level profitability
• Benchmark efficiency across store formats

**Inventory & Supply Chain**
• Analyse stock-outs, overstocking, and expiry risk
• Align inventory planning with seasonal demand

**Forecasting & Trend Analysis**
• Build demand forecasts at product and regional levels
• Improve planning for inventory and staffing

**Geographic & Market Insights**
• Link demographics and competition to performance
• Identify expansion and localisation opportunities

**Business Value:**
Supports smarter pricing, improved margins, operational efficiency, and scalable growth.

---


