# 👟 Adidas Sales Dashboard

An interactive Power BI dashboard analyzing **Adidas sales performance** across Egyptian cities, product categories, and time — built to track revenue trends, discounting impact, and regional demand at a glance.

## 🧭 Overview

This dashboard turns raw sales transaction data into an executive-ready view of Adidas's performance. It highlights gross vs. net sales, discount impact, and how revenue shifts across cities, categories, and months — supporting quick decisions on inventory, promotions, and regional focus.

## ✨ Key Features

- **Top-line KPI cards**: Gross Sales, Discount Value, Net Sales, and Units Sold
- **Year and Category filters** to slice the entire report by time period or product type
- **Geographic sales map** showing Net Sales by city (bubble size = relative sales volume)
- **Category breakdown** highlighting net sales per product category
- **Sankey/alluvial flow chart** showing how Net Sales shift across cities year-over-year (2016–2018)
- **Monthly sales trend line** tracking Net Sales fluctuations throughout the year

## 📊 KPIs Tracked

| Metric | Description |
|---|---|
| Gross Sales | Total sales value before discounts |
| Discount Value | Total value deducted via discounts/promotions |
| Net Sales | Gross Sales minus Discount Value (actual realized revenue) |
| Quantity | Total units sold |

## 🔍 Visualizations

- **Net_Sales by City** — geo bubble map across Egyptian cities (Alexandria, Cairo, Giza, Ismailia, Luxor, Port Said, Sharm El Sheikh)
- **Net_Sales by Category** — bar visual isolating performance of the selected product category (e.g., Accessories)
- **Net_Sales by Year and City** — flow diagram tracking how each city's contribution to net sales evolves from 2016 to 2018
- **Net_Sales by Month** — line chart of monthly net sales with value labels, revealing seasonal dips (e.g., February) and peaks (e.g., July)

## 🎛️ Filters & Interactivity

- **Year** dropdown (default: All)
- **Category** dropdown (e.g., Accessories)
- All visuals update dynamically based on the selected year/category combination

## 🛠️ Tech Stack

- **Power BI** — dashboard design, data modeling, and DAX measures
- **Data source**: Adidas retail sales transaction data (city, category, date, gross/net sales, discounts, quantity)

## 🚀 Getting Started

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Connect/refresh the data source with updated sales data
4. Use the Year and Category filters to explore performance by segment

## 💡 Insights Enabled

- Identify which **cities** drive the most net sales and how that ranking shifts year over year
- Spot **seasonal trends** in monthly sales (e.g., post-holiday dips, summer peaks)
- Quantify the **impact of discounting** on overall revenue
- Compare performance across **product categories** to guide merchandising decisions

## 📌 Notes

- Replace sample data with the latest sales export to keep KPIs current
- Map bubble sizes are relative — refer to underlying values for exact comparisons
- "Adidas" branding/imagery used here is for illustrative dashboard design purposes only

---

*Built with Power BI to turn Adidas sales data into actionable retail insights.*
