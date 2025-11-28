# 📊 Amazon Sales Analytics Dashboard (Power BI)

A fully interactive **Power BI dashboard** built to analyze Amazon product sales across multiple categories using year-to-date (YTD) and quarter-to-date (QTD) metrics.  
This project transforms raw e-commerce sales data into actionable insights through KPIs, trend charts, product analysis, and customer review tracking.

---

## 🚩 Problem Statement

Amazon product sales data contains thousands of transactions across multiple categories, time periods, and ratings.  
The objective of this dashboard is to provide a clear analytical summary that helps answer:

- How are sales performing this year compared to previous quarters?  
- Which product categories drive the highest revenue?  
- What are the top-selling products so far this year?  
- How do weekly and monthly sales trends behave over time?  
- How do product reviews correlate with performance?  

The goal is to enable **data-driven decision making** using interactive visual insights.

---

## 🎯 KPI Requirements

The dashboard includes four primary KPIs:

### **📌 YTD Sales**  
Monitor total year-to-date sales to evaluate overall revenue performance.

### **📌 QTD Sales**  
Track quarter-to-date revenue to identify quarterly trends and fluctuations.

### **📌 YTD Products Sold**  
Analyze the total number of units sold this year to understand product movement.

### **📌 YTD Reviews**  
Evaluate total year-to-date review count to measure customer engagement and satisfaction.

---

## 📈 Charts & Visualization Requirements

### **1. YTD Sales by Month — Line Chart**  
Shows monthly sales patterns to reveal seasonality and growth trends.

### **2. YTD Sales by Week — Column Chart**  
Displays weekly sales fluctuations for short-term performance tracking.

### **3. Sales by Product Category — Heatmap**  
Highlights YTD vs QTD metrics for each product category.  
Useful for comparing revenue contribution and identifying high-performing segments.

### **4. Top 5 Products by YTD Sales — Bar Chart**  
Identifies key revenue-generating products.

### **5. Top 5 Products by YTD Reviews — Bar Chart**  
Shows highly rated or frequently reviewed products, indicating customer preference.

---

## 🖥️ Dashboard Preview

Below is the main report page showcasing KPIs, charts, and slicers:

![Dashboard Overview](images/dashboard-overview.png)

> *(Replace the image path above with your actual screenshot file name, e.g.  
`![Dashboard](https://raw.githubusercontent.com/<username>/amazon-sales-powerbi-dashboard/main/Screenshot-dashboard.png)`)*

---

## 🛠️ Tools & Technology Used

- **Power BI Desktop**
- **Power Query** for data cleaning and ETL  
- **DAX Measures** for KPI calculations (YTD, QTD, dynamic measures)
- **Data Modeling** (relationships, date table, star schema)
- GitHub for version control & project documentation

---

## 🔍 Insights From the Dashboard

Some key insights uncovered through visualization:

- Sales show consistent growth with peaks in **September–December**.  
- **Men Shoes** and **Cameras** are top revenue contributors.  
- Weekly sales display sharp movement in mid-year weeks, highlighting seasonal demand.  
- Products like **Nikon Wide Lens** and **Atomos Ninja** dominate YTD sales.  
- SanDisk products lead the review charts, indicating strong customer trust and market presence.

---

## 📂 Repository Structure

```plaintext
.
├── Amazon-sales-dashboard.pbix       # Main Power BI file
├── README.md                         # Documentation
|--- Amazon-combined-dataset.xlsx     # Dataset used
└── images/                           # Dashboard screenshots
    └── dashboard-overview.png
