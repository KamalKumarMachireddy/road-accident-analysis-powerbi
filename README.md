# Road Accident Analysis and Dashboard using Power BI

## Overview

This repository contains a Power BI project that analyzes a comprehensive road accident dataset. The goal of this project is to identify key insights, trends, and performance indicators related to road safety. The dashboard enables interactive exploration of accident data to support data-driven decision-making for road safety improvements.

## Features

- Interactive Power BI dashboard
- Visualizations of accident trends over time
- Accident severity analysis
- Analysis by vehicle type, weather conditions, junction controls, and more
- Key Performance Indicators (KPIs) such as:
  - Total Accidents
  - Total Casualties
  - Fatal Accidents
  - Severity Rate (%)

## Dataset

The dataset includes details of road accidents, including:
- Accident Index
- Accident Date and Time
- Accident Severity
- Vehicle Types Involved
- Weather Conditions
- Road Surface Conditions
- Junction Controls
- Carriageway Hazards

> Note: The dataset was imported from a provided source (e.g., UK Department for Transport or a similar source).

## Data Preparation

- Filled missing values (e.g., "Carriageway_Hazards" set to "None")
- Handled nulls in Time column
- Standardized text entries (e.g., fixed typos in "Junction_Control")
- Formatted data types appropriately (dates, categories, numbers)
- Grouped similar vehicle types for better clarity

## Exploratory Data Analysis (EDA)

- Distribution of accidents by severity, time, weather, and day of week
- Correlation analysis between weather/road conditions and severity
- Identification of high-risk junction types
- Trends in accident frequency across different time intervals

## Dashboard Visualizations

- **Cards** for total metrics (Accidents, Casualties, Fatalities, Vehicles)
- **Bar Charts** for accident distribution by vehicle type and day of the week
- **Donut Chart** for accident severity distribution
- **Line Chart** for accident trends over time
- **Stacked Bar Charts** for severity vs weather and road surface conditions
- **Horizontal Bar Chart** for top junction controls by accident count
- **Slicers** for interactive filtering by multiple attributes

## Key Findings

- Most accidents are slight (85.49%), but fatal and serious accidents still occur at notable rates
- Cars are involved in the majority of accidents
- Uncontrolled junctions have higher accident frequencies
- Adverse weather and road conditions increase accident severity
- Urban areas report higher accident counts due to traffic density

## Recommendations

- Improve signage and controls at uncontrolled junctions
- Enhance road maintenance, especially in adverse weather
- Implement targeted safety campaigns for peak hours and weekends
- Use historical trends to predict and mitigate high-risk periods

## Getting Started

1. Clone the repository.
2. Open the Power BI (.pbix) file in Power BI Desktop.
3. Connect to the dataset if needed or refresh data.
4. Interact with the dashboard to explore the data.

## Author

Created by Machireddy Kamal Kumar  
For questions or suggestions, feel free to open an issue.

