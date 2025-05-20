# solar-challenge-week1

#  Solar Data Discovery - Week 0 Challenge (10 Academy AIM Program)
---
## 🚀 Project Overview

This repository contains my submission for **10 Academy’s Week 0 Challenge**, which involves understanding, exploring, and analyzing environmental and solar measurement data across **Benin**, **Sierra Leone**, and **Togo**.  

The goal is to generate actionable insights that help **MoonLight Energy Solutions** identify **high-potential regions** for solar farm installations based on environmental metrics such as GHI, DNI, DHI, temperature, humidity, wind speed, and more.

---

## 🎯 Business Objective

MoonLight Energy Solutions aims to expand its solar infrastructure efficiently. This project analyzes country-wise environmental data to support:

- 📊 Strategic investments in solar farms
- 🌍 Regional prioritization for deployment
- ♻️ Enhancing operational sustainability
- 🧠 Data-driven decision making

---

## 🗃️ Dataset Overview

Data is sourced from Solar Radiation Measurement Logs. Each row includes:

- **Timestamp**
- **GHI, DNI, DHI** – Solar irradiance metrics  
- **Ambient & Module Temperatures** (Tamb, TModA, TModB)  
- **Humidity, Wind Speed, Wind Direction, Pressure**
- **Cleaning and Precipitation Events**

Each country's dataset is profiled, cleaned, and visualized individually before performing a comparative analysis.

---

## 📌 Project Tasks

### ✅ Task 1: Git & Environment Setup

- Repository initialized with Git & GitHub Actions
- Virtual environment and `requirements.txt` setup
- Continuous Integration with GitHub Actions
- Folder structure organized for notebooks, scripts, and dashboards

### 📊 Task 2: Data Profiling, Cleaning & EDA

Performed for each country individually:
- Summary statistics and missing value reports
- Outlier detection using Z-scores
- Imputation and cleaning
- Time-series and seasonal analysis
- Correlation heatmaps, scatter plots, wind & humidity impact
- Exported cleaned datasets

### 🌍 Task 3: Cross-Country Comparison

- Boxplots for GHI, DNI, DHI comparisons
- Summary tables with mean, median, std deviation
- Statistical testing (ANOVA) to assess significance
- Strategic insights for regional solar potential

### 💻  Interactive Streamlit Dashboard

- Filters by country and variables
- Boxplots and interactive metrics
- Deployed on [Streamlit Cloud](#) (demo link if available)
- Responsive and intuitive user interface

---

## 🧪 Technologies Used

| Stack | Description |
|-------|-------------|
| **Python** | Data analysis and scripting |
| **Pandas, NumPy, Seaborn, Matplotlib** | Data cleaning, visualization |
| **Scikit-learn, SciPy** | Statistical testing |
| **Git & GitHub** | Version control |
| **Streamlit** | Dashboard development |
| **VS Code & Jupyter Notebooks** | Development environments |

---

## 🧾 Folder Structure

