<img width="1024" height="1024" alt="ChatGPT Image Oct 1, 2025, 11_56_30 AM" src="https://github.com/user-attachments/assets/7983ed5e-4c3a-4883-8959-53730923627f" />
EnviroScan: AI-Powered Pollution Source Identifier using Geospatial Analytics
Project Overview

EnviroScan is a comprehensive system designed to identify the likely sources of pollution using artificial intelligence and geospatial analytics. Traditional pollution monitoring systems measure pollutant levels but fail to pinpoint the specific sources. EnviroScan bridges this gap by analyzing real-time air quality data, weather conditions, and location-based features to classify pollution sources and provide actionable insights for urban planners and environmental agencies.

Main Objectives:

Predict likely pollution sources such as industrial activity, vehicular traffic, agricultural burning, or natural causes.

Visualize pollution hotspots and high-risk zones on interactive maps.

Generate real-time alerts when pollutant levels exceed safe thresholds.

Produce detailed reports for decision-making and urban planning.

Key Features

Real-Time Pollution Monitoring

Collects air quality data (PM2.5, PM10, NO₂, CO, SO₂, O₃) from OpenAQ API.

Collects weather data (temperature, humidity, wind speed, wind direction) from OpenWeatherMap API.

Geospatial Analysis

Extracts location-based features like roads, industrial zones, dump sites, and agricultural fields using OpenStreetMap and OSMnx.

Calculates distances to nearest pollution sources for better contextual analysis.

Machine Learning for Source Prediction

Rule-based labeling for initial datasets (Vehicular, Industrial, Agricultural, Burning, Natural).

Trains models such as Random Forest, XGBoost, and Decision Tree.

Uses pollutant levels, weather, and spatial proximity features as input.

Evaluates models using accuracy, precision, recall, F1-score, and confusion matrix.

Interactive Visualization and Heatmaps

Dynamic heatmaps showing pollution intensity.

Source-specific markers for industrial, vehicular, agricultural, and natural sources.

Filterable maps by location, date, and predicted source.

Dashboard and Alerts

Streamlit-based real-time dashboard for user-friendly interaction.

Displays pollutant trends, source prediction charts, and pie charts for distribution.

Sends alerts when pollution exceeds safe thresholds.

Allows exporting daily and weekly reports.
