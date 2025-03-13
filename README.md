# Climate Change Analysis 🌍🌡️

## Overview
This project analyzes climate change patterns using historical weather data. It focuses on key factors like temperature trends, humidity, precipitation, wind speed, and air pressure. Various data visualization techniques and machine learning models are used to understand the impact of climate change over time.

## Features
✅ Data preprocessing and cleaning
✅ Seasonal temperature analysis
✅ Feature importance analysis using machine learning
✅ Visualizations for weather trends
✅ Insights on climate change effects

## Dataset
The dataset includes historical weather data with attributes such as:
- **Date**: Timestamp of the recorded data
- **Temperature (°C)**: Daily temperature
- **Humidity (%)**: Moisture content in the air
- **Precipitation (mm)**: Rainfall recorded
- **Wind Speed (km/h)**: Speed of wind movement
- **Air Pressure (hPa)**: Atmospheric pressure

## Methodology
1. **Data Preprocessing**:
   - Convert date columns into useful formats
   - Handle missing values
2. **Feature Analysis**:
   - Use **Random Forest Regressor** to determine which features impact temperature the most
   - Create a **feature importance plot**
3. **Seasonal Analysis**:
   - Extract seasons from month values
   - Generate **box plots** to show temperature distribution per season
4. **Visualization Techniques**:
   - **Line charts** for temperature trends
   - **Scatter plots** for humidity vs. precipitation
   - **Box plots** for seasonal variations
   - **Bar charts** for feature importance

## Technologies Used
🟢 **Python**
🟢 **Pandas** (for data processing)
🟢 **Plotly** (for interactive visualizations)
🟢 **Scikit-Learn** (for machine learning analysis)

## Results & Insights
📌 Temperature trends reveal increasing fluctuations over the years.
📌 **Humidity** and **precipitation** significantly impact temperature variations.
📌 Different seasons show varying temperature ranges, helping in climate prediction.
📌 Feature importance analysis helps in understanding which weather factors influence temperature changes the most.

## Installation & Usage
1️⃣ Clone the repository:
```bash
   git clone https://github.com/your-username/climate-change-analysis.git
```
2️⃣ Install dependencies:
```bash
   pip install pandas plotly scikit-learn
```
3️⃣ Run the analysis script:
```bash
   python climate_analysis.py
```

## Conclusion
This project helps in understanding climate change by analyzing historical weather data. By leveraging machine learning and visualizations, we can identify key weather factors that influence temperature changes. These insights can be useful for climate research, policymaking, and environmental awareness. 🌱💡

---
Feel free to contribute and expand this project! 😊✨

