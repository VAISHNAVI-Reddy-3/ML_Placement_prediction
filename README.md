# ML Placement Prediction System

## Overview
The **ML Placement Prediction System** is a machine learning project designed to predict whether a student is likely to get placed based on relevant student features.

The project uses supervised machine learning classification algorithms to learn patterns from historical student data and predict placement status.

## Objectives
- Analyze student data and identify patterns related to placement.
- Preprocess data by handling missing values and encoding categorical features.
- Train and evaluate machine learning classification models.
- Compare model performance and predict student placement status.

## Machine Learning Models
The project explores classification algorithms such as:
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Git and GitHub

## Project Workflow
1. Data collection and loading
2. Data cleaning and preprocessing
3. Feature selection and transformation
4. Train-test splitting
5. Model training
6. Model evaluation
7. Placement status prediction

## Dataset
The project uses student placement data containing multiple features. The target variable is `PlacementStatus`.

Identifiers and features that could cause data leakage, such as student IDs and post-placement salary information, should be excluded from model training.

## Model Evaluation
Models can be evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/VAISHNAVI-Reddy-3/ML_Placement_prediction.git
   ```

2. Open the project folder:

   ```bash
   cd ML_Placement_prediction
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

4. Open the Python scripts or notebooks and run the project according to the file structure.

## Repository
GitHub: https://github.com/VAISHNAVI-Reddy-3/ML_Placement_prediction

## Author
Vaishnavi

## Disclaimer
This project is intended for educational purposes. Predictions depend on the quality of the dataset and the trained model.
