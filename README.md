# Airbnb NYC Real Estate Data Pipeline & Analysis

## 📊 Project Overview

This project demonstrates a complete end-to-end real estate data pipeline and analysis using PySpark, SparkSQL, and Power BI. The dataset is sourced from Airbnb NYC listings (2024), and covers data engineering, data cleaning, transformations, and market analysis for rental pricing trends.

---

## 🛠️ Tools & Technologies

- Python
- PySpark (SparkSQL)
- JupyterNotebook
- Hadoop (winutils for Windows Spark support)
- Power BI (for final visualization)

---

## 🔄 ETL Pipeline Steps

1️⃣ **Ingestion**  
- Load raw Airbnb CSV data.

2️⃣ **Data Cleaning**  
- Clean price columns (remove "$" and ",").
- Convert date columns to proper formats.
- Handle null values.

3️⃣ **Data Transformation**  
- Add derived fields like `price_per_night`.
- Prepare dataset for analysis.

4️⃣ **Storage**  
- Save processed data into optimized Parquet format.

---

## 🔎 Exploratory Data Analysis

- Total Listings
- Average Pricing
- Listings by Room Type
- Price Buckets Distribution
- Top Neighborhoods by Pricing
- Review vs Price Correlation

---

## 📈 Dashboard Design (Power BI)

- Price Heatmap by Neighborhood
- Price Distribution by Room Type
- Top Expensive Neighborhoods
- Reviews vs Pricing Scatterplot
- Overall Rental Market Trends

---

