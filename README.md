# Coffee-Shop-Analysis


# ☕ Coffee Shop Sales Dashboard

## 📊 Overview

* This project analyzes sales data from a fictional coffee shop chain, **Maven Roasters**, to uncover key business insights and trends.
* Using **Microsoft Excel**, I cleaned, transformed, and visualized the dataset to create an **interactive dashboard** that provides a clear picture of the shop’s performance across time, product categories, and locations.
* The goal of this analysis is to help management make **data-driven decisions** to increase revenue, optimize product offerings, and improve customer experience.

---

## 📁 Dataset Information

* **Time period covered:** January to June
* **Fields included:**

  * `transaction_id` – unique ID for each transaction
  * `transaction_date` – date of purchase
  * `transaction_time` – time of purchase
  * `store_location` – branch where the sale occurred
  * `product_category` – main category (e.g., Coffee, Bakery, Tea, etc.)
  * `product_type` – specific item (e.g., Espresso, Croissant, Green Tea)
  * `price` – unit price of the item
  * `quantity` – number of items sold

---

## ⚙️ Data Preparation & Cleaning

### Step 1: Understanding the Data

* Reviewed the dataset to determine the number of transactions, date range, and available product categories.
* Verified data consistency and checked for missing values or formatting issues.

### Step 2: Feature Engineering

* Added several new columns to support deeper analysis:

  * **Revenue** = `Price × Quantity`
  * **Month** = Extracted from the transaction date (formatted as text e.g. Jan, Feb)
  * **Day of Week** = Extracted from the transaction date (e.g. Mon)
  * **Hour** = Extracted from the transaction time to analyze hourly sales patterns

---

## 📈 Data Exploration (Pivot Tables)

* Created multiple PivotTables to explore trends and relationships in the data:

  1. **Revenue by Month** – to identify sales seasonality and revenue trends over time
  2. **Transactions by Day of Week** – to determine which days drive the most customer traffic
  3. **Transactions by Hour of Day** – to find peak hours of operation
  4. **Transactions by Product Category** – to see which categories perform best
  5. **Top 15 Product Types (by Transactions)** – to identify best-selling products and revenue contribution

---

## 🎨 Dashboard Development

* Built a **dynamic Excel dashboard** using PivotCharts and slicers to make insights interactive.

### Components Included:

* **Line Chart:** Revenue by month
* **Column Charts:** Transactions by day of week and hour of day
* **Bar Chart:** Transactions by product category
* **PivotTable:** Top 15 product types with total revenue and transaction count
* **Slicer:** Store location filter connected to all PivotTables and Charts

### Dashboard Design Highlights:

* Clean, professional layout
* Hidden PivotTables for visual focus
* Removed gridlines for a polished appearance
* Consistent color scheme and labeling for readability

---

## 💡 Key Business Insights

* From the dashboard analysis, several insights were drawn:

  * **Peak Performance Periods:**

    * Sales were recorded between **January and June**, with revenue gradually increasing mid-year.
    * Weekends show higher transaction volumes compared to weekdays.
  * **Customer Behavior:**

    * Peak hours occur in the **morning** and **early afternoon**, aligning with coffee demand patterns.
  * **Product Insights:**

    * **Coffee** remains the top-performing category, generating the most revenue.
    * Bakery and cold beverage sales show seasonal spikes during warmer months.
  * **Store Comparison:**

    * Store-level slicer analysis highlights differences in sales trends and customer preferences across locations.

---

## 💼 Business Impact

* This analysis empowers management to make informed operational and marketing decisions by enabling them to:

  * Identify **high-performing periods** and plan promotions accordingly.
  * Optimize **product mix and inventory** to meet demand patterns.
  * Adjust **staffing levels** to match peak hours and days.
  * Benchmark **store performance** to replicate success strategies across branches.

---

## 🧰 Tools & Techniques Used

* **Microsoft Excel**

  * Data Cleaning and Preparation
  * Calculated Columns and Formulas
  * PivotTables and PivotCharts
  * Slicers for Interactive Filtering
  * Dashboard Design and Visualization
* **Analytical Techniques**

  * Descriptive Analysis
  * Trend Identification
  * Product and Category Analysis

---

## 📎 Files in this Repository

* `Coffee Shop Sales.xlsx` – dataset used for analysis
* `Coffee Shop Sales Dashboard.png` – image of the final dashboard *(optional if uploaded)*
* `README.md` – project documentation

---

## 👩‍💻 Author

* **Name:** Joy Bii
* **Role:** Data Enthusiast | Aspiring Data Analyst

---




