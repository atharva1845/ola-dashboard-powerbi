# ola-dashboard-powerbi
# OLA Booking Analytics Dashboard 🚖📊

This Power BI dashboard project presents a comprehensive data analysis of ride booking behavior, cancellations, payments, and ratings for a ride-hailing service (simulated as OLA). It showcases end-to-end data handling — from SQL-based extraction and Excel preprocessing to DAX-based modeling and Power BI visual storytelling.

---

## 🔍 Project Overview

The goal of this project is to analyze 100,000 rows of ride data and derive business insights on customer behavior, driver performance, booking patterns, and payment trends. It uses **SQL** for querying, **Excel** for cleaning and shaping, and **Power BI** for dashboard creation and analysis.

---

## 📁 Data Columns

- Date, Time, Booking_ID
- Booking_Status, Customer_ID, Vehicle_Type
- Pickup_Location, Drop_Location
- V_TAT (Vehicle Turnaround Time), C_TAT (Customer Turnaround Time)
- Cancelled_Rides_by_Customer, Cancelled_Rides_by_Driver
- Incomplete_Rides, Incomplete_Rides_Reason
- Booking_Value, Payment_Method, Ride_Distance
- Driver_Ratings, Customer_Rating

---

## 📊 Dashboard Structure (Multi-Page View)

### 1. **Overall**
- Ride Volume Over Time (Line chart)
- Booking Status Breakdown (Pie chart)

### 2. **Vehicle Type**
- Top 5 Vehicle Types by Ride Distance (Bar chart)

### 3. **Revenue**
- Revenue by Payment Method (Stacked bar chart)
- Top 5 Customers by Total Booking Value (Leaderboard)
- Ride Distance Distribution Per Day (Histogram/Scatter)

### 4. **Cancellation**
- Cancelled Ride Reasons (Bar chart — Customer & Driver)

### 5. **Ratings**
- Driver Rating Distribution (Box plot)
- Customer vs. Driver Ratings (Scatter plot)
- Average Customer Ratings by Vehicle Type (Column chart)

---

## ⚙️ Technologies Used

- **SQL**: For querying and extracting structured data
- **Excel**: For data cleaning, filtering, and prep
- **Power BI**: For dashboard creation using:
  - Interactive slicers
  - Page navigation
  - DAX formulas for calculated columns and KPIs
  - Custom visuals and formatting

---

## 🧠 Key Insights

- Majority of bookings were successful with peak ride volume on weekends.
- Cash and UPI dominate as payment methods.
- Sedans and SUVs cover the highest ride distances.
- Driver ratings show a consistent pattern; customer ratings vary more.
- Cancellations are more frequent by drivers due to no-shows or location mismatch.

---

## 📂 Files Included

- `Ola_Dashboard.pbix` – Power BI working file
- `Ola_Dashboard.pdf` – Exported static version of dashboard
- `Dataset_Sample.csv` – Sanitized sample of the dataset (optional)
- `README.md` – This project description

---

## 📎 How to Use

1. Clone or download the repo
2. Open `Ola_Dashboard.pbix` in Power BI Desktop
3. Explore visualizations by interacting with slicers and pages

---

## 🏷️ Tags

`Power BI` `SQL` `Excel` `Data Analytics` `Dashboard` `Ride Sharing` `Visualization` `Business Intelligence` `DAX`


