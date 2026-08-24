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

* **Month** – Extracted from the Order Date.


## 🧮 Data Cleaning




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
