**🚢 Titanic Dataset Exploratory Data Analysis (EDA)**

**📌 Project Overview**

This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset to understand passenger demographics and identify key factors that influenced survival.

The analysis combines:
Manual EDA using Python (NumPy, Pandas, Matplotlib, Seaborn)
Automated data profiling using YData Profiling

**🎯 Objectives**

Understand the structure and quality of the dataset
Identify missing values and data inconsistencies
Analyze relationships between features and survival outcomes
Extract meaningful insights using statistics and visualizations

**🧠 Dataset Description**

The Titanic dataset contains information about passengers aboard the RMS Titanic.

**📊 Key Features**

Survived – Survival status (0 = No, 1 = Yes)
Pclass – Passenger class (1st, 2nd, 3rd)
Name – Passenger name
Sex – Gender
Age – Passenger age
SibSp – Number of siblings/spouses aboard
Parch – Number of parents/children aboard
Fare – Ticket fare
Embarked – Port of embarkation

**🔍 Exploratory Data Analysis Workflow**


**1️⃣ Data Loading & Initial Inspection**
Dataset loading
Shape and column inspection
Preview of initial records

**2️⃣ Data Quality Checks**
Missing value analysis
Duplicate detection
Data type validation

**3️⃣ Statistical Summary**

Descriptive statistics for numerical features
Distribution analysis

**4️⃣ Univariate Analysis**

Survival distribution
Gender distribution
Passenger class distribution
Age distribution

**5️⃣ Bivariate Analysis**

Survival vs Gender
Survival vs Passenger Class
Survival vs Age
Survival vs Fare

**6️⃣ Insights & Observations**

Survival patterns across different demographic groups
Impact of socio-economic factors on survival probability

**📊 Automated Data Profiling (YData Profiling)**

Along with manual EDA, this project includes a YData Profiling report that provides:
Dataset overview
Missing value heatmaps
Feature distributions
Correlation analysis
Automated data quality alerts
📁 Report file:
ydata_profiling_report.html

**🚀 How to View the Analysis**
🔹 Static View (GitHub)

GitHub has limitations rendering interactive widgets, so the notebook is optimized for static viewing:

👉 Notebook on GitHub:
https://github.com/Harshh777/Data-Storytelling-Analysing-Survival-on-the-Titanic/blob/main/Analyzing_the_Titanic_dataset.ipynb

🔹 Interactive View (Recommended)

To explore the full interactive YData Profiling report, run the notebook locally or open it in Google Colab:

👉 Google Colab Notebook:
https://colab.research.google.com/drive/1me4wcJugEi5wtUO_xbjjVw3c1mwTyzf9?usp=sharing

**🛠 Tools & Libraries Used**

Python
Pandas
NumPy
Matplotlib
Seaborn
YData Profiling

**📌 Key Takeaways**

Gender and passenger class significantly influenced survival

Higher-class passengers had better survival chances

Females showed a much higher survival rate than males

Fare and age showed meaningful relationships with survival outcomes
