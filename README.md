Here is the ecommerce dataset link -

https://www.kaggle.com/datasets/mojtaba142/hotel-booking?select=hotel_booking.csv

# 🏨 Hotel Booking Cancellation Dashboard (Excel Project)

## 📌 Project Overview

An interactive **Excel dashboard** built to analyze hotel booking data from 2015 to 2017. It helps visualize total and cancelled bookings, booking trends, guest types, and room status insights using Pivot Tables, charts, slicers, and custom formulas.

---

## 📈 Dashboard Highlights

- **Total Bookings vs Cancelled Bookings** (by Guest Type)
- **Room Status vs Cancellations** (Desired vs Undesired rooms)
- **Monthly Booking Trends**
- **Hotel Type Distribution** (City Hotel vs Resort Hotel)
- **Total Bookings & Cancellations**
- **Interactive Filters by Year**

---

## 🧠 Calculated Columns

### 🔹 Room Status

Identifies if the guest was assigned the same room type they reserved.

```excel
=IF([@[reserved_room_type]] = [@[assigned_room_type]], "Desired", "Undesired")

**### 🔹 Guest Type
Classifies guests as Couples, Single, or Family.

📊 Dataset Fields Used
arrival_date_year

arrival_date_month

hotel (City/Resort)

reserved_room_type, assigned_room_type

adults, children, babies

is_canceled

🛠 Tools & Features
Microsoft Excel

Pivot Tables & Charts

Data Slicers

Excel Formulas (IF, AND)

📌 Insights
Couples make up the majority of bookings and cancellations.

Undesired room assignments result in higher cancellation rates.

Resort Hotels have more bookings than City Hotels.

Booking activity peaks between May and August.

📷 Dashboard Preview


![image](https://github.com/user-attachments/assets/1989f721-3f60-4d9a-b8b4-0dba9dbf7290)

