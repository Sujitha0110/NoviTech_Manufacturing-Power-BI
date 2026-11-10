# Novitech Manufacturing Analytics – Power BI Dashboard

## 📊 Project Overview

**Novitech Manufacturing Analytics Dashboard** is an interactive **Power BI analytics project** designed to monitor and analyze manufacturing operations, production performance, quality, finance, procurement, supplier reliability, raw material risk, and operator and shift efficiency.

The dashboard helps management identify **business trends, operational issues, cost drivers, quality problems, supplier performance, and supply chain risks** through interactive KPIs and visual reports.

---

## 🎯 Objectives

- Monitor overall manufacturing performance
- Analyze production and plant efficiency
- Track product quality and defects
- Monitor machine downtime and energy usage
- Estimate the cost exposure of defects
- Analyze procurement spend by supplier and raw material
- Evaluate supplier lead time, delay rate and ratings
- Identify delayed purchase orders
- Identify critical raw materials and supply chain risks
- Understand product-to-material dependency through the bill of materials
- Compare shift and operator experience performance
- Support data-driven business decisions

---

## 📑 Dashboard Pages

The Power BI report contains **7 analytical pages** (1920 × 1080), each with a page navigator, left-side slicers, KPI cards and a **Reset filters** button:

### 1. 📊 Executive Overview
- KPI strip: Total Production, Defect Rate, Total Downtime, Total Energy, Procurement Spend, Defect Cost Exposure
- Plant performance matrix vs. defect cost exposure
- Production volume vs. defect rate over time
- Procurement spend by raw material / supplier country
- Impact drivers on downtime and delivery delays (supplier scatter)
- Drill-through target page

### 2. 🏭 Production & Plant
- KPIs: Energy per Unit, Avg Downtime per Run, Production Runs, Total Production
- Plant performance comparison table
- Production output by category & product (with % volume share)
- Production volume trend by plant

### 3. ⚙️ Quantity & Efficiency
- KPIs: Defect Rate, Total Defects, Total Downtime, Defect Cost Exposure
- Defect rate by product
- Downtime vs. energy efficiency analysis
- Operational time loss by plant

### 4. 💰 Finance & Cost
- KPIs: Procurement Spend, Defect Cost Exposure, Average Lead Time, Delay Rate
- Spend by material
- Defect cost exposure by plant
- Procurement spend distribution by supplier
- Treemap of spend and orders by material and supplier

### 5. 🤝 Procurement & Suppliers
- KPIs: Procurement Spend, Delay Rate, Total Purchase Orders, Average Supplier Rating, Average Lead Time
- Procurement spend by supplier
- Supplier delivery reliability matrix
- Lead time & delay rate trend

### 6. 🧱 Raw Materials & Risk
- KPIs: Procurement Spend, Purchase Orders, Delayed Orders, Delay Rate, Average Lead Time
- Critical materials risk analysis
- Material dependency matrix (product category × raw material BOM count)

### 7. 👷 Operator & Shift
- KPIs: Total Production, Production Runs, Total Downtime, Avg Downtime per Run, Defect Rate
- Production output vs. downtime by plant
- Output and defect rate by operator experience
- Output, downtime and defect rate by shift

---

## 🗂️ Data Model

The project uses a star-style manufacturing data model with **fact, dimension and bridge tables** to support analysis across production, quality, procurement and workforce.

### Dimension Tables

- `dim_plants`
- `dim_products`
- `dim_operators`
- `dim_suppliers`
- `dim_raw_materials`

### Bridge Table

- `bridge_bill_of_materials` (links products to raw materials; also holds the report's DAX measures)

### Fact Tables

- `fact_production_runs`
- `fact_purchase_orders`

The data model enables cross-analysis between **production, quality, downtime, energy, procurement, suppliers, materials, and shift/operator performance**.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **DAX** (calculated measures)
- **Data Modeling**
- **Bookmarks & Drill-through**
- **Custom Theme (Fluent 2 base) & Page Backgrounds**
- **Interactive Dashboard Design**

---

## 📌 Key Features

- Interactive KPI cards
- Combo, scatter, treemap, donut, bar and matrix visuals
- Plant-wise and product-wise analysis
- Production and downtime monitoring
- Defect and defect cost exposure analysis
- Energy per unit tracking
- Supplier reliability and lead time analysis
- Delayed order monitoring
- Raw material dependency and risk analysis
- Shift and operator experience analysis
- Slicers for Plant, Product Category, Supplier, Raw Material, Shift, Experience and Date
- One-click **Reset filters** buttons (bookmarks) on every page
- Horizontal page navigation
- Management-focused dashboard design

---

## 📈 Key Business KPIs

- Total Production
- Total Defects
- Defect Rate
- Estimated Defect Cost Exposure
- Total Downtime
- Average Downtime per Run
- Total Energy / Energy per Unit
- Total Production Runs
- Total Procurement Spend
- Total Purchase Orders
- Delayed Orders
- Delay Rate
- Average Lead Time
- Average Supplier Rating
- BOM Count

---

## 📈 Business Benefits

This dashboard helps organizations:

- Improve production visibility
- Compare plant performance
- Reduce machine downtime
- Identify quality issues and their cost
- Improve energy efficiency
- Control procurement spend
- Evaluate supplier performance
- Identify delayed orders
- Detect raw material risks
- Improve supply chain visibility
- Understand shift and operator impact on output and quality
- Make faster and data-driven decisions

---

## 📁 Project File

The main Power BI report is provided as:

`Novitech_Manufacturing_Dashboard_Complete.pbix`

Open the file using **Microsoft Power BI Desktop** (a recent version) to explore the complete interactive dashboard.

---

## 👨‍💻 Project Type

**Business Intelligence & Data Analytics Project**

**Domain:** Manufacturing Analytics  
**Tool:** Microsoft Power BI  
**Focus:** Production, Quality, Operations, Finance, Procurement, Supply Chain & Workforce Analytics

---

## ⭐ Project Highlights

> A complete manufacturing analytics solution built in Power BI to transform manufacturing data into meaningful business insights and support effective, data-driven decision making.

---
