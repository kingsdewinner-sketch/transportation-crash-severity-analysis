# Predictive Analysis of 144k+ Records: A Deep Dive into Behavioral Data
Data analysis and visualization of motor vehicle crash severity patterns using public transportation datasets.

## Overview
This project analyzes motor-vehicle crash data from NYC Open Data to identify patterns in crash severity and high-risk driving behaviors.

## Tools Used
Python
Excel
Tableau
Data Visualization
Exploratory Data Analysis

## Dataset
NYC Open Data Motor Vehicle Collision Dataset

## Data Validation & Rigor
To ensure the analytical integrity of the 144k+ records, a multi-stage data cleaning and validation process was conducted using **Excel**:

* **Data Filtering:** Narrowed the scope to recent years (2023–2024) to ensure the analysis reflects current urban safety trends and infrastructure.
* **Inconsistency Removal:** Identified and removed duplicate entries and resolved conflicting records where crash attributes did not align with official NYC Open Data schemas.
* **Spatial Validation:** Cross-referenced geographic coordinates (Latitude/Longitude) against borough labels and zip codes to ensure 100% spatial accuracy for mapping.
* **Handling Missing Values:** Performed targeted imputation for contributing factors and vehicle types, ensuring that "Inattentive Driving" and "Speeding" metrics were not skewed by null entries.

## Key Analysis
- Crash severity index creation
- Temporal crash pattern analysis
- Geographic clustering of severe crashes
- Behavioral risk factor analysis

## Dashboard
An interactive Tableau dashboard visualizing crash patterns and severity.

## Insights
- Commuting hours show increased crash severity
- Driver inattention and speeding strongly correlate with crash severity
- Geographic clusters indicate potential infrastructure safety concerns
