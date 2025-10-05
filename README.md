# Traffic Indicator Analysis

An Exploratory Data Analysis (EDA) of I-94 Interstate Highway traffic data to identify temporal and environmental factors influencing traffic volume and congestion patterns.

## Project Overview

This project analyses 48,000+ hourly traffic records from the I-94 Interstate Highway dataset (2012–2018), aiming to uncover patterns in traffic flow across **seasons, weekdays, and weather conditions** to understand how and why congestion occurs.

**Objectives:**
- Identitfy seasonal & temporal patterns in traffic volume.
- Analyse correlations between traffic volume & weather-related features.
- Visualise traffic trends to highlight congestions patterns.

## Dataset 

- **Source:** [UCI - Metro Interstate Traffic Volume](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume).

- **Size:** ~48,000 hourly entries from **2012-2018**

- **Key Features:** 
    - `date_time` - Timestamp of observation
    - `traffic_volume` - Number of cars passing per hour
    - `temp`, `rain_1h`, `snow_1h`, `clouds_all`, `weather_main` - Environmental indicators

## How to Run

**Requirements:**
- Python 3.x
- Libraries: `pandas`, `matplotlib`
- Any Jupyter Notebook enviroment

**Steps:**
1. Clone this repository
```
https://github.com/TounseA/traffic-indicator-analysis.git
```

2. Open the notebook & run all cells
```
jupyter notebook Indicators of Heavy Traffic on I-94.ipynb
```

## Key Findings 
- **Seasonality:** Traffic volume increases by approximately 12.7% from winter to summer, indicating higher movement during warmer months.
- **Weekday Patterns:** 43% higher traffic volume on weekdays compared to weekends, with Friday being the busiest day.
- **Lowest Activity:** December recorded the lowest traffic volume (~4,300 cars), aligning with colder weather and holidays.