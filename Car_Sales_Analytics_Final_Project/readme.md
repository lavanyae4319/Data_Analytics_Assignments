# Car Sales Business Analytics Dashboard

## Project Overview

This project focuses on analysing car sales data using **Power BI**. The main purpose is to convert raw car sales data into an interactive dashboard that provides useful business insights.

The dashboard helps analyse vehicle sales, selling prices, market values, mileage, vehicle condition, vehicle makes, states, sellers, body types, transmission types, and sales trends.

## Problem Statement

A used-car business has a large amount of sales data containing vehicle and transaction details. Analysing this data manually can make it difficult to understand sales performance, pricing patterns, and vehicle trends.

This project uses **Power BI** to clean, transform, analyse, and visualize the car sales data. The final dashboard provides interactive KPIs and visualizations to support better business decisions.


## Objectives

* Analyse car sales data using Power BI.
* Clean and transform the dataset using Power Query.
* Prepare the data for analysis.
* Create DAX measures and KPIs.
* Analyse selling price and market value.
* Analyse sales by vehicle make and state.
* Compare sellers and vehicle categories.
* Analyse mileage and vehicle condition.
* Create an interactive Power BI dashboard.
* Generate useful business insights and recommendations.

## Tools and Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Power BI Service**
* **MySQL**
* **GitHub**

## Project Workflow

The project was completed through the following steps:

1. Collect the car sales dataset.
2. Connect the data source.
3. Clean and transform the data using Power Query.
4. Set appropriate data types.
5. Prepare the data model.
6. Create DAX measures.
7. Create KPI cards.
8. Design Power BI visualizations.
9. Add filters and slicers.
10. Analyse business questions.
11. Generate business insights.
12. Publish the report to Power BI Service.


## Data Cleaning

Power Query was used to prepare the dataset.

The main cleaning activities included:

* Checking column names.
* Checking data types.
* Converting numerical columns to appropriate numeric types.
* Converting `Sale Date` into Date/Time format.
* Checking missing and blank values.
* Handling unsuitable records.
* Preparing the dataset for visualization and analysis.

---

## DAX Measures

The following measures were created for the dashboard.

### Total Selling Price

```DAX
Total Selling Price = SUM(CarSales[sellingprice])
```

### Vehicles Sold

```DAX
Vehicles Sold = COUNTROWS(CarSales)
```

### Average Selling Price

```DAX
Average Selling Price = AVERAGE(CarSales[sellingprice])
```

### Average MMR

```DAX
Average MMR = AVERAGE(CarSales[mmr])
```

### Average Odometer

```DAX
Average Odometer = AVERAGE(CarSales[odometer])

## Dashboard Features

The Power BI dashboard includes:

* Total Selling Price KPI
* Number of Vehicles Sold KPI
* Average Selling Price KPI
* Average MMR KPI
* Average Mileage KPI
* Sales by Vehicle Make
* Sales by State
* Sales by Seller
* Sales by Body Type
* Transmission-wise Analysis
* Selling Price vs MMR
* Vehicle Condition Analysis
* Mileage Analysis
* Sales Trend Analysis
* Interactive Slicers

## Business Questions

The dashboard helps answer the following questions:

1. What is the total selling value of the vehicles?
2. How many vehicles were sold?
3. What is the average selling price?
4. Which vehicle makes have higher sales performance?
5. Which body types have higher sales?
6. How do automatic and manual vehicles compare?
7. Which states have higher sales activity?
8. Which sellers have better sales performance?
9. How does mileage relate to selling price?
10. How does selling price compare with MMR?

## Business Insights

The dashboard helps identify:

* Sales performance of different vehicle makes.
* Price differences between vehicle categories.
* Differences between selling price and MMR.
* The relationship between mileage and selling price.
* The effect of vehicle condition on pricing.
* State-wise sales performance.
* Seller-wise sales performance.
* Demand patterns based on body type and transmission.
* Sales trends over time.

## Business Recommendations

* Consider MMR, mileage, and condition when evaluating vehicle prices.
* Monitor high-performing vehicle makes and models.
* Compare state-wise sales performance.
* Track seller performance regularly.
* Use the dashboard for regular sales monitoring.
* Compare selling prices with market values before pricing vehicles.
* Focus on vehicle categories with strong sales performance.
* Use data-based insights for inventory and pricing decisions.

## Power BI Service

The completed Power BI report can be published to **Power BI Service**.

The deployment process includes:

1. Publish the Power BI report.
2. Select the required workspace.
3. Open the published report.
4. Check the semantic model/dataset.
5. Configure data-source credentials if required.
6. Configure refresh settings.
7. Run a manual refresh.
8. Check refresh history.
9. Verify that the latest data is available.

---

## Project Output

The final output is an interactive **Car Sales Business Analytics Dashboard** developed using Power BI.

The dashboard provides a consolidated view of car sales performance and allows users to explore the data using different filters and visualizations.

### Dashboard
### Power BI Service
### Refresh History

## Learning Outcomes

Through this project, I learned:

* How to work with real-world business data.
* How to clean and transform data using Power Query.
* How to create data models in Power BI.
* How to create DAX measures and KPIs.
* How to design interactive dashboards.
* How to create useful data visualizations.
* How to analyse business data.
* How to identify business insights.
* How to make data-based recommendations.
* How to publish and refresh reports using Power BI Service.
* How to prepare a business analytics project report.

## Conclusion

This project demonstrates an end-to-end business analytics workflow using Power BI. The car sales dataset was cleaned, transformed, analysed, and visualized to create an interactive dashboard.

The dashboard helps users understand sales performance, pricing, vehicle characteristics, seller performance, and regional trends. The project demonstrates practical skills in **Power Query, DAX, data visualization, Power BI, business analysis, and reporting**.


## Author

**Name:** Lavanya E

**Project:** Car Sales Business Analytics Dashboard


Add the final GitHub repository link below:

**GitHub:** `[Add your GitHub Repository Link Here]`
