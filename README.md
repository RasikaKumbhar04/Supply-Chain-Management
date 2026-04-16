# 📦 Supply Chain Management – Project (P1249)
🔗 [Supply Chain Management Dashboard Link](https://drive.google.com/file/d/1AHEWBn9WK-dwQ7i_P952tXibvjJRYFth/view?usp=drive_link) - **hosted externally due to file size constraints**

<p align = "center"><img width="1536" height="420" alt="image" src="https://github.com/user-attachments/assets/8a8f03d1-f2ba-439a-8643-f8b5fa2e869a" />

---

## Project Overview

End‑to‑end **Supply Chain & Retail Analytics** solution built using **Excel and Power BI**.

This project delivers a complete analytics framework for monitoring orders, revenue, cost, profit, inventory availability, and customer distribution across stores, regions, and product hierarchies. It covers data preparation, fact‑dimension modeling, dashboard development, and actionable supply chain insights.

## 📸 Dashboard Preview

<p align = "center"><img width="1536" height="580" alt="image" src="https://github.com/user-attachments/assets/c72e9fce-66e1-475c-b2d1-33d1fee71457" />

---

⭐ **Executive Summary**

This project demonstrates the full analytics lifecycle:

     ✅ Data Import → Cleaning → Transformation  
     ✅ Fact & Dimension Modeling (Retail Star Schema)  
     ✅ KPI Computation → Sales & Inventory Analysis  
     ✅ Power BI Dashboard Development  
     ✅ Action‑oriented Supply Chain Insights  

Designed as an industry‑ready BI project, it highlights strong skills in data modeling, KPI design, Power BI visualization, and analytical storytelling.

---

⭐ **Project Scope & Responsibilities**

1. Data Preparation & Cleaning
   
    - Imported multiple Excel datasets covering sales, inventory, products, stores, customers, and calendar data  
    - Cleaned missing values and standardized numeric, date, and categorical fields  
    - Ensured consistency across all fact and dimension tables  

2. Data Relationships & Modeling

   Developed a Retail Star Schema using the following tables:
        
          Fact Tables
          - `F_SALES`
          - `F_POINT_OF_SALE`
          - `F_INVENTORY_ADJUSTED`
          
          Dimension Tables
          - `D_PRODUCT`
          - `D_STORE`
          - `D_CUSTOMER`
          - `4_5_4_CALENDAR`
          - `D_GEOJSON_US_COUNTIES`
  
      Additionally, a consolidated Supply Chain View was used for reporting and KPI validation, ensuring accurate calculations and smooth dashboard interactions.

3. KPI Analysis & Computation

    Designed KPIs to track:

        - Total Orders  
        - Total Revenue  
        - Total Cost Amount  
        - Total Profit  
        - Profit %  
        - Quantity on Hand  
        - Unique Customers  

    All KPIs dynamically respond to slicers and filters.

4. Dashboard Development (Power BI)

    Key Dashboard Features
   
       ✅ Executive KPI cards (Orders, Revenue, Cost, Profit, Inventory, Customers)  
       ✅ Store‑wise & Region‑wise Revenue Analysis
       ✅ Profit by Store State  
       ✅ Revenue by Product Type  
       ✅ Inventory Status Classification  
            - In Stock  
            - At Risk  
            - Low Stock  
       ✅ Product‑level Quantity on Hand Indicators  
       ✅ Sales by Product Family (Treemap)
          
     Interactive Filters Included
   
        - Date  
        - Store Region & State  
        - Product Line & Product Family
        - Quantity on Hand

 5. Business Insights & Recommendations

        - Identified top‑performing stores, regions, and product families  
        - Highlighted low‑stock and at‑risk inventory items  
        - Analyzed revenue contribution by product type and geography  
        - Provided insights to support inventory replenishment and demand planning  

---

🛠️ **Tools & Technologies**

  - **Excel** – Source datasets  
  - **Power BI** – Data modeling, DAX measures, dashboarding  
  - **Power Query** – Data cleaning and transformation  

---

📁 **Project Files**

| Component            | Access / Details                        |
|---------------------|------------------------------------------|
| Power BI Dashboard  | 🔗 [Power BI dashboard link](https://drive.google.com/file/d/1AHEWBn9WK-dwQ7i_P952tXibvjJRYFth/view?usp=drive_link)              |
| Dataset Files       | Excel – Fact & Dimension Tables          |
| Dashboard Screenshot| Included in this repository              |

📌 *PBIX file is hosted externally due to file size constraints.*

---

🗂️ **Dataset Description**

| Dataset Name           | Purpose                                          |
|------------------------|--------------------------------------------------|
| `F_SALES`              | Sales transactions including revenue & quantity  |
| `F_POINT_OF_SALE`      | POS‑level transaction data                       |
| `F_INVENTORY_ADJUSTED` | Inventory quantities & stock adjustments         |
| `D_PRODUCT`            | Product details, categories, product families    |
| `D_STORE`              | Store details including region & state           |
| `D_CUSTOMER`           | Customer identifiers                             |
| `4_5_4_CALENDAR`       | Retail calendar for time‑based analysis          |
| `D_GEOJSON_US_COUNTIES`| Geographic mapping                               |
| `Supply Chain View`    | Consolidated reporting view                      |

---

🧱 **Data Model (Retail Star Schema)**

                          4_5_4_CALENDAR
                                │
                                │
        ------------------------------------------------
        |                     |                        |
     F_SALES          F_POINT_OF_SALE       F_INVENTORY_ADJUSTED
        |                     |                        |
        |                     |                        |
     D_PRODUCT            D_PRODUCT                 D_PRODUCT
        |
     D_STORE
        |
     D_CUSTOMER

---------

🔄 **Data Integration Workflow**

    - Excel Files → Power BI  
    - Power Query → Data Cleaning & Transformation  
    - Power BI Data Model → KPIs & Visual Layer  

✅ Closely aligned with real‑world supply chain BI workflows  

✅ Clean, efficient, and scalable design  

---

📈 **Key Business Insights**

1. Sales & Revenue Insights
   
    - Revenue contribution varies significantly across regions and stores  
    - Some high‑volume products show lower profitability  

2. Inventory Insights
   
    - *At Risk* and *Low Stock* products highlight replenishment priorities  
    - Inventory imbalance reveals potential stock‑out and overstock risks  

3. Product Performance Insights
   
    - Selected product families disproportionately contribute to total revenue  
    - Treemap analysis identifies slow‑moving categories  

4. Customer Insights
   
    - Customer demand is concentrated in specific regions and stores  
    - Unique customer metrics support demand distribution analysis  

---

🚀 **How to Use This Project**

- Power BI
  - Open the dashboard using the SharePoint link  
  - Refresh data if required  
  - Use slicers to explore insights by date, region, store, and product  

