# Customer Segmentation using RFM Analysis

## Overview
This project segments customers of an online retail business into actionable 
groups based on their purchasing behavior, using the **RFM (Recency, Frequency, 
Monetary) model** — one of the most widely used techniques in customer 
segmentation and marketing analytics.

The analysis was built on the **Online Retail Dataset**, which includes 
transactional data from a UK-based online retailer selling to both individual 
consumers and wholesale buyers.

## What is RFM?
- **Recency** — How recently did the customer make a purchase?
- **Frequency** — How often does the customer purchase?
- **Monetary** — How much does the customer spend?

Each dimension is scored from 1 to 5, and customers are grouped into segments 
such as Champions, Loyal Customers, Promising/New, At Risk, and Lost Customers.

## Process
1. Data cleaning (handling missing values, removing invalid transactions)
2. Outlier detection and business context (identifying wholesale buyers)
3. Building the RFM table per customer
4. Scoring each dimension (1–5) using rank-based quantile binning
5. Segmenting customers based on R and F scores
6. Analyzing revenue concentration (Pareto principle)
7. Visualizing segment distribution and revenue share

## Key Insight
**Champions represent 25.8% of customers but generate 65.9% of total revenue**
