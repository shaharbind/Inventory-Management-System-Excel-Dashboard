# 📦 Inventory Management System – Excel Dashboard

A structured Excel dashboard that manages inventory data, tracks stock, sales, and purchases, and provides real-time reorder notifications.

---

## 📊 Dashboard Preview
![Inventory Management Dashboard](assets/screenshot.png)

---

## 🎯 Objectives
- Track **customers, products, purchases, sales, stock amount, and profit/loss**.  
- Monitor **top products** and **top customers** by sales value.  
- Provide **real-time reorder notifications** when stock is low.  
- Analyze **total stock distribution** across product categories.  

---

## 📁 Files Included

| File Name | Description |
|-----------|-------------|
| `Inventory-Dashboard.xlsx` | Main Excel workbook with dashboard, data tables, and charts. |
| `assets/screenshot.png` | Dashboard screenshot preview. |

---

## 🔧 How to Use
1. Open `Inventory-Dashboard.xlsx` in Excel (2016 or later / Office 365).  
2. Update the **Products, Customers, Vendors, Purchases, and Sales** sheets.  
3. Refresh PivotTables: **Data → Refresh All**.  
4. Review the **Dashboard** sheet: KPI cards, reorder alerts, and visual summaries update automatically.  

---

## 🧱 Data Model (Example)
- **customers**: `customer_id`, `name`, `contact`  
- **products**: `product_id`, `name`, `category`, `price`, `stock_qty`  
- **purchases**: `purchase_id`, `product_id`, `qty`, `purchase_price`, `date`  
- **sales**: `sale_id`, `product_id`, `qty`, `sale_price`, `date`, `customer_id`  

**Calculated fields inside Excel:**
- **Stock Amount** = `SUM(product.stock_qty * product.price)`  
- **Profit/Loss** = `Total Sales – Total Purchase`  
- **Reorder Flag** = IF(`stock_qty < threshold`, "Needs reorder", "")  

---

## 📊 Core Metrics & Visuals
- **KPI Cards**: Customers, Products, Purchase Amount, Sales Amount, Stock Amount, Profit/Loss.  
- **Bar Chart**: Top 5 Products by sales.  
- **Bar Chart**: Top 5 Customers by purchase value.  
- **Column Chart**: Total Stock by product category.  
- **Reorder Notifications Panel**: Products needing immediate attention.  

---

## 🧠 Excel Skills Demonstrated
- Data cleaning & preparation: **Remove Duplicates, Data Validation**.  
- Formulas: **SUMIFS, IF, VLOOKUP/XLOOKUP, COUNTIFS**.  
- PivotTables & PivotCharts for aggregation and visualization.  
- Conditional Formatting for reorder alerts.  
- Interactive Dashboard layout design.  

---

## 📈 Business Insights (Examples)
- **Smart Watch, Laptop HP xyz i5, and Wireless Printer** frequently hit reorder thresholds.  
- **Top 5 Customers** contribute a major share of revenue (Dyana Store, Jain Technology, etc.).  
- Profit/Loss indicator helps identify **negative margins** early.  
- Stock visualization highlights **overstocked items** like Desktops and Speakers vs. understocked items.  

---

## 🙋 Contact
**Arbind Shah**  
LinkedIn: [www.linkedin.com/in/arbind-shah](https://www.linkedin.com/in/arbind-shah)
