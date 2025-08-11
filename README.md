# Internship-Task-5

# Heart Disease Prediction using Decision Tree & Random Forest
Project Overview
This project focuses on predicting the likelihood of heart disease using machine learning algorithms — Decision Tree Classifier and Random Forest Classifier.
The dataset (heart.csv) contains patient health records, and the models aim to classify patients as having heart disease or no heart disease.

The project uses GridSearchCV for hyperparameter tuning, evaluates performance using ROC-AUC score, confusion matrix, and classification report, and visualizes the models for better interpretability.

📂 Dataset
File: heart.csv

Source: Kaggle - Heart Disease UCI Dataset

Description: The dataset contains features like age, cholesterol, blood pressure, heart rate, etc.

# Tech Stack
Programming Language: Python

Libraries:

pandas — Data manipulation

numpy — Numerical operations

matplotlib & seaborn — Data visualization

scikit-learn — Model building & evaluation

# Steps Performed
Data Loading & Preprocessing

Load dataset and check for missing values

Split data into training & testing sets

Model Building

Decision Tree Classifier

Random Forest Classifier

Hyperparameter Tuning

Used GridSearchCV to find the best parameters

Model Evaluation

Accuracy, ROC-AUC score

Confusion Matrix

Classification Report

Visualization

Decision Tree plot

ROC Curve

Feature importance (Random Forest)

Model Comparison

Compared Decision Tree and Random Forest performance

# Results
| Model         | Accuracy (Test) | ROC-AUC Score |   |
| ------------- | --------------- | ------------- | - |
| Decision Tree | **96.99%**      | **0.979**     |   |
| Random Forest | **99.16%**      | **0.9662**     |   |

# How to Run
# Clone the repository
git clone https://github.com/BL1183757/Internship-Task-5.git
cd Internship-Task-5

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook Internship_Task_5.ipynb

# Visualizations
Decision Tree Structure (first 3 levels)

Random Forest Feature Importance

ROC Curves for both models

Confusion Matrices

# Conclusion
Random Forest performed slightly better in terms of accuracy and ROC-AUC score.

Feature importance analysis helps identify the key health factors influencing predictions.

# License
This project is licensed under the MIT License.

