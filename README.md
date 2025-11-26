🧠 Project Overview

This project focuses on predicting house prices using the House Prices – Advanced Regression Techniques dataset from Kaggle.
The main goal: Enhance model performance using effective feature engineering techniques such as:

✔ Handling missing values
✔ Encoding categorical variables
✔ Reducing skewness in numerical features
✔ Creating new meaningful features
✔ Using advanced ML models for better accuracy

🎯 Objective

Build a machine learning model that accurately predicts housing prices by improving the dataset quality through systematic feature engineering.

📂 Dataset

Dataset Source: Kaggle
House Prices – Advanced Regression Techniques
Contains:

79 explanatory variables

SalePrice (target variable)

Files used:

File	Description
train.csv	Training data with target
test.csv	Test data without target
data_description.txt	Feature definitions
sample_submission.csv	Submission format


🔧 Tools & Libraries Used

Python

pandas

numpy

matplotlib

seaborn

scikit-learn

🏗️ Steps Performed
1️⃣ Data Loading & Initial Inspection

Checked dataset shape

Identified missing values

Analyzed SalePrice distribution

2️⃣ Missing Value Treatment

Numerical columns → filled using median

Categorical columns → filled using "None"

3️⃣ One-Hot Encoding

Applied pd.get_dummies()

Aligned columns between train & test

4️⃣ Log Transformation & Skew Correction

Applied np.log1p() on target and skewed features

Improved model stability & accuracy

5️⃣ Feature Engineering

Created helpful new features:

HouseAge

RemodAge

TotalSF (Total square footage)

TotalBath

Remodeled (Yes/No)

6️⃣ Model Building & Evaluation

Models tried:


RandomForest	
RandomForest + Log Transform	
GradientBoosting + Feature Engineering

📊 Performance Metric

Used RMSE (Root Mean Squared Error)
Model improvements showed a significant performance boost after feature engineering.


