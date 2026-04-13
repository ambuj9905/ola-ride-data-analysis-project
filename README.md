# 🚖 Ola Ride Data Analysis – SQL & Power BI Project

Analyzed 100K+ ride booking records to uncover insights on revenue, cancellations, customer behavior, and operational efficiency using SQL and Power BI.

---

## 📌 Table of Contents

* Overview
* Business Problem
* Dataset
* Tools & Technologies
* Project Structure
* SQL Analysis
* Power BI Dashboard
* Dashboard Preview
* Business Questions & Insights
* How to Run
* Final Recommendations
* Author

---

## 📊 Overview

This project focuses on analyzing Ola ride booking data to extract actionable insights that help improve ride efficiency, reduce cancellations, and increase revenue.

---

## ❗ Business Problem

Ride-sharing companies face multiple challenges:

* High ride cancellations
* Uneven demand across vehicle types
* Revenue fluctuations
* Customer satisfaction issues

This project aims to solve these problems using data-driven insights.

---

## 📁 Dataset

* Source: Public dataset
* Records: 100K+ rides
* Features include:

  * Booking ID
  * Ride Distance
  * Booking Status
  * Payment Method
  * Vehicle Type
  * Booking Value
  * Ratings

👉 Dataset Link: https://topvarsity.in/wp-content/uploads/2024/12/Bookings-100000-Rows.xlsx

---

## 🛠 Tools & Technologies

* SQL (Data Analysis, Aggregations, Joins)
* Power BI (Dashboard & Visualization)
* Excel

---

## 📂 Project Structure

```
ola-ride-data-analysis/
│
├── dataset/        # Raw data
├── sql/            # SQL queries
├── powerbi/        # Power BI dashboard
├── screenshots/    # Dashboard images
```

---

## 🧠 SQL Analysis

Performed SQL-based analysis to answer key business questions:

* Retrieved all successful bookings
* Calculated average ride distance by vehicle type
* Identified top 5 customers by booking count
* Analyzed customer and driver cancellations
* Evaluated revenue from successful rides
* Compared customer and driver ratings

---

## 📊 Power BI Dashboard

The dashboard is divided into 5 key sections:

### 🚖 Overall

* Ride Volume Over Time
* Booking Status Breakdown

### 🚗 Vehicle Type

* Top Vehicle Types by Ride Distance

### 💰 Revenue

* Revenue by Payment Method
* Top 5 Customers by Booking Value
* Ride Distance Distribution

### ❌ Cancellation

* Customer Cancellation Reasons
* Driver Cancellation Reasons

### ⭐ Ratings

* Driver Ratings Distribution
* Customer vs Driver Ratings

---

## 📸 Dashboard Preview

### 🔹 Overall Dashboard

![Overall Dashboard](https://github.com/user-attachments/assets/77537f02-0aa0-4471-b47d-a1353af0ab58)

### 🔹 Vehicle Type Analysis

![Vehicle Analysis](https://github.com/user-attachments/assets/92c68040-ce21-4740-a4f0-eedde954fc8e)

### 🔹 Revenue Insights

![Revenue](https://github.com/user-attachments/assets/a5289f79-ebcc-49b8-8bba-98274272afab)

### 🔹 Cancellation Analysis

![Cancellation](https://github.com/user-attachments/assets/7a3e6008-f7fb-4025-90c8-93024b339554)

### 🔹 Ratings Analysis

![Ratings](https://github.com/user-attachments/assets/d4e73b78-ba65-4d6d-80ac-81f499c40863)

---

## ❓ Business Questions & Insights

### 🚖 Ride Success Rate

* Majority of rides are successfully completed (~60–65%)
* Remaining rides are cancelled or incomplete

### ❌ Cancellation Analysis

* Customer cancellations mainly due to delays
* Driver cancellations due to personal or vehicle issues
* Certain vehicle types show higher cancellation rates

### 💰 Revenue Insights

* Prime Sedan and Prime Plus generate maximum revenue
* Cash and UPI dominate payment methods

### 👥 Customer Behavior

* Top 5 customers contribute significantly to total bookings
* Peak ride demand observed during specific time periods

### ⭐ Ratings Analysis

* Average rating is around 4.0
* Slight variation across vehicle types
* Some ride categories show lower satisfaction

---

## ⚙️ How to Run

1. Clone the repository:

```
git clone https://github.com/yourusername/ola-ride-data-analysis.git
```

2. Run SQL queries from `/sql` folder

3. Open Power BI dashboard:

```
powerbi/ola_dashboard.pbix
```

---

## 📌 Final Recommendations

* Reduce driver cancellations using incentive strategies
* Improve ride allocation during peak hours
* Focus on low-rated services to improve customer satisfaction
* Promote digital payments for better tracking and efficiency

---

## 👨‍💻 Author

**Ambuj Singh**
Data Analyst

* LinkedIn: [Add your link]
* Portfolio: [Add your link]

⭐ If you like this project, give it a star!
