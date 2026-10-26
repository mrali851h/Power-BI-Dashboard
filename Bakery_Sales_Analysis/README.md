# 🍞 Bakery Sales Dashboard
![Bakery Sales](/Images/db_bakary_Overview.gif)
A comprehensive interactive Business Intelligence dashboard designed to analyze bakery sales performance, customer behavior, product performance, inventory levels, and operational efficiency across 2023–2024.

---

## 📊 Project Overview

This dashboard provides end-to-end visibility into bakery operations through five interconnected analytical pages. It enables data-driven decision-making by highlighting sales trends, top-performing products and categories, customer segments, seasonal and festival impacts, weather effects, inventory health, and waste management.

**Key Metrics at a Glance:**

| Metric              | Value |
|---------------------|-------|
| Total Sales         | $3M   |
| Total Cost          | $2M   |
| Total Profit        | $1M   |
| Orders              | 7K    |
| Products            | 35    |
| Customers           | 2K    |

---

## 🖥️ Dashboard Pages

### 1. Overview
![Bakery Sales](/Images/db_bakary_Overview.gif)

High-level performance summary with key KPIs and trend analysis.

**Visualizations:**
- **KPI Cards**: Total Sales, Total Cost, Total Profit, Order Count, Product Count, Customer Count
- **Sales Trends by Year & Quarter**: Line chart showing sales progression from Jan 2023 to Oct 2024 with trend line
- **Sales by Category**: Horizontal bar chart ranking product categories
- **Customer Segments**: Sales contribution by Young Professional, Family, Student, and Senior Citizen
- **Top Products**: Highest-selling individual products (Chocolate Cake, Cookies, Black Forest Cake, etc.)

**Key Insights:**
- Cakes lead category sales ($895K)
- Young Professionals generate the highest sales ($399K)
- Chocolate Cake is the top-selling product ($292K)

---

### 2. Customer Analytics
![Bakery Sales](/Images/db_bakery_customer.gif)
Deep dive into customer behavior, preferences, and external influencing factors.

**Visualizations:**
- Customer Segments by Sales
- Payment Methods Distribution (UPI, Cash, Card, Wallet)
- Festival Customer Attraction
- Seasonal Sales Performance
- Weather Impact on Sales (Clear → Foggy)

**Key Insights:**
- UPI is the dominant payment method (~7K transactions)
- Non-festival periods attract the majority of customers
- Monsoon season generates the highest sales ($872K)
- Clear weather correlates with peak sales ($770K), declining under foggy conditions

---

### 3. Product Performance
![Bakery Sales](/Images/db_bakery_product.gif)
Analysis of production volume, sales volume, and promotional effectiveness.

**Visualizations:**
- Highest Production Volume Products (Nankhatai, Puff, Paav, etc.)
- Highest Production Volume Categories
- Highest Sales Volume Products
- Highest Sales Volume Categories
- Loyalty Membership Impact (Yes 42% / No 58%)
- Promotion Impact on Sales (Yes 30% / No 70%)

**Key Insights:**
- Indian Bakery category leads both production (21K) and sales volume (16K)
- Nankhatai tops both production (9.1K) and sales volume (7K)
- Majority of sales occur without loyalty membership or promotions

---

### 4. Stock & Inventory
![Bakery Sales](/Images/db_bakery_stock.gif)
Inventory health monitoring and waste analysis.

**Visualizations:**
- Highest Available Stock Products
- Highest Waste Percentage Products
- Highest Available Stock Categories
- Highest Waste Percentage Categories

**Key Insights:**
- Nankhatai holds the highest available stock (1,990 units)
- Peanut Butter shows the highest waste percentage (47%)
- Indian Bakery category has the largest available stock (5.0K)
- Cakes category has the highest waste rate (43%)

---

### 5. Summary & Operations
![Bakery Sales](/Images/db_bakery_summary.gif)
Consolidated view combining festival performance, storage analysis, and detailed category metrics.

**Visualizations:**
- Festival Sales Ranking
- Stock Distribution by Storage Type & Category (Dry Storage, Room Temperature, Refrigerated)
- Detailed Category Table including:
  - Units Produced / Sold / Available
  - Waste Percentage
  - Total Sales / Cost / Profit
  - Performance Rating

**Key Insights:**
- Non-festival periods drive the majority of sales ($2,074K)
- Refrigerated storage is fully allocated (100%)
- Cakes deliver the highest sales ($895K) and profit ($340K) despite higher waste
- Indian Bakery offers strong volume with solid profitability and top rating

---

## 📈 Key Business Insights

1. **Category Leadership**  
   Cakes dominate revenue, while Indian Bakery leads in volume.

2. **Customer Focus**  
   Young Professionals and Families are the primary revenue drivers. Targeting these segments can maximize ROI.

3. **Seasonality & External Factors**  
   Monsoon and clear weather conditions significantly boost sales. Inventory planning should align with these patterns.

4. **Waste Management Opportunity**  
   High waste rates in Cakes (43%) and certain spreads/jams present a clear opportunity for process improvement and margin expansion.

5. **Promotion & Loyalty**  
   Current promotion and loyalty programs contribute modestly. Refining these strategies could unlock additional growth.

---

## 🛠️ Technology Stack

| Component          | Technology                          |
|--------------------|-------------------------------------|
| Visualization      | Power BI / Tableau / Looker Studio  |
| Data Source        | Relational Database / Excel / CSV   |
| Data Modeling      | Star Schema (Fact + Dimension)      |
| Interactivity      | Cross-filtering, Slicers, Drill-through |
| Time Period        | 2023 – 2024                         |

> **Note:** The exact tool used can be adjusted based on the implementation environment.

---


---

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (or equivalent BI tool)
- Access to the source data files

### Installation & Usage
1. Clone or download this repository.
2. Open the dashboard file (`.pbix` / `.twbx` / etc.) in your BI tool.
3. Update data source connections if necessary.
4. Use the year slicers (2023 / 2024) and Clear Filter button to explore the data interactively.

### Filters Available
- Year selection (2023 / 2024)
- Clear Filter functionality across all pages
- Cross-page filtering and highlighting

---

## 📌 Recommendations

| Priority | Recommendation                                      | Expected Impact                  |
|----------|-----------------------------------------------------|----------------------------------|
| High     | Reduce waste in Cakes and Spreads categories        | Improved margins                 |
| High     | Strengthen focus on Young Professional & Family     | Higher revenue                   |
| Medium   | Optimize inventory for Monsoon & Clear weather      | Better stock availability        |
| Medium   | Enhance loyalty program value proposition           | Increased repeat purchases       |
| Low      | Review promotion effectiveness                      | Higher promotional ROI           |

---

## 📧 Contact & Contribution

This project was developed for analytical and educational purposes.  
Feel free to fork, adapt, and improve the dashboard for your own bakery or retail analytics use cases.

---
## 👤 Author

**Ali Hanafy**

- GitHub: [Ali Hanafy](https://github.com/mrali851h/Power-BI-Dashboard)
- LinkedIn: [Ali Hanafy](https://www.linkedin.com/in/ali-hanafy-5a8462384)


