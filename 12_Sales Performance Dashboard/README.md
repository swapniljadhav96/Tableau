# 🛍️ Sales & Distribution Dashboard  

This project demonstrates **data preparation, modeling, analysis, and visualization best practices**.  

---

## 🎯 Objective  
To create an **interactive Tableau dashboard** that provides insights into:  
- Sales performance vs monthly targets  
- Distributor-level achievements and gaps  
- Product category contribution to sales  
- Discounts, YoY growth, and order trends  
- Regional sales performance across India  

---

## 📂 Data Preparation & Modeling  
- Removed **duplicates** from `b2b_orders`  
- Handled **missing Product IDs** with calculated fields  
- Established proper **relationships/joins** between datasets  
- Built **Region → Distributor → Product hierarchy**  
- Ensured correct **granularity** at SKU and Distributor level  

---

## 🔑 KPIs  
- 💰 **Total Sales:** ₹21.2M  
- 🎯 **Total Target:** ₹16.8M  
- ✅ **Target Achievement:** 126.2%  
- 📈 **YoY Growth:** 2.80%  
- 💸 **Discount %:** 10.66%  
- 📦 **Total Orders:** 2,119  

---

## 📊 Dashboard Highlights  

### 1) Sales Performance  
- **Monthly Sales vs Target** bar chart  
- **Target Achievement %** calculated field  
- **Forecasted Sales Trend (13 months)** with seasonal patterns  

### 2) Product Analysis  
- **Sales by Product Category** (Pie chart) – Beauty & Personal Care, Food & Beverages, Home Care  
- **Category Trends** over time  

### 3) Distributor Analysis  
- **Top/Bottom Performers** ranked by Target Achievement %  
- Conditional formatting for under-performing distributors  

### 4) Discounts & Growth  
- **Discount %** and **Total Discounts applied** by SKU  
- **YoY Growth** metric with dynamic calculation  

### 5) Geo Analysis  
- **Map of India** with region-wise sales performance  
- Highlighted **regions below target**  
- Tooltip shows distributor-level sales  

---

## ⏱️ Time-Based Analysis  
- **MTD, QTD, YTD, WTD** filters using parameters  
- Correct handling of **financial years & week starts (Monday)**  

---

## ✨ Interactivity & Features  
- **Filters:** Region, Distributor, SKU, Date  
- **Parameters:** Switch between Sales, Achievement %, Growth %  
- **Dashboard Actions:** Highlight distributor on map → Drilldown into detail table  
- **Cascading Filters:** Region → Distributor → Product  

---

## ✅ Insights  
- Sales are **126% of target** (overachieved 🎉)  
- **Beauty & Personal Care** contributes the most (41%)  
- Some distributors achieved **5x target**, while others are underperforming  
- Discounts are **~10.6%**, requiring monitoring  
- **YoY growth is modest (2.8%)** → improvement opportunity  

---

## 🖼️ Dashboard Preview  
![](https://github.com/swapniljadhav96/Tableau/blob/main/12_Sales%20Performance%20Dashboard/Dashboard%20image.png)
