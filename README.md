# COVID-19 India Data Cleaning & Exploratory Data Analysis

## 📑 Table of Contents

- [Introduction](#introduction)  
- [Dataset](#dataset)  
- [Methodology](#methodology)  
- [Key Findings](#key-findings)  
- [Visualizations](#visualizations)  
- [Conclusion](#conclusion)  
- [How to Run](#how-to-run)  

---

### 🧭 Introduction

This project aims to analyze the spread and impact of COVID-19 in India through data cleaning, transformation, and exploratory data analysis (EDA). It highlights state-wise trends, growth of cases over time, and recovery/death rates to gain insights into the pandemic's behavior.

---

### 📊 Dataset

- Source: [Kaggle - COVID-19 India Dataset](https://www.kaggle.com/datasets/imdevskp/covid19-corona-virus-india-dataset)
- File used: `covid_19_india.csv`
- Time Period: January 2020 to August 2021
- Features include: State/UT, Date, Confirmed cases, Recovered cases, Deaths, and more.

---

### 🧪 Methodology

- Loaded and explored raw data from Kaggle
- Cleaned data:
  - Converted date formats
  - Standardized column names
  - Removed nulls and duplicates
- Performed EDA using:
  - Time-series plots
  - State-wise aggregations
  - Distribution graphs
- Visualized trends and correlations

---

### 📈 Key Findings

- **Maharashtra** and **Delhi** had consistently high numbers of confirmed cases.
- The **recovery rate** increased significantly over time.
- **Death rate** remained relatively low compared to the confirmed and recovered numbers.
- A few states dominated the total case count distribution.
- COVID-19 growth followed a strong **exponential trend** early on and later plateaued.

---

### 🖼️ Visualizations

- Line plot of daily confirmed, recovered, and death cases.
- Bar plot of top 10 states with the most confirmed cases.
- Pie chart showing the distribution of total outcomes (Recovered, Deaths, Active).
- Heatmap showing correlations between variables.

---

### ✅ Conclusion

This project provides a clear picture of how COVID-19 affected India on a regional and temporal scale. The insights can help policymakers and citizens understand the dynamics of the outbreak and how it evolved across states.

---

### ⚙️ How to Run

To run this project locally or in Google Colab:

1. Clone the repo:
   ```bash
   git clone https://github.com/PSYCHOLOGIST1261992/covid19-india-eda.git
