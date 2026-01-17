# Customer Segmentation using RFM Analysis (Power BI)

## Project Overview
This project demonstrates customer segmentation using RFM (Recency, Frequency, Monetary) analysis.
The objective is to classify customers into meaningful segments and deliver actionable business insights through an interactive Power BI dashboard.

## Business Problem
Businesses often struggle to identify which customers generate the most value and which are at risk of churn.
This project helps stakeholders:
- Identify high-value customers (VIP / Champions)
- Detect at-risk and lost customers
- Design targeted retention and marketing strategies

## Dataset
- Each row represents a single customer
- Key features:
  - Recency: Days since last purchase
  - Frequency: Number of transactions
  - Monetary: Total spending value
  - Customer Segment: VIP / Champions, Loyal, At Risk, Lost, Potential Loyalists

## Tools & Technologies
- Python: Data cleaning, RFM feature engineering, and KMeans clustering
- Power BI: Data modeling, DAX measures, and interactive dashboard development

## Power BI Dashboard Highlights
- Total Customers and Total Revenue KPIs
- Customer distribution by segment
- Revenue contribution by segment
- Comparative RFM behavior across customer segments
- Interactive slicers for dynamic analysis

## Repository Structure
- `powerbi/Customer_Segmentation_RFM_Dashboard.pbix` : Power BI dashboard file
- `rfm_clustered_named.csv` : Final customer-level dataset used in Power BI

## Key Business Insights
- VIP / Champion customers generate a disproportionately high share of revenue
- Loyal and Potential Loyalists represent strong upsell and cross-sell opportunities
- At Risk and Lost customers highlight churn risk and reactivation potential

## How to Use This Project
1. Download the Power BI `.pbix` file
2. Open it using Power BI Desktop
3. Interact with the dashboard using slicers and filters to explore insights

