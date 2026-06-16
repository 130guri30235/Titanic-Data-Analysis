# Titanic-Data-Analysis
Exploratory Data Analysis of the Titanic Dataset using Python and Pandas.


Titanic Dataset Exploratory Data Analysis

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset using Python and Pandas. The objective is to understand passenger information, identify patterns in survival rates, detect missing values, and gain insights into factors that influenced survival during the Titanic disaster.

🎯 Objectives

- Load and explore the Titanic dataset.
- Understand the structure and dimensions of the dataset.
- Identify missing values and data quality issues.
- Analyze passenger demographics such as age, gender, and passenger class.
- Examine survival rates across different groups.
- Draw meaningful conclusions from the data.

🛠 Technologies Used

- Python
- Pandas
- Jupyter Notebook

📊 Analysis Performed

1. Data Loading

The dataset was loaded into a Pandas DataFrame using "read_csv()".

2. Dataset Exploration

- Viewed the first few records using "head()".
- Checked dataset dimensions using "shape".
- Examined column names using "columns".
- Inspected data types and non-null values using "info()".

3. Missing Value Analysis

- Identified missing values using "isnull().sum()".
- Determined which columns require data cleaning.

4. Passenger Distribution Analysis

- Analyzed gender distribution using "value_counts()".
- Examined passenger class distribution.

5. Survival Analysis

- Calculated overall survival rate.
- Compared survival rates between male and female passengers.
- Analyzed survival rates across different passenger classes.

📈 Key Findings

- The dataset contains 891 passenger records and 12 columns.
- Missing values were found in columns such as Age and Cabin.
- Female passengers had a significantly higher survival rate than male passengers.
- First-class passengers had a higher survival rate compared to second-class and third-class passengers.
- Passenger class and gender were important factors influencing survival.

📂 Project Files

- "Titanic_Analysis.ipynb" – Jupyter Notebook containing the complete analysis.
- "Titanic_Project.csv" – Titanic dataset used for analysis.

📝 Conclusion

This project demonstrates the fundamentals of data analysis using Python and Pandas. Through exploratory data analysis, meaningful insights were extracted regarding passenger demographics and survival patterns. The project also highlights the importance of data exploration and cleaning before performing advanced analytics or machine learning.

👩‍💻 Author

Gurleen Kaur
B.Tech CSE (AI) Student | Python & AI/ML Learner | Aspiring Data Analyst and AI Engineer
