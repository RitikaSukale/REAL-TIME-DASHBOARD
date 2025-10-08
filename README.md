# REAL-TIME-DASHBOARD

#COMPANY: CODTECH IT SOLUTIONS

#NAME: Ritika Ramchandra Sukale

#INTERN ID: CT04DY2239

#DOMAIN: POWER BI

#DURATION: 4 WEEKS

#MENTOR: NEELA SANTOSH

#DESCRIPTION:
Real-Time Weather Tracker – India
1. Introduction
This project focuses on developing a Real-Time Weather Tracker Dashboard for various cities across India. The dashboard continuously fetches live weather data from the WeatherAPI and displays it visually using Power BI. The main goal is to monitor weather parameters such as temperature, humidity, wind speed, pressure, and weather conditions in real time. Such real-time visualization helps users, analysts, and policymakers quickly understand the current weather situation and take informed decisions.

3. Objectives
•	To design and implement a dashboard that displays current weather conditions of Indian cities.
•	To automatically update the dashboard using live API data.
•	To compare and analyze temperature, humidity, pressure, and wind trends across cities.
•	To enhance data interpretation through interactive and visually appealing charts.

4. Data Source and API Integration
The project uses WeatherAPI (https://www.weatherapi.com/) as the live data source. It provides real-time weather information in JSON format.
Data Fields Fetched:
•	City name
•	Temperature (°C)
•	Humidity (%)
•	Wind speed (km/h) and direction
•	Atmospheric pressure (hPa)
•	Weather condition (e.g., clear, cloudy, rain)
•	Latitude and longitude
Data Fetching Process:
1.	Power BI connects to the WeatherAPI endpoint using an API key.
2.	The JSON response is converted into tabular format.
3.	Data refreshes automatically every few minutes to ensure live updates.

4. Data Processing
Before visualization, data goes through cleaning and transformation steps:
•	Converted JSON to structured table format.
•	Removed missing or null values.
•	Rounded numeric columns (e.g., temperature, pressure).
•	Mapped city names to their coordinates for the India map visualization.
•	Adjusted timestamps to local time (IST).

6. Dashboard Design and Visuals
The dashboard was built in Power BI, designed with a dark theme for better contrast and readability. It includes multiple visuals to represent different weather aspects:
Visualization	Description	Purpose
Temperature Trend (Minute-by-Minute)	Line chart showing temperature variation per minute.	To observe short-term changes in temperature.
Wind Speed vs. Direction	Horizontal bar chart showing average wind speed by direction.	Identifies dominant wind patterns.
City-Wise Temperature Map	Map of India with temperature indicators by city.	Shows spatial temperature distribution.
Current Temperature by City	Bar chart comparing latest temperatures across cities.	Quickly identifies hottest and coolest cities.
Pressure Variation by City	Line chart comparing pressure across locations.	Monitors pressure trends and stability.
Temperature vs. Latitude	Scatter plot correlating latitude and temperature.	Reveals how temperature varies across regions.
		
7. Key Insights and Observations
•	Coastal cities like Chennai and Kochi showed higher humidity compared to inland cities.
•	Ahmedabad and Delhi recorded moderate temperatures with light rain during the data capture time.
•	Wind direction was mostly west-southwest (WSW), indicating seasonal flow.
•	Pressure variation between cities remained within a small range (1008–1014 hPa).
•	Latitude analysis confirmed that southern cities generally experience higher average temperatures.

9. Technical Implementation
Tools Used:
•	Power BI: For visualization and dashboard design.
•	WeatherAPI: For real-time weather data.
Data Flow: WeatherAPI → Power BI Web Connection → Data Transformation (Power Query) → Live Dashboard Display
Refresh Setup: Power BI’s automatic refresh feature ensures updated data every few minutes.

11. Challenges and Solutions
Challenge	Solution
API rate limits restricted frequent calls	Implemented optimal refresh intervals.
Missing or inconsistent city data	Handled null values and fallback defaults.
Data refresh delays in Power BI	Scheduled background refresh and cache clearing.
JSON structure changes	Used dynamic parsing to extract key fields.

13. Conclusion
The Real-Time Weather Tracker – India provides a comprehensive live view of weather conditions across multiple cities. It demonstrates how API-driven real-time dashboards can enhance data accessibility and analysis. The project can be extended by integrating forecast data, alert notifications, or historical trend comparisons to strengthen predictive insights.


OUTPUT:
