# Sales and Order Quantity Performance Analysis

This project analyzes sales and order quantity data from January 2020 to October 2021. The analysis provides insights into overall performance, product category trends, and top-performing cities.

## 🛠️ Dashboard Tool

The visualization dashboard for this analysis was created using **Looker Studio**.

## 📊 Key Performance Indicators (KPIs)

* **Total Sales (Jan 2020 - Oct 2021):** $175,475,057
* **Total Sales (2021 YTD):** $84,154,048
* **Year-over-Year Performance:** Sales in 2021 show a decrease of 7.8% compared to the previous period.

## 💡 Key Insights

### 1. Performance by Product Category

* **Highest Order Quantity:** **eBooks** are the most frequently ordered product, followed by Training Videos and Blueprints.
* **Highest Sales Revenue:** **Drones** generate the most revenue, significantly outpacing all other categories. This indicates a high price point per unit.
* **Sales Contribution:**
    * **Robots** and **Drones** together account for nearly 70% of total sales (**42.4%** and **27.2%** respectively).
    * **eBooks**, despite having the highest order quantity, contribute a smaller portion of the total revenue.

### 2. Top Performing Cities

The top cities by both total sales and order quantity are:

1.  **Washington**
2.  **Houston**
3.  **Sacramento**
4.  **San Diego**
5.  **Albany**

Washington leads significantly in total sales, while Houston has a slightly higher order quantity than its sales value might suggest.

### 3. Sales Trends

* The sales trend line shows significant volatility with several peaks and troughs between January 2020 and October 2021.
* The highest sales peak occurred around **July 2021**.

## 🚀 Solution

Based on the analysis, here are several strategic solutions to drive growth:

1.  **Increase Revenue from Low-Price Categories**
    * **Problem:** eBooks and Training Videos sell a lot but don't generate much revenue.
    * **Solution:**
        * Bundle them with higher-priced items like Robot Kits or Drones.
        * Introduce premium versions (e.g., advanced training).

2.  **Expand High-Performing Products**
    * **Problem:** Drones and Robots are top earners.
    * **Solution:**
        * Increase inventory and product variations.
        * Run targeted promotions or upsell complementary products (e.g., spare parts, maintenance kits).

3.  **Geo-Targeted Marketing Campaigns**
    * **Problem:** Need to capitalize on strong markets for continued growth.
    * **Solution:**
        * Focus on Washington, Houston, and Sacramento.
        * Run localized ads and offers.
        * Explore referral or loyalty programs in top cities.

## 📁 Data Source

The analysis is based on the `Dataset_result.csv` file, which contains transactional data with the following columns:

* `order_date`
* `category_name`
* `product_name`
* `product_price`
* `order_qty`
* `total_sales`
* `cust_email`
* `cust_city`
