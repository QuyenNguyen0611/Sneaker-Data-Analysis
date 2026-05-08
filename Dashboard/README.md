# Dashboard Development: Revenue & Inventory Efficiency

Two interactive dashboards were developed to provide the business with real-time visibility into sneaker sales performance and inventory efficiency. These dashboards are designed to support operational monitoring and strategic decision-making.

## 1. Revenue Performance Dashboard

**Purpose:**
Track overall sales performance and provide detailed breakdowns by key product and customer attributes.

**Key Features:**

- Total revenue and units sold with year-over-year (YoY) comparison.
- Monthly revenue trends highlighting highest and lowest performing months.
- Revenue breakdown by:
    * Gender (Men vs. Women)
    * Edition (Limited vs. Not Limited)
    * Price bucket (Low, Mid, High)
- Product type (e.g., Classic, Special Release)
    * Top-performing sneaker models with current and prior year revenue comparison.
    * Interactive filters for year, price bucket, edition, and type.

**Business Value:**

- Quickly identify best-selling products and underperforming segments.
- Detect seasonal patterns and high-revenue months.
- Enable targeted promotions based on product and customer segmentation.
  <img width="826" height="417" alt="Screenshot 2026-05-08 at 14 48 05" src="https://github.com/user-attachments/assets/24b9c9f4-d54d-45b7-acdc-ebddfb0991e7" />
<img width="835" height="419" alt="Screenshot 2026-05-08 at 14 47 59" src="https://github.com/user-attachments/assets/20f79e78-6619-445d-b0b0-95e235aab7ba" />


## 2. Inventory Efficiency Dashboard
**Purpose:** Monitor production, sales efficiency, damaged products, and overproduction risks to optimize inventory management.

**Key Features:**
- Total units produced, sold, unsold, and damaged with YoY comparison.
- Damaged rate visualization by product.
- Overproduction analysis highlighting models with excess inventory.
- Scatterplot of product hold duration versus damaged rate.
- Sold vs. Unsold vs. Damaged rate trend over time.
- Interactive filters by year, price bucket, edition, and type.

**Business Value:**
- Identify products contributing to high damage rates or overstock situations.
- Optimize stock levels to reduce waste and improve turnover.
- Support data-driven inventory planning to minimize financial losses.
<img width="835" height="419" alt="Screenshot 2026-05-08 at 14 47 59" src="https://github.com/user-attachments/assets/13c46e9e-d92c-4a4e-aeb7-6499c1e48bc3" />

## 3. Technical Implementation
- Dashboards built using an interactive BI tool (Tableau).
- Data processed and aggregated in Python for consistency with the forecasting model.
- Modular filter system for flexible analysis by product and customer attributes.

## 4. Conclusion
The dashboards provide actionable insights into both sales performance and operational efficiency. They complement the seasonality analysis and forecasting work by enabling continuous monitoring and proactive management of revenue and inventory performance.

