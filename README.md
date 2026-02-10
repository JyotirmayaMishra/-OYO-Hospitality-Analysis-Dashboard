<p align="center">
  <img src="oyo-logo.png" alt="oyo logo" width="200"/>
</p>

# -OYO-Hospitality-Analysis-Dashboard 📊
OYO Hospitality Analysis Dashboard analyzes city-wise booking trends, revenue, and cancellation behavior using SQL, Excel, and Power BI, enabling data-driven insights for improving pricing and booking performance.
______________________

## Project Overview

This project analyzes hotel booking data from OYO to understand booking trends, revenue patterns, cancellation behavior, and city-wise performance. The analysis aims to identify key factors affecting booking volume, average revenue per booking, and stay conversion rates across different locations.

Using SQL for data aggregation, Excel for data validation, and Power BI for visualization, raw booking data is transformed into actionable insights. City-level analysis highlights variations in demand and pricing, showing that high booking volumes do not always correspond to higher revenue. Cancellation trends are examined to identify revenue leakage and operational inefficiencies.

An interactive Power BI dashboard enables dynamic exploration of key metrics such as total bookings, average booking amount, stayed percentage, and cancellation rate, helping stakeholders make data-driven decisions to optimize pricing strategies and improve overall business performance.

______________________
## Business Insights
- Gurgaon has the highest booking volume, while Mumbai generates the highest average revenue per booking.
- Delhi and Noida show high cancellation rates, indicating revenue leakage.
- Pune has the lowest cancellation rate, showing strong booking quality.
- High volume does not always translate to high revenue.

  _______________________

  ## 📊 OYO Dashboard
![dashboard](dashboard.png)

This dashboard provides a city-wise analysis of OYO hotel bookings, highlighting booking volume, average booking amount, stayed percentage, and cancellation rates. It helps identify high-performing cities, revenue patterns, and areas of booking loss for data-driven decision-making.
____________________

## Tools Used
- SQL (MySQL)
- Power BI
- Excel

## Key KPIs
- Total Bookings
- Average Booking Amount
- Cancellation Rate %
- Stayed Percentage
- City-wise Booking Distribution
_____________________________________________
## 📊 OYO Dashboard Preview

---

## Booking By City
________

![booking_by_city](booking_by_city.png)
![booking_by_city(1)](booking_by_city(1).png)

- Booking data is aggregated using SQL with a JOIN between sales and city tables and grouped by city.

- COUNT(*) is used to calculate total bookings per city and results are sorted in descending order.

- The SQL output is visualized in Power BI using a bar chart to compare booking volume across cities.

- The analysis identifies high-demand and low-demand cities for performance comparison.

  ----

  ## Average Booking Amount By City



  
