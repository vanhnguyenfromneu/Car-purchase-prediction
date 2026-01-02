# 🚗 Car Purchase Prediction

## Project Overview
This project aims to predict whether a customer will purchase a car based on their demographic information (Gender, Age) and Estimated Salary. This is a binary classification problem using the `Social_Network_Ads` dataset.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, TensorFlow (Keras)
* **Environment:** Google Colab

## 📊 Model Performance
I implemented and compared four different machine learning models. Below are the evaluation results on the test set:

| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| **Logistic Regression** | 88.7% | 0.913 | 0.750 | 0.824 |
| **Decision Tree** | 91.2% | 0.839 | 0.929 | 0.881 |
| **Random Forest** | 91.2% | 0.862 | 0.893 | 0.877 |
| **Neural Network (ANN)** | **93.8%** | **0.897** | **0.929** | **0.912** |

🏆 **Conclusion:** The **Neural Network** model achieved the highest performance across most metrics, demonstrating superior capability in capturing non-linear relationships in this dataset.

## 📂 Dataset
The dataset used is `Social_Network_Ads.csv`.
* **Features:** Gender, Age, EstimatedSalary
* **Target:** Purchased (0 or 1)
