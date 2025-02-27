# Semiconductor Yield Prediction Using Machine Learning

## Project Overview
This project focuses on predicting the *pass/fail yield* of semiconductor manufacturing entities using machine learning. The goal is to determine the most important sensor signals that impact yield, improving *process throughput, reducing production costs, and decreasing time to learning*.

## Steps Followed

1. *Data Import & Exploration*  
   - Load dataset and inspect features.
   - Handle missing values and drop unnecessary columns.

2. *Data Analysis & Visualization*  
   - Univariate, Bivariate, and Multivariate Analysis.
   - Correlation heatmaps and pairplots.

3. *Data Preprocessing*  
   - Segregate *features & target* (pass/fail).
   - Handle class imbalance using *SMOTE* if needed.
   - Split data into *train & test* sets.
   - Standardize numerical features.

4. *Model Training & Hyperparameter Tuning*  
   - Train multiple classifiers (*Random Forest, SVM, Naive Bayes*).
   - Use *GridSearchCV* for hyperparameter tuning.
   - Compare models based on accuracy & classification reports.

5. *Model Selection & Saving*  
   - Select the best-performing model.
   - Save the model using joblib for future use.

## Dataset Description
- *File Name:* sensor-data.csv
- *Shape:* (1567, 592)
- *Target Variable:* Pass/Fail (−1 = Pass, 1 = Fail)
- *Features:* 591 sensor signals collected during manufacturing.

##  Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Google Colab
