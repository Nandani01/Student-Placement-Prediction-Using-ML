# Student-Placement-Prediction-Using-ML
This project aims to build a machine learning model to predict whether a student will be placed based on their academic performance (CGPA) and aptitude (IQ).

Dataset
The dataset used for this project contains information about students, including:

cgpa: Cumulative Grade Point Average, a measure of academic performance.
iq: Intelligence Quotient, a measure of aptitude.
placement: A binary variable indicating whether the student was placed (1) or not placed (0).
The dataset was loaded from a CSV file named placement.csv.

Methodology
The project follows a standard machine learning workflow:

Data Preprocessing: The initial dataset was cleaned by removing irrelevant columns and splitting the data into training and testing sets.
Exploratory Data Analysis (EDA): Visualizations such as scatter plots, bar plots, box plots, and a heatmap were used to understand the relationships between the features and the target variable.
Feature Scaling: StandardScaler was applied to the features to normalize their range, which is important for algorithms like Logistic Regression.
Model Training: A Logistic Regression model was trained on the scaled training data.
Model Evaluation: The trained model was evaluated using the accuracy score on the test set.
Decision Boundary Visualization: The decision boundary of the trained model was visualized to show how the model separates the two classes (placed and not placed) based on CGPA and IQ.
Model Saving: The trained model was saved using pickle for future use.
Results
The model achieved an accuracy of [Insert Accuracy Score Here] on the test set, indicating its ability to predict student placement based on the provided features.
