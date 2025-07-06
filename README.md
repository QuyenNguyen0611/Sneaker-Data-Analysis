# Sneaker Sales Data Analysis & Forecasting Report
## Project Overview
This project aims to support business decision-making for sneaker sales by:
- Analyzing seasonality patterns in sneaker sales data.
- Building a forecast model to predict sales/revenue for the next year.
- Proposing a dashboard framework to monitor revenue and inventory efficiency.

## 1. Dataset Summary
Source: [Kaggle](https://www.kaggle.com/datasets/comhek/500-snickers-dataset)

**Key Variables:**
- `name`: Name of the sneaker model.
- `type`: One of the seven types: Creamy, Peanut Butter, Brownie, Classic, Almond, White Chocolate, Crisper.
- `total_product`: Total number of units produced.
- `total_sold`: Total number of units sold.
- `damaged`: Number of units damaged.
- `edition`: Name of the edition.
- `price`: Selling price of the sneaker.
- `gender`: Gender category of the target customer.
- `sell_through_rate`: Percentage of units sold relative to total units produced.
- `damaged_rate`: Percentage of damaged units relative to total units produced.
- `unsold_inventory`: Percentage of unsold units relative to total units produced.
- `estimated_revenue`: Estimated revenue generated from a specific sneaker model.
- `is_limited_edition`: Indicator whether the sneaker is a limited edition (1 = Yes, 0 = No).
- `price_buck`: Price category of the sneaker (High, Mid, or Low).
- `manufacturing_date`: Date when the sneaker was manufactured.
- `selling_date`: Date when the sneaker was sold.

**Note:** The following fields were considered redundant and removed:
- `month`, `year`, and `quarter`: All derivable from manufacturing_date.
- `date`: Duplicate of manufacturing_date.

## 2. Methodology
The project followed a structured time series approach to analyze seasonality patterns and forecast sneaker sales:

- Data Preparation

* Cleaned and transformed historical sneaker sales data (2015–2024).

* Created new metrics such as damaged rate, sold rate, and unsold rate for deeper insight.

* Aggregated revenue at monthly and yearly levels for time series analysis.

- Seasonality Analysis

* Applied time series decomposition to extract trend, seasonal, and residual components.

* Visualized monthly seasonal impact to identify consistently high and low sales months.

* Confirmed a clear, recurring 12-month seasonal pattern in the data.

- Forecast Modeling

* Used auto_arima to select the optimal SARIMA model based on AIC criteria.

* Fitted the SARIMA model to historical monthly revenue data.

* Generated a 12-month revenue forecast with confidence intervals to account for uncertainty.

- Visualization: Created interactive charts using Plotly to clearly present seasonal patterns and forecast results.

## 4. Dashboard Proposal: Revenue & Inventory Efficiency
**Objective:** Provide business stakeholders with interactive, real-time visibility into sneaker sales performance and inventory efficiency, enabling timely, data-driven decisions.

**Tool:** Tableau

## 5. Conclusion
This project confirms the existence of strong seasonality in sneaker sales and provides a robust sales forecast for the next year. A dashboard framework is proposed to equip the business with real-time visibility into revenue trends and inventory efficiency, enabling more proactive and data-driven decisions.

