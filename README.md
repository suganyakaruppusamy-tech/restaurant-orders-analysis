# 🍽️ Restaurant Sales Analysis in Power BI

## 📌 Project Review
In today’s competitive food and restaurant industry, data analysis is crucial for understanding customer preferences, improving sales performance, and making better business decisions.  
This project transforms raw restaurant transaction data into interactive dashboards using **Microsoft Power BI**, uncovering insights on menu effectiveness, customer behavior, and operational trends.

---

## 🎯 Objectives
- Analyze restaurant sales and customer ordering behavior.  
- Identify most and least ordered menu items.  
- Evaluate category‑wise performance.  
- Monitor and optimize weekly Average Order Value (AOV).  
- Detect risky items and best performers by price and quantity.  
- Analyze spend tier contribution across time of day.  

---

## 📊 Data Information
- **Source**: Maven Analytics  
- **Timeline**: 2023  
- **Size**: 10,000+ rows, 7 columns  
- **Domain**: Foods & Beverages  

---

## 🛠️ Tools & Technologies Used
- **Excel** → Initial data cleaning  
- **Power BI (Power Query)** → Data modeling, transformations, and dashboard creation  

---

## 🧹 Data Preprocessing
- Handled missing values (Mean, Median, Mode).  
- Removed duplicates.  
- Corrected and standardized data types.  
- Renamed columns for readability.  

---

## 🔄 Data Transformation
- Created calculated columns and tables.  
- Derived KPIs:  
  - Total Revenue  
  - Total Orders  
  - Total Items Sold  
  - Average Order Value  

---

## 🗂️ Data Model
- **Tables**:  
  - `menu_items` (catalog: category, item_name, price)  
  - `order_details` (fact table: quantity, cost, hour, item_id)  
  - `calendar` (date dimension)  
- **Relationships**:  
  - `menu_items → order_details` (1:*)  
  - `calendar → order_details` (1:*)  
- **Design Pattern**: Classic **Star Schema**  

---

## 📈 Dashboard Features
- KPI cards for revenue, orders, and AOV.  
- Bar charts, pie charts, and line charts for trends.  
- Heatmap for peak ordering times.  
- Tree map for customer spend segmentation.  
- Scatter plot for risky vs. best‑performing items.  

---

## 🖼️ Dashboard Preview
<img width="940" height="566" alt="image" src="https://github.com/user-attachments/assets/69c6e27b-d6f9-4eae-89e4-8d9037ea37e2" />


---

## 🔑 Key Insights
- **Top Items**: Hamburger (759), Edamame (620), Korean Beef Bowl (588).  
- **Least Ordered**: Hot Dog (257), Fettuccine Alfredo (249), Chicken Tacos (123).  
- **Cuisine Performance**: Italian ($49,462.7) and Asian ($46,720.65) lead revenue.  
- **AOV Trend**: Stable around $29.5–30.5, peak at Week 9 ($32.05).  
- **Peak Hours**: Lunch (12–1 PM) and Dinner (5–6 PM).  
- **Customer Segmentation**: Regular spenders ($20–$49) dominate, Dinner is prime revenue window.  

---

## 🏁 Conclusion
This project highlights clear customer behavior patterns:  
- Italian and Asian cuisines dominate sales.  
- Lunch and dinner are peak demand periods.  
- Regular spenders drive consistent revenue.  
- Low‑performing items need repositioning or promotions.
- 
By leveraging these insights, restaurants can optimize menus, pricing, promotions, and operations to improve profitability and customer satisfaction.
