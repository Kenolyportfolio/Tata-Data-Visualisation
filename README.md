# Tata-Data-Visualisation – Power BI Project

## Overview

This project presents a full end–to–end analysis of an online retail dataset with the goal of supporting strategic decisions for the CEO and CMO.
The analysis covers revenue trends, international performance, customer value, and market demand. All insights were developed using cleaned and validated data to ensure accuracy.

This repository includes:
- Data cleaning workflow
- DAX measures
- Four Power BI pages aligned with executive questions
- Business insights for forecasting, marketing and expansion


## 📁 Dataset
The dataset contains transactional records from an online retail store, including:
Invoice Number, Invoice Date, Stock Code, Description, Quantity, Unit Price, Customer ID, Country

## Cleaning Rules Applied
Two data quality checks were implemented before analysis:
1. Quantity Check: Any quantity below 1 was removed (negative quantities represent returns).
2. Unit Price Check: Any unit price below 0 was excluded as incorrect entries.

New Columns Created
Revenue = Quantity × Unit Price
Year and Month extracted from Invoice Date
Sorting column for Month to ensure correct chronological order

## 🛠 Tools & Technologies
Power BI – data cleaning, modelling, visuals
Power Query – data transformation rules
DAX – KPIs and calculated measures
Excel (original dataset)

## 📌 Executive Questions & Visuals
1️⃣ Monthly Revenue Trend for 2011 (CEO)
Goal: Identify seasonal patterns to support yearly forecasting
Visual:https://github.com/Kenolyportfolio/Tata-Data-Visualisation/blob/main/Time%20series%20of%20Monthly%20Revenue%20For%202011%20only.JPG

Key Insight: Revenue climbs through the year and peaks in November.

2️⃣ Top 10 Countries by Revenue (Excluding UK) – CMO
Goal: Understand strongest international markets
Visual:https://github.com/Kenolyportfolio/Tata-Data-Visualisation/blob/main/Top%2010%20Countries%20By%20Revenue%20And%20Quantity%20Sold.JPG

Key Insight: Germany, Netherlands and France represent the strongest non-UK markets.

3️⃣ Top 10 Customers by Revenue – CMO
Goal: Identify VIP customers for retention strategies
Visual: https://github.com/Kenolyportfolio/Tata-Data-Visualisation/blob/main/Top%2010%20Customers%20By%20Revenue.JPG

Key Insight: A small customer group contributes a large share of sales.

4️⃣ Demand by Country (Excluding UK) – CEO
Goal: Identify expansion opportunities
Visual:(https://github.com/Kenolyportfolio/Tata-Data-Visualisation/blob/main/Product%20Demand%20By%20Country.JPG)

Key Insight: Central European countries show strong demand and strong expansion potential.

## 💼 Business Impact

This analysis provides leadership with:

Reliable revenue trends for forecasting

Clear visibility into strong international markets

Prioritised customer segments for marketing

Data-driven expansion insights based on real demand


It demonstrates a full analytics workflow: cleaning, modeling, analysis and executive communication.
