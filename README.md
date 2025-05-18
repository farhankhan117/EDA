# Titanic Dataset - Exploratory Data Analysis (EDA)

## Objective
Explore and preprocess the Titanic dataset to understand data, handle missing values, encode categorical variables, scale features, and remove outliers.

## Tools & Libraries
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- scikit-learn  

## Summary of Steps
- Loaded data and examined structure and statistics  
- Filled missing `Age` with median, `Embarked` with mode, dropped `Cabin` column  
- Label encoded `Sex` and one-hot encoded `Embarked`  
- Standardized `Age` and `Fare`  
- Detected and removed outliers in `Fare` (>300) using boxplot  
- Prepared cleaned dataset ready for modeling

## Conclusion
The dataset is now clean, with no missing values and properly encoded categorical variables. Outliers have been addressed, and features standardized, making the data suitable for machine learning models and further analysis.

## Project Files
- `Titanic-Dataset.csv` - Raw data  
- `titanic_eda.ipynb` - EDA code and visualizations  
- `README.md` - This summary


