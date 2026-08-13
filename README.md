# Porter Delivery Analysis

## Project Overview

This project analyzes delivery performance and operational patterns using **Microsoft Excel**. The analysis covers 197,428 orders and focuses on delivery times, order volumes, market performance, store performance, delivery partner capacity, order protocols, and order value patterns.

The objective is to identify operational bottlenecks, understand demand patterns, and generate insights that can support delivery performance and resource planning.

## Objectives

* Analyze order volumes across markets, days, and hours
* Measure and analyze delivery time performance
* Identify peak demand periods
* Evaluate delivery partner capacity during high-demand periods
* Compare delivery performance across markets, stores, categories, and order protocols
* Analyze relationships between order characteristics and order value
* Build an Excel dashboard for operational reporting

## Tools & Skills

* Microsoft Excel
* Pivot Tables
* Excel Formulas
* Data Cleaning & Analysis
* KPI Analysis
* Descriptive Analysis
* Correlation Analysis
* Data Segmentation
* Operational Performance Analysis
* Dashboard Development

## Dataset

The dataset contains **197,428 order records** covering the period from **October 2014 to February 2015**.

Key fields include:

* Market ID
* Order creation time
* Actual delivery time
* Store ID
* Store primary category
* Order protocol
* Total items
* Distinct items
* Order subtotal
* Delivery partner information
* Delivery time metrics

## Analysis Performed

### Order Volume Analysis

* Order distribution across different markets
* Peak order-placement hours
* Order volumes by day of the week
* Store-level order volumes

### Delivery Performance Analysis

* Average delivery time
* Delivery-time distribution
* Delivery-time outlier analysis
* Percentage of orders delivered within 30 minutes
* Delivery performance by day
* Delivery performance across markets and categories

### Operational Analysis

* Efficiency of different order protocols
* Relationship between order volume and busy delivery partners
* Relationship between on-shift partners and delivery time
* Delivery partner availability across markets
* Identification of stores with longer average delivery times

### Order Value Analysis

* Relationship between total items and order subtotal
* Average order value by market
* Impact of item price range on order value
* Store category and above-average order value analysis

## Key Metrics

* **Total Orders:** 197,428
* **Average Delivery Time:** 47.53 minutes
* **Orders Delivered Within 30 Minutes:** 25,933
* **30-Minute Delivery Rate:** 13.15%
* **Peak Order Hour:** 2 AM
* **Orders During Peak Hour:** 36,976
* **Busiest Day:** Saturday
* **Saturday Orders:** 34,541

## Key Insights

* **Market 2** recorded the highest order volume with **55,058 orders**, representing approximately **27.89%** of total orders.
* **2 AM** was the peak order-placement hour with **36,976 orders**, showing a strong concentration of late-night demand.
* **Saturday** was the busiest day with **34,541 orders**, followed by Sunday with **33,620 orders**.
* Only **13.15%** of valid delivered orders were completed within 30 minutes, indicating significant room for improving delivery speed.
* Order volume and busy delivery partners showed a very strong positive correlation of **0.958**, indicating that partner activity closely follows demand.
* **Monday** had the highest average delivery time at approximately **51.32 minutes**, while **Wednesday** had the lowest at approximately **44.06 minutes**.
* The median delivery time was approximately **44.33 minutes**. The analysis identified **6,278 statistical outliers**, which should be investigated for potential operational or data-quality issues.

## Business Recommendations

* Increase delivery partner capacity during peak demand periods.
* Investigate the operational reasons behind higher delivery times on Mondays.
* Review stores and markets with consistently high delivery times.
* Identify operational bottlenecks affecting the low 30-minute delivery rate.
* Use historical demand patterns to improve delivery partner scheduling.

## Limitations

* The dataset does not contain a customer identifier, so reliable first-time versus repeat-customer analysis cannot be performed.
* Some delivery-time records contain extreme values and require careful interpretation.
* The dataset covers a limited historical period, so the findings should not be treated as current operational performance.
* Correlation indicates association and does not establish causation.

## Project Structure

```text
Porter-Delivery-Analysis/
│
├── README.md
├── Porter_Delivery_Analysis.xlsx
└── screenshots/
    └── dashboard.png
```

## Conclusion

This project demonstrates how Microsoft Excel can be used to analyze large-scale delivery operations, identify demand and capacity patterns, evaluate delivery performance, and convert operational data into actionable business insights.

## Author

**Ishan Keshre**

Business Analyst | Data Analytics | SQL | Power BI | Excel
