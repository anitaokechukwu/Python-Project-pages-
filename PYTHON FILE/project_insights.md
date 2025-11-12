## Cookies Sales Order Data Analysis

## Objective:

A cookie-selling company wants to understand **customer performance, profitability, 
and sales trends** over time. The goal is to analyze transaction records to uncover 
**who their top customers are, when sales peak, and how costs impact profits**.

## Approach

- **Data Cleaning & Preparation**
    - Removed placeholder values (`XXXXXX`).
    - Split `Customer ID` and `Customer Name`.
    - Created new fields: `Profit`, `Month`, `Year`.
- **Profitability Analysis**
    - Calculated total profit for each customer.
    - Identified top customers by profit contribution.
- **Order Insights**
    - Average cookies shipped by order status (`Shipped` vs `Open`).
    - Revenue and profit distribution across customers.
- **Revenue Trends**
    - Monthly revenue trends from 2017–2020.
    - Yearly cost analysis to identify the year with the highest expenses.
    - Seasonal trends in revenue (monthly breakdown).
- **Customer Performance**
    - Ranked customers by total revenue generated.
    - Visualized top revenue-generating customers.

## Visualizations

- Bar charts of **customer revenue & profit**
- Pie chart of **average cookies shipped by order status**
- Line chart of **monthly revenue trends**
- Bar chart of **yearly cost analysis**

## Key Findings

- **Top Customer:** Cascade Grovers (≈ **2.25M revenue**)
- **Lowest Revenue Customer:** Acme Grocery Stores (≈ **542K**)
- **Year with Highest Cost:** 2018 (≈ **1.06M**)
- **Monthly Peak Revenue:** May (≈ **730K**)
- **Cookies Shipped:** Open orders shipped slightly more (≈551) than completed Shipped orders (≈520)

## Business Impact

- Helps identify **high-value customers** for loyalty programs.
- Seasonal insights (peak in **May**) can guide **inventory planning**.
- Cost trends reveal opportunities for **expense control**.
- Supports **customer performance tracking** for better decision-making.

## Tools Used

- **Python** – for data analysis and scripting
- **Pandas** – for data cleaning, transformation, grouping, and aggregation
- **Matplotlib** – for data visualization (bar charts, line plots, pie charts)
- **Jupyter Notebook** – for running and documenting the analysis interactively

## Conclusion

The analysis helped identify the **most valuable customers**,
**peak revenue periods**, and **cost-heavy years**.
These insights can support decision-making around **customer relationship management**,
**inventory planning**, and **cost control strategies**
