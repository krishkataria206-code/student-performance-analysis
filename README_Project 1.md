# student-performance-analysis
Student Performance Prediction and Learning Pattern Analysis , K-Means, Logistic Regression, and Random Forest.
Student Performance Prediction and Learning Pattern Analysis
Project Overview
This project analyzes student academic performance to understand learning patterns and predict whether a student will pass or fail the final exam. The analysis uses machine learning techniques including clustering and classification models.
The goal is to identify different student learning behaviors and build predictive models that can help educational institutions detect students who may need additional academic support.
Dataset
The dataset used in this project is the Students Performance in Exams dataset obtained from Google.
It contains information about student exam scores and background attributes such as gender, parental education level, and lunch type.
Main features include:
Math Score
Reading Score
Writing Score
Gender
Parental Level of Education
Lunch Type
Test Preparation Course

A new variable called average_score was created to represent overall performance.
Project Objectives
The main objectives of this project are:
Perform Exploratory Data Analysis (EDA) to understand patterns in student performance.
Identify learning profiles using clustering techniques.
Build machine learning models to predict whether a student will pass or fail.
Evaluate model performance using cross-validation and classification metrics.

Methodology
1. Data Exploration
The dataset was explored to understand distributions and relationships between variables. Visualizations such as histograms, boxplots, and correlation heatmaps were used to analyze score patterns.

2. Feature Engineering
An average score was calculated from the math, reading, and writing scores.
Students were labeled as Pass or Fail based on their average score.

3. Unsupervised Learning
K-Means Clustering was applied to identify student learning profiles based on exam performance.
Example clusters include:
Consistent learners
Average learners
Struggling learners

4. Supervised Learning
Two machine learning models were trained to predict pass/fail outcomes:
Logistic Regression
Random Forest Classifier

5. Model Evaluation
Model performance was evaluated using:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Cross Validation

Results
Both models achieved very high prediction accuracy.
Logistic Regression Accuracy: 100%
Random Forest Accuracy: 100%
The models were able to correctly classify all students in the test dataset.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Project Structure
student-performance-analysis

│
├── student_performance_analysis.ipynb
├── summary.txt
└── README.md
Conclusion
This project demonstrates how machine learning techniques can be used to analyze educational data and predict student performance. Such models can help institutions identify students at risk and provide early academic interventions.
Kaggle:
Students Performance in Exams Dataset
