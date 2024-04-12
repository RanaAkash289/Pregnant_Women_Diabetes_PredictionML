# Pregnant_Women_Diabetes_PredictionML

Overview
This project focuses on predicting diabetes in pregnant women using machine learning techniques. Given the significant health risks associated with gestational diabetes, our goal was to develop an efficient predictive model to assist in early diagnosis and intervention.

Dataset
We utilized the Pima Indian Diabetes Dataset (PIDD) from the UCI Machine Learning Repository, which features medical attributes such as glucose concentration, BMI, insulin levels, and more, across 768 patients.

Methodology
Our approach involved preprocessing the data to handle null values and split the dataset into training and testing subsets (70/30 split). We implemented two machine learning models:

Random Forest Classifier: An ensemble method that combines multiple decision trees to improve prediction accuracy.
XGBoost Classifier: A gradient boosting framework that uses a series of weak learners to create a strong predictive model.
Results
The performance of the models was evaluated based on their accuracy in predicting diabetes:

Random Forest Accuracy: 73.6%
XGBoost Accuracy: 74.3%
XGBoost slightly outperformed Random Forest, indicating a more robust model for this particular dataset.

Conclusion
The project successfully demonstrated the use of ensemble and boosting techniques to predict gestational diabetes. These models can potentially assist healthcare providers in making timely decisions to manage and treat diabetes effectively.

Future Work
Further enhancements will focus on refining the models to address diagnostic errors and integrate additional predictors to improve accuracy and reliability.
