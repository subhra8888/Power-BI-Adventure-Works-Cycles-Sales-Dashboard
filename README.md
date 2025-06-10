# Adventure Works
A Microsoft Power BI business intelligence dashboard for AdventureWorks, a fictional global manufacturing company that produces cycling equipment and accessories.
This data was derived from the [AdventureWorks sample databases](https://drive.google.com/drive/folders/1evNA3oT4vTgGGTYEmuAqQFJc-sH_WRzr?usp=sharing) available from Microsoft. 
![Final Report](https://github.com/subhra8888/Power-BI-Adventure-Works-Cycles-Sales-Dashboard/blob/master/Final%20Report%20View.png)


The customer base is spread across 6 countries on 3 continents: Australia, Canada, France, Germany, United Kingdom and United States. Sales and return data is available for the period between 01/01/2020 and 30/06/2022. Customer profiles include date of birth, annual income, education level, number of children, occupation and homeowner status.

## Features
* Track key performance indicators (KPIs) related to sales, revenue, profit, and returns.
* Compare performance across different regions.
* Analyse product-level trends.
* Identify high-value customers.

## Project Highlights
  This project involved the following tasks:
  * Connecting and transforming the raw data
  * Building a relational data model
  * Creating calculated columns and measures using DAX
  * Created a rolling calendar using PowerQuery M code
  * Building an interactive dashboard

## Dashboard Elements
 ### Executive Summary View
  * High-level KPIs for revenue, profit, orders and return rates
  * Page-level filtering by product and product category
 *  Drill-through per product to product detail view

 ### Map View
 * Total orders per country
 ### Product Detail View
* Per-product performance against order, revenue and profit targets
* "What if" analysis via price adjustment shows adjusted profit
 ### Customer Detail View
 * Total customer and per-customer revenue analysis
 ### Custom UI Elements
* Filter pane for filtering by year and geography
* Custom tooltip for product category order metrics

## Insights
* Approximately $24.9 million in revenue and $10.5 million in profit was generated between 01/01/2020 and 30/06/2022. There is an appreciable dip in revenue between 01/06/2020 and 01/11/2020 (possibly due to the simulated impact of the COVID-19 pandemic), after which revenue appears to grow linearly. December 2021 was an exceptional year in terms of revenue at $1.64 million, and it would be worth investigated the cause of this. Was this due to a highly successful seasonal campaign, e.g. a Black Friday promotion?
* Understandably, tires and tubes are the most ordered product type, while cycling shorts are the most returned product type. After mountain bike fenders, sports helmets top the list of revenue-generating products, despite having relatively high return rates:



