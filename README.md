# Superstore Sales Dashboard & 15-Day Forecast

Power BI project analyzing retail sales performance and forecasting short-term demand for a superstore chain.

## Objective
Turn raw order-level retail data into a decision-ready dashboard: identify which regions, categories, and channels drive revenue and profit, and forecast near-term sales volume to support inventory and staffing decisions.

## Tools
Power BI (data modeling, DAX, time-series forecasting)

## What's in the dashboard

**Overview page**
- Headline KPIs: 22K orders, $1.6M sales, $175K profit, 4 avg. ship days
- Sales by Region (donut): West 33%, East 29%, Central 22%, South 16%
- Sales by Payment Mode: COD 43%, Online 35%, Cards 22%
- Sales by Segment: Consumer 48%, Corporate 33%, Home Office 19%
- Sales & Profit by Month, filterable by year (2019 vs 2020)
- Sales by Ship Mode: Standard Class ($0.33M) far ahead of Second Class, First Class, and Same Day
- Sales by Category/Sub-Category: Technology, Furniture, and Office Supplies roughly even at the category level; Phones, Chairs, and Binders lead sub-categories
- Profit and Sales by State, plotted on a map (California, New York, and Texas are the top three states by sales)

**Forecast page**
- Daily total sales volume plotted from Jan 2019 to Jan 2021 to expose seasonality and spikes
- A 15-day forward forecast with confidence interval band, projecting a range that peaked near 10.6K and settled around 3.0K by the forecast horizon
- Sales-by-category breakdown reused alongside the forecast for context

## Key takeaways
- The West and East regions together account for roughly 62% of sales — a natural starting point for any region-targeted campaign
- Standard Class shipping dominates order volume, which matters for warehouse/logistics planning
- The daily sales series is highly volatile day-to-day but has a clear step-up in late 2020, which the forecast model had to account for rather than smoothing away

## Files
- `superstore_dashboard.pbix` — main dashboard
- Screenshots included in this folder
