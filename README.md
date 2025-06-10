# AdventureWorks Power BI Dashboard

## 📘 Project Description
A Microsoft Power BI business intelligence dashboard designed for **AdventureWorks**, a fictional global manufacturing company that produces cycling equipment and accessories. This project explores the company’s performance across sales, returns, and customer trends from **01/01/2015 to 30/06/2017**, spanning 6 countries across 3 continents:
**Australia, Canada, France, Germany, United Kingdom, and the United States.**
A Microsoft Power BI business intelligence dashboard for AdventureWorks, a fictional global manufacturing company that produces cycling equipment and accessories.
This data was derived from the [AdventureWorks sample databases](https://drive.google.com/drive/folders/1evNA3oT4vTgGGTYEmuAqQFJc-sH_WRzr?usp=sharing) available from Microsoft. 

## ⭐ Features
* Interactive, multi-page Power BI dashboard.
* Sales, returns, and customer analysis with multiple visual types.
* Forecasting and what-if analysis.
* Row-Level Security (RLS) for user-specific views.
* Natural Language Query (NLQ) integration.
* Custom tooltips, slicers, and bookmarks for enhanced user experience.

## 🔍 Project Highlights
  This project involved the following tasks:
  * **Forecasting:** Projected revenue trends for the next 6 months with a 90% confidence interval.
  * **What-If Analysis:** Dynamic adjustment of product pricing and impact on revenue.
  * **Key Influencers:** Analyze how different factors affect order quantity.
  * **RLS:** Data restricted by user role to maintain confidentiality.
  * **Interactive Dashboard:** Filters, tooltips, and bookmarks enhance report navigation and insights.

## 📊 Dashboard Elements
 ### 🌍 Map View
  * **Revenue by Country** – Map visual
  * **Top 5 Customers by Revenue via NLQ** – Matrix filtered by region
 *  **Bookmark** – Highlights Europe’s 6-month World Cup duration

 ### 🛍️ Product Detail View
 * **Revenue by Product Category** – Donut chart
 * **Return Quantity & Return Rate by Product** – Matrix
 * **Product Revenue & YoY Growth** – Scroller chart
 * **Order Quantity by Sub-Category** – Clustered bar chart
 * **What-If Parameter** – Simulate % increase/decrease in product price
 * **Decomposition Tree** – Drill-down on Revenue by Category > Sub-Category > Product
   
 ### 👥 Customer Insights View
* **Top 5 Customers by Revenue** – Stacked bar chart
* **Top 5 Customers by Revenue (Matrix)**
* **Bottom 5 Customers by Revenue (Matrix)**
* **Key Influencers** – Analyze Order Quantity by Product Price and Country
  
 ### 📈 Performance & Trend View
 * YOY Revenue Growth – Line and stacked column chart
 * Monthly Revenue Forecast – Line chart with 90% confidence interval
 * Monthly Return Quantity, Orders & Returns – Area chart
 * KPI Cards:
   * Revenue vs Target Revenue
 
 ### Custom UI Elements
* Filter pane for filtering by year and geography
* Custom tooltip for product category order metrics

## Insights
* Approximately $24.9 million in revenue and $10.5 million in profit was generated between 01/01/2020 and 30/06/2022. There is an appreciable dip in revenue between 01/06/2020 and 01/11/2020 (possibly due to the simulated impact of the COVID-19 pandemic), after which revenue appears to grow linearly. December 2021 was an exceptional year in terms of revenue at $1.64 million, and it would be worth investigated the cause of this. Was this due to a highly successful seasonal campaign, e.g. a Black Friday promotion?
* Understandably, tires and tubes are the most ordered product type, while cycling shorts are the most returned product type. After mountain bike fenders, sports helmets top the list of revenue-generating products, despite having relatively high return rates:



