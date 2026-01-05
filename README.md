# Spice Odyssey & Co. Sales Analysis
 ---
## 🎯 Objective
Analyze and interpret Spice Odyssey Restaurant & Co. Sales data to uncover actionable insights that drive customer engagement, menu & product optimization, targeted marketing, inventory & operational planning.
### **Project Purpose:**
  * To analyze restaurant sales data and uncover ordering patterns, customer preferences, and revenue drivers.
  * To support data-driven decisions for menu optimization, pricing strategy, and operational planning.
### **Key KPIs:**
  * Total Orders: 5K
  * Total Sales:  ~160K
  * Average Price: ~13.16
  * Average Order Value (AOV): ~29.27
### **Deliverables:**
  * Interactive Power BI dashboard
  * Actionable business insights
  * Strategic recommendations for menu & operations
---

## 📘 Project Overview 
### **Context Highlights:**
  * Kevaro Athletics, a global sports organization, maintains a diverse selection pool of 50 athletes representing 11 countries and multiple sporting disciplines.
  * This project evaluates the balance and fairness of gender participation and salary distribution, reflecting organizational commitment toward inclusivity and performance-based equity.


### **Context Highlights:**
  * This project analyzes sales data for Spice Odyssey Restaurant & Co., a multi-cuisine restaurant brand, to provide a holistic view of business performance and customer behavior.
  * The analysis helps Spice Odyssey’s marketing and product teams understand:
    * The restaurant operates across multiple cuisine categories — Asian, Mexican, Italian, and American.
    * Sales performance varies by weekday, meal type, and time of day.
    * Stakeholders lacked a centralized analytics solution to:
        * Monitor overall performance.
        * Identify demand patterns.
        * Uncover revenue and growth opportunities.
  * This analysis consolidates raw transactional data into a single, interactive Power BI dashboard, enabling faster insights and more informed strategic decisions.
---
 
## 🗂️ Data Overview & Schema     
### **Data Source:**  
  * **Source:** Internal restaurant transactional sales dataset (simulated business data for analytics use case)
  * **Data Type:** Structured, row-level order transaction data
  * **Time Period:** January 2023 – December 2023

### **Data Structure & Metrics:** 
  * **Key Index Types:** Order ID, Order Date, Order Hour, Weekday Order Number, Item Name
  * **Total Rows:** ~5,000 order-level records
  * **Categories:**
    * Cuisine Category: Asian, Mexican, Italian, American
    * Meal Type: Breakfast, Lunch, Dinner, Late Night
    * Time Dimensions: Month, Weekday, Hour
  * **Calculated Metrics:**
    * Total Orders
    * Total Sales
    * Average Price
    * Average Order Value (AOV)
---
 
## 💻 Tech Stack    
### **Tools:**
  * **Excel**
      * Data validation & exploratory analysis
  * **PowerQuery**
      * ETL transformations
  * **PowerBI**
      * Visualization, DAX measures & dashboard design
      * DAX – Calculated measures and time intelligence
  * **PowerPoint**
      * Presentation and final dashboard snapshots
---
        
## 📈 Methodology & Analysis  
### **Prepare, Process & Analytical Approach:** 
  * **Data Preparation & Cleaning:**
    * Imported raw restaurant sales data & verified column consistency (Order Date, Order Time, Category, Item Name, Price).
    * Performed data quality checks: Missing values, Duplicate Order_Details_ID, Invalid or inconsistent price entries.
    * Standardized date and time formats & ensured category and item naming consistency for downstream BI usage.
  * **Data Modeling & Integration:**
    * Imported the cleaned Excel dataset into Power BI.
    * Used a single-table, flat data model for performance and simplicity.
    * Created logical analytical groupings: Order Date → Month, Weekday, Order Time → Order Hour, Category → Item hierarchy.
    * Enabled dynamic slicing by: Item Category, Meal Type, Weekday Order Number.
  * **Feature Engineering:**
    * Created derived columns using Excel + Power BI: Order Month, Weekday Order Number (for correct weekday sorting), Meal Type classification based on order time.
    * Developed key DAX measures: Total Orders, Total Sales, Average Price, Average Order Value (AOV).
  * **Visualization Design:**
    * Designed KPI cards for quick executive-level insights.
    * Optimized visual hierarchy for business storytelling and decision-making.
  * **Validation & Formatting:**
    * Validated slicer interactions across all visuals.
    * Finalized dashboard for presentation and stakeholder consumption.
---
 
## ❓ Problem Statement     
Restaurants generate large volumes of transactional data across orders, menu items, cuisines, meal times, and days of operation. However, without structured analysis, it becomes difficult to identify: Best cuisine categories, Peak order placement periods, Top revenue-generating menu items, Ordering behavior variation by time and meal type. This project analyzes Spice Odyssey Restaurant & Co.’s sales data to uncover actionable insights that support menu optimization, operational planning, and revenue growth.

### **Key Questions:**
  * Which cuisine category receives the highest number of orders?
  * How do orders and sales vary across weekdays and time?
  * Which cuisines and items drive the most revenue?
  * What patterns define high-value customer orders?
---

## 💡 Key Insights
### **Top Findings:** 
  * Asian cuisine is the most ordered category.
  * Dinner time contributes the highest share of orders (~60%).
  * Lunch and dinner hours (12 PM & 5–7 PM) generate peak revenue.
  * Premium items like Tofu Pad Thai and Steak Torta drive higher sales.

### **Supporting Metrics:**
  * Asian category: ~2.6K orders
  * Dinner orders: ~60.6% of total
  * Peak weekday demand: Monday & Friday
  * Highest-selling item: Tofu Pad Thai (~8.1K sales)
---
 
## 📍 Conclusion
### **Summary:** 
 * The analysis reveals that customer demand at Spice Odyssey Restaurant & Co. is highly influenced by cuisine type, meal timing, and ordering patterns across the week. Certain cuisines consistently outperform others in both order volume and revenue contribution, indicating clear customer preferences.

 * Asian and Mexican cuisines emerge as the strongest growth drivers, leading in total orders and maintaining competitive average prices. These categories present significant opportunities for menu expansion, promotional focus, and inventory prioritization.

 * High-value orders are primarily concentrated during peak meal hours—especially lunch and dinner periods—and are associated with premium or popular menu items. This highlights the importance of aligning pricing strategies, staffing, and promotional efforts with high-traffic time windows.

 * The interactive Power BI dashboard provides a centralized, real-time view of restaurant performance, enabling management to:
   * Monitor sales and order trends dynamically.
   * Identify high-performing cuisines and items.
   * Optimize menu strategy and operational planning.
   * Make faster, data-driven business decisions.

---

## 🖥️ Dashboard Overview
![image alt](https://github.com/Cnik1710/Spice-Odyssey-Co.-Sales-Analysis/blob/180389131830c4f6f2fed3b722dfacc92c4a7943/04.%20Spice%20Odyssey%20Restaurant%20%26%20Co.%20Sales%20Analysis%20Dashboard.png)

---

## ✅ Business Impact & Use Cases   
  * By identifying top-performing cuisines and high-value menu items, the dashboard supports revenue optimization through informed pricing, bundling, and promotional strategies. Category-level demand insights highlight strong growth opportunities in Asian and Mexican cuisines, guiding menu expansion and product development decisions.

  * Operational efficiency is enhanced through analysis of peak ordering hours and meal-type trends, enabling improved staff scheduling, inventory planning, and kitchen workload management. Marketing teams can leverage weekday and time-based demand patterns to design targeted campaigns such as lunch offers, dinner combos, and weekday-specific promotions.

  * The centralized Power BI dashboard replaces manual reporting, allowing leadership to track daily, weekly, and monthly performance in real time. This ensures faster insights, consistent reporting, and better strategic planning across the organization.

  * Primary Use Cases
    * Restaurant Management: Monitor performance trends and optimize operations to improve profitability.
    * Menu & Product Teams: Identify high-demand and underperforming items to guide menu strategy.
    * Marketing Teams: Launch targeted, time-based promotional campaigns.
    * Operations & Supply Chain: Align staffing and ingredient procurement with demand patterns.
    * Leadership & Stakeholders: Drive strategic decisions using reliable KPIs and visual insights.
---
 
 ## 🙏 Acknowledgements & Contact 
 ### Project Analyst: Anik Chakraborty	
   📧 Email: anikc1710@gmail.com  
 ### Special Thanks To: 
   * Coding Ninjas – for project framework and guidance  
   
