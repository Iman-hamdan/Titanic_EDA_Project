# Titanic EDA Project

## Project Overview
This project explores the Titanic dataset to analyze survival trends and generate insights. It involves:
1. Loading and inspecting the dataset.
2. Performing exploratory data analysis (EDA).
3. Visualizing survival trends by gender, class, and age.
4. Cleaning and saving the dataset.

## Key Steps
1. **Load Data**: Used pandas to load and preview the Titanic dataset.
2. **Check Missing Values**: Identified columns with missing data and decided on handling strategies.
3. **Univariate Analysis**: Visualized age and survival distributions using histograms.
4. **Bivariate Analysis**: Analyzed survival rates by gender and class using bar plots.
5. **Handle Missing Data**: Filled missing values in the `age` column and dropped columns with excessive missing data.
6. **Save Cleaned Data**: Saved the cleaned dataset for future use.

## Key Insights
1. Survival rates were higher for women compared to men.
2. Passengers in higher classes (e.g., first-class) had a greater chance of survival.
3. Age distribution showed that younger passengers had slightly better survival rates.

## Files in Repository
- `titanic3.xls`: Original dataset.
- `EDA_Titanic.ipynb`: Jupyter Notebook documenting the EDA process.
- `cleaned_titanic_data.xlsx`: Cleaned dataset.
- `README.md`: Project overview and methodology.

## Requirements
To run the analysis, install the following Python libraries:
```bash
pip install pandas matplotlib seaborn xlrd openpyxl
