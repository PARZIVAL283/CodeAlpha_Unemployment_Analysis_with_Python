# CodeAlpha Task 2: Unemployment Analysis with Python 📊

## 📌 Project Overview

This project analyzes unemployment trends in India using Python and data visualization techniques. The primary objective is to explore unemployment rates across different regions, investigate changes during the COVID-19 period, compare urban and rural unemployment, and identify patterns in the available data.

This project was completed as part of the **CodeAlpha Data Science Internship — Task 2**.

## 🎯 Objectives

* Analyze unemployment rate trends over time.
* Investigate unemployment patterns before and during the COVID-19 period.
* Identify regions with relatively high and low average unemployment rates.
* Compare urban and rural unemployment trends.
* Explore monthly patterns in unemployment data.
* Examine correlations between unemployment, employment, and labour participation.
* Present data-driven insights through clear visualizations.

## 📂 Datasets

Two CSV datasets were used for this project:

1. `Unemployment in India.csv`
2. `Unemployment_Rate_upto_11_2020.csv`

The datasets contain unemployment-related information for Indian regions, including variables such as:

* **Region:** Name of the region.
* **Date:** Date of the observation.
* **Frequency:** Reporting frequency.
* **Estimated Unemployment Rate (%):** Estimated unemployment percentage.
* **Estimated Employed:** Estimated number of employed people.
* **Estimated Labour Participation Rate (%):** Estimated labour force participation percentage.
* **Area:** Urban or rural classification, available in the first dataset.

The second dataset also contains geographic fields such as longitude and latitude.

## 🛠️ Technologies Used

* **Python** — Programming language
* **Google Colab** — Development environment
* **Pandas** — Data cleaning and manipulation
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization

## 🔍 Project Workflow

### 1. Data Loading and Inspection

* Loaded both CSV datasets using Pandas.
* Examined dataset dimensions, column names, and sample records.
* Inspected missing values and data types.

### 2. Data Cleaning and Preprocessing

* Removed unnecessary whitespace from column names.
* Removed completely empty rows.
* Converted date columns into datetime format.
* Converted relevant measurements into numeric types.
* Excluded records missing essential fields for specific analyses.

### 3. Exploratory Data Analysis (EDA)

* Calculated average unemployment rates.
* Examined unemployment trends over time.
* Compared unemployment across regions.
* Investigated urban and rural differences.
* Explored monthly patterns in the available observations.

### 4. COVID-19 Analysis

* Compared average unemployment before March 2020 with observations from March 2020 onward.
* Examined changes in unemployment during the pandemic period.
* Investigated whether urban and rural observations showed different patterns.

### 5. Correlation Analysis

* Calculated correlations among unemployment rate, estimated employment, and labour participation rate.
* Created a correlation heatmap.
* Used a scatter plot to explore the relationship between unemployment and labour participation.

## 📈 Visualizations

The project includes the following visualizations:

* Unemployment Rate Trends in India (2019–2020)
* Urban vs Rural Unemployment Trends
* Top 10 Regions by Average Unemployment Rate
* Average Unemployment Before and During COVID-19
* Urban vs Rural Unemployment During COVID-19
* Average Unemployment Rate by Calendar Month
* Correlation Heatmap
* Unemployment Rate vs Labour Participation Rate

## 💡 Key Insights

The analysis is designed to identify:

* Changes in estimated unemployment rates over time.
* Regions with comparatively high or low average unemployment rates.
* Differences between urban and rural unemployment observations.
* Changes in unemployment during the COVID-19 period.
* Relationships between unemployment and labour participation.
* Potential monthly patterns that may warrant further investigation.

**Note:** Final numerical findings should be reported from the executed notebook outputs. No specific regional ranking, correlation, or percentage change is assumed in advance.

## ⚠️ Limitations

* The analysis covers a limited historical period, primarily around 2019–2020.
* Monthly patterns over this short period do not establish recurring seasonality.
* The comparison before and during COVID-19 is descriptive and does not prove causation.
* Regional averages may not represent official national unemployment estimates.
* Missing observations and differences in dataset structure can affect comparisons.
* The two datasets should be checked for overlapping records and differences in coverage before combining them.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open Google Colab at https://colab.research.google.com/.
3. Upload the notebook and both CSV datasets.
4. Update the file paths if necessary.
5. Run the notebook cells in sequence.
6. Review the generated charts, statistics, and conclusions.

## 📁 Project Structure

```text
CodeAlpha_UnemploymentAnalysis/
│
├── data/
│   ├── Unemployment in India.csv
│   └── Unemployment_Rate_upto_11_2020.csv
│
├── plots/
│   └── Generated visualizations
│
├── CodeAlpha_Unemployment_Analysis.ipynb
├── requirements.txt
└── README.md
```

## 📚 Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Statistical analysis
* Time-series visualization
* Regional data comparison
* Correlation analysis
* Python programming
* Data interpretation and reporting

## 👨‍💻 Internship

**Organization:** CodeAlpha
**Domain:** Data Science
**Task:** Task 2 — Unemployment Analysis with Python

## 🏁 Conclusion

This project demonstrates how Python can be used to explore unemployment data, visualize economic trends, compare regional observations, and investigate changes during the COVID-19 period.

It provides practical experience in data preprocessing, exploratory analysis, visualization, and evidence-based interpretation—important skills for real-world data science projects.

---

**If you find this project useful, feel free to ⭐ the repository!**
