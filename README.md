# Business Performance Dashboard — Customer & Product Analytics

A multi-page Power BI dashboard built to explore customer retention failure and product revenue concentration risk across a retail business, enabling data-driven decisions on where to invest and what to retain.

## Technologies Used

| Tool | Purpose |
|---|---|
| **MS SQL Server** | Data storage and querying |
| **Power BI Desktop** | Dashboard development and visualisation |
| **Power Query** | Data cleaning, transformation and shaping |
| **DAX (Data Analysis Expressions)** | Calculated columns, measures and KPIs |
| **File Format** | `.pbix` (Power BI Desktop file) |

## Data Source

The dataset used in this project was sourced from a **YouTube tutorial video** focused on business analytics and Power BI dashboard development. It contains customer-level and product-level transactional data across a 4-year period (2010–2014), including customer orders, sales, lifespan, recency, product categories, subcategories, costs and revenue metrics.

## Features and Highlights

Business Problem

The business was experiencing a sharp and unexplained decline in customer growth post-2013, despite a massive acquisition spike that made performance appear strong on the surface. Leadership had no visibility into whether the issue was rooted in acquisition, retention or product performance and which specific customer segments and product categories were driving the revenue collapse.

Simultaneously, the commercial team was seeing inconsistent profit contributions across product categories but could not identify which subcategories were actually worth investing in. Bikes appeared to be the star performer by revenue, but the underlying margin data told a completely different story that was invisible without deeper analysis.

This dashboard was built to surface both problems simultaneously i.e. giving leadership a single view of customer lifecycle health alongside product profitability reality.

## Goal

- Identify **why customer growth collapsed** after 2013 despite strong acquisition numbers
- Determine **which customer segments** are churning, at what rate and at what revenue cost
- Uncover **which products and subcategories** are truly profitable vs which are revenue-heavy but margin-poor
- Provide **actionable strategic recommendations** on where to focus retention investment and product diversification effort

## Key Visuals Walkthrough

### Page 1 — Customer Growth & Acquisition Analysis
- **5 KPI Cards** — Total Sales, Customers, Avg Lifespan, Avg Order Value, Avg Monthly Revenue
- **Phase-annotated Area + Line Chart** — Total, New, VIP and Regular customers from 2010–2014 divided into Starting Point, Stabilization, Growth and Decline phases
- **Insight** — New customers perfectly overlap Total Customers throughout, confirming VIP and Regular segments never grew — the business ran entirely on acquisition

### Page 2 — Customer Behaviour & Retention Analysis
- **4 KPI Cards** — Churn Rate, Retention Rate, At Risk Rate, Repeat Purchase Rate
- **Churn Rate by Customer Category** — New (49.1%), VIP (44.3%), Regular (31.6%) with Female/Male gender split
- **Revenue % by Customer Category** — near-equal revenue distribution across New, VIP and Regular
- **AOV by Churn Status** — Churned customers (1,203) outspend Active customers (989) — the business is losing its highest-value segment
- **Avg Lifespan by Customer Category** — VIP 21.8 months vs New 1.2 months
- **Revenue by Customer Segment** — At Risk segment holds ~28M in revenue, Lost contributes negligibly

### Page 3 — Product Performance & Profitability Analysis
- **5 KPI Cards** — Orders, Quantity, Top Product, Profit Margin %, Avg Monthly Revenue
- **Revenue Growth by Year** — 55.6% → 8.2% → -70.6% showing sharp and consistent decline
- **Profit by Category** — Bikes 11.1M vs Accessories 0.4M vs Clothing 0.1M
- **Top 5 Subcategory by Profit Margin** — Tires & Tubes and Helmets lead at 62.9% while Road Bikes sits at 36.5%
- **Top 5 Subcategory by Avg Selling Price** — Mountain Bikes at 1,753 confirms premium positioning
- **Lowest 3 Products by Orders** — all three are Bike variants, contradicting the business's over-investment in Bikes
- **Total Customers by Subcategory** — Tires & Tubes leads with 16,583 customers

### Page 4 — Product Revenue & Subcategory Deep Dive
- **Pareto Chart** — Road Bikes at 49.5% of total revenue, top 3 subcategories drive 96.5% combined
- **Orders by Performance Category** — Bikes exclusively in High Performer, Clothing confined to Low Performer
- **Top 5 Subcategory by Avg Change in Sales** — Road Bikes leads sales momentum
- **Bookmark Navigator** — toggles between summary bar chart and detailed matrix with Orders, Revenue, Cost, Growth Rate % and Profit Margin % per subcategory with conditional formatting

---

## Impact and Insights

### Customer Insights
- **46.5% churn rate** — nearly half the customer base is lost, driven primarily by One-time New customers with a lifespan under 6 months
- **AOV Paradox** — churned customers (AOV 1,203) spend significantly more per order than active customers (989), confirming the business is losing its highest-value segment first
- **VIP Retention Crisis** — VIP customers churn at 44.3% despite having the longest lifespan of 21.8 months, indicating no loyalty infrastructure exists to reward longevity
- **28M Revenue at Risk** — At Risk customers hold ~28M in revenue, representing the single highest-ROI retention intervention opportunity
- **Conversion Funnel Broken** — Regular customers have the lowest churn rate (31.6%) yet the segment remains small, confirming the New → Regular → VIP journey is failing at the onboarding stage
- **Gender Parity** — Female and Male customers behave almost identically across all metrics, confirming gender-based segmentation will not solve the retention problem

### Product Insights
- **Revenue collapsed -70.6% in 2013** — the business growth model is unsustainable and weakening
- **96.5% of revenue from 3 subcategories** — extreme concentration risk; if Road Bikes demand drops the entire business is vulnerable
- **High Revenue ≠ High Margin** — Road Bikes generates 49.5% of revenue but carries only 36.5% profit margin, while Tires & Tubes serves 16,583 customers at 62.9% margin
- **Accessories are critically underleveraged** — high margin, high customer base, low manufacturing cost and strong repeat purchase potential — the most scalable profit opportunity in the portfolio
- **Lowest performing products are all Bikes** — Mountain-500 and Mountain-100 variants with 36–41 orders each, contradicting the business's strategic over-investment in the Bikes category
- **Strategic Recommendation** — reduce dependency on premium low-margin Bikes, invest in high-margin accessory subcategories (Tires & Tubes, Helmets, Bottles & Cages) and build a customer retention infrastructure to convert New customers into Regular and VIP segments

---

*Built with Power BI Desktop | Data sourced from YouTube tutorial dataset | Project by [Your Name]*

