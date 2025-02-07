# Heart Failure Prediction using Logistic Regression and Random Forest

This project compares the performance of Logistic Regression and Random Forest models for predicting heart failure using the Heart Failure Clinical Records dataset from Kaggle.

## Dataset

The dataset contains medical records of patients and includes features such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and the presence of heart disease.  It can be downloaded from Kaggle
## Project Overview

This project explores the following steps:

1. **Data Loading and Exploration:** Loads the dataset, displays basic information, and visualizes the distribution of heart disease.
2. **Data Preprocessing:** Encodes categorical features (Sex, ChestPainType, RestingECG, ExerciseAngina, ST_Slope) using Label Encoding.  Visualizes a correlation matrix and compares systolic blood pressure between healthy and sick patients.
3. **Feature Selection:** Selects all features except 'HeartDisease' as input features (X) and 'HeartDisease' as the target variable (y).
4. **Data Scaling:** Scales the input features using StandardScaler.
5. **Data Splitting:** Splits the data into training and testing sets (80/20 split).
6. **Model Training and Evaluation:**
    * **Logistic Regression:** Trains a Logistic Regression model, makes predictions on the test set, and evaluates performance using classification report, confusion matrix, and accuracy. Visualizes the classification results based on RestingBP and Cholesterol.
    * **Random Forest:** Trains a Random Forest model, makes predictions, and evaluates performance using classification report, confusion matrix, and accuracy.
7. **Results Comparison:** Compares the accuracy of both models and presents the results in a DataFrame.

## Requirements

* Python 3
* Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
