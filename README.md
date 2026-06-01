# Task 5: Train-Test Split & Evaluation Metrics

## 📌 Project Overview

This project demonstrates the implementation of **Train-Test Split** and the evaluation of a **Logistic Regression** model using the **Heart Disease Dataset**. The objective is to understand how machine learning models are trained, tested, and evaluated using standard classification metrics.

---

## 🛠️ Technologies Used

* Python
* Scikit-Learn
* Pandas
* NumPy
* Matplotlib
* Seaborn

## 📂 Dataset

**Heart Disease Dataset (`heart.csv`)**

The dataset contains medical attributes used to predict whether a patient is likely to have heart disease.

## 🎯 Objectives

* Split the dataset into training and testing sets.
* Understand the importance of Train-Test Split in Machine Learning.
* Train a Logistic Regression model.
* Generate predictions on unseen test data.
* Evaluate model performance using:

  * Accuracy
  * Precision
  * Recall
  * Confusion Matrix
* Interpret the model's prediction results.

## 🔄 Train-Test Split

The dataset was divided into:

* **Training Set:** 80%
* **Testing Set:** 20%

The training set was used to train the model, while the testing set was used to evaluate its performance on unseen data.

## 🤖 Model Training

A **Logistic Regression** classifier was trained using the training dataset. The model learned patterns and relationships from the data to predict the presence of heart disease.

---

## 🔍 Prediction

After training, the model was used to make predictions on the testing dataset. These predictions were then compared with the actual values to evaluate model performance.

---

## 📊 Evaluation Metrics

### Accuracy

Accuracy measures the proportion of correctly classified instances among all observations.

**Formula:**

Accuracy = (TP + TN) / (TP + TN + FP + FN)

---

### Precision

Precision indicates how many of the predicted positive cases are actually positive.

**Formula:**

Precision = TP / (TP + FP)

---

### Recall

Recall measures how many actual positive cases were correctly identified by the model.

**Formula:**

Recall = TP / (TP + FN)

---

## 📈 Confusion Matrix

A Confusion Matrix provides a detailed breakdown of classification results.

It consists of:

* **True Positive (TP):** Correctly predicted positive cases
* **True Negative (TN):** Correctly predicted negative cases
* **False Positive (FP):** Incorrectly predicted positive cases
* **False Negative (FN):** Incorrectly predicted negative cases

The confusion matrix helps in understanding the strengths and weaknesses of the classification model.

---

## ✅ Results

The Logistic Regression model was successfully trained and evaluated on the Heart Disease Dataset. Performance metrics such as Accuracy, Precision, Recall, and the Confusion Matrix were used to assess the model's effectiveness in predicting heart disease.

---

## 📁 Project Structure

```text
Task-5/
│
├── task5.py          # Model implementation
├── heart.csv         # Dataset
├── output.png        # Output/Result visualization
└── README.md         # Project documentation
```

---

## 🏁 Conclusion

This project provided hands-on experience with:

* Train-Test Split methodology
* Logistic Regression for classification
* Model prediction techniques
* Evaluation metrics such as Accuracy, Precision, and Recall
* Interpretation of the Confusion Matrix

These concepts are fundamental for building and evaluating Machine Learning classification models effectively.
