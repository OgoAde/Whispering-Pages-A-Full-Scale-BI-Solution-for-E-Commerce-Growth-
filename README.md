# 📚 Optimizing Customer Experience & Marketing ROI with Microsoft Fabric  
### Whispering Pages Case Study — A Full-Scale BI Solution for E-Commerce Growth  

![Header](./A_digital_illustration_features_data_analytics_wit.png)

---

## 📌 Project Overview

This case study presents a Business Intelligence solution developed for **Whispering Pages**, an emerging e-commerce bookstore in Canada aiming to become a market leader. The project focused on enhancing **customer experience**, **inventory optimization**, and **marketing efficiency** through the implementation of a **scalable data architecture** and **insight-driven analytics**.

**Objectives:**
- Identify and optimize **customer segments** for targeted engagement  
- Streamline **inventory management** to reduce overstock and stockout scenarios  
- Maximize **marketing ROI** and reduce spend inefficiencies  
- Enable continuous **self-serve reporting and automation** for business teams  

---

## 🛠️ Tools & Technologies

| Platform | Tools & Frameworks |
|---------|--------------------|
| **Data Platform** | Microsoft Fabric, Lakehouse, Dataflows |
| **Visualization** | Power BI (DAX, Power Query, Tooltip Design) |
| **Architecture** | Medallion Architecture (Bronze → Silver → Gold) |
| **Data Sources** | CRM Systems, Campaign APIs, Transactional Data |
| **Pipeline** | Automated ETL Pipelines for Refresh and Reuse |

---

## 📈 Key Business Problems Addressed

1. **Inventory Imbalance**  
   Frequent overstock or out-of-stock conditions due to inaccurate forecasting

2. **Ineffective Marketing Spend**  
   High spend during major campaigns (e.g., Black Friday) yielded similar results as smaller ones

3. **Limited Customer Segmentation**  
   Generic messaging and missed upsell opportunities due to lack of spend-tier targeting

---

## 🔑 KPIs Tracked

| Category | KPI |
|---------|-----|
| **Marketing & Acquisition** | ROI, Average Purchase Value (APV) |
| **Customer Retention & Loyalty** | Repeat Purchase Rate (RPR), Average Revenue per Customer (ARPC) |

---

## 🧱 Architecture Overview

We implemented a **Medallion Architecture** within Microsoft Fabric using the following structure:

- **Bronze Layer**: Raw data ingestion from CRM and API connectors  
- **Silver Layer**: Cleansed and enriched tables (structured joins and transformations)  
- **Gold Layer**: Business-friendly tables used for reporting in Power BI  

Dataflows were used at each stage to ensure **lineage**, **modularity**, and **reuse** by multiple teams. A **data pipeline** was also built to handle automated refresh and support real-time reporting.

---

## 📊 Insights & Visualizations

### 1. Customer Spend Segmentation (Donut Chart)
- **62.5%** of customers are medium spenders ($200–$300 per visit) — approx. **12.6M users**  
- **26%** are low spenders (less than $200) — approx. **5.1M users**  
- Remaining **11.5%** are high spenders  
> 📌 *Insight: Focus marketing on medium spenders with tailored promotions for upselling.*

---

### 2. Sales Trend Analysis (Line Chart + Tooltip)
- Peak in 2020 (likely due to pandemic)  
- Flattening trend in 2021–2022  
- Tooltip feature shows **top-selling book titles** and **monthly sales volume** on hover  
> 📌 *Insight: Helps forecast demand and stock high-demand titles seasonally.*

---

### 3. Top 10 Loyal Customers (Bar Chart + Slicer)
- Interactive chart sliced by **year** and **genre**  
> 📌 *Insight: Enables personalized loyalty rewards and priority customer programs.*

---

### 4. Campaign ROI Analysis (Bubble Chart)
- Spring Sales Campaign: $10K spend → $1.7M revenue  
- Black Friday Campaign: $80K spend → same $1.7M revenue  
> 📌 *Insight: High-spend doesn’t always equal high return. Indicates market saturation or poor targeting.*

---

### 5. Dynamic KPI Cards (Across All Pages)
- Real-time cards display: `Total Revenue`, `ROI`, `RPR`, `APV`, and `ARPC`  
- Updated via slicers (Year, Month, Genre) for contextual drilldowns  
> 📌 *Insight: One-click analysis for stakeholders with intuitive filters.*

---

## 🎯 Business Impact

✅ Unlocked detailed customer segmentation for upsell targeting  
✅ Reduced marketing waste by identifying underperforming high-spend campaigns  
✅ Enabled proactive inventory stocking using historical demand patterns  
✅ Delivered scalable, reusable reporting structure for future growth  

---

## 📦 Deliverables

- ✅ Power BI Report (Multiple pages with tooltips, slicers, and KPIs)  
- ✅ Fabric Lakehouse Architecture (Bronze → Silver → Gold)  
- ✅ Automated Data Pipeline  
- ✅ Documentation & Recommendations  

---

## 💡 What's Next?

- Extend customer segmentation with **RFM modeling**  
- Integrate **seasonality prediction models** using Azure Machine Learning  
- Build **inventory forecasting dashboard** tied to campaign calendars  

---

## 🧠 Skills Used

`Microsoft Fabric`, `Power BI`, `Dataflows`, `Medallion Architecture`, `Lakehouse`, `DAX`, `Power Query`, `Data Modeling`, `KPI Development`, `Customer Segmentation`, `Marketing Analytics`, `Inventory Optimization`, `ROI Analysis`, `CRM & API Integration`, `Data Storytelling`

---

## 🔗 Visual Access
*Power BI report visuals will be re-embedded once access is restored. Placeholder image used above.*

---

