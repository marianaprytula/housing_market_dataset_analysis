# Housing Dataset Analysis

This project presents a Power BI dashboard that analyzes the Housing dataset from the Udemy course. 
---

## Project Overview

- **Goal**: Analyze the T-shirt Brands dataset using visual dashboards.
- **Tools Used**:
  - Microsoft Power BI 
  - Google BigQuery
  - DAX

---

## Data Source

- The data is loaded to Google BigQuery from csv file.

---

## Data cleaning

-  **Choosing the correct types for columns in Power BI**
-  **Handling NULL values** (using the most occurring value in columns)

---

## Adding Table with the following measures:

-  Average Price for Square meter
-  Last 12 months Sales
-  Latest year Sales Growth
-  Median Sales Price Change
-  Offer to Square meter Ratio
-  TotalYTD Sales
-  Units Sold in latest Year & Quarter


---

## Visuals for the following cases:

-  Latest Year Sales Growth by sales_type
-  Purchase price vs Offer Price scatter plot 
-  Cards visuals for Last 12 months Sales and Latest year&quarter Sales Growth
-  Stacked Column Chart for Median Sales Price percentage Change by Year
-  Table with TotalYTD Sales
-  Key influencers visual (analyzing Purchase Price by Age
-  Donut chart with Average Price of Square meter by Region
-  Offer to SQM Ratio by sales_type Stacked Column Chart
-  Stacked Column Chart for displaying Sales by Region
-  Adding slicers for area and city
  -  Average of Offer Price and Average of purchase_price by house type (stacked bar chart)
  -  Average of Interest, Average of Inflation, and Average of Yield by house type (stacked bar chart)
  -  Average Price SQM and Sum of sqm price by house type (line & stacked bar chart)


---


## ⚙️ Setup Instructions

### Clone this Repository
```bash
git clone https://github.com/marianaprytula/housing_market_dataset_analysis.git

Create Google Cloud account and Load data to Google BigQuery using csv file.

Connect to Google BigQuery ('Get data from' functionality in Power BI)
