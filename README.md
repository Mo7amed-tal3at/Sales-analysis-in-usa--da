# Sales Analysis in USA 


## Project Overview 

Retail businesses operate in a highly dynamic environment where performance varies across regions, products, customer types, and time. To remain competitive and profitable, it's essential to track **key performance indicators** such as **Sales**, **Profit**, and **Order Quantity** in a timely and organized way.

Insights and recommendations are provided on the following key areas:

  1. **Regional Performance Over Time**  
     - Comparison of **Sales**, **Profit**, and **Order Quantity** across **Central, East, South, and West** regions.
     - Year-over-year (YoY) analysis to highlight areas of growth and decline.
  
  2. **Sales and Profit Trends**  
     - Tracking performance metrics annually to understand business momentum.
     - Identifying patterns such as revenue drops with simultaneous profit growth, indicating cost efficiency improvements.
  
  3. **Customer Segmentation**  
     - Analysis of **Consumer**, **Corporate**, and **Home Office** segments based on order volume and profitability.
     - Insights to drive targeted marketing and loyalty programs.
  
  4. **Shipping Mode Impact**  
     - Evaluating performance across shipping types (Standard, Second Class, First Class, Same Day).
  
  5. **Discount Analysis**  
     - Measuring how discounts affect sales and profitability.
  
  6. **City-Level Profitability**  
     - Identifying **cities with negative profit** to guide location-specific strategy adjustments.

  
  7. **Year-over-Year Performance Comparison**  
     - Enabling quick insight into how each metric has evolved compared to the previous year, to support strategic planning.



By making regional and metric-specific performance instantly accessible, the dashboard supports better planning, strategic decision-making, and performance optimization at both regional and national levels.

### Interactive Dashboard
An interactive Power BI dashboard is available for download [**here**](https://github.com/Mo7amed-tal3at/Sales-analysis-in-usa--da/blob/main/Sales.pbix).

## Data Structure
Below is an image that shows the structure of the data and the relation among entities - 
![image](https://github.com/user-attachments/assets/62320912-63b3-407a-b6a4-a725807c6c8c)

## Executive Summary 

## 📋 Executive Summary

This project presents an interactive Power BI dashboard designed to monitor and analyze sales performance across multiple regions. It allows users to switch between key metrics—**Sales**, **Profit**, and **Order Quantity**—while comparing current year (CY) performance with the previous year (PY). The dashboard also explores customer segments, shipping preferences, and discount patterns, offering a comprehensive view of business operations.

It is intended to assist sales managers, analysts, and executives in identifying opportunities, reducing losses, and making data-informed decisions.

---

### Overview of Findings

- **Sales and Profit by Region**:  
  The **East** and **West** regions outperformed others in both profit and sales. The **South** region reported the lowest figures, highlighting a potential area for growth or intervention.

- **YoY Performance**:  
  The overall **Year-over-Year (YoY)** performance showed a **total raisein sales and profit**.

- **Customer Segments**:  
  The **Consumer** segment generated the largest number of orders, followed by **Corporate** clients. This pattern is useful for targeted promotions and loyalty strategies.

- **Shipping Modes**:  
  Most orders were made using **Standard Class**, while **Same Day shipping** was the least used—likely due to higher cost or limited availability.

- **Discount Analysis**:  
  From **5,026 total orders**, around **59.1%** included at least one item with a discount. Monitoring discount impact on profit is essential for future pricing strategy.

- **Negative Profit Cities**:  
  Cities like **Philadelphia**, **Houston**, and **San Antonio** reported significant losses, calling for a deeper review of pricing, shipping costs, or local demand in those areas.

Below is the Overview Page from PowerBI dashboard. The entire interactive dashboard can be downloaded [**here**](https://github.com/Mo7amed-tal3at/Sales-analysis-in-usa--da/blob/main/Sales.pbix).
  
  ![image](https://github.com/user-attachments/assets/9976b877-9ac7-4c5b-b7b8-9e41ec8443ba)

## Deep Dive – Insights

This section presents a detailed breakdown of the key insights extracted from the dataset.
### Business performance by region over years :

  - #### Year 2022:

      - **Central**:  
        Sales saw a slight decline of **1%**, while **Profit** surged by **+2072%**, and **Order Quantity** increased by **+5%**.
      
      - **East**:  
        Strong performance with **+21% growth in Sales**, **+24% in Profit**, and **+19% in Quantity**, indicating solid demand and improved margins.
      
      - **South**:  
        Underperformed across all metrics—**Sales declined by 31%**, **Profit dropped by 30%**, while **Quantity** saw a modest **+1% increase**.
      
      - **West**:  
        Experienced a **5% drop in Sales**, a slight **+2% increase in Profit**, and a **4% decrease in Quantity**.
      
      > 🔎 **Overall (2022 vs. 2021)**:  
      Total **Sales declined by 3%**, but **Profit increased by 24%**, and **Order Quantity** grew by **5%**, reflecting more efficient operations despite revenue loss.

  - #### Year 2023:

    - **Central**:  
      Sales increased by **43%**, **Profit** rose by **70%**, and **Order Quantity** grew by **30%**—reflecting strong overall growth and improved operational efficiency.
    
    - **East**:  
      Sales increased by **16%**, while **Profit** slightly declined by **4%**. However, **Quantity** rose by **20%**, suggesting rising demand but possibly tighter margins.
    
    - **South**:  
      Sales grew by **31%**, and **Profit** jumped significantly by **113%**, with a **20% increase in Quantity**. This indicates a major profitability recovery in the region.
    
    - **West**:  
      Experienced a **34% increase in Sales**, a **17% rise in Profit**, and a **24% increase in Quantity**—confirming consistent performance across all KPIs.
    
    > 🔎 **Overall (2023 vs. 2022)**:  
    Total **Sales increased by 30%**, **Profit improved by 33%**, and **Order Quantity** rose by **23%**, showing significant company-wide growth across all regions.



  - #### Year 2024:

      - **Central**:  
        Sales remained almost flat (**0% change**), while **Profit** dropped sharply by **-62%**, despite a **22% increase in Quantity**. This indicates rising volume but possibly lower pricing or increased costs.
      
      - **East**:  
        Strong performance with **+18% growth in Sales**, **+65% increase in Profit**, and a **20% rise in Quantity**—showing healthy demand and improved margins.
      
      - **South**:  
        Sales dropped by **-31%**, and **Profit** decreased by **-50%**, although **Quantity** still rose by **+19%**. This suggests unprofitable sales or high cost-to-serve in this region.
      
      - **West**:  
        Outstanding performance with **+33% increase in Sales**, **+82% in Profit**, and a **41% growth in Quantity**, making it the top-performing region in 2024 across all metrics.
      
      > 🔎 **Overall (2024 vs. 2023)**:  
      Total **Sales increased by 20%**, **Profit rose by 14%**, and **Order Quantity** jumped by **27%**, showing strong year-over-year growth, especially driven by East and West regions.
      
         

    - ![image](https://github.com/user-attachments/assets/6d41d259-1e35-4076-8dcf-9efc8afbc07d)
      
### 🎯 Customer Segmentation – Deep Dive

The dataset includes three main customer segments: **Consumer**, **Corporate**, and **Home Office**.

- The **Consumer segment** accounts for the largest number of orders, making it the most active and possibly the most valuable group in terms of revenue generation.

- The **Corporate segment** follows with a moderate order volume, indicating a stable B2B (business-to-business) base that may require different pricing or service models.

- The **Home Office segment** has the lowest number of orders, suggesting a smaller yet potentially niche customer group that could benefit from targeted offers.

🔍 **Insight**:  
Despite high order volumes from the Consumer segment, it's crucial to evaluate **profitability per segment**—as higher volume doesn't always equal higher profit. Strategic campaigns such as loyalty programs for Consumers and personalized service for Corporate clients can help maximize retention and revenue across segments.
  ![image](https://github.com/user-attachments/assets/ba987a82-43f9-449e-8a18-1c722a978426)

###  Shipping Mode Impact – Deep Dive

The dataset includes four shipping modes: **Standard Class**, **Second Class**, **First Class**, and **Same Day**.

- **Standard Class** is the most frequently used mode, likely due to its affordability and wide availability.
- **Second Class** and **First Class** have moderate usage, offering a balance between cost and delivery speed.
- **Same Day** shipping has the lowest usage, possibly due to higher delivery costs or limited service coverage.

 **Insight**:  
Despite the popularity of Standard Class, it's important to assess its profitability. If Same Day or First Class modes lead to better customer satisfaction and higher order value, promoting them strategically could enhance both revenue and loyalty.

---

### Discount Analysis – Deep Dive

Out of a total of **5,026 orders**, approximately **59.1%** included at least one product with a discount.

- Discounts are widely used across all segments, but their effectiveness varies.
- While discounts may increase sales volume, they can significantly erode profit margins if not carefully managed.

 **Insight**:  
A high discount rate does not necessarily correlate with higher profit. Implementing **smart discount strategies**—targeted by segment, region, or order size—can improve margins without sacrificing volume.

---

### City-Level Profitability – Deep Dive

Some cities consistently report **negative profit**, including:

- **Philadelphia**
- **Houston**
- **San Antonio**

These cities contribute to revenue but do so at a loss—likely due to high discounting, elevated shipping costs, or low-margin product categories.

 **Insight**:  
It's critical to investigate why these cities are unprofitable. Adjusting pricing strategies, reducing shipping costs, or re-evaluating marketing efforts in these areas can convert losses into gains.

  ##  Recommendations

1. **Regional Performance**  
   - Focus retention and marketing strategies in underperforming regions like **South** and **Central**, while continuing to support growth in **East** and **West**.

2. **Customer Segmentation**  
   - Maintain loyalty programs for the high-volume **Consumer** segment.  
   - Explore customized B2B offers for **Corporate** clients.  
   - Consider targeted promotions to increase engagement from **Home Office** customers.

3. **Shipping Mode Impact**  
   - Review cost-to-profit ratio for **Same Day** and **First Class** shipping.  
   - Promote higher-value shipping where feasible to improve satisfaction and margin.

4. **Discount Strategy**  
   - Reduce blanket discounts; shift to **targeted, data-driven offers** by region or segment.  
   - Monitor discount impact on **profitability**, not just sales volume.

5. **City-Level Profitability**  
   - Investigate causes of losses in cities like **Philadelphia**, **Houston**, and **San Antonio**.  
   - Adjust pricing, reduce discounting, or optimize delivery routes in those areas.


