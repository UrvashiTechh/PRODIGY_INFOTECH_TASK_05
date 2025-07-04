# PRODIGY_INFOTECH_TASK_05
TASK5
🚗 Traffic Accident Analysis – Pattern Discovery & Visualization
<img width="1680" alt="Screenshot 2025-07-04 at 11 49 32 AM" src="https://github.com/user-attachments/assets/4a2f714b-5b3b-4bc6-aa82-4e4e32101b51" />
📌 Overview
This project focuses on analyzing real-world traffic accident data to uncover patterns and insights related to road conditions, weather, and time of day. By performing exploratory data analysis (EDA) and geospatial visualization, the project aims to identify accident hotspots and the most common contributing factors.

🎯 Objectives
Identify key factors contributing to accidents

Understand how accidents correlate with:

Weather conditions

Road types/surface conditions

Time of day (rush hours vs. night)

Visualize geographic hotspots using maps and plots

📁 Dataset
Source: US Accidents Dataset (Kaggle)

Size: 3+ million accident records across the U.S.

Key columns:

Start_Time, End_Time, Weather_Condition

Severity, City, State, Start_Lat, Start_Lng

Visibility(mi), Humidity(%), Temperature(F)

Wind_Speed(mph), Precipitation(in)

Side, Sunrise_Sunset, Street

🧰 Tools & Libraries
Python (Jupyter Notebook)

pandas, numpy – data cleaning & analysis

matplotlib, seaborn – EDA & visualizations

plotly, folium – interactive mapping of accident hotspots

geopandas, datetime – spatial and time-based analysis

🔍 Data Exploration & Cleaning
Removed incomplete or irrelevant records

Handled missing values in Weather_Condition, Precipitation, and Wind_Speed

Converted time columns to proper datetime objects

Extracted new features: hour, day, month, day/night classification, etc.

📊 Exploratory Data Analysis (EDA)
🔸 Temporal Analysis
Accidents peak during morning and evening rush hours

Weekdays show higher accident rates than weekends

🔸 Weather & Road Conditions
Higher accident rates observed during:

Rainy, foggy, and snowy conditions

Poor visibility and wet roads

🔸 Severity Insights
Visualized distribution of accident severity levels

Correlated severity with weather, time of day, and road type

🗺️ Hotspot Mapping
Created interactive maps using Folium and Plotly to display:

Geographic clusters of accidents

High-risk states and cities

Severity heatmaps using latitude & longitude

📈 Key Visuals
Histogram of accidents per hour

Heatmaps of accident density by day & time

Weather condition bar chart

Folium map showing real-world accident clusters

✅ Conclusions
Rush hours, poor weather, and low visibility are major contributing factors

Cities with higher traffic volumes showed stronger clusters

Mapping techniques help identify focus areas for safety improvements

📎 Files Included
Prodigy_Infotech_Task_5.ipynb – Jupyter Notebook containing full analysis, visualizations, and insights

RTA Dataset.csv – Raw dataset containing traffic accident records

README.md – Project overview and documentation
