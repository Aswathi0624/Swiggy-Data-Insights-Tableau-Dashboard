# Swiggy-Data-Insights-Tableau-Dashboard

## Project Overview
The Swiggy Data Analysis Dashboard is a comprehensive 5-page Tableau project designed to analyze restaurant data from multiple perspectives, including overall performance, location trends, restaurant success metrics, delivery efficiency, and pricing behavior.

This project transforms raw data into interactive visual insights, enabling users to explore patterns and make data-driven decisions.

## Objectives
- Analyze overall restaurant performance across different cities
- Identify top cities and locations with high restaurant concentration
- Evaluate delivery performance and its impact on customer satisfaction
- Examine the relationship between price and ratings
- Provide data-driven insights to support business decisions

## Dataset
- **File:** swiggy dataset.csv
- **Records:** 5,373 restaurants | 5,943 orders | 855,150 ratings  
- **Key Columns:**
  - Restaurant Name  
  - City / Area  
  - Food Type  
  - Price  
  - Delivery Time  
  - Ratings  

### Data Preparation
- Imported directly into Tableau  
- Cleaned and standardized using Tableau’s built-in data preparation tools  
- Derived KPIs:
  - **Total Restaurants**
  - **Total Orders**
  - **Average Delivery Time**
  - **Total Ratings**
  - **Average Ratings**

## Dashboards Features

### 1. **Swiggy Data Insights Dashboard**
- KPIs: Restaurants, Orders, Ratings, Delivery Time  
- City-wise restaurant distribution  
- Food type distribution (donut chart)  
- Ratings by city  
- Price distribution histogram  

### 2. **City & Location Insights**
- Orders by city (map visualization)  
- Top areas by restaurant count  
- City vs delivery time (pie chart)  
- Food preferences by city (tabular view)  

### 3. **Restaurant Performance**
- Top 10 vs Bottom 10 restaurant ratings  
- Price vs ratings (scatter plot)  
- Ratings vs food type (treemap)  
- Food type vs restaurants (bubble chart)  

### 4. **Delivery Performance Analysis**
- Avg delivery time by city  
- Delivery time distribution (histogram)  
- Delivery time vs ratings correlation  
- Fastest delivery cities ranking  
- Area-wise delivery data (table)  

### 5. **Price & Rating Analysis**
- Price vs ratings across Food Types (scatter plot)  
- Avg price by city  
- Price range vs rating (treemap)  
- Ratings distribution histogram  
- Avg ratings by food type  

##  Insights
- **Cuisine Trends:** Indian and Chinese dominate; while American and Seafood have limited presence.  
- **City Leaders:** Kolkata has the highest restaurant count; Hyderabad leads in ratings volume.  
- **Delivery Performance:** Average delivery time 54 minutes; Kolkata and Chennai are fastest.  
- **Price vs Ratings:** Higher-priced restaurants tend to score better, but most cluster below ₹500.  
- **Restaurant Benchmarking:** McDonald’s, Subway, and La Pino’z Pizza are top performers; weaker performers average below 3.0 ratings.  

## Tools & Technologies
### **Tableau Desktop / Tableau Public**
- Data visualization and dashboard creation
### **Features used**:
- Calculated Fields
- Interactive Filters
- KPI Cards
### **Charts** :
Bar, Scatter, Treemap, Bubble, Map, Histogram
### **CSV Dataset**
- Direct import into Tableau
- Fully cleaned and transformed within Tableau

## How to Use
- Open the Tableau workbook (.twbx file)
- Use filters (City, Area, Food Type, Restaurant)
- Navigate across all 5 dashboards
- Interact with visuals for deeper insights

## Applications
- Benchmarking restaurant performance  
- Understanding customer food preferences by city  
- Optimizing delivery operations  
- Aligning pricing strategies with customer ratings  


## Dashboard Previews

<img width="1281" height="719" alt="overview" src="https://github.com/user-attachments/assets/27dc151f-3229-4707-94e3-aadca7d7ef98" />

<img width="1286" height="721" alt="City and location insights" src="https://github.com/user-attachments/assets/9915aa55-c0bd-46d3-a004-1735f781190e" />

<img width="1278" height="716" alt="Restaurant Performances" src="https://github.com/user-attachments/assets/efcabb73-f868-4302-bdce-905e9df4a845" />

<img width="1375" height="770" alt="Delivery Performance analysis" src="https://github.com/user-attachments/assets/07bfcf50-6aae-40cc-8116-c15de9205ede" />

<img width="1271" height="718" alt="Price and Ratings analysis" src="https://github.com/user-attachments/assets/566d5e22-36a5-467b-bd25-63a3eb94d8fa" />
