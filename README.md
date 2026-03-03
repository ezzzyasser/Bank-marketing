# Bank Term Deposit Prediction

This project applies machine learning to predict the success of telemarketing campaigns. Using the **Bank Marketing Dataset**, the goal is to build a classification model that determines whether a client will subscribe to a term deposit ("yes" or "no").

## 🚀 Project Overview

Direct marketing campaigns are costly and time-consuming. This project demonstrates how data science can optimize these efforts by identifying the most likely prospects based on demographic data, economic indicators, and previous campaign history.

## 🛠️ Key Features

* **Data Cleaning & Preprocessing**: Handled missing values, outliers (via Isolation Forest), and categorical encoding.
* **Imbalance Handling**: Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to address the class imbalance in the target variable.
* **Exploratory Data Analysis (EDA)**: Visualized client demographics (age, job, education) and their impact on subscription rates.
* **Model Comparison**: Implemented and compared three major algorithms:
* **Support Vector Machine (SVM)**
* **Random Forest**
* **Decision Tree**


* **Performance Evaluation**: Models were assessed using Accuracy, Confusion Matrices, and Learning Curves.

## 🧰 Tech Stack

* **Language**: Python
* **Libraries**:
* `Scikit-Learn` (Modeling & Metrics)
* `Pandas` & `NumPy` (Data Manipulation)
* `Matplotlib` & `Seaborn` (Visualization)
* `Imbalanced-learn` (SMOTE)



## 📊 Results

The models were trained and tested on the `bank-additional-full.csv` dataset. The **SVM** model achieved a strong baseline accuracy of ~86%, with the project focusing on balancing precision and recall to ensure the bank doesn't miss potential customers.


