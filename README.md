# Diabetes Prediction using Machine Learning
This project performs Exploratory Data Analysis (EDA) and builds a simple Random Forest classification model to predict diabetes based on medical features.
# Dataset
Source: Kaggle - Pima Indians Diabetes Database
Rows: 768
# Features:
  Pregnancies
  Glucose
  BloodPressure
  SkinThickness
  Insulin
  BMI
  DiabetesPedigreeFunction
  Age
  Outcome (Target: 0 = No diabetes, 1 = Diabetes)
# EDA Steps
.head(), .info(), .describe()
Check for zero values in critical columns
Class distribution plot for Outcome
Histograms and boxplots for all features
Correlation heatmap
Pairplot
Violin plots to compare feature distribution by outcome
# Model
Model Used: Random Forest Classifier
Train/Test Split: 80/20
Evaluation Metrics:
  Accuracy Score
  Confusion Matrix
  Classification Report (Precision, Recall, F1-score)
# Tech Stack
Python
Libraries: pandas, matplotlib, seaborn, scikit-learn
# How to Run
Download diabetes.csv from Kaggle and place it in your project folder.
Run the Python file (.py) or Jupyter Notebook (.ipynb).
Results and visualizations will display automatically.
