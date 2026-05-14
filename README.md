# restaurant-orders-analysis
A restaurant order dataset containing menu items and order details, with a custom-built Calendar table for time-based analysis — modelled in Power BI.
## 📌 About This Dataset

This dataset contains transactional order data from a restaurant,
structured for data analysis and visualization in Power BI.

## 🗂️ Dataset Overview

The data model consists of 3 tables:

- **menu_items** – Contains item-level details like category, 
  item name, and price.
- **order_details** – Fact table capturing quantity, cost category, 
  hour of order, and item references.
- **Calendar** – A custom-built date dimension table created 
  manually to enable time-based filtering, slicing, and 
  trend analysis across the dataset.

## 💡 Note on Calendar Table

The Calendar table was independently created and added to the 
data model to support time intelligence functions in Power BI. 
It serves as a dedicated date dimension linked to the 
order_details fact table.

## 🎯 Use Cases

- Sales trend analysis by date and hour
- Menu item performance tracking
- Category-wise revenue breakdown
- Peak hour identification
- Cost vs quantity insights

## 🛠️ Tools Used

- Power BI (Data Modelling & Visualization)
- SQL / Excel (Data Preparation)

## 📊 Schema

Star Schema — order_details as fact table,
menu_items and Calendar as dimension tables.
