# US Crime Data Analysis & Prediction (2020-2024)

An end-to-end Data Science project focused on analyzing crime patterns in the United States and building a predictive model to identify crime types and victim demographics.

## Project Overview
Using a large-scale dataset (originally 1 million records), this project explores the relationships between crime types, locations, weapons, and victim profiles. The goal is to provide data-driven insights for law enforcement and build a multi-output prediction system.

### Key Objectives:
* **Pattern Analysis:** Identifying hotspots (e.g., Harbor & Mission) and peak crime hours (6 PM - 9 PM).
* **Demographic Insight:** Analyzing which age groups (20-39) and genders are most vulnerable.
* **Predictive Modeling:** Developing a **Random Forest** model to predict both the **Type of Crime** and **Victim's Age** simultaneously.

## Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy, Datascience.
* **Visualization:** Matplotlib, Seaborn (fivethirtyeight style).
* **Machine Learning:** Scikit-learn (MultiOutputClassifier, RandomForestClassifier, LabelEncoder, StandardScaler).

## Data Pipeline
1. **Cleaning:** Dropped irrelevant columns, handled missing values, and removed duplicates.
2. **Standardization:** Unified area names, simplified crime categories into 5 main types, and categorized weapons into 7 groups.
3. **Feature Engineering:** Converted time formats, extracted "Hour" features, and encoded categorical variables for ML readiness.

## Key Findings
* **Most Frequent Crime:** Violence and Theft.
* **Main Weapon:** Physical violence followed by firearms.
* **Trend:** A general decrease in crime rates was observed between 2022 and 2024.
* **High-Risk Time:** Serious crimes peak between 6 PM and 11 PM.

## Machine Learning Model
we implemented a **Multi-Output Random Forest Classifier** to handle the complexity of predicting multiple targets (Categorical for crime type and Numerical for age).
* **Data Split:** 80% Training / 20% Testing.
* **Pre-processing:** Used Label Encoding and Feature Scaling to ensure model stability.

## Repository Contents
* `Data_management_project.ipynb`: The complete Python notebook containing EDA and Modeling.
* `Project_Report.pdf`: Comprehensive documentation including visualizations and conclusion.

---
*Developed as part of the Data Management and Representation course.*
