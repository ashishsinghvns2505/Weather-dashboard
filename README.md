# Weather-dashboard
1.Weather dashboard: 

Real-Time Weather and Air Quality Dashboard Using Power BI and WeatherAPI. n this project, I built a real-time weather dashboard using Power BI by connecting it with live data from WeatherAPI.

2.Purpose:

This project demonstrates how to create a real-time interactive weather dashboard using Power BI integrated with live data from WeatherAPI. It visualizes current weather conditions and enhances the user experience with Air Quality Index (AQI) indicators, providing both environmental insights and practical health suggestions. It’s a great learning project for anyone looking to understand API integration, data transformation, and dashboard design in Power BI.

3. Data Source:

Primary Source: WeatherAPI.com
Data Format: JSON
Data Includes:
    > Current Weather Data (temperature, humidity, wind speed, etc.)
    > Air Quality Data (PM2.5, CO, NO2, etc.)

4. Features / Highlights:

🔗 Live API Integration:
Connected Power BI to live weather data using the Web API connector and dynamic URLs from WeatherAPI.com. This enabled the dashboard to fetch real-time weather and air quality data directly into Power BI.

🛠 Data Transformation in Power Query Editor:
Used Power Query to parse the JSON response, expand nested records (like current, condition, and air_quality), and clean up the data. Renamed and structured columns for better clarity and usability in visuals.

📈 Interactive and Real-Time Weather Visualizations:
    Created dynamic visuals such as:
     > Cards for key weather metrics (temperature, humidity, wind speed)
     > Charts showing variations in conditions (if extended with historical data)
     > Slicers/Filters to switch between different cities easily

🎨 Custom Icons and Weather Conditions:
Added weather icons and condition descriptions to make the dashboard more visually engaging and informative.

🌫 Air Quality Index (AQI) Indicators with DAX:
   Created reusable and scalable DAX measures to display:
     > AQI Color Coding (based on pollutant severity)
     > AQI Status (e.g., Good, Moderate, Unhealthy)
     > AQI Suggestions (health tips based on air quality levels)
       These measures provide context-aware insights for different pollutants like pm2.5, co, no2, PM10, SO2, CO etc.
       
♻️ Reusable DAX Templates:
Developed a set of generic DAX formulas that can be easily adapted for any air quality metric. This makes the dashboard scalable and quick to update when adding new data sources or pollutants.

🎛 User Interactivity and Customization:
Enabled dynamic interaction with filters, slicers, and conditional formatting, giving users control to view real-time data specific to cities or environmental factors of their interest.

🧠 Learning Focused Implementation:
Perfect for beginners to intermediate Power BI users—this project covers working with APIs, transforming JSON, building responsive visuals, and writing DAX logic to enhance insight generation.

5. Screenshots / Demos
   Dashboard Screenshot.png
