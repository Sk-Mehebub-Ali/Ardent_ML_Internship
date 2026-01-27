# Credit Card Fraud Detection using Machine Learning

**Project-6**

## 📌 Project Overview

This project focuses on building a **Credit Card Fraud Detection system** using machine learning techniques. The goal is to classify transactions as **fraudulent (1)** or **legitimate (0)** based on transaction features. Due to the highly imbalanced nature of fraud datasets, special care is taken during model training and evaluation.

Two powerful ensemble learning algorithms are implemented and compared:

* **Random Forest Classifier**
* **XGBoost (Extreme Gradient Boosting)**

---

## 🎯 Objectives

* Load and explore a credit card transaction dataset
* Perform data preprocessing and feature engineering
* Train multiple machine learning models
* Evaluate model performance using standard classification metrics
* Visualize important features contributing to fraud detection

---

## 🛠️ Technologies & Libraries Used

* **Python 3**
* **NumPy** – Numerical computations
* **Pandas** – Data manipulation and analysis
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning models & evaluation
* **XGBoost** – High-performance gradient boosting

---

## 📂 Project Structure

```
project6.ipynb
README.md
```

---

## 🔍 Workflow

1. **Import Libraries**
   Load all required Python libraries.

2. **Load Dataset**
   Read the credit card transaction dataset into a Pandas DataFrame.

3. **Data Preprocessing**

   * Handle missing values (if any)
   * Feature scaling and transformation
   * Train-test split

4. **Model Training**

   * Train **Random Forest Classifier**
   * Train **XGBoost Classifier**

5. **Model Evaluation**
   Models are evaluated using:

   * Accuracy
   * Precision
   * Recall
   * F1 Score
   * ROC-AUC Score
   * Confusion Matrix

6. **Feature Importance Visualization**
   Plot the top important features using XGBoost.

---

## 📊 Evaluation Metrics

The following metrics are used to measure performance:

| Metric    | Description                                  |
| --------- | -------------------------------------------- |
| Accuracy  | Overall correctness of the model             |
| Precision | How many predicted frauds are actually fraud |
| Recall    | How many actual frauds were detected         |
| F1 Score  | Balance between precision & recall           |
| ROC-AUC   | Probability of correct classification        |

---

## 📈 Results

* XGBoost outperforms Random Forest in detecting fraudulent transactions.
* High **Recall** and **ROC-AUC** scores ensure fewer fraud cases are missed.
* Feature importance analysis helps understand key factors behind fraud prediction.

---

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/Tanmoydey2004/ML-INTERNSHIP/blob/main/Project%20-%3E%206/project6.ipynb
```

2. Install required packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

3. Run the notebook:

```bash
jupyter notebook project6.ipynb
```

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Use of SMOTE for data balancing
* Deep learning models (ANN, LSTM)
* Real-time fraud detection pipeline

---
