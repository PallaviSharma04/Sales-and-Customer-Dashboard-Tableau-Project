# Sales and Customer Dashboard in Tableau
## Table of Contents
- [Project Overview](#project-overview)
- [Project Goals](#project-goals)
- [Tools & Technology](#tools-and-technology)
- [Analytical Approach](#analytical-approach)
- [Business Insights](#business-insights)
- [Recommendations](#business-recommendations)

## Project Overview
This project aims to analyze sales and customer performance for a retail business using interactive Tableau Dashboards. The *Sales Dashboard* and *Customer Dashboard* provides a comprehensive view of sales, profit, product performance and customer behaviour. The analysis cover data from 2020 to 2023. The dashboards include interactive filters for year, product categories and location, allowing users to explore trends dynamically and optimize business strategies. 

## Project Goals
- Identify key trends in sales and profit across different years and months.
- Analyze product performance to determine the most and least profitable subcategories.
- Evaluate regional sales trends to optimize business strategies.
- Understand customer behaviour to improve engagement and retention.
- Provide actionable recommendations to enhance profitability and sales growth.

## Tools and Technology
- **Tableau Public**: Used for creating interactive dashboards.
- **Data Source**: <a href ="https://github.com/PallaviSharma04/Sales-and-Customer-Dashboard-Tableau-Project/tree/main/Dataset"> Dataset </a>

## Analytical Approach
The analytical process for this project followed a structured approach, ensuring data accuracy, meaningful insights, and an intuitive user experience in Tableau. The key steps included:

**1. Connecting to Data** 
  - Imported raw CSV files into Tableau.

**2. Creating a Data Model**
  - Established relationships between tables, ensuring seamless data integration.

**3. Data Cleaning & Transformation**
  - Renamed tables and Ensured the data in the fields is of correct data type.

**4. Creating Calculated Fields & Parameters**
  
  - Developed custom calculations for Current Year, Previous Year, Current Year Sales/Profit/Quantity/Customers/Sales_per_customer/orders, Previous Year Sales/Profit/Quantity/Customers/Sales_per_customer/orders, % Difference Sales/Profit/Quantity/Customers/Sales_per_customer/orders, Min/Max Sales/Profit/Quantity/Customers/Sales_per_customer/orders, etc.
  - Implemented parameter for dynamic filtering by Year.

**5. Building Charts & Visualizations**
  
  - Designed interactive charts to represent Sales, Profit and Quantity Analysis with current year and previous year comparisons, Sub-Category Performance Analysis and Customer behaviour.

**6. Formatting & Enhancing Readability**

  - Refined visuals by removing unnecessary gridlines, lines and clutter.
  - Cleaned up axis labels and headers for better clarity.
  - Applied color coding to highlight key insights.
  - Enhanced tooltips for an informative, user friendly experience.

**7. Dashboard Development & User Experience**
  - Structured dashboard using containers for a clean layout.
  - Added legends, filters, and dynamic navigation to improve interactivity.
  - Incorporated icons and visual elements to enhance usability.

## Business Insights
The analysis provided by the dashboards( The interactive dashboard can be downloaded <a href="https://public.tableau.com/app/profile/pallavi.sharma4076/viz/SalesCustomerDashboard_17377065104000/SalesDashboard">here </a>) highlights the following key findings into the company's sales trends, profitability, customer behaviour and regional performance for **2023**:
### Sales Dashboard
**1. Key Metrics**:
- **Total Sales**: $733K (20.4% growth YoY)
- **Total Profit**: $93K (14.2% growth YoY)
- **Total Quantity Sold**: 12K units (26.8% growth YoY)

**2. Monthly Highlights**:
  - **Highest Sales**: November ($118K) ;
    **Lowest Sales**: February ($20K) 
  - **Highest Profit**: March ($15K) ;
    **Lowest Profit**: April ($1K) 
  - **Highest Units Sold**: November (1.8K units) ;
    **Lowest Units Sold**: February (0.4K units)

**3. Weekly Highlights**: 
  - **Week 48** in 2023 recorded the **highest weekly sales, reaching $36K**, which surpassed the average weekly sales of 2023($14K). On the other hand **Week 21** experienced the **lowest sales at $4.36K**, falling below the average.
  - **Week 12** achieved the **highest weekly profit ($9K)**, exceeding the year's average weekly profit of $2K, In contrast, **Week 16** experienced the **largest weekly loss ($3K)**.

**4. Subcategory Performance**:

  - **Top-Selling Subcategories**: Phones($105K), Chairs($96K), and Binders($73K).
  - **Most Profitable Subcategories**: Copiers($25K), Accessories($16K), and Phones($13K).
  - **Loss-Making Subcategories**: Tables, Machines, Suppliers, and Bookcases.

**5. Regional Insights**: 

  - In **Central**, **Eastern** **and Southern regions**, the most sold subcategories are **Chairs** and **Phones**.
  - In **Western region**, the most sold subcategories are **Copiers** and **Binders**.

**6. Yearly Trends (2020-2023)**:

  - Sales consistently peak in **Q4 (mostly November-December)**, while **February** consistently records the lowest sales across all years.
  - Profit trends generally **align with high-sales months**, except in **2023**, **where March had the highest profit**.
  - Across all years, **Phones** and **Chairs** remain the **most sold subcategories**.
  - In **2022 and 2023**, **Copiers and Accessories** were the **most profitable**, while **Tables** have been **consistently loss-making** across all years.

![Sales Dashboard](https://github.com/user-attachments/assets/874b8f4f-25e0-4d6d-8ecc-eb064b8355ce)

### Customer Dashboard
**1. Key Metrics**:

  - **Total Customers**: 693 (8.6% increase YoY)
  - **Average Sales per Customer**: $1,058 (10.8% increase YoY)
  - **Total Orders**: 1,687 (28.3% increase YoY)

**2. Monthly Trends**:

  - **November 2023** recorded the **highest customer activity with 216 customers** making purchases, while **February had the lowest customer count**.
  - **Order volume peaked in November**, aligning with the highest customer engagement, while **February had the fewest total orders**.
  - Customers **spent the most on average in January**, whereas **April saw the lowest average sales per customer**.


**3. Customer Order Trends**:

  - **Most common order frequency**: 1-2 orders per customer with 200 customers in each category.
  - **Least common order frequency**: 7-8 orders per customer with only 2 customers each.

**4. Top Customers (by Profit)**:

  - **Raymond Buch** was the **top customer by profit** in 2023, contributing $14,203 in sales and $6,780 in profit from 3 orders.


![Customer Dashboard](https://github.com/user-attachments/assets/9a71a60b-bea4-4a0a-a4c7-bb89d382c263)

## Business Recommendations
**1. Focus on Profitable Subcategories**:
  - Promote **Copiers, Phones and Accessories** as these are highly profitable.
  - Offer targeted discounts or marketing campaigns to further boost sales in these areas.

**2. Address Loss-Making Subcategories**: 
  - Investigate the reason behind the losses in **Tables, Machines, Suppliers and Bookcases**.
  - Consider revising pricing strategies, supplier contracts, or discontinuing consistently low-performing products like **Tables**.

**3. Leverage Regional Insights**:
  - Prioritize sales of **Phones and Chairs** in Central, Eastern and Southern regions.
  - Develop regional strategies to expand the market for **Copiers and Binders** in Western region.

**4. Customer Retention**:
  - Engage high-value customers like **Raymond Buch** with loyalty programs or exclusive offers.
  - Focus on converting customers with 1-2 orders into repeat buyers through promotions or subscription plans.

**5. Seasonal Planning**:
  - Increase marketing efforts in **Q4 (November-December)**, the **peak sales period**.
  - Develop targeted campains for **January,February & April**, historically **low-performing months**.
