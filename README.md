# 📊 Sales, Customer & Inventory Analytics Dashboard (Power BI)

## 📌 Description

The **Sales, Customer & Inventory Analytics Dashboard** is a complete end-to-end **business intelligence solution** built in **Power BI** to analyze and monitor business performance across sales, customers, products, and inventory.

The dashboard provides deep insights into:

- Sales performance and trends  
- Customer behavior and segmentation  
- Product performance and profitability  
- Inventory levels, stock movement, and overstock risk  

The system is built using a **Star Schema data model**, advanced **DAX measures**, and interactive visuals to deliver **executive-level reporting and decision support**.

---

## 🛠️ Tools and Technologies Used

- **Power BI Desktop** – Dashboard development & data modeling  
- **DAX (Data Analysis Expressions)** – KPIs, measures, time intelligence  
- **Power Query (M)** – Data cleaning & transformation  
- **SQL Server / CSV Dataset** – Data source  
- **Data Modeling** – Star Schema  

---

## 💻 Environments Used

- Windows 10 / 11  
- Power BI Desktop  
- SQL Server Management Studio (SSMS)  
- VS Code (for documentation)  

---

## 📊 Dashboard Pages Overview

### 1️⃣ Sales Overview Dashboard
- Executive KPI cards (Sales, Profit, Orders, Quantity)
- Sales trends over time
- Sales by country and category
- Top products analysis

<p align="center">
  <img src="Screenshots/dashboard.png" alt="PakMart Dashboard" width="900">
</p>

### 2️⃣ Trends & YoY Analysis Dashboard
- This Year vs Last Year comparison
- Profit trends
- Sales by gender
- Monthly and yearly performance comparison
- YoY analysis table

### 3️⃣ Customer & Product Intelligence Dashboard
- Product hierarchy matrix (Category → Subcategory → Product)
- Sales, Profit, Quantity by product
- Distribution analysis
- Insight summary panel

### 4️⃣ Inventory & Operations Dashboard
- Inventory KPIs (Total stock, inventory value, product count)
- Overstock risk table
- Stock by category & subcategory
- Inventory movement analysis (Units In / Units Out)

### 5️⃣ Product Drillthrough Page
- Product-level deep analysis
- Sales trend for selected product
- Inventory status
- Profit and stock movement

### 6️⃣ Customer Drillthrough Page
- Customer profile analysis
- Sales, Profit, Orders KPIs
- Purchase trend over time
- Product and category breakdown

---

## ⭐ Key Features

- 📊 Interactive multi-page dashboards  
- 🗂️ Star Schema data model  
- 📅 Advanced filtering using slicers (Year, Country, Category)  
- 📈 Time Intelligence (YoY, Last Year, Trends)  
- 🧮 Advanced DAX measures for KPIs and comparisons  
- 🔎 Drillthrough pages for Product & Customer deep analysis  
- 📦 Inventory risk analysis (Overstock detection)  
- 📑 Business-ready executive reporting  

---

## 🎯 Business Outcomes

- ✔️ Better data-driven decision-making  
- ✔️ Identification of high-performing and low-performing products  
- ✔️ Customer behavior and purchase pattern analysis  
- ✔️ Inventory optimization and stock risk control  
- ✔️ Performance tracking across years and categories  
- ✔️ Executive-level management reporting  

---

## 🧠 Data Model

- **Fact Tables:**
  - FactInternetSales (Sales)
  - FactProductInventory (Inventory)

- **Dimension Tables:**
  - DimDate  
  - DimProduct  
  - DimCustomer  
  - DimGeography  
  - DimSalesTerritory  

- Fully connected **Star Schema** with optimized relationships.

---

## ⚙️ How to Use

1. Open the `.pbix` file in **Power BI Desktop**  
2. Refresh the data  
3. Use slicers to filter:
   - Year  
   - Country  
   - Category  
4. Right-click any product or customer → **Drillthrough** to view details  
5. Navigate between pages using page tabs or navigation buttons  

---

## 📁 Files Overview

- `Sales_Customer_Inventory_Dashboard.pbix` → Main Power BI file  
- `Dataset.sql / CSV` → Source data  
- `README.md` → Project documentation  
- `Screenshots/` → Dashboard images  

---

## 🏁 Conclusion

This project demonstrates **real-world business intelligence development skills** including:

- Data modeling  
- DAX & time intelligence  
- KPI design  
- Trend analysis  
- Drillthrough reporting  
- Executive dashboarding  

It simulates a **complete enterprise BI system** used by management teams for **strategic planning, performance monitoring, and operational optimization**.

---

## 👤 Author

**Muhammad Hasaan**  
Aspiring Data Analyst | Power BI | SQL | Data Visualization
