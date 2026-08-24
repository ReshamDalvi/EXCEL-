# 🚕 UBER DATA ANALYTICS DASHBOARD

## 🎯 Project Objective

The main objective of this project is to analyze Uber’s 2024 ride-booking data and develop an interactive dashboard that provides rich insights into booking patterns,
vehicle performance, revenue streams, cancellation behaviors, customer satisfaction metrics, and ride quality.

---

## 📂 Dataset Description

The dataset contains 15,000 ride-booking records that provide a comprehensive view of Uber's ride-sharing operations. The dataset includes information on bookings, vehicle types, customer and driver activity, trip details, booking value, cancellations, payment methods, locations, and ratings.

### 📋 Dataset Columns

| **Column** | **Description** |
|----------- | ------------ |
|Date                          |      Date of the booking |
|Time                          |      Time of the booking |
|Booking ID                    |      Unique identifier for each ride booking |
|Booking Status                |      Status of booking (Completed, Cancelled by Customer, Cancelled by Driver, etc.) |
|Customer ID                   |      Unique identifier for customers |
|Vehicle Type                  |      Type of vehicle (Go Mini, Go Sedan, Auto, eBike/Bike,  UberXL, Premier Sedan) |
|Pickup Location               |      Starting location of the ride |
|Drop Location                 |      Destined location of the ride |
|Avg VTAT                      |      Average time for driver to reach pickup location (in minutes) |
|Avg CTAT                      |      Average trip duration from pickup to destination (in minutes) |
|Cancelled Rides by Customer   |      Customer-initiated cancellation flag |
|Customer Cancellation Reason  |      Reason for customer cancellation |
|Cancelled Rides by Driver     |      Driver-initiated cancellation flag |
|Driver Cancellation Reason    |      Reason for driver cancellation |
|Incomplete Rides              |      Incomplete ride flag |
|Incomplete Rides Reason       |      Reason for incomplete rides |
|Booking Value                 |      Total fare amount for the ride |
|Ride Distance                 |      Distance covered during the ride (in km) |
|Driver Ratings                |      Rating given by customer (1-5 scale) |
|Customer Ratings              |      Rating given by driver (1-5 scale) |
|Payment Method                |      Method used for payment (UPI, Cash, Credit Card, Uber Wallet, Debit Card) |

---

## 🧮 Calculated Columns

* **Month** – Extracted from the Date.
* **Date** -  Extracted from the Date.


## 🧹 Data Cleaning

* Avg VTAT & Avg CTAT: Replaced nulls with 0 and added minutes (min) unit.
* Cancellation & Incomplete Ride Flags: Replaced nulls with 0.
* Cancellation & Incomplete Ride Reasons: Replaced nulls with Not Applicable and standardized reason names.
* Booking Value: Replaced nulls with 0 and added ₹ formatting.
* Ride Distance: Replaced nulls with 0, converted values to KM by dividing by 100000, and added KM unit.
* Driver & Customer Ratings: Replaced nulls with 0.0 and standardized ratings to decimal format.
* Payment Method: Replaced nulls with Not Initiated.
* Reason Standardization: Simplified inconsistent descriptions such as Customer Behavior, Excess Passengers, Personal Issue,   Customer No-Show, and Unspecified Issue.

---


## 📈 Dashboard Features:

### ⭐ KPI Cards:

* Total Rides
* Completed Rides
* Completion Rate (%)
* Total Revenue
* Average Booking Value
* Average Ride Distance
* Average Driver Rating
* Average Customer Rating

### Charts

* 📈 Bookings & Revenue Trend
* 🍩 Booking Status Distribution
* 📊 Bookings by Vehicle Type
* 📊 Revenue by Vehicle Type
* 📊 Payment Method Distribution
* 🥧 Customer Cancellation Reasons
* 📍  Top Pickup Locations

### Interactive Filters

* Month
* Vehicle Type
* Booking Status
* Payment Method
* Pickup Location

---

## 📊 Dashboard Preview

## 🔍 Key Insights

* **Total Rides:** 150,000
* **Completed Rides:** 93,000
* **Completion Rate (%):** 62%
* **Total Revenue:** ₹51.85M
* **Average Booking Value:** ₹346
* **Average Ride Distance:** 16.75 KM
* **Average Driver Rating:** 4.2
* **Average Customer Rating:** 4.4

### 📅 Monthly Booking Performance
* July recorded the highest number of bookings with 12,897, indicating the peak booking month.
* February recorded the lowest bookings with 11,927.
* March recorded the highest Booking Value at approximately ₹4.57M, indicating the strongest revenue performance of the year.

### 🚗 Vehicle Performance
* Auto had the highest booking volume with 37,419 bookings.
* Auto also generated the highest Booking Value of approximately ₹12.88M.

### 💳 Payment Method
* UPI was the most-used actual payment method with 45,909 bookings.
* Not Initiated has 48,000 records, but since this represents bookings without an initiated payment method, it should not be   described as a payment preference.

### 📍 Pickup Location
* Khandsa was the top pickup location with 949 bookings.
* Barakhamba Road followed closely with 946 bookings.

### ❌ Customer Cancellation
* Wrong Address was the most common customer cancellation reason with 2,362 cancellations.
* Driver is not moving was the second-highest reason with 2,335 cancellations.

---

## ❓ Business Questions Answered

* How many total bookings were made, and what percentage of bookings were successfully completed?
* Which month had the highest number of bookings?
* Which month generated the highest Booking Value?
* Which vehicle type has the highest number of bookings?
* Which vehicle type generates the highest Booking Value?
* Which payment method is most preferred by customers?
* Which pickup locations have the highest demand?
* What are the most common reasons for customer cancellations?
* What proportion of bookings are cancelled by customers, cancelled by drivers, or incomplete?
* What is the average Booking Value and average Ride Distance per booking?
* What are the average Driver and Customer Ratings?
* How do booking trends vary across different months?

---

## 📝 Conclusion

The Uber Data Analytics Dashboard provides a comprehensive analysis of ride-booking performance for 2024. The analysis       highlights key trends in bookings, Booking Value, vehicle performance, payment preferences, pickup locations,                cancellations, and customer and driver ratings.

The dashboard helps identify peak booking periods, high-performing vehicle types, popular pickup locations, preferred        payment methods, and major cancellation reasons, enabling better understanding of customer behavior and operational          performance.

Overall, this project demonstrates how Excel, PivotTables, Pivot Charts, and interactive slicers can be used to transform raw ride-booking data into meaningful business insights and data-driven decision-making.

---

## 🛠️ Tools & Technologies

* Microsoft Excel
* Data Cleaning
* Excel Formulas
* Pivot Tables
* Pivot Charts
* Slicers
* Dashboard Design
* Data Analysis
