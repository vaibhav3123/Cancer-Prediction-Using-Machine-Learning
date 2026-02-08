# 🩺 Cancer Prediction Using Machine Learning (Logistic Regression)

## 📌 Project Overview

This project focuses on predicting whether a breast tumor is **Malignant (cancerous)** or **Benign (non-cancerous)** using **Logistic Regression**, a supervised machine learning algorithm.
The model is trained on medical diagnostic data and evaluated for accuracy.

## 🎯 Objective

* To build a machine learning model that predicts cancer diagnosis
* To preprocess medical data using scaling techniques
* To evaluate model performance using accuracy and confusion matrix

## 🗂 Dataset

* Dataset used: **Breast Cancer Dataset**
* Target variable: `diagnosis`

  * `1` → Malignant (Cancerous)
  * `0` → Benign (Non-cancerous)
* Unnecessary columns like `id` and `Unnamed: 32` are removed

## 🛠️ Technologies & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## ⚙️ Project Workflow

1. Import required libraries
2. Load and explore the dataset
3. Handle missing values
4. Data visualization and analysis
5. Encode target variable
6. Feature scaling using **StandardScaler**
7. Train-test split
8. Model training using **Logistic Regression**
9. Model evaluation
10. Prediction on new data

## 📊 Model Evaluation

* **Accuracy Score** is used to evaluate the model
* **Confusion Matrix** helps understand prediction performance

## 🔍 Sample Prediction

The model can predict cancer diagnosis for new patient data:

* **Output**

  * `1` → Malignant
  * `0` → Benign

Example result:

Diagnosis: Malignant

## 📌 Conclusion

This project demonstrates how machine learning can assist in medical diagnosis by predicting cancer using Logistic Regression. It highlights the importance of data preprocessing, feature scaling, and proper model evaluation.

## 🙌 Author

**Vaibhav Bari**
MCA (Data Science)
📍 India

