# Retail Store Sales Analysis – Power BI Project

This Power BI project analyzes the sales performance of an online retail store using real-world data. The dashboard and visuals were created in response to specific business questions posed by the CEO and CMO.

## Objectives

This report addresses the following key questions:

### Q1: Monthly Revenue Trend (2011 Only)

- **Requested by**: CEO  
- **Purpose**: To identify seasonal trends and revenue patterns for forecasting future performance.
- **Visual**: Line chart showing **monthly revenue** for the year **2011 only**.

### Q2: Top 10 Countries by Revenue (Excluding UK)

- **Requested by**: CMO  
- **Purpose**: To identify top-performing countries (excluding the UK) in terms of both revenue and quantity sold.
- **Visual**: Bar chart showing **top 10 countries** with revenue and quantity metrics.

---

### Q3: Top 10 Customers by Revenue

- **Requested by**: CMO  
- **Purpose**: To identify and retain high-value customers.
- **Visual**: Sorted bar chart with **customer IDs** ranked by total revenue.

---

### Q4: Product Demand by Country (Excluding UK)

- **Requested by**: CEO  
- **Purpose**: To determine demand hotspots for international expansion.
- **Visual**: Filled map or bar chart showing **total quantity sold by country**, excluding the United Kingdom.

---

##  Data Cleaning Steps

To ensure the quality of insights, the dataset was cleaned using Power BI’s Power Query Editor:

1. **Removed returned items** (Quantity < 1).
2. **Removed pricing errors** (UnitPrice < 0).
3. Created a custom **Revenue column** = `Quantity * UnitPrice`.

---

##  File

- `RetailSalesAnalysis.pbix`: Power BI file with four separate tabs (`Q1`, `Q2`, `Q3`, `Q4`) for each business question.

---

## How to View

1. Download Power BI Desktop (free from Microsoft).
2. Open the `.pbix` file to explore interactive dashboards and visuals.

---

##  Author

**Shri Vishaal**  
Business Analyst | Power BI Enthusiast | Student Entrepreneur  

![Retail Store Analysis](./a3940ccc-780e-4803-9037-acddc11452e6.png)
