# FMCG_Sales_And_Marketing_Analysis


##  Objective

The primary objective of this project is to provide a **comprehensive analysis of sales performance, financial health, customer behavior, and marketing effectiveness** in the FMCG (Fast-Moving Consumer Goods) industry. The insights derived from this report are designed to support **data-driven decision-making**, enhance operational strategies, and optimize growth opportunities for key stakeholders.

---

##  Project Overview

This Power BI report presents a detailed analysis of a fictional FMCG company's performance over a **two-year period (2023–2024)**. The company operates in **four regions of Bangladesh**:

* **Dhaka**
* **Khulna**
* **Chittagong**
* **Rajshahi**

The company offers **four major product categories**:

* **Snacks**
* **Beverage**
* **Personal Care**
* **Dairy**

During the two-year period, the company launched multiple **promotional campaigns**, including:

* Discount Offers
* Bundle Offers
* Buy-One-Get-One-Free (BOGO)

Seven core datasets were used in the analysis:

* `fact_sales`
* `sales_target`
* `customer`
* `product`
* `region`
* `promotion`
* `date`

---

##  Working Methodology

### 1. **Data Preparation**

* All datasets were cleaned and transformed using **Power Query** in Power BI.
* Data issues like missing values, inconsistent formats, and duplicates were resolved.

### 2. **Data Modeling**

* A **star schema** data model was created to ensure optimal performance and ease of analysis.
* Relationships were established between fact and dimension tables.

### 3. **DAX Measures**

Developed multiple DAX measures using:

* `CALCULATE`
* `FILTER`
* `ALL`
* **Time Intelligence Functions** (e.g., YTD, MTD, previous year comparison)
* **Field Parameters** to analyze the impact of **price changes on sales**

### 4. **Dashboard Design**

A six-page interactive dashboard was created, including:

* **Sales Dashboard** – Sales trends, top products, region-wise performance
* **Finance Dashboard** – Revenue, cost, profit analysis with KPIs
* **Customer Dashboard** – RFM segmentation and customer value insights
* **Marketing Dashboard** – Promotion analysis and marketing ROI
* **Problem Areas** – Identified issues in regions, product categories, and sales decline
* **Recommendations** – Strategic suggestions for improvement

Additional Features:

* **Tooltips** for enhanced interactivity and contextual insights

---

## 📈 Key Insights & Features

###  Sales Analysis

1. **Current year sales fell by 22.2% YoY** (from 34.89K to 27.13K), yet **orders increased by 6.1%**, suggesting smaller order sizes or lower-value purchases.
2. **Daily sales decreased from 96 to 74 units** (–22.4% YoY), despite a short-term forecast showing potential recovery.
3. **Promotions boosted performance**, as **post-promotion daily sales (43)** exceeded **pre-promotion sales (37)**.
4. **Sales channels are evenly distributed**, with **Departmental Stores leading at 33.9%**, and **Bundle Offers driving the highest daily sales (4,716 units)** among promotion types.

   ![Sales](https://github.com/user-attachments/assets/135b99c1-b7bd-4348-87de-babe6ba8a919)




###  Financial Overview

1. **Snacks lead in sales** with a total cost of **0.64M** and a profit margin of **22.95%**, while **Dairy lags** with the lowest total cost of **0.25M** and **19.49%** profit margin.
2. **Current year revenue dropped by 21.3%** from **1.1M to 0.90M**, and cost reduced by **21.2%** from **0.9M to 0.72M**, keeping **profit % nearly flat at 24.8%** (down just 0.4% YoY).
3. **Revenue per day declined** from **3,119 in 2023** to **2,448 in 2024**, and **revenue per customer** fell from **2,277 to 1,792**, signaling a drop in both customer value and activity.
4. **Chittagong region** shows the highest revenue (darkest on map), while **Rajshahi** lags (lightest), indicating significant regional performance variation.

   ![Finance](https://github.com/user-attachments/assets/65142261-ecce-4c57-bde6-b3cc5cee60fa)




###  Customer Insights

* **RFM segmentation** to group customers by purchase behavior.
* Identifies **loyal customers**, **high spenders**, and **at-risk segments**.

###  Marketing Effectiveness

* Assesses success of **promotional campaigns**.
* Correlates **marketing efforts with sales performance** and customer acquisition.

---

## 📂 File Structure

```
/FMCG-Sales-Marketing-PowerBI
│
├── FMCG_Sales_Marketing.pbix       # Power BI report file
├── README.md                       # Project documentation
├── Data/                           # Cleaned CSV/Excel files (optional)
│
```

---

## 📬 Contact

If you have questions or feedback, feel free to reach out via [GitHub Issues](https://github.com/yourusername/FMCG-Sales-Marketing-PowerBI/issues) or connect with me on [LinkedIn](https://www.linkedin.com/in/yourname).

---

Let me know if you want help creating a thumbnail for your GitHub repository or writing a project summary for LinkedIn or your resume!
