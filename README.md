🚢 Titanic Dataset Analysis (Exploratory Data Analysis)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset to understand passenger characteristics and identify factors that influenced survival.
The analysis combines manual EDA using Python with an automated data profiling report generated using YData Profiling.

The goal of this project is to:
Understand the structure and quality of the dataset
Identify missing values and data inconsistencies
Analyze relationships between features and survival outcome
Generate insights using statistical summaries and visualizations

🧠 Dataset Description
The Titanic dataset contains information about passengers onboard the RMS Titanic.
Key Features:

Survived – Survival status (0 = No, 1 = Yes)
Pclass – Passenger class
Name – Passenger name
Sex – Gender
Age – Age of passenger
SibSp – Number of siblings/spouses aboard
Parch – Number of parents/children aboard
Fare – Ticket fare
Embarked – Port of embarkation

🔍 Exploratory Data Analysis Performed

The notebook covers the following steps:

1️⃣ Data Loading & Inspection
Reading the dataset
Checking shape and column types
Initial data preview

2️⃣ Data Quality Checks
Missing value analysis
Duplicate checks
Data type validation

3️⃣ Statistical Summary
Descriptive statistics for numerical features
Distribution analysis

4️⃣ Univariate Analysis
Survival distribution
Gender, class, and age distributions

5️⃣ Bivariate Analysis
Survival vs Gender
Survival vs Passenger Class
Survival vs Age and Fare

6️⃣ Insights & Observations
Survival patterns across different groups
Impact of socio-economic factors on survival

📊 Automated Data Profiling (YData Profiling)

In addition to manual EDA, this project includes a YData Profiling report that provides:
Dataset overview
Missing value heatmaps
Feature distributions
Correlation analysis
Alerts for data quality issues
📁 The report is available as:
ydata_profiling_report.html




🚀 How to View the EDA
Because GitHub has limitations rendering complex interactive widgets, I have optimized the notebook for static viewing.

Static View: Open Analyzing_the_Titanic_dataset.ipynb directly in GitHub.
Interactive View: If you want to see the full interactive ydata-profiling report, you can run the notebook locally or in Google Colab.
Google Colab link :https://colab.research.google.com/drive/1me4wcJugEi5wtUO_xbjjVw3c1mwTyzf9?usp=sharing
