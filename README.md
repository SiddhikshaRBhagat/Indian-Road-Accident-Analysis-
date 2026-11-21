# Indian-Road-Accident-Analysis-
Tableau Dashboard Project - 🚗 Indian Road Analysis (2022-2025)


## 📌 Project Overview

The **Road Accident Analysis Dashboard** is a Tableau data visualization project designed to analyze road accidents and identify patterns, trends, and factors contributing to road accidents.

The project provides insights into accident severity, casualties, road types, weather conditions, traffic density, accident causes, and geographical distribution across different states.

The main objective is to transform road accident data into meaningful insights that can help understand accident patterns and support better road safety awareness and decision-making.

## 🎯 Project Objectives

- Analyze the overall number of road accidents and casualties.
- Understand the distribution of accidents based on severity.
- Identify the major causes contributing to road accidents.
- Analyze accident patterns across different days of the week.
- Examine the relationship between weather conditions and road accidents.
- Understand accident distribution across different road types.
- Analyze road accident distribution across states.
- Evaluate traffic density and its impact on accident occurrences.
- Identify important accident-related KPIs.

## 🛠️ Tools & Technologies Used

- **Tableau Desktop:** Data visualization and dashboard development.
- **Microsoft Excel:** Dataset storage and data source.
- **Data Analytics:** Data exploration, aggregation, and KPI analysis.

## 📊 Dataset Description

The project uses an Indian Road Accidents dataset covering the period **2022–2025**.

The dataset contains the following important attributes:

| Column | Description |
|---|---|
| Accident Id | Unique identifier for each accident |
| Accident Severity | Severity level of the accident |
| Casualties | Number of casualties |
| Cause | Cause of the accident |
| Date | Date of the accident |
| Day Of Week | Day on which the accident occurred |
| Festival | Festival-related information |
| Hour | Hour of accident occurrence |
| Is Peak Hour | Indicates peak-hour occurrence |
| Is Weekend | Indicates weekend occurrence |
| Lanes | Number of road lanes |
| Latitude | Geographical latitude |
| Longitude | Geographical longitude |
| Risk Score | Accident risk score |
| Road Type | Type of road where the accident occurred |
| State | State where the accident occurred |
| Temperature | Temperature at the time of accident |
| Traffic Density | Traffic density condition |
| Traffic Signal | Traffic signal information |
| Vehicles Involved | Number of vehicles involved |
| Visibility | Visibility conditions |
| Weather | Weather conditions |

## 📈 Dashboard Description

The Tableau project consists of two interactive dashboards.

### 1. Road Accident Overview Dashboard

This dashboard provides a high-level overview of road accident statistics through KPI cards and visualizations.

**Key Performance Indicators (KPIs):**
- Total Accidents
- Total Casualties
- Average Risk Score
- Average Vehicles Involved
- Average Casualties Per Accident

**Visualizations:**
- Accident Severity Distribution
- State-wise Road Accidents Distribution
- Weather Condition Analysis

**Purpose:** To provide an overall understanding of accident statistics, severity patterns, and geographical distribution.

### 2. Road Accident Factors Analysis Dashboard

This dashboard focuses on analyzing different factors associated with road accidents.

**Visualizations:**
- Road Type Accidents
- Accident Cause Analysis
- Traffic Density Analysis
- Casualties by Severity
- Day of Week Analysis

**Purpose:** To understand how accident causes, road conditions, traffic density, and days of the week relate to road accident occurrences and casualties.

## 🧮 Calculated Fields and KPIs

The project includes calculated fields to derive important performance indicators.

| KPI | Calculation |
|---|---|
| Total Accidents | COUNT(Accident Id) |
| Total Casualties | SUM(Casualties) |
| Average Risk Score | AVG(Risk Score) |
| Average Vehicles Involved | AVG(Vehicles Involved) |
| Average Casualties Per Accident | SUM(Casualties) / COUNT(Accident Id) |
| High Severity Accidents | Count indicator for high-severity accidents |

## 🔍 Key Areas of Analysis

The dashboards help explore the following areas:

1. **Accident Severity:** Understand how accidents are distributed across different severity levels.
2. **Geographical Analysis:** Identify the distribution of road accidents across Indian states.
3. **Weather Analysis:** Examine accidents under different weather conditions.
4. **Road Type Analysis:** Compare accident occurrences across different road types.
5. **Accident Causes:** Analyze the contribution of different accident causes.
6. **Traffic Density:** Explore accident patterns under different traffic density conditions.
7. **Casualty Analysis:** Evaluate casualties across accident severity categories.
8. **Weekly Trends:** Understand how accident occurrences vary across different days of the week.

## 💡 Project Outcomes

This project demonstrates how Tableau can be used to convert raw road accident data into interactive and meaningful visual insights.

It provides a structured view of accident statistics and allows users to explore accident-related factors from multiple perspectives, including geographical, environmental, and road-related conditions.


