# Titanic-EDA
This project performs comprehensive exploratory data analysis (EDA) on the famous Titanic dataset, investigating factors that influenced passenger survival rates during the disaster. The analysis utilizes Python, pandas, matplotlib, seaborn, and scikit-learn to extract meaningful insights and build a basic predictive model.
Project Structure

titanic_eda.py - Main Python script containing all analysis code
README.md - Project documentation (this file)
Generated visualizations:

missing_values.png - Visualization of missing data
survival_distribution.png - Overall survival distribution
survival_by_gender.png - Survival rates by gender
survival_by_class.png - Survival rates by passenger class
age_distribution.png - Age distribution by survival
survival_by_age_group.png - Survival rates by age group
survival_by_family_size.png - Survival rates by family size
passenger_by_port.png - Number of passengers by embarkation port
survival_by_port.png - Survival rates by embarkation port
fare_distribution.png - Fare distribution by survival
correlation_matrix.png - Correlation between numerical features
age_class_gender_survival.png - Multivariate analysis of age, class, and gender
confusion_matrix.png - Evaluation of the predictive model
feature_importance.png - Feature importance in the predictive model



Key Features

Data Cleaning and Preprocessing:

Missing value analysis and visualization
Feature engineering (age groups, family size)


Exploratory Data Analysis:

Univariate analysis of passenger demographics
Bivariate analysis of survival factors
Multivariate analysis combining key features


Data Visualization:

Bar charts for categorical comparisons
Histograms and KDE plots for distributions
Heatmaps for correlation analysis
Custom visualizations to reveal insights


Machine Learning:

Random Forest classifier implementation
Pipeline creation with preprocessing steps
Model evaluation and performance metrics
Feature importance analysis



Key Findings

Gender was the strongest predictor of survival, with females having much higher survival rates
Passenger class significantly influenced survival, with 1st class passengers having the best chances
Young children had better survival prospects compared to adults
Passengers with mid-sized families (3-4 members) had higher survival rates than those traveling alone or in very large groups
Fare paid correlated with survival rates, likely due to its relationship with passenger class and accommodation location on the ship

Skills Demonstrated

Data cleaning and handling of missing values
Exploratory data analysis techniques
Feature engineering and selection
Data visualization best practices
Pipeline construction for machine learning
Model building and evaluation
Statistical analysis and interpretation

How to Use This Project

Make sure you have the required libraries installed:
pip install pandas numpy matplotlib seaborn scikit-learn

Run the main script:
python titanic_eda.py

Review the generated visualizations and console output to understand the analysis findings

Future Improvements

Implement more advanced feature engineering techniques
Try additional machine learning algorithms and compare performance
Create an interactive dashboard for exploration
Add hypothesis testing to validate key findings
Enhance visualizations with more detailed annotations

Credits

Dataset: Titanic passenger data from Kaggle/Seaborn
Analysis and code by: Pranoti
Jan 2025- in progress
