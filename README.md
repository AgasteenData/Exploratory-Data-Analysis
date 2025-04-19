# Exploratory-Data-Analysis
Exploratory Data Analysis on the NHANES dataset, focusing on health, lifestyle, and demographic variables. This project cleans and visualizes data related to smoking, BMI, education level, blood pressure, and more, to uncover meaningful patterns and trends.
# NHANES Health Survey - Exploratory Data Analysis

This project performs a detailed **Exploratory Data Analysis (EDA)** on a health survey dataset from **NHANES** (National Health and Nutrition Examination Survey). The aim is to uncover patterns related to **smoking behavior, BMI, age, education level, blood pressure**, and other demographic and health indicators.

---

##  Dataset Summary

The dataset contains various health, demographic, and lifestyle metrics such as:

- **Smoking habits**
- **Gender**
- **Age**
- **Marital status**
- **Education level**
- **Weight**
- **BMI**
- **Height**
- **Systolic Blood Pressure**

---

##  Key Steps

###  Data Cleaning
- Renamed columns for better readability
- Handled missing values using mode/median
- Recoded numerical values to readable categories (e.g., gender, smoking, education)
- Removed duplicates

### Exploratory Analysis
- Created histograms for key quantitative variables
- Analyzed outliers and distributions for:
  - Age
  - Weight
  - Height
  - BMI

---

## Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy.stats`

---

## Visualizations
- KDE-based histograms to show distribution of health metrics
- Outlier detection using quantile range
- Clipped extreme values for fair visualization

---

## Insights
- Most individuals fall into a healthy BMI range.
- Data shows varied smoking patterns based on age and marital status.
- Educational level seems to correlate with certain health indicators.

