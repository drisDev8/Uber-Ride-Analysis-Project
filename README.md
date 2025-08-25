## 📌 Uber-Ride-Analysis-Project
This project is a comprehensive data analysis of an Uber dataset from the year 2024, designed to provide actionable insights into booking patterns, revenue streams, cancellation behaviors, and customer satisfaction. Utilizing Power BI, I created an interactive and user-friendly dashboard that makes it easy to navigate and explore key business metrics. 

## 📂 Datasets Information
The dataset contains a total of 148,770 bookings with detailed ride-sharing data. The raw data included the following key columns: <br>
Date and Time <br>
Booking ID (unique identifier for each ride) <br>
Booking Status (e.g., Completed, Cancelled by Customer, Cancelled by Driver) <br>
Customer ID and Vehicle Type <br>
Booking Value and Ride Distance <br>
Driver Ratings and Customer Rating <br>
Payment Method <br>
Cancellation Reasons by Driver and Customers

## 🎯Business Problem Addressed
Analyzed the high total cancellation rate of 25%. This analysis aimed to break down the reasons for these cancellations to understand the underlying operational issues and customer/driver behavior.

## 🔧 Analysis and Tools Used
# Data Cleaning and Transformation:
1. Converted Booking Value from a string to a whole number. <br>
2. Converted Ride Distance, Customer Rating, and Driver Ratings from strings to decimal numbers. <br>
3. Ensured the Date and Time columns were in the correct format for time-based analysis. <br>

# DAX Measures:
1. Cancelled Bookings: Counts all bookings cancelled by either a customer or a driver. <br>
2. Cancelled Percentage: Calculates the total cancellation rate. <br>

# Visualizations and Interactive Dashboard:
1. Card Visuals: Used to prominently display key performance indicators (KPIs) like Total Bookings and Cancellation Rate. <br>
2. Buttons and Bookmarks: Implemented interactive buttons and bookmarks for seamless navigation between the Overview Analysis, Revenue Analysis, and Ratings reports. <br>
3. A "Home" button to return to the main analysis, a "Refresh" button to clear all slicers, and an "Info" button to view dataset details. <br>
4. Column Charts: Used for Revenue Distribution by Payment Method, showing UPI and Cash as the top contributors. <br>
5. Line Graph: Created a "Ride Volume Over Time" graph to show booking trends, with a simplified Y-axis scale (0, 5k, 10k, 15k) to highlight overall trends and readability.<br>

## 🔍 Key Insights
Through this analysis, I uncovered several critical insights: <br>
1. High Cancellation Rate: The total cancellation rate stands at 25%, with 18% initiated by drivers and 7% by customers, highlighting a significant operational challenge. <br>
2. Vehicle Performance: The Auto vehicle type is the most profitable with the highest booking value ($11.73M) and total distance traveled (602K km). In contrast, Uber XL has the lowest utilization. <br>
3. Stable Ride Volume: The monthly ride volume is consistently stable, ranging from 11.9K to 12.9K, suggesting a mature market with no significant seasonal fluctuations. <br>
4. Payment Method Trends: UPI is the highest contributor to revenue (45%), followed by Cash (25%). <br>
5. High-Value Customers: The analysis of the top 5 customers revealed a small group of high-spending, loyal users with a high Customer Lifetime Value (CLV). <br>

# Ratings Analysis:
6. Customer ratings are consistently high (average 4.40-4.41), indicating overall satisfaction. <br>
7. Driver ratings are slightly lower but stable (average 4.23-4.24), with Go Sedan receiving the highest customer ratings and the UberXL category having the most satisfied drivers. <br>

## 🧠Skills Gained:
Through this case study, I gained hands-on experience in:

1. Data Cleaning and Transformation: Converting data types, ensuring data integrity, and preparing raw data for analysis. <br>
2. DAX: Creating custom measures and calculations to derive meaningful business metrics. <br>
3. Data Visualization: Designing and implementing various chart types (e.g., card visuals, line graphs, column charts) to present data clearly. <br>
4. Interactive Dashboard Design: Building a user-friendly and navigable report with buttons, bookmarks, and slicers. <br>
5. Business Problem Solving: Identifying and addressing key business challenges (e.g., high cancellation rates, vehical analysis) through data-driven insights. <br>
6. Storytelling with Data: Moving beyond raw numbers to create a clear and actionable narrative from the analysis. 

## 👤About Me
LinkedIn: https://www.linkedin.com/in/dristi-handique/

