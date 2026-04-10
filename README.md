# Global Retail Financial Performance Dashboard

## Business Overview
Large-scale logistics and retail operations require immediate visibility into profitability across multiple dimensions (time, geography, and product category). This dashboard was engineered to provide executive leadership with a consolidated, highly interactive view of global sales performance, highlighting both revenue growth and margin risks.

## Technology Stack
* **Business Intelligence:** Power BI
* **Data Language:** Advanced DAX
* **Data Modeling:** Star Schema

## Key Features & Architecture
1. **Enterprise Data Modeling:**
   * Architected a strict **Star Schema** with a central `Fact_Order` table surrounded by `Dim_Customer`, `Dim_Date`, and `Dim_Product` tables, ensuring optimal query performance and accurate cross-filtering across millions of potential rows.
2. **Advanced DAX & Dynamic Context:**
   * Implemented **Dynamic Measure Switching** using the DAX `SWITCH` function. This allows end-users to toggle the entire dashboard context between Profit, Quantity, and Sales metrics seamlessly, saving screen space and reducing visual clutter.
   * Engineered **Time-Intelligence** measures to track Year-to-Date (YTD) and Previous Year-to-Date (PYTD) metrics, visualizing the variance through a dynamic Waterfall chart.
3. **Risk & Profitability Analysis:**
   * Developed a "State Profitability Segmentation" scatter plot designed specifically to identify high-volume, negative-margin regions, allowing decision-makers to immediately spot areas bleeding cash despite high sales numbers.

## Business Impact
Delivered a self-service analytical tool that shifts the focus from simple operational reporting to strategic financial analysis, enabling executives to benchmark YoY performance and pinpoint logistical profit leaks instantly.

<img width="1379" height="460" alt="image" src="https://github.com/user-attachments/assets/de04b69a-d202-4e6b-a0f0-1fdf332f1040" />
