Task 5: Train-Test Split & Evaluation Metrics

Introduction

The purpose of this task is to understand the concept of Train-Test Split and evaluate the performance of a Machine Learning model using various evaluation metrics. The Heart Disease Dataset was used to train and test a Logistic Regression model.

Tools Used

- Python
- Scikit-Learn

Dataset

Heart Disease Dataset

Objectives

1. Split the dataset into training and testing sets.
2. Understand the purpose of training and testing data.
3. Train a Logistic Regression model.
4. Predict outcomes on test data.
5. Calculate Accuracy, Precision, and Recall.
6. Understand and explain the Confusion Matrix.
7. Interpret the model results.

Train-Test Split

The dataset was divided into two parts:

- Training Data (80%)
- Testing Data (20%)

Training data was used to train the model, while testing data was used to evaluate its performance on unseen data.

Model Training

A Logistic Regression model was trained using the training dataset. After training, the model learned patterns from the data and was used for prediction.

Prediction

The trained model was applied to the testing dataset to generate predictions.

Evaluation Metrics

Accuracy

Accuracy measures the proportion of correctly predicted observations to the total observations.

Precision

Precision measures how many predicted positive cases are actually positive.

Recall

Recall measures how many actual positive cases are correctly identified by the model.

Confusion Matrix

A Confusion Matrix is used to evaluate the performance of a classification model by comparing actual values with predicted values.

It consists of:

- True Positive (TP)
- True Negative (TN)
- False Positive (FP)
- False Negative (FN)

Results

The Logistic Regression model was successfully trained and tested on the Heart Disease Dataset. The evaluation metrics were calculated to assess the model's performance and prediction capability.

Files Included

- task5.py
- heart.csv
- output.png
- README.md

Conclusion

This task provided practical understanding of Train-Test Split, Logistic Regression, Accuracy, Precision, Recall, and Confusion Matrix. It also demonstrated how model evaluation helps in measuring the effectiveness of a Machine Learning model.