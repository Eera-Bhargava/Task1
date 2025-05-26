# Task1
# Titanic Dataset: Data Cleaning & Preprocessing

This project focuses on **data preprocessing, visualization, and feature engineering** using the Titanic dataset. It includes handling missing values, encoding categorical variables, outlier detection, normalization, and preparing the dataset for machine learning models.

# Features Implemented

- Handled missing values (`Age`, `Cabin`, `Embarked`) using statistical strategies
- Replaced missing values based on `Survived` status (conditional imputation)
- Encoded categorical features (`Sex`, `Embarked`, `Cabin`, `Pclass`)
- Standardized numerical features (`Age`, `Fare`, `SibSp`, `Parch`)
- Visualized and removed outliers using boxplots and IQR method
- Dataset ready for ML model training



# Technologies Used
- Python 
- Pandas 
- NumPy 
- Matplotlib 
- Seaborn 
- Scikit-learn 


# Boxplot

![Boxplot](visualizations/boxplot_age.png)
> Outliers were detected in columns like `Fare`, `Age`, and `SibSp`.


#Future Work
- Train ML models like Logistic Regression or Decision Tree
- Perform hyperparameter tuning
- Evaluate model performance using accuracy, precision, recall, and AUC


