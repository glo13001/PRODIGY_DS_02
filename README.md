# PRODIGY_DS_02
Titanic Dataset Exploratory Data Analysis (EDA)
This repository contains Python code to perform Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic dataset from Kaggle.

About the Dataset
The Titanic dataset consists of passenger information such as age, gender, class, embarkation point, and survival status. The goal of this analysis is to explore the relationships between variables and identify patterns and trends in the data.

Files in the Repository
-train.csv: The original dataset file.
-titanic_eda.ipynb: Jupyter Notebook containing the Python code for data cleaning and exploratory data analysis.
-README.md: This file, providing an overview of the project.

Data Cleaning and EDA Process
1.Importing Libraries and Loading Data: The necessary libraries (pandas, matplotlib, and seaborn) are imported, and the dataset is loaded.
2.Data Cleaning:
Handling missing values: Missing values in the 'Age' and 'Embarked' columns are filled, and the 'Cabin' column is dropped due to excessive missing data.
3.Exploratory Data Analysis:
-Univariate analysis: Distributions of numerical features (Age), gender distribution, class distribution, and survival count are visualized.
-Bivariate analysis: Relationships between variables like class vs. survival, gender vs. survival, age vs. survival, and embarked port vs. survival are explored.
