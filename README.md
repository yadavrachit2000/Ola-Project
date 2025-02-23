![Ola_Cabs_logo svg](https://github.com/user-attachments/assets/dfd9661b-ecf4-4cda-a03a-c2f6d2861586)
# OLA Ride Analytics

## 📊 Project Overview
This project provides a comprehensive analysis of OLA ride data using **MySQL Workbench** for data querying and **Power BI** for interactive dashboard visualizations. The goal is to derive insights related to customer behavior, ride performance, payment methods, and driver analytics to support business decision-making and operational improvements.

---

## 🛠️ Software & Tools Used

- **MySQL Workbench**: For writing and executing SQL queries to extract, transform, and analyze ride data.
- **Power BI**: To create dynamic and interactive dashboards, visualizing key performance indicators (KPIs) and insights derived from SQL analysis.

---

## 🏗️ Project Structure

```
OLA-Ride-Analytics/
│
├── dashboards/
│   └── ola_ride_analytics.pbix
├── data/
│   └── Ola Booking Data.csv
├── README.md
├── Ride Analytics Queries and Results.pdf
```

---

## 🔍 Key SQL Analyses Performed

1. **Successful Bookings**: Retrieved all rides with a successful booking status.
2. **Average Ride Distance**: Calculated the average ride distance per vehicle type.
3. **Cancelled Rides by Customers**: Computed the total number of customer-cancelled rides.
4. **Top 5 Customers**: Identified customers with the highest number of rides.
5. **Driver Cancellations**: Analyzed driver cancellations due to personal and car-related reasons.
6. **Driver Ratings (Prime Sedan)**: Extracted max and min driver ratings for Prime Sedan rides.
7. **UPI Payments**: Retrieved rides paid via UPI.
8. **Customer Ratings**: Found average customer ratings per vehicle type.
9. **Total Booking Value**: Calculated the total value of successfully completed rides.
10. **Incomplete Rides**: Listed all incomplete rides with corresponding reasons.

---

## 📈 Power BI Dashboard Highlights

- **Ride Distribution**: Breakdown of rides by vehicle type, location, and booking status.
- **Customer Insights**: Key customer trends, top customers by bookings, and rating patterns.
- **Revenue Metrics**: Total booking value visualization, highlighting successful and incomplete rides.
- **Driver Performance**: Analysis of driver ratings and cancellation reasons.
- **Payment Analysis**: Distribution of payment methods used across rides.

---

## 🎯 Key Insights & Business Recommendations

- **Customer Retention**: Focus on top customers by offering loyalty programs.
- **Operational Efficiency**: Reduce driver-related cancellations through improved support.
- **Revenue Growth**: Promote Prime Sedan rides, which have higher customer ratings.
- **Payment Optimization**: Encourage UPI payments due to seamless transaction processes.

---

## 🚀 How to Run This Project

1. **Database Setup**:
   - Import the dataset into MySQL Workbench.
   - Execute the SQL scripts in the Ride Analytics Queries and Results.pdf.

2. **Power BI Dashboard**:
   - Open the `OLA Ride Analytics.pbix` using Power BI Desktop.
   - Refresh data connections to load the latest data from MySQL.

---
