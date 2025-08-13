# 🚖 Uber Trip Analysis

## 📌 Project Overview
This project delivers a deep-dive analysis of Uber trip data for June 2024, revealing patterns in bookings, revenues, distances, and trip behaviors. By examining payment preferences, trip types, locations, and time-based booking trends, the dashboard empowers decision-making for operational efficiency, targeted marketing, and customer satisfaction.

---

## 📊 Key Visualizations
- **Summary Metrics:**  
  - Total Bookings: **87K – 98K**  
  - Total Booking Value: **$1.31M – $1.47M**  
  - Total Trip Distance: **293K – 330K Miles**  
  - Avg Booking Value: **$14.95 – $14.98**  
  - Avg Trip Time: **16 Minutes**

- **Breakdowns & Trends:**  
  - **By Payment Type:** Uber Pay dominates (67.3%), followed by Cash (32%), Amazon Pay & Google Pay (<1%).  
  - **By Trip Type:** Day trips lead (85%), night trips account for 15%.  
  - **By Day & Hour:** Peak bookings mid-to-late month; highest activity between **09:00–18:00**.  
  - **By Vehicle Type:** UberX leads in bookings (32,900), Uber Comfort in average trip distance (48K miles).  
  - **By Location:** Penn Station/Madison Square tops with **3.9K bookings**.

- **Heatmaps & Line Charts:**  
  - Pickup hour vs. day matrix to spot hot times for demand.  
  - Weekly booking trends highlighting weekend peaks.

---

## 🔍 Insights & Analysis
- **Dominant Service:** UberX captures the largest share, suggesting it’s the preferred and most accessible option.
- **High-Value Rides:** Uber Black & Uber Comfort yield similar booking values despite fewer rides—premium pricing strategy.
- **Payment Insights:** Heavy reliance on Uber Pay presents a loyalty and cashback opportunity; low adoption of alternative wallets.
- **Time Patterns:** Morning to evening sees the bulk of rides; late-night trips minimal but potentially higher fare per mile.
- **Location Hotspots:** Targeted marketing at Penn Station, Upper East Side, and Lenox Hill could drive incremental bookings.

---

## 🛠 Technologies Used
- **Data Visualization:** Microsoft Power BI  
- **Data Processing:** DAX for metrics & calculated columns  
- **Data Source:** CSV/Excel exports from Uber’s trip dataset  
- **Optional Preprocessing:** Python (Pandas, NumPy) for data cleaning

---

## 📂 Project Steps
1. **Data Collection:** Obtain Uber trip data for the period.
2. **Data Cleaning:** Remove duplicates, standardize formats, check for missing values.
3. **Modeling:** Define relationships between tables (trips, vehicles, locations).
4. **Dashboard Design:**  
   - Summary KPI cards  
   - Pie, bar, line, and heatmap visuals  
5. **Analysis:** Generate insights on service, time, and location patterns.
6. **Testing:** Validate numbers & filter interactions.
7. **Deployment:** Publish dashboard for stakeholder access.

---

## 🚀 How to Use
1. Clone the repository:  
   ```bash
   git clone <repo-url>
2. Open .pbix file in Power BI Desktop.
3. Use date and city filters to focus on a desired period or location.
4. Hover over visuals for interactive tooltips.
5. Export reports or screenshots for sharing.

---

## 📬 Contact  
👤 **Your Name**  
📧 your.email@example.com  
🌐 [Your Portfolio Link]  

---

## 📜 License  
This project is licensed under the **MIT License** — free to use, modify, and share with attribution. 
