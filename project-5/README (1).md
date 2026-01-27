# 📧 Spam Detection Using Naive Bayes & TF-IDF

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** techniques. The model is built using **TF-IDF Vectorization** and **Naive Bayes classification** for efficient text classification.

---

## 🚀 Project Overview

Spam detection is a common real-world application of machine learning and NLP.  
This project demonstrates how to build an **end-to-end spam classifier** using Python and scikit-learn.

### Key Features:
- Data loading from GitHub
- Text preprocessing
- TF-IDF feature extraction
- Naive Bayes classification
- Model evaluation
- Custom message testing
- Visualization of dataset distribution

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  

---

## 📂 Dataset

The dataset used contains labeled SMS messages:

- **Ham (0)** → Normal message  
- **Spam (1)** → Spam message  

Dataset Source:  
https://github.com/programmer-sahil/Ardent_ML_Training

---

## 🔍 Workflow

1. Import required libraries  
2. Load dataset  
3. Data preprocessing  
4. Text vectorization using **TF-IDF**  
5. Split data into training & testing sets  
6. Train **Naive Bayes model**  
7. Evaluate model accuracy  
8. Predict custom messages  
9. Visualize spam vs ham distribution  

---

## 📊 Visualization

A bar chart is plotted to show the distribution of **Spam vs Ham messages**, helping to understand dataset balance.

---

## 🧪 Sample Prediction

You can test custom messages such as:

** python
  sample_msgs = [
      "Congratulations! You won a free gift card",
      "Hey bro, are we still meeting tomorrow?"
  ]

## 📈 Model Performance

High accuracy using TF-IDF + Multinomial Naive Bayes

Efficient and fast text classification

## ▶️ How to Run

  ```Clone this repository:
  
  git clone https://github.com/your-username/your-repo-name.git
```

Install dependencies:
```
pip install pandas numpy scikit-learn matplotlib
```

Run the notebook:
```
jupyter notebook Project_5.ipynb
