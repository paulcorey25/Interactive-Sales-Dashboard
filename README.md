
# 📊 Interactive Sales Dashboard (Power BI)

This Power BI dashboard visualizes synthetic sales data across regions, product categories, sales types, and distributors. It simulates a full-featured reporting solution used by business stakeholders to monitor performance, identify trends, and drill into sales performance by slicing data interactively.

![Dashboard Preview](dashboard.png)

---

## 🚀 Features

- **Dynamic Filters** for:
  - Region
  - Product Category
  - Sales Type
  - Distributor

- **KPI Cards**:
  - Total Revenue
  - Year-over-Year % Change (YoY%)
  - Order Count
  - Average Order Value (AOV)

- **Visualizations**:
  - Line chart of Revenue by Month
  - Stacked bar chart of Order Count by Region and Product Category
  - Detailed order table with filtering and total revenue

---

## 🧠 Tech Stack

- **Power BI Desktop**
- **DAX Measures** for KPIs and trends
- **Python (Faker)** for dummy data generation
- **CSV Data** source (no external dependencies)

---

## 📁 File Structure

```
Interactive-Sales-Dashboard/
│
├── SalesData.csv               # Cleaned synthetic sales dataset
├── dashboard.png               # Screenshot of completed dashboard
├── README.md                   # Project documentation (this file)
```

---

## 🧪 How to Use

1. Clone or download this repository
2. Open Power BI Desktop
3. Load the `SalesData.csv` file
4. Rebuild visuals using:
   - Line chart for revenue trend
   - Card visuals for KPIs
   - Stacked bar chart for regional breakdown
   - Table visual for order details
5. Optional:
   - Add drillthrough pages
   - Enable forecasting
   - Format date for cleaner axis labels

---

## 🔎 Notes

- All data in this project is randomly generated and used for demonstration purposes only.
- The dashboard is optimized to showcase interactive filtering and executive reporting best practices.
- Useful as a portfolio sample, client demo, or base template for freelance Power BI work.

---

Made with ⚡ by Corey Paul
