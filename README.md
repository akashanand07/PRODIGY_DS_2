# PRODIGY_DS_2
Task-02: Data Cleaning & Exploratory Data Analysis (EDA)
📌 Project Overview
This project is part of Prodigy InfoTech Data Science Internship (Task-02).
The objective is to perform data cleaning and exploratory data analysis on a dataset, identify relationships between variables, and uncover patterns and trends in the data.

For demonstration, the Titanic dataset from Kaggle was used.

📂 Dataset
Source: Kaggle Titanic Dataset (or dataset provided in the task link)

Rows: 891

Columns: 12

Target Variable: Survived (0 = No, 1 = Yes)

🛠 Steps Performed
1️⃣ Data Loading & Inspection
Loaded dataset using pandas.

Inspected first few rows and dataset info.

Checked for missing values and data types.

2️⃣ Data Cleaning
Handled missing values in Age, Cabin, and Embarked.

Converted categorical variables into numerical format using label encoding / one-hot encoding.

Removed irrelevant columns (PassengerId, Name, Ticket) for EDA purposes.

3️⃣ Exploratory Data Analysis (EDA)
Univariate Analysis:

Distribution of Age, Fare.

Countplots for Gender, Survival, Passenger Class.

Bivariate Analysis:

Survival rate by Gender.

Survival rate by Pclass.

Relationship between Age and Survival.

Correlation Heatmap to identify relationships between numeric variables.

4️⃣ Key Findings
Females had a much higher survival rate compared to males.

1st class passengers were more likely to survive than 2nd or 3rd class.

Younger passengers (especially children) had higher survival rates.

Fare amount had a positive correlation with survival.

📊 Visualizations
Bar plots for gender vs survival.

Histograms for age distribution.

Heatmap for correlations.

Boxplots for fare vs class.

BELOW IMAGES ARE UPLOADED FOR DEATILED


1)SERVIVAL RATE BY GENDER

<img width="705" height="556" alt="TITANIC" src="https://github.com/user-attachments/assets/0261c00c-a8f4-47b4-8d15-9d3c388cb65d" />

