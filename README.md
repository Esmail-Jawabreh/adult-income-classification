# Adult Income Classification

## Overview
This project applies machine learning classification techniques to predict whether an individual's income exceeds $50K per year based on demographic and employment-related attributes.  
The project uses the **Adult Census Income Dataset** from the UCI Machine Learning Repository.

## Dataset
- **Source:** [UCI Machine Learning Repository – Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)  
- **File:** `adult.csv`  
- **Description:** Contains demographic and work-related attributes such as age, education, occupation, hours-per-week, and income category.

## Objectives
1. Load and explore the dataset.
2. Handle missing values and perform data cleaning.
3. Encode categorical variables for machine learning models.
4. Train and evaluate classification models (e.g., Logistic Regression, Decision Tree, Random Forest).
5. Compare model performance and select the best one.

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

## Key Steps & Results
- **Data Preprocessing:** Handled missing values and encoded categorical features.
- **Modeling:** Trained multiple models and evaluated them using accuracy and classification reports.
- **Best Model:** Random Forest Classifier achieved the highest accuracy (XX%).
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix.

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/adult-income-classification.git
   cd adult-income-classification
