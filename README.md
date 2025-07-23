# Weather-dashboard
# 🌤️ Real-Time Weather & Air Quality Dashboard Using Power BI & WeatherAPI

---

## 1️⃣ Weather Dashboard

This project showcases a **real-time weather dashboard** built using **Power BI** and **WeatherAPI**.

🔹 It connects to **live weather and air quality data**  
🔹 Visualizes the data using **interactive and dynamic visuals**  
🔹 Built to deliver both **environmental insights** and **practical health information**

---

## 2️⃣ Purpose

The goal of this project is to demonstrate how to:

- ✅ Build a **real-time interactive dashboard** in Power BI  
- ✅ Integrate **live data** using WeatherAPI  
- ✅ Visualize **weather conditions** and **air quality indicators**  
- ✅ Provide **health tips** based on **AQI levels**

This project is ideal for learning:

- 🔧 API integration  
- 📄 JSON transformation  
- 📊 Dashboard design in Power BI  
- 🧮 DAX logic for calculated measures

---

## 3️⃣ Data Source

**API Provider**: [WeatherAPI.com](https://www.weatherapi.com/)  
**Data Format**: JSON

### 📥 Data Includes:

- 🌡️ **Current Weather**:
  - Temperature
  - Humidity
  - Wind speed

- 🌫️ **Air Quality**:
  - PM2.5
  - CO
  - NO₂
  - PM10
  - SO₂
  - O₃

---

## 4️⃣ Features & Highlights

### 🔗 Live API Integration
- Connected Power BI to **WeatherAPI** using the **Web API connector**
- Used **dynamic URLs** for real-time data fetching

---

### 🛠 Data Transformation in Power Query
- Parsed nested JSON fields like `current`, `condition`, `air_quality`
- Renamed columns and structured data for visual clarity

---

### 📈 Interactive Weather Visuals
- **KPI Cards** for temperature, humidity, and wind speed
- **Line/Bar charts** to show trends (if extended with historical data)
- **Slicers** for selecting different cities or regions

---

### 🎨 Custom Visual Enhancements
- Added **custom weather icons**
- Used **condition descriptions** to enhance visual storytelling

---

### 🌫 Air Quality Indicators (AQI) with DAX
- Developed **dynamic DAX measures** for pollutants:
  - ✅ **Color-coded AQI**
  - ✅ **AQI Status**: Good, Moderate, Unhealthy, etc.
  - ✅ **Health Tips** based on air quality levels

---

### ♻️ Reusable & Scalable DAX Templates
- Created **generic DAX logic** for pollutants like:
  - PM2.5, PM10, NO₂, SO₂, CO, O₃
- Easy to **extend** for new metrics or additional sources

---

### 🎛 User Interactivity
- Implemented:
  - Filters
  - Slicers
  - Conditional formatting
- Users can select data by **city** or **specific pollutant**
- Dashboard updates **automatically in real-time**

---

### 🧠 Learning-Oriented Design
Perfect for **Power BI beginners to intermediates**, covering:

- API connection setup  
- Parsing and transforming JSON  
- Building responsive visuals  
- Writing insightful DAX logic  

---

### Screenshots:
   
![Dashboard Preview](images/weather-dashboard-screenshot.png)



