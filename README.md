# Business Performance Dashboard — Customer & Product Analytics

A multi-page Power BI dashboard built to explore customer retention failure and product revenue concentration risk across a retail business, enabling data-driven decisions on where to invest and what to retain.

## Technologies Used

The following technologies and tools were used to build this project:

- 🗄️ MS SQL Server – Used for database storage and SQL querying
- 🔄 Power Query – Used for dashboard creation and visualization
- 📊 Power BI Desktop – Used for data cleaning, transformation, and preprocessing
- 📈 DAX (Data Analysis Expressions) – Used for creating calculated columns, measures, KPIs, and business metrics
- 📁 .pbix File Format – Used for storing and sharing the Power BI project file


## Data Source

The dataset used in this project was obtained from a YouTube tutorial/project.

**Dataset Link:**
[(https://academy.datawithbaraa.com/l/digital_download/930511/sql-course-materials)](https://academy.datawithbaraa.com/l/digital_download/930511/sql-course-materials)

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

Project by - Janice John

