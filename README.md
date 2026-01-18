# INDIAN-DOMESTIC-FLIGHT-ANALYSIS-
Business - focused airline data analysis project using AWS Athena and SQL delivering insights on routes , pricing and market dominance .
✈️ Indian Flight Data Analysis (SQL Project)
📌 Project Overview

This project analyzes Indian domestic flight data to uncover insights related to airline pricing, route demand, revenue potential, and airline performance.
The analysis is performed using AWS Athena and SQL, focusing on real-world business questions rather than dashboard-based visualization.

The goal of this project is to demonstrate end-to-end data analytics thinking, including data cleaning, exploratory analysis, and business insight generation.

🎯 Objectives

Identify high-revenue and high-demand flight routes

Analyze airline pricing behavior

Understand the impact of flight stops on ticket prices

Determine dominant airlines on major routes

Identify major aviation hub cities in India

Provide actionable business recommendations

🛠️ Tools & Technologies

AWS S3 – Data storage

AWS Athena – SQL querying and analysis

SQL – Data cleaning and business analysis

GitHub – Project documentation

📂 Dataset Description

The dataset contains Indian domestic flight information with the following key columns:

Airline

Date of Journey

Source City

Destination City

Route

Departure Time

Arrival Time

Total Stops

Price

Additional Information

🧹 Data Cleaning & Preparation

The following steps were performed before analysis:

Removed duplicate flight records

Handled missing values in route and stop-related columns

Standardized price values

Converted columns to appropriate data types

Validated outliers using the IQR method

Created final analytical tables for querying

These steps ensured data accuracy and reliability for business analysis.

📊 Business Questions Answered
1️⃣ Which routes generate the highest revenue potential?

Routes such as DEL → BOM → COK generate the highest revenue due to high flight frequency and higher average prices.

2️⃣ Which routes have the highest number of flights?

Metro-connected routes like BLR → DEL and CCU → BOM → BLR show the highest flight counts.

3️⃣ How does ticket price vary based on the number of stops?

Non-stop flights are the cheapest on average.

Flights with multiple stops are significantly more expensive.

4️⃣ Do connecting flights generate more revenue than non-stop flights?

Connecting flights generate higher total revenue due to higher average ticket prices.

5️⃣ Which airlines dominate high-demand routes?

Jet Airways and IndiGo dominate most high-demand routes.

6️⃣ How much does price vary across airlines for the same route?

Significant price variation exists among airlines operating on identical routes.

7️⃣ Which cities act as major aviation hubs?

Delhi, Bangalore, and Kolkata act as major aviation hubs with the highest traffic.

8️⃣ Which airline provides the best value for money?

IndiGo offers the best balance of lower average prices and high route coverage.

9️⃣ Are higher prices associated with specific routes?

Routes involving multiple metro connections tend to have higher prices.

🔟 What overall trends are observed?

Metro connectivity strongly drives demand

Route frequency impacts revenue

Airline dominance is linked to network strength

📈 Key Business Insights

Revenue potential depends on both flight volume and pricing

High-demand routes are dominated by a few major airlines

Connecting flights contribute more to revenue than non-stop flights

Pricing strategies vary significantly across airlines

💡 Business Recommendations

Increase capacity on high-revenue routes

Optimize pricing strategies for connecting flights

Strengthen presence on metro-based routes

Apply competitive pricing on shared routes

Focus expansion efforts on major hub cities

📌 Conclusion

This project demonstrates how SQL-driven analysis using AWS Athena can transform raw flight data into actionable business insights.
It highlights real-world data cleaning challenges, analytical thinking, and decision-oriented reporting without relying on dashboards.

🧠 Skills Demonstrated

SQL data analysis

Data cleaning and validation

Business problem solving

AWS Athena & S3 usage

Analytical reporting

📎 Project Structure
├── SQL_Queries/
│   ├── data_cleaning.sql
│   ├── business_analysis.sql
├── Report/
│   └── Indian_Flight_Data_Analysis_Report.pdf
├── README.md

👤 Author

Sanket Kankal
Aspiring Data Analyst

⭐ If you like this project, feel free to star the repository!
