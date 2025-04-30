
# Pricing Analyst Dashboard – Power BI Portfolio Project

## Project Overview
This project simulates the responsibilities of a **Pricing Analyst** by analyzing sales and pricing data for a retail business. The main objective is to explore key pricing metrics, identify margin drivers, and understand the impact of discount strategies using interactive visualizations in **Power BI**.

---

## Dataset
A synthetic dataset of 150 sales records was generated for this project. It includes:
- **Product Name, Category**
- **List Price (€), Discount (€), Cost (€)**
- **Units Sold, Region, Date Sold**

> *Note: This dataset was generated for educational purposes using Python and does not reflect real company data.*

---

## Key Metrics (KPIs)
The following KPIs were calculated and visualized:
- **Total Revenue** = (List Price - Discount) × Units Sold  
- **Profit** = Revenue - (Cost × Units Sold)  
- **Profit Margin %** = (Profit ÷ Revenue) × 100  
- **Average Discount %** = (Discount ÷ List Price) × 100  
- **Units Sold**  
- **Average Selling Price (ASP)** = Revenue ÷ Units Sold

---

## Power BI Dashboard Highlights
- **Top Cards**: Revenue, Margin %, Discount Rate, Units Sold  
- **Trend Analysis**: Revenue & Profit Margin over time  
- **Product Ranking**: Top products by revenue and margin  
- **Regional Analysis**: Revenue and margin by region  
- **Filters/Slicers**: Date, Product Category, Region  

---

## Tools Used
- **Power BI** – for data modeling and dashboard creation  
- **Microsoft Excel / CSV** – for data storage and preprocessing  
- **Python (Pandas)** – for synthetic data generation (available in a separate repo)

---

## Key Findings
1. **Top-performing products**:  
   - **Smartwatch** drives the highest profit (€0.23M) with a strong margin of 40%, followed by Yoga Mat and Bluetooth Speaker.
   - **Yoga Mat** achieves the highest volume (180 units/month) with a healthy margin of 35%.
2. **Optimal Discount Band**:  
   - **10–20%** discount band generated the highest revenue (€1.1M) while maintaining profitability.
   - Deeper discounts (20%+) did not yield proportional revenue increases.
3. **Price-Volume Dynamics**:  
   - High‐price items (e.g. Coffee Maker at €150 avg.)  show lower sales volume, indicating price sensitivity.
   - Mid-priced products (e.g., LED Desk Lamp at €60 avg.) hit the sweet spot - good volume and strong margins.
4. **Regional Performance**:  
   - **Europe** accounts for 45% of total revenue, followed by **North America** at 30%.
   - Asia and South America have growth potential, showing lower current sales but higher margin rates.
5. **Margin by category**:  
   - Electronics achieved the highest gross margin (~38%), while Apparel lagged (~32%), suggesting a review of cost or price strategy.

---

## File Structure
```
/pricing-analyst-dashboard
│
├── SalesData.csv       # Clean dataset used in Power BI
├── Financial Dashboard 2025.pbix                    # Power BI dashboard file
└── README.md                         # This file
```

---
