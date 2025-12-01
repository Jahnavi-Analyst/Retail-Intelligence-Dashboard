# **Retail Intelligence Dashboard – Category, Region & Target Analysis**

This project presents an interactive **Power BI dashboard** designed to offer a detailed view of retail performance across **categories, regions, and monthly targets**. It helps business users gain clear, actionable insights into sales trends, target achievements, and profitability patterns.



## **📌 Project Overview**

The **Retail Intelligence Dashboard** consolidates multiple business views into a single reporting solution. It provides insights into:

* **Category-wise sales & profit analysis**
* **Furniture monthly target (MoM) performance**
* **Regional sales & profit distribution across Indian states**
* **High-level navigation via a clean and interactive main menu**

The dashboard is designed for decision-makers to quickly spot trends, compare performance, and identify growth opportunities.



## **📊 Dashboard Pages & Insights**

### ### **1️⃣ Main Navigation Page**

A simple and elegant landing page providing easy navigation to:

* Category-Wise Analysis
* Furniture Target MoM Analysis
* Regional Sales & Profit Analysis



### **2️⃣ Category-Wise Sales and Profitability Analysis**

This section provides insights into performance across **Electronics, Clothing, and Furniture**.

#### **Key Insights**

* **Electronics** generates the **highest sales (₹165K)** but has a moderate profit margin of **6.35%**.
* **Clothing** achieves **₹139K in sales** with the **highest profit margin (8.03%)**, making it the most profitable category.
* **Furniture** has the **lowest sales (₹127K)** and a very low margin of **1.81%**, indicating underperformance.

#### **Visuals Included**

* Category slicer
* Total Sales, Profit & Margin KPIs
* Sales by Category (bar chart)
* Scatter chart for *Sales vs Profit Margin*
* Category performance table



### **3️⃣ Furniture Monthly Target (MoM) Analysis**

A detailed MoM breakdown of furniture targets with trend visualization.

#### **Key Insights**

* Monthly targets show a **general downward trend** after January.
* Some months display **more than 10% MoM variation**, suggesting seasonal adjustments or demand fluctuations.
* A **rolling average** approach is recommended for smoother target planning.

#### **Visuals Included**

* MoM % KPI
* Total Target KPI
* Month slicer
* Monthly Target Trend (line chart)
* Target vs MoM % (bar + line combo chart)
* Detailed Month-Year target table



### **4️⃣ Regional Sales and Profit Analysis**

Analyzes performance across multiple Indian states using map and bar chart visuals.

#### **Key Insights**

* Highlights the **top 5 states by order count**.
* Some states show **high sales but low margins**, indicating pricing or cost concerns.
* Others show **strong profit margins despite lower orders**, revealing potential growth opportunities.
* Madhya Pradesh and Maharashtra lead overall sales performance.

#### **Visuals Included**

* Profit Margin, Total Profit & Total Sales KPIs
* Top 5 States Table (Orders, Sales, Avg Profit)
* Sales by State – Choropleth Map
* Top 5 States Sales – Bar chart
* State slicer



## **🛠️ Tools & Technologies Used**

* **Power BI Desktop**
* Data Modeling (Star schema approach)
* DAX Measures for:

  * MoM %
  * Profit Margin %
  * Avg Profit per Order
  * Category-level aggregations
* Power BI visuals: bar charts, line charts, map visuals, slicers, KPIs, tables

