# 💳 Credit Card Fraud Detection using Machine Learning

### 📌 Problem Statement
Credit card fraud is a critical challenge in the financial industry, causing substantial monetary losses and eroding customer trust. Financial institutions process millions of transactions daily,
where fraudulent transactions represent only a very small fraction, making fraud detection a highly imbalanced and complex classification problem.

### Traditional rule-based systems often fail to adapt to evolving fraud patterns and generate a high number of false positives, leading to poor customer experience and operational inefficiencies.
---

## 📖 Project Overview
Credit card fraud is a major challenge in the financial industry, where fraudulent transactions occur rarely but cause significant financial and reputational loss. Due to extreme class imbalance, traditional accuracy-based evaluation is insufficient for building reliable fraud detection systems.

This project focuses on building a **machine learning–based fraud detection model** that classifies transactions as **fraudulent or legitimate**, with emphasis on **precision, recall, and real-world reliability**.

---

## 🎯 Objectives
#### The objective of this project is to develop a machine learning–based fraud detection system that can accurately identify fraudulent credit card transactions while minimizing false positives and effectively handling severe class imbalance. The solution aims to support real-time risk assessment and enhance the reliability of transaction monitoring systems.
---

## 📊 Dataset Description
  - Dataset Overview:
The dataset comprises simulated credit card transactions, encompassing both genuine and fraudulent activities. The data is presented in CSV format, sourced from the Kaggle public dataset. Generated using the Sparkov Data Generation tool developed by Brandon Harris, the dataset spans from January 1, 2019, to December 31, 2020.
link for the datset :- https://www.kaggle.com/datasets/kartik2112/fraud-detection/data

---

## 🔁 Project Workflow
1. Importing required libraries  
2. Loading and inspecting the dataset  
3. Analyzing class imbalance  
4. Data preprocessing and scaling  
5. Exploratory Data Analysis (EDA)  
6. Feature–target separation  
7. Train–test split  
8. Model training  
9. Model evaluation and comparison  
10. Insight generation

---

## ⚙️ Machine Learning Models Implemented
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

These models were chosen to compare **baseline, tree-based, and ensemble approaches**.

---

## 📈 Model Evaluation Strategy
Due to class imbalance, model performance was evaluated using:
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

Accuracy was not treated as the primary metric, as it can be misleading in fraud detection problems.

---

## 🧠 Key Findings
- Class imbalance significantly impacts fraud detection models  
- Ensemble models provide better fraud detection capability  
- Recall is critical to reduce missed fraud cases  
- Proper preprocessing improves overall model reliability  


---

## 🏭 Industry Relevance
- Banking and financial services  
- Fraud detection systems  
- Risk management and compliance  
- Transaction monitoring and security analytics  

---
## 🔮 Future Enhancements
- Real-Time Fraud Detection Simulation
Extend the project to simulate real-time transaction monitoring, mimicking production fraud detection pipelines.
- Deployment as an Application
Deploy the trained model using Streamlit or Flask to enable interactive fraud prediction and model demonstration.




## 👩‍💻 Author

### Akshatha Raj
Data Science | Machine Learning | Analytics
