# Shopify Stock – Financial Analytics Dashboard

## 📊 Project Overview
The **Shopify Stock Financial Analytics Dashboard** is an interactive Power BI project designed to analyze Shopify stock price trends and financial performance over time. It uses historical stock market data, DAX measures, and interactive filters to present key insights through a visual dashboard.

## 🎯 Objectives
- Analyze Shopify's historical stock closing prices.
- Compare stock performance with the previous year.
- Track year-to-date closing price metrics.
- Calculate average closing prices.
- Explore stock trends using date and month filters.

## 🛠️ Tools & Technologies
- **Power BI Desktop** – Dashboard development and visualization
- **Power Query** – Data transformation
- **DAX (Data Analysis Expressions)** – Financial calculations
- **Data Modeling** – Relationships between the stock data and Date table

## 📁 Dataset
The dataset contains historical Shopify stock market information, including:
- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

## 📈 Key Performance Indicators (KPIs)
The dashboard includes four KPI cards:
- **Latest Close** – Displays the latest closing price metric.
- **Close LY** – Shows the previous-year closing price metric.
- **Close YTD** – Displays the year-to-date closing price metric.
- **Average Close** – Shows the average closing price.

## 📊 Dashboard Visualizations
1. **Stock Price Trend:** Visualizes stock price trends over time.
2. **Monthly Average Close:** Displays average closing price metrics by month.
3. **Stock Price Details:** Presents date-wise closing price and previous-year comparison.
4. **Year Slicer:** Filters data by year.
5. **Month Slicer:** Enables month-based filtering and exploration.

## 🧮 DAX Measures
The project includes measures for:
- Average Close
- Close LY (Last Year)
- Close Previous Month
- Close YTD (Year to Date)
- Latest Close

These measures support time-based financial analysis using the Date table.

## 🔗 Data Model
The data model contains three tables:
- **shopify_stock:** Historical stock market data.
- **Date:** Calendar table containing date, day of week, month, month name, and year.
- **Measure:** A dedicated table for organizing DAX measures.

A relationship connects the stock data with the Date table to support date-based analysis.

## 💡 Key Learnings
- Building interactive dashboards in Power BI.
- Creating and organizing DAX measures.
- Working with calendar tables and date relationships.
- Applying time-intelligence concepts.
- Designing KPI cards, line charts, tables, and slicers.
- Presenting financial data through interactive visualizations.

## 👨‍💻 Author
**Samrabinson P**

BCA Student | Aspiring Data Analyst & Full Stack Developer

---
