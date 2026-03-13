# Deep Dive Business Analysis & Interactive Dashboard

## Project Overview

This project performs deep-dive analysis on an ecommerce dataset to extract business insights and build visual analytics. The analysis focuses on key performance indicators (KPIs), customer behavior, and revenue patterns.

## Dataset

The dataset used in this project contains ecommerce transaction records including customer purchases, product categories, payment methods, and revenue.

Main fields in the dataset:

* order_id
* customer_id
* product_id
* category
* quantity
* price
* order_date
* country
* payment_method
* revenue

## Key Analysis Performed

### KPI Metrics

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value

### Revenue Analysis

* Monthly revenue trends
* Country-wise revenue distribution
* Category-wise revenue

### Cohort Analysis

Customer retention analysis based on first purchase month.

### Customer Segmentation

Customer segmentation using **RFM analysis** and **K-Means clustering**.

RFM Features:

* Recency
* Frequency
* Monetary

### Funnel Analysis

Simulated customer funnel showing:

* Visitors
* Product Views
* Add to Cart
* Purchases

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn
* Google Colab

## Project Structure

```
task3-deep-dive-analysis
│
├── data
│   └── ecommerce_business_dataset.csv
│
├── notebook
│   └── task3_analysis.ipynb
│
├── outputs
│   ├── customer_segments.csv
│   └── monthly_revenue.csv
│
├── requirements.txt
└── README.md
```

## How to Run the Project

1. Install dependencies

```
pip install -r requirements.txt
```

2. Open the notebook

```
task3_analysis.ipynb
```

3. Run all cells to generate analysis and outputs.

## Outputs Generated

* customer_segments.csv
* monthly_revenue.csv
* Visualization charts
* Cohort analysis heatmap
* Customer segmentation clusters

## Author

Business Data Analysis Project
