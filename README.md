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

- Sales trend analysis by AOV and number of weeks
- Menu item performance tracking
- Category-wise revenue breakdown
- Peak hour identification
- Cost vs quantity insights

## 🛠️ Tools Used

- Power BI (Data Modelling & Visualization)
  
 Business Insights Possible
📈 Sales Analysis
✅ Total revenue by day / week / month
✅ Revenue growth trend over time
✅ Best performing sales period
✅ Slowest sales period identification
🍕 Menu Performance
✅ Top 10 best selling menu items
✅ Bottom 10 least selling menu items
✅ Most profitable food category
✅ Least ordered items 
✅ Price vs quantity relationship
⏰ Time Based Analysis
✅ Peak ordering hours in a day
✅ Busiest day of the week
✅ Seasonal trends by month
✅ Off peak hours identification
✅ Hour wise revenue breakdown
💰 Cost Analysis
✅ High cost vs low cost orders
✅ Average order value
✅ Cost category distribution
✅ Revenue per order analysis

📌  Overall Summary
This restaurant dataset is a well-structured Star Schema
model that enables deep analysis of:

🍽️  Menu Performance
📅  Time Based Trends
💰  Revenue & Cost Patterns
⏰  Peak Hour Identification

The custom Calendar table adds powerful time intelligence
capabilities making this dataset ideal for building
professional Power BI dashboards and deriving
actionable business insights for restaurant management.
