
# 🏨 Hotel Booking Cancellation Dashboard (Excel Project)

## 📌 Project Overview
An interactive Excel dashboard built to analyze hotel booking data from 2015 to 2017.  
It helps visualize total and cancelled bookings, booking trends, guest types, and room status insights using Pivot Tables, charts, slicers, and custom formulas.

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

→ Identifies whether the guest was assigned the same room type they originally reserved.
If yes → marked as “Desired”, otherwise “Undesired”.

### 🔹 Guest Type
  
→ Classifies guests as Couples, Single, or Family.

Couples: 2 adults, no children/babies

Single: 1 adult, no children/babies

Family: Any other combination



---

## 📊 Dataset Fields Used
- `arrival_date_year`
- `arrival_date_month`
- `hotel` (City / Resort)
- `reserved_room_type`, `assigned_room_type`
- `adults`, `children`, `babies`
- `is_canceled`

---

## 🛠 Tools & Features
- Microsoft Excel  
- Pivot Tables & Charts  
- Data Slicers  
- Excel Formulas (IF, AND)

---

## 📌 Insights
- Couples make up the majority of bookings and cancellations.
- Undesired room assignments result in higher cancellation rates.
- Resort Hotels have more bookings than City Hotels.
- Booking activity peaks between May and August.

---

## 📂 Dataset Source  
[Hotel Booking Dataset on Kaggle](https://www.kaggle.com/datasets/mojtaba142/hotel-booking?select=hotel_booking.csv)

---

## 🙌 Author  
Created with 💡 and Excel by srishtiagrawal02

---

## 📷 Dashboard Preview  
<img width="788" alt="{530D6BC4-E221-43B8-9F54-6DAFEFAA1D4F}" src="https://github.com/user-attachments/assets/a6cb8545-a1a5-4621-96a5-0f1bb164f879" />
