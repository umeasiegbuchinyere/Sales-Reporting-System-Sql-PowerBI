# Sales-Reporting-System-Sql-PowerBI

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/96228135-d409-464c-bbbe-a22065a480a9" />


# Table of Content
- [Project Overview](Project-Overview)
- [Data Source](Data-Source)
- [Problem Statement](Problem-Statement)
- [Tools Used](Tools-Used)
- [Skills Demonstrated and Data Analysis](Skills-Demonstrated-and-Data-Analysis) 
- [Visualisations](Visualisations)
- [Insights from Analysis](Insights-from-Analysis)
- [Conclusion and Recommendations](Conclusion-and-Recommendations)


# Project Overview
The Sales Reporting System is a data-driven solution designed to help businesses track, analyze, and visualize their sales performance. The project leverages PostgreSQL for 
database management and Power BI for interactive reporting, providing stakeholders with actionable insights for strategic decision-making.

# Data Source
The dataset used in this project was synthetically generated to simulate real-world sales transactions.
It contains:

- Customer data – 5 unique customers with names, IDs, and locations.
- Product data – 7 products with categories, prices, and IDs.
- Order data – 35 orders including products purchased, customers, and quantities.

This data was manually created and inserted into a PostgreSQL database to demonstrate the complete workflow—from database creation and querying to interactive reporting in Power BI.

# Problem Statement
Businesses often store sales records but lack a streamlined way to analyze them for decision-making. Without clear visibility into customer purchasing patterns, top-selling products, 
and sales trends, opportunities for growth and optimization are missed. This project addresses the need for a centralized Sales Reporting System that organizes data in PostgreSQL and
delivers actionable insights through Power BI dashboards.

# Tools Used
- PostgreSQL – Database creation, management, and querying.
- pgAdmin – Interface for managing the PostgreSQL database.
- SQL – Data definition, manipulation, and analysis queries.
- Power BI – Data visualization and interactive dashboard creation.

# Skills Demonstrated and Data Analysis




- ## Created Tables
<img width="664" height="288" alt="sill 30" src="https://github.com/user-attachments/assets/c9e19673-b33e-42f6-b668-302c66e82e28" />







- ## Inserted into the Tables


<img width="751" height="510" alt="skill 20" src="https://github.com/user-attachments/assets/c986c9ef-0a91-467b-910e-67a497a5ed34" />







- ## Combined tables thereby creating a relationship


   <img width="703" height="826" alt="skill 9" src="https://github.com/user-attachments/assets/12d97a97-197c-4a00-a5fb-4f14c61a447b" />







- ## Aggregated data and created view for virtual disposition as a table


   <img width="599" height="497" alt="skill 50" src="https://github.com/user-attachments/assets/e95d5764-b42c-4594-8424-82f6da6f2a3b" />


  # Visualisations

  A Comprehensive dashboard was developed using Power BI for interactive insight into the sales Report.

  Slicer Application: Slicers were added via Visualisation > Filter by fields such as Customers.


 <img width="987" height="558" alt="dashboard" src="https://github.com/user-attachments/assets/638a4e86-1b4e-47af-a320-2d27f0770f02" />




# Insights from Analysis

1.   Top Products by Price:

   - Laptop is the most expensive product at $800 per unit.
   - Earpod is the least expensive at $100 per unit.

2.   Customer Spending Patterns:

   - Customers are purchasing a variety of products, with Glory Bendo and Alice Smith appearing multiple times in the dataset.
   - High-ticket items like laptops and smartphones contribute significantly to total revenue.

3.   Order Quantities:

   - Large quantity orders include items like Earpods (6 units by Blessing Ike) and Handsets (5 units by Glory Bendo).
   - Smaller, high-value purchases like laptops (1 unit by Alice Smith) also impact revenue significantly.

4.   Revenue Drivers:

   - Revenue is driven by both high-price low-quantity sales (e.g., laptops) and low-price high-quantity sales (e.g., earpods, handsets).
   - This indicates a mixed sales strategy with both premium and volume products contributing to performance.


# Conclusion and Recommendations

Conclusion

The sales data reveals variations in performance across customers and products. While certain products maintain consistent demand, others show low sales, indicating a possible 
lack of market fit or insufficient promotion. Customer buying patterns suggest that a small group of customers contributes significantly to overall revenue, signaling a dependency 
risk if those customers reduce orders. Seasonal or periodic spikes indicate opportunities for targeted marketing during peak demand periods.

Recommendations

-   Focus on High-Performing Products:Allocate more marketing and inventory resources to products with strong sales trends.

-   Improve Low-Performing Products: Investigate causes of low sales—pricing, quality, awareness—and take corrective measures.

-   Diversify Customer Base: Reduce reliance on top customers by expanding outreach and acquiring new buyers.

-   Leverage Seasonal Demand: Create promotional campaigns ahead of identified peak sales periods.

-   Data-Driven Stock Planning: Use historical sales trends to optimize inventory levels and prevent overstock or shortages.



  




 











