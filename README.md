("![Flight Booking Analysis](https://www.jagoinvestor.com/wp-content/uploads/files/book-cheap-flight-india.jpg)"

# ✈️ Flight Booking Analysis

## 🚀 Project Overview
This **comprehensive flight booking analysis** explores a rich dataset to uncover **insightful trends, booking patterns, and pricing dynamics**.  
The goal is to identify actionable insights that help airlines, booking platforms, and travel planners make **data-driven decisions**.

---

## 📊 Dataset Description
The dataset contains **detailed flight booking records** including:

- **FlightDate**: Date of the flight  
- **BookingDate**: Date when the ticket was booked  
- **Origin**: Departure airport  
- **Destination**: Arrival airport  
- **Price**: Ticket price  
- **PassengerCount**: Number of passengers  
- **FlightDuration**: Duration of the flight in hours  

**Engineered Features**:  
- **Days_Between_Booking**: Number of days between booking and flight 🗓️  
- **Price_Per_Hour**: Ticket price normalized per flight hour 💰  

---

## 🛠️ Tech Stack
- **Python 3**  
- **Pandas & NumPy** – Data manipulation and cleaning  
- **Matplotlib & Seaborn** – Stunning visualizations  
- **Jupyter Notebook** – Interactive exploration and reporting  

---

## 📝 Analysis Steps

### 1️⃣ Initial Inspection
- Checked dataset **shape, columns, and data types**  
- Ensured a **solid understanding of the data structure** before cleaning  

### 2️⃣ Missing Values & Safe Filling
- Filled **string columns** with mode and **numeric columns** with median  
- Handled missing values **conservatively** to maintain dataset integrity  

### 3️⃣ Dedupe & Text Normalization
- Removed duplicate rows  
- Normalized text data (lowercase, trimmed whitespace, consistent formatting)  

### 4️⃣ Numeric Validation & Outlier Handling (IQR)
- Verified numeric columns for **valid ranges**  
- Handled outliers using the **Interquartile Range (IQR)** method  

### 5️⃣ Dates & Feature Engineering
- Created **Days_Between_Booking** 🗓️  
- Created **Price_Per_Hour** 💵  
- Added meaningful features for **deeper insights and fair comparisons**  

### 6️⃣ Save Cleaned Data & Preview
- Saved cleaned dataset for **reliable and consistent analysis**  
- Previewed the data to **ensure transformations were applied correctly**  

### 7️⃣ Visualizations
- Bar charts: Top origins & destinations 🏙️  
- Line charts: Booking trends over time 📈  
- Histograms: Fare and delay distributions 📊  
- Weekend vs weekday flight analysis  

---

## ✨ Executive Summary

- **Rapid Growth Pre-2019:** Flight bookings increased steadily with more travelers and added routes.  
- **Operational Challenges in 2020:** Global pandemic caused sharp decline in bookings and disruptions.  
- **Resilient Demand Post-2021:** Strong rebound in traveler demand, creating high load factors.  
- **Key Opportunities:** Focus on **dynamic pricing, route optimization, premium cabins**, and **flexible booking policies**.  

---

## 🔑 Key Insights

- Steady growth of flight bookings until 2019, driven by **increasing travel demand**  
- Sharp decline in 2020 due to **pandemic restrictions**  
- Post-2021 recovery resulted in **higher load factors and ticket prices**  
- Weekend and early bookings **tend to command higher fares**  
- Engineered features like **Days_Between_Booking** and **Price_Per_Hour** are **highly informative**  

---

## 💡 Recommendations

- Implement **dynamic pricing strategies** to optimize revenue 💰  
- Focus on **high-demand and premium routes** 🌍  
- Continuously monitor **booking trends** for scheduling and marketing adjustments 📊  
- Leverage engineered features for **targeted insights and predictions** 📈  

---

📂 Project Structure

├── data/                  # Raw & cleaned datasets
├── notebooks/             # Jupyter notebooks
├── images/                # Visualizations exported from notebooks
├── requirements.txt       # Dependencies
├── LICENSE                # License file (MIT)
├── README.md              # Project overview (this file)

---

## 📌 How to Run
1. Clone the repository  
2. Open `Flight_Booking_Analysis.ipynb` in Jupyter Notebook  
3. Load the dataset CSV file  
4. Run all cells sequentially to reproduce analysis, visualizations, and summary  

---


## 📈 Results

The flight booking analysis revealed **key trends, patterns, and actionable insights**:

---

## 📜 License

This project is licensed under the **MIT License**.  


---
## 👤 Author
**Shital Kamble (SHITAL)**  
Flight Booking Data Analyst ✈️  
