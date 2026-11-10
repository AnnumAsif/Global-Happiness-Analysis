# 🌍 Global Happiness Insights (2016)

An exploratory data analysis and visualization project analyzing the **World Happiness Report (2016)** to uncover the demographic, regional, and economic drivers of global well-being.

---

## 📌 Project Overview
The World Happiness Report is a landmark survey tracking national and personal variations in global happiness. This project investigates the core factors influencing happiness scores across countries—including economic prosperity, social support, life expectancy, and governance—to determine what characterizes a thriving society.

---

## 📊 Key Features & Analysis
* **Data Cleaning & Preprocessing:** Handled missing values, standardized data types, and imputed numerical attributes for robust statistical modeling.
* **Top 10 Economies vs. Life Expectancy:** Comparative bar chart analysis of the world's leading nations.
* **Correlation Matrix Heatmap:** Evaluated the strength of positive relationships between Happiness Scores, GDP per Capita, Family support, and Healthy Life Expectancy.
* **Regional Disparities:** Scatter plots tracking GDP per Capita against Happiness Score across distinct global regions.
* **Regional Share Analysis:** Aggregate pie chart visualization illustrating the average happiness score share distribution by region.
* **Interactive Choropleth Map:** Geographic visualization mapping global economic output and health metrics using Python (`folium`). [ https://annumasif.github.io/Global-Happiness-Analysis/ ]

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Geospatial Mapping:** `folium`, `requests` (GeoJSON integration)

---

## 📁 Repository Structure
```text
├── Global_Happiness_Insight.ipynb   # Main Jupyter Notebook containing the full analysis and dashboard
├── README.md                        # Project documentation
└── sample_data/                     # Directory containing the source dataset (2016.csv)
