# 🏨 Hotel Booking Cancellations Analysis Dashboard

## 📌 Project Overview
This project analyzes a dataset of **hotel bookings** obtained from **Kaggle** to understand the patterns and factors contributing to **booking cancellations**.  
The data was cleaned, processed, and visualized through an interactive **dashboard** to help hotels make data-driven decisions and reduce cancellation rates.

---

## 📂 Dataset
- **Source:** [Kaggle – Hotel Booking  Dataset]
- **File Used:** `Hotel Cancellations.xlsx`  
- **Original Format:** CSV (converted and cleaned for Excel analysis)  
- **Key Columns:**
  - `hotel` – Type of hotel (City or Resort)
  - `is_canceled` – Whether the booking was canceled
  - `lead_time` – Number of days between booking and arrival
  - `arrival_date_year`, `arrival_date_month`, `arrival_date_day_of_month`
  - `adults`, `children`, `babies`
  - `country` – Guest origin
  - `market_segment`, `distribution_channel`
  - `previous_cancellations`, `booking_changes`
  - `deposit_type`, `customer_type`, `adr` (Average Daily Rate)

---

## 🧹 Data Cleaning Steps
The dataset was cleaned using Excel and Python to ensure accuracy and consistency:
1. Removed duplicate records.  
2. Handled missing values (replaced or dropped depending on context).  
3. Corrected data types (e.g., dates, numbers).  
4. Standardized categorical values (e.g., hotel types, country codes).  
5. Created new calculated columns for analysis (e.g., cancellation rate).

---

## 📊 Data Analysis
The following analyses were performed:
- **Cancellation Trends** by hotel type and season.  
- **Lead Time vs Cancellation Rate** correlation.  
- **Impact of Deposit Type** on booking cancellations.  
- **Geographic Analysis** of customer countries.  
- **Revenue and ADR Insights** between canceled and non-canceled bookings.

---

## 📈 Dashboard
An interactive dashboard was created to visualize insights, including:
- Total Bookings and Cancellation Rate.  
- Cancellation by Hotel Type and Month.  
- Top Countries by Cancellations.  
- Relationship between Lead Time and Cancellations.  
- Average Daily Rate (ADR) Comparison.

---

## 🛠️ Tools & Technologies
- **Data Source:** Kaggle  
- **Data Cleaning & Transformation:** Excel, Python (Pandas)  
- **Visualization / Dashboard:** Excel Dashboard / Power BI (if applicable)

---

## 🎯 Key Insights
- Resort hotels have higher cancellations compared to city hotels.  
- Longer lead times are strongly correlated with higher cancellation rates.  
- Non-refundable deposits significantly reduce cancellations.  
- Certain countries contribute disproportionately to cancellations.

---

## 📁 Files Included
- `Hotel Cancellations.xlsx` → Cleaned dataset and dashboard  
- `README.md` → Project overview and documentation  

---

## 🚀 Future Improvements
- Automate data refresh from Kaggle using Python scripts.  
- Integrate the dashboard into Power BI or Tableau for web visualization.  
- Add predictive modeling for cancellation forecasting using ML.
