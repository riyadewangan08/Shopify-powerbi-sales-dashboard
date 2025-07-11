# 🛍️ Shopify Sales and Funnel Analysis Dashboard (Power BI)
This project presents a complete end-to-end analysis of Shopify sales — starting from cleaning a raw, messy dataset in Python (Jupyter Notebook), performing exploratory data analysis (EDA), and finally building an interactive Power BI dashboard.
The Power BI dashboard highlights key business KPIs and provides actionable insights to support decision-making based on real-time sales metrics and customer trends.


---

## 🖼️ Dashboard Preview
![Shopify Dashboard Preview](https://github.com/riyadewangan08/shopify-sales-analysis/raw/045b3218760363393447eca6983b7f6c412b6cf6/shopify%20sales%20and%20funnel%20dashboard.png)



---

## 📊 Project Objective

The goal of this project is to build a comprehensive dashboard that:
- Tracks **Net Sales**, **Average Order Value**, and **Total Quantity Sold**
- Monitors sales performance **by time**, **product type**, **location**, and **payment gateway**
- Enables business stakeholders to identify high-performing areas and customer trends

---

## 📁 Files Included

| File Name                                  | Description                                               |
|--------------------------------------------|-----------------------------------------------------------|
| `shopify sales dashboard and database.pbix` | Power BI file containing the complete dashboard           |
| `shopify sales and funnel dashboard.png`    | Screenshot preview of the final dashboard                 |
| `Shopify_Sales_Data_Cleaning_and_EDA.ipynb` | Jupyter notebook used for data cleaning and EDA           |
| `Dirty_Shopify_Sales.xlsx`                 | Raw dataset before cleaning                               |
| `Cleaned_Shopify_Sales.xlsx`               | Final cleaned dataset used for dashboard                  |
| `README.md`                                | Project documentation                                     |


--
## 📊 Part 1: Data Cleaning & EDA with Jupyter Notebook

All data preprocessing and exploratory data analysis were done in:

📄 `Shopify_Sales_Data_Cleaning_and_EDA.ipynb`

### 🧹 Data Cleaning Steps
- Handled missing values and typos
- Converted `'nan'` strings to actual `NaN`
- Fixed inconsistent casing and invalid dates
- Removed duplicates and irrelevant columns
- Handled outliers using 99th percentile filtering

### 📈 Graphs Included in EDA
- 🔥 Heatmap of missing values
- 🏙️ Bar chart: Top 10 Cities by Total Sales
- 📦 Histogram: Distribution of Quantity Ordered
- 📉 Line plot: Sales Over Time
- 🧩 Correlation heatmap for numeric columns

📦 Final cleaned dataset: `Cleaned_Shopify_Sales.xlsx`

---

## 📊 Part 2: Power BI Dashboard

The cleaned dataset was imported into Power BI to build an interactive sales dashboard.

## 📌 Key Visuals and Features

- **KPIs**: Net Sales, Avg Order Value, Quantity Sold
- **Sales Trend**: Line chart by Day and Bar chart by Hour
- **Product Analysis**: Net Sales by Product Type
- **Geo-Insights**: Map of sales by City and Billing Province
- **Funnel Insights**: Net Sales by Payment Gateway (shopify, paypal, gift card, etc.)
- **Slicer Panel**: Interactive filters for metric type and gateway

---

## 🔧 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Excel / CSV** (for data source)
- **Map Visualizations** (ArcGIS, Filled Map)
- **Custom Slicers** and Time Intelligence

---

## 📈 Business Insights & Outcomes

- Shopify’s primary sales come from **Shopify Payments (58%)**, followed by PayPal and Gift Cards
- **Peak order hours** occur between **11 AM to 4 PM**, indicating high engagement during midday
- States like **Texas, California, and Florida** contribute significantly to total revenue
- Certain product categories like **Clothing** and **Electronics** dominate net sales
- High repeat order value observed in top cities (Washington, Houston, New York)

---

## 🧠 Conclusion

This dashboard serves as a powerful tool for executives and marketing teams to:
- Make data-driven sales strategies
- Improve customer targeting by region and product
- Optimize payment gateway offerings

📌 **Note**: All data shown here is for analysis and demonstration purposes only.


## 👤 Author

**Riya dewangan**  
📧EMAIL: riyadew77@gmail.com



