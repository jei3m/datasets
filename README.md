# Datasets Repository

This repository contains datasets collected during my college studies in Machine Learning. These datasets cover various domains including environmental science, education, and demographics.

## Dataset Catalog

### 1. Bay Water Quality Data (1994)
- **Description**: Water quality measurements from a bay area including salinity, dissolved oxygen, pH, temperature readings, and other environmental factors.
- **Variables**:
  - Site_Id, Unit_Id, Read_Date
  - Salinity (ppt), Dissolved Oxygen (mg/L), pH
  - Secchi Depth (m), Water Depth (m)
  - Water Temp (Â°C), Air Temp (Celsius and Fahrenheit)
  - Time, Field_Tech, Verification info
  - Year
- **Size**: 34 records, 17 features
- **Format**: CSV
- **Use Case**: Time series analysis, environmental monitoring, regression tasks

### 2. SAT-GPA Correlation Data
- **Description**: Dataset showing the relationship between SAT scores and college GPA.
- **Variables**:
  - SAT: Student SAT score (400-2400 scale)
  - GPA: College Grade Point Average (0.0-4.0 scale)
- **Size**: 32 records, 2 features
- **Format**: CSV
- **Use Case**: Correlation analysis, linear regression, educational research

### 3. US Life Expectancy Data (1960-1995)
- **Description**: Annual life expectancy data for the United States.
- **Variables**:
  - DATE: Year of measurement
  - SPDYNLE00INUSA: Life expectancy at birth (years)
- **Size**: 36 records, 2 features
- **Format**: CSV
- **Use Case**: Time series forecasting, demographic studies

## Potential Applications
These datasets can be used for:
- Time series analysis and forecasting (water quality and life expectancy data)
- Correlation and regression analysis (SAT-GPA relationship)
- Feature engineering practice (water quality dataset has multiple variables)
- Data cleaning practice (some water quality entries have missing values)

## Data Notes
1. **Water Quality Dataset**:
   - Contains some missing values (marked as N/A)
   - Includes both metric and imperial units for temperature
   - Some apparent duplicate columns (AirTemp-Celsius and AirTemp (C))

2. **SAT-GPA Dataset**:
   - SAT scores are on the pre-2016 scale (600-2400)
   - GPA values range from 2.4 to 3.28

3. **Life Expectancy Dataset**:
   - Values are precise to many decimal places
   - Shows steady increase over time as expected

## Special Mention:
This Commit and README is made possible by GitWrite.
Check out this Repository: https://github.com/jei3m/git-write