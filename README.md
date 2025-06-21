# AQI-Analysis
This project analyzes historical AQI data from major Indian cities using Python and visualizes key insights through plots. It aims to uncover pollution trends, city-wise air quality comparisons, and pollutant behaviors over time.
## 📁 Dataset

- **Source**: [AQI Dataset.xlsx]
- **Cities Covered**: Delhi, Mumbai, Chennai, Bangalore, Hyderabad
- **Duration**: 2018 – 2024
- **Features**: AQI, PM2.5, PM10, NO2, SO2, CO, O3, Date, City

## 🛠️ Tools & Libraries

- **Python**: Data analysis & preprocessing
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scipy`
- **Jupyter Notebook**: Exploratory Data Analysis (EDA)

## 📊 Key Analysis Performed

### 1. **Data Cleaning & Preprocessing**
- Removed nulls and inconsistent values
- Converted date strings to datetime format
- Extracted Month and Year features
- Converted pollutant columns to numeric types

### 2. **Exploratory Data Analysis (EDA)**
- Average AQI across cities and months
- Identification of the most and least polluted cities
- Seasonal trends and pollutant variations
- AQI trend over years per city

### 3. **Advanced Analysis**
- Correlation matrix to identify strongest AQI influencers
- Detection of SO₂ and CO spikes using Z-score method
- Count of unhealthy AQI days per city (AQI > 150)

### 4. **Visualizations**
- Line & bar charts using `matplotlib` & `seaborn`

## 📌 Key Findings

- **Delhi** consistently had the highest AQI levels across all years.
- **Winter months (Dec–Jan)** showed higher pollution levels in most cities.
- High correlation between AQI and pollutants such as PM2.5, PM10, and SO₂.
- Over 700 spike days detected in SO₂ and CO levels.

