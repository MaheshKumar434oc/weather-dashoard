# weather-dashoard
1. Project Title / Headline

🌤️ Weather Dashboard: Real-Time & Weekly Weather Insights Report
An interactive Power BI dashboard providing live and forecasted weather insights across 7 major Indian cities—enabling day-wise filtering, condition comparison, and trend analysis for more informed environmental awareness and planning.

2. Short Description / Purpose

The Weather Dashboard is a dynamic and visually engaging Power BI report designed to display current weather conditions, today’s forecasts, and weekly weather trends across 7 key Indian cities: Ajmer, Mumbai, Guwahati, Lucknow, Thiruvananthapuram, Hyderabad, and Noida. The purpose of this dashboard is to enable users to monitor, compare, and analyze weather conditions across these locations in real-time—supporting personal, operational, and planning decisions.

3. Tech Stack

The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Main platform for creating the dashboard and data visuals.
• 📂 Power Query – Used for transforming and shaping raw API data into tabular form.
• 🧠 DAX (Data Analysis Expressions) – For building dynamic visuals, KPIs, and conditional logic.
• 📁 File Format – .pbix for development and .png/.gif for dashboard previews and sharing.
• 📝 Tables Used – current_data, forecast_day, and forecast_hour tables, derived from structured JSON API responses.

4. Data Source

Source: A weather data provider API (free version) offering real-time weather information in JSON and XML formats.
For this project, I used the free tier of the Weather API, which supports up to 1 million API calls per month—sufficient for regular updates. The API delivers structured weather data that is converted into tabular form within Power BI. This dataset includes real-time updates and can be refreshed to always show the latest weather conditions, including temperature, precipitation, humidity, air quality, and more.

5. Features / Highlights
• Business Problem

Accurate and up-to-date weather information is essential for individuals, businesses, and city planners. However, accessing comparative weather conditions across multiple regions in one place can be difficult without a centralized tool.

• Goal of the Dashboard

To build a centralized, interactive weather reporting tool that:

Tracks and compares current and forecasted weather across multiple cities.

Helps users identify trends and anomalies in weather patterns.

Supports planning for outdoor activities, logistics, health, or general awareness.

• Walkthrough of Key Visuals

• KPIs (Top Section)
Shows real-time metrics including:

🌡️ Temperature

🌫️ Air Quality Index

🌧️ Precipitation

💨 Visibility

💧 Humidity

☀️ UV Index

• Line Chart (Weekly Trends)
Displays trends across the week for each metric (temperature, humidity, etc.) for selected cities.

• 100% Stacked Bar Chart (Rain Probability)
Shows the percentage chance of rain for each day of the week—great for identifying weather-critical days.

• Interactive Buttons
Buttons allow users to select specific days of the week or filter by cities for a focused analysis.

• Icons & Changing Weather Images
Dynamic weather icons and condition images update with the data to provide an intuitive and visually appealing experience.

• Donut Chart (PM 10 Analysis)
Visualizes PM 10 levels to determine if the air quality is within a safe range or exceeds control limits.

6. Business Impact & Insights

Event Planning: Enables individuals and businesses to make informed decisions about event scheduling and travel based on weather trends.

Health & Safety: Helps health professionals and concerned citizens monitor air quality and UV index across cities.

Operational Forecasting: Logistics companies can use the dashboard to anticipate delays or disruptions caused by rain, poor visibility, or high humidity.

Government & Policy Use: Urban planners and environmental agencies can use the tool for air quality tracking and regional climate monitoring.

User Convenience: A one-stop weather hub, replacing the need to check multiple sources for different cities.

7. Screenshots / Demos

(To be added by you as per your dashboard visuals.)
