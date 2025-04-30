
# Financial Dashboard – Power BI Portfolio Project

## Project Overview
An interactive Power BI dashboard that reveals how discount strategies, pricing levels, and product mix impact revenue, profit, and margins across regions and categories.

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
![image alt](https://github.com/hoaiphuongpham/pricing-analyst-dashboard/blob/961ea0c80d6c35b2f53cb5935e25b7c24a04cf72/Dashboard%202025.jpg)

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

## Recommendations & Suggestions

Based on the analysis, consider the following strategic actions:

- **Optimize Discount Strategy**: Focus promotions in the 10–20% band where revenue uplift is highest; avoid discounts above 20% that erode profit.
- **Reprice High-Volume, Low-Margin Products**: Increase prices moderately on mid-tier products (e.g., LED Desk Lamp) to boost margins without sacrificing volume.
- **Expand in High-Margin Regions**: Allocate marketing spend to Asia and South America, where margins are strong but sales volume is currently low.
- **Product Portfolio Review**: Evaluate underperforming items (low volume and low margin) for potential phase-out or bundling opportunities.
- **Continuous Monitoring**: Set up monthly refresh and alerts in Power BI Service for KPI thresholds (e.g., margin drop below 30%).

---

## File Structure
```
/pricing-analyst-dashboard
│
├── pricing_analyst_dataset.csv       # Clean dataset used in Power BI
├── Financial Dashboard 2025.pbix                    # Power BI dashboard file
└── README.md                         # This file
```

---
