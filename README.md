# SCT_DS_4
Analyzing traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accidents hotspots and contributing factors.
# 🚗 Traffic Accident Pattern Analysis

This project analyzes traffic accident data to identify key patterns related to:
- 🕓 Time of day
- 🌦️ Weather conditions
- 🚧 Road conditions
- 🔥 Accident hotspots
- 💥 Causes and severity of accidents

> 📍 Dataset Source: RTA Dataset (uploaded locally, originally from an Indian traffic report)

---

## 📊 Objectives

- Analyze trends in traffic accidents across different time slots and days of the week
- Examine accident severity and common causes
- Visualize hotspots (simulated) using geographic mapping
- Provide insights to reduce and prevent future accidents

---

## 🗂️ Dataset Overview

| Column Name           | Description                                |
|-----------------------|--------------------------------------------|
| `Time`                | Time of accident occurrence (HH:MM:SS)      |
| `Day_of_week`         | Day of the week                            |
| `Accident_severity`   | Severity level (e.g., slight, serious)     |
| `Cause_of_accident`   | Primary cause of accident                  |
| `Type_of_vehicle`     | Vehicle involved in accident               |
| `Age_band_of_driver`  | Age group of the driver                    |
| `Sex_of_driver`       | Gender of the driver                       |
| `Latitude` & `Longitude` | Simulated coordinates for mapping        |

> Note: Latitude/Longitude were simulated for heatmap visualization due to lack of geospatial data.

---

## 🧪 Tech Stack

- **Python**
- **Pandas** – Data manipulation
- **Seaborn / Matplotlib** – Data visualization
- **Folium** – Geospatial heatmap
- **Jupyter Notebook / Google Colab**

---

## 📈 Key Visualizations

- Accidents by hour of day
- Accidents by day of week
- Distribution of accident severity
- Top 10 causes of accidents
- Accident severity across vehicle types
- Heatmap of accident hotspots (simulated)

---

## 💡 Insights Gained

- Accidents peak during early morning and evening rush hours
- Weekends show increased severity, possibly due to high-speed or fatigued driving
- Human error and rule violations are major contributors
- Certain vehicle types (e.g., commercial vans) show higher accident rates

---

## 🗺️ Heatmap Preview

Accident hotspots across a simulated map of Delhi using random GPS noise:

![Heatmap Preview](images/heatmap_preview.png)  
*Note: For real implementation, accurate GPS data is recommended.*

---

## 🚀 How to Run

1. Clone the repository
2. Open the notebook in **Google Colab** or **Jupyter Notebook**
3. Upload the CSV dataset (`RTA Dataset.csv`)
4. Run cells to explore visualizations and trends

---

## 📎 Files in This Repository

| File Name                   | Purpose                                |
|-----------------------------|----------------------------------------|
| `RTA Dataset.csv`           | Dataset used for the project           |
| `traffic_analysis.ipynb`    | Main notebook with full analysis       |
| `README.md`                 | This documentation                     |
| `images/heatmap_preview.png`| Preview image for the heatmap         |

---
