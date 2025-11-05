# 🌊 Warm Waters off Peru — Exploring El Niño’s Impact  

## Overview  
This project analyzes **sea surface temperature (SST) changes** off the coast of Peru to understand the **El Niño phenomenon** and its climatic impact.  
By visualizing long-term temperature patterns, it reveals how **El Niño events** disrupt normal ocean conditions, affecting global weather systems and marine ecosystems.  
Through statistical and visual analysis, the project connects **environmental data** to real-world climatic trends.  

---

## Objectives  
- Investigate **sea surface temperature variations** across years.  
- Identify **El Niño events** through temperature anomalies.  
- Compare **average, maximum, and minimum SSTs** over time.  
- Visualize data trends to interpret **climate irregularities**.  

---

## Dataset  
**File:** `sea-surface-temperature-peru.csv`  

This dataset contains sea surface temperature measurements collected off the coast of Peru across multiple years, highlighting changes associated with El Niño and La Niña cycles.  

| Column Name | Description |
|--------------|-------------|
| `year` | Year of observation |
| `month` | Month of observation |
| `sst` | Sea Surface Temperature (°C) |
| `anomaly` | Deviation from long-term average SST |
| `location` | Coastal region or measurement point |

---

## Key Steps and Analysis  

### 1. Data Loading and Preparation  
- Imported dataset using **pandas** and inspected structure.  
- Handled missing values and converted time columns to a **datetime index**.  
- Computed **annual mean SST** for trend analysis.  

### 2. Trend and Anomaly Analysis  
- Calculated **temperature anomalies** to highlight El Niño years.  
- Identified warm and cool phases relative to the baseline average.  
- Compared year-to-year SST fluctuations.  

### 3. Visualization  
Used **Matplotlib** and **Seaborn** to create:  
- **Line plots** showing annual SST trends.  
- **Heatmaps** of monthly SST variation across years.  
- **Anomaly plots** highlighting El Niño spikes.  

---

## Key Insights  
- **El Niño years** (e.g., 1982–83, 1997–98, 2015–16) show clear spikes in sea temperature.  
- Consistent warming trends over decades suggest **long-term oceanic changes** beyond natural oscillations.  
- The data illustrates how **climate phenomena** can be visualized through temperature-based evidence.  

---

## Tools & Libraries  
- **Python**  
- **Pandas** – for data manipulation and time-series handling  
- **Matplotlib** – for visualization of trends and anomalies  
- **Jupyter Notebook** – for interactive analysis and documentation    

---

## Author  
Developed as a **climate data analysis project**, this work demonstrates how environmental datasets and visualization techniques can uncover the long-term and cyclical effects of **El Niño** on global and regional climates.
