![COVID-19 Data Science Project](project_banner.png)
# 🌍 COVID-19 Data Science Project

### Exploratory Data Analysis | Data Visualization | Machine Learning

A Data Science project focused on exploring global COVID-19 trends, analyzing pandemic data, creating interactive visualizations, and building a Machine Learning model using Python.

---

## 📌 Project Overview

This project analyzes global COVID-19 data to understand the spread of the pandemic, death rates, and vaccination trends across different countries.

The project covers the complete Data Science workflow, from data cleaning and exploratory data analysis to visualization and machine learning.

## 🎯 Project Objectives

- Explore global COVID-19 data.
- Identify missing values and clean the dataset.
- Analyze cases, deaths, and vaccination trends.
- Create interactive visualizations.
- Build and evaluate a Machine Learning model.

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Random Forest Regressor
- Jupyter Notebook

## 📊 Exploratory Data Analysis

The project includes:

- Dataset overview and exploration.
- Missing values analysis.
- Data cleaning and preprocessing.
- Numerical and categorical data analysis.
- Country-level COVID-19 statistics.

## 📈 Data Visualizations

Interactive visualizations created using Plotly:

1. 🌍 COVID-19 Cases Around the World — World Map
2. ☠️ Top 10 Countries by Total Deaths
3. 📉 Global Daily New COVID-19 Cases
4. 💉 Global Fully Vaccinated People
5. 🎯 Actual vs Predicted COVID-19 Cases
6. 🌟 Random Forest Feature Importance

## 🤖 Machine Learning

**Algorithm:** Random Forest Regressor

**Problem Type:** Regression

**Target Variable:** Total COVID-19 Cases per Million

**Features:** 6

**Training Records:** 189

**Testing Records:** 48

### Model Evaluation

| Metric | Result |
|---|---:|
| MAE | 99,478.39 |
| RMSE | 136,085.83 |
| R² Score | 0.558 |

The model explains approximately 55.8% of the variation in the test data.

## 📂 Dataset

Dataset provided by **Our World in Data**.

[Download COVID-19 Dataset](https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv)

Download the CSV file and save it in the project folder with the filename:

`covid_data.csv`

## 🚀 How to Run This Project

1. Clone or download this repository.
2. Download the dataset from the link above.
3. Place `covid_data.csv` in the project folder.
4. Open `COVID_19_EDA.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells.

## ⚠️ Limitations

- Some columns contained a large number of missing values.
- Median imputation may affect the original data distribution.
- The model uses only 237 country-level records.
- The model results show associations, not causal relationships.
- Predictions should not be considered reliable medical or epidemiological forecasts.

## 👩‍💻 Author

**Afifa Fatima**

Aspiring Data Scientist | Python | Machine Learning | Data Visualization

---

⭐ If you find this project interesting, feel free to explore the notebook!
