# Titanic Dataset - Exploratory Data Analysis (EDA)

## Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify factors that influenced passenger survival.

The analysis includes data cleaning, handling missing values, outlier treatment, feature engineering, visualization, and extracting insights from the dataset.

## Dataset
- Dataset: Titanic Dataset
- Source: Kaggle Titanic Competition

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## EDA Steps Performed

### Data Cleaning
- Handled missing values
- Removed unnecessary columns
- Checked for duplicates

### Feature Engineering
- Created `family_size`
- Created `family_type`
- Extracted passenger titles from the `Name` column

### Outlier Treatment
- Z-Score Method
- IQR Method

### Encoding
- One-Hot Encoding
- Label Encoding

### Visualizations
- Count Plots
- Histograms
- KDE Plots
- Box Plots
- Heatmaps
- Survival Analysis Charts

## Key Insights

### Survival Patterns
- Female passengers had significantly higher survival rates.
- First-class passengers were more likely to survive.
- Children had better survival chances than adults.

### Economic Factors
- Higher fare passengers showed better survival rates.
- Passenger class strongly influenced survival.

### Family Factors
- Small families had higher survival rates.
- Passengers traveling alone had lower survival rates.

### Feature Importance
Important features identified:
- Sex
- Pclass
- Fare
- Age
- Title
- Family Type

## Conclusion
Survival on the Titanic was heavily influenced by gender, passenger class, age, and socioeconomic status. Feature engineering and data preprocessing helped uncover meaningful patterns that can be used for predictive modeling.

## Project Structure

```
Titanic-EDA/
│
├── Titanic_EDA.ipynb
├── README.md
└── images/
```

## Future Work
- Build Machine Learning models
- Compare classification algorithms
- Perform feature selection
- Hyperparameter tuning

## Author
Sourav Kumar
B.Tech AIML, BIT Mesra
