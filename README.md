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

1.**RFM analysis** categorized customers into Loyal, Potential Loyalist, and At Risk segments, churned and new customes

2.Marketing promotions boosted sales for Potential Loyalists by **15%**, validating the importance of targeted offers.

3.The top **20%** of customers accounted for a major share of total sales, reinforcing loyalty strategies.

![Customer](https://github.com/user-attachments/assets/22b4a33f-9320-454e-815d-bf832dfc0404)



###  Marketing Effectiveness

1.**Snacks**: Bundle offers drove a **110.6%** sales increase, capturing **85.9%** of total revenue.

2. **Personal Care**: Discounts led to a **214.4%** daily sales boost, maintaining **86.2%** revenue share.
 
3. **Beverages**: Promotions resulted in a **473.2%** rise in sales, though profits dropped by **27.84%**.
   
4. **Dairy**: Sales surged by **462.6%** under bundle offers, holding **73.1%** of total revenue.

![new_marketing](https://github.com/user-attachments/assets/89f5681d-fbab-45f7-9823-8055d28e1553)





### Problems

1.**Dhaka** is the **lowest  revenue** generating region ( Lowest number of customer and low  revenue per customer value)

2.**Beverage** has very **low sales per product** value in compare to it's number of products( Highest number of products in beverage category)

3.40-55 price range contributes most  both in revenue **(54%)** and sales quantity **(37%)**, but it provides very **low profit%** (especially in snacks)

4.**Low revenue per customer** generates in **online channel**, while profit% is also lower then other 2 channels

5.High number of lost customers **(19.40%)** and at risk customers **(24%)** who have high chance of becoming lost customers





### Recommendation

1.Dhaka has low % of loyal customer (**3%** less then overall) which impact the revenue as loyal customer's sales amount per order is high. **Convert potential loyal customer to loyal customer** by providing special offer  on high purchase amount

2.**Increase the stock of high selling product and decrease the stock of low selling product of beverage**. Introduce discount offer for beverage as discount offer .

3.**Proper pricing strategy (increase price/decrease cost) for high price product (40-55)** as it has lowest profit% although it provides highest revenue(specially for snacks and personal care item)

4.**Provide more discount offer reducing other offer in online channel as in online channel**, discount offer has highest profit%(32%) and highest sales quantity per order value(10)

5.**Introduce some new products of personal care** as though it has low product number, but it has highest profit%(37.3%) and highest sales revenue per product value($2896)

6.**Reconnect with lost and at risk customer** and provide special discount offer for high and mid range price product




