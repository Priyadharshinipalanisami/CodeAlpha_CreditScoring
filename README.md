# CodeAlpha_CreditScoring
💳 Credit Scoring AI | Machine Learning based Credit Risk Prediction System that analyzes financial data and predicts customer creditworthiness using Logistic Regression, Decision Tree, and Random Forest algorithms.
# 💳 Credit Scoring AI - Machine Learning Based Credit Risk Prediction

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Python-blue)
![Python](https://img.shields.io/badge/Python-3.x-yellow)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)

## 📌 Project Overview

**Credit Scoring AI** is a Machine Learning-based system that predicts an individual's creditworthiness by analyzing financial and personal information.

The project helps financial institutions identify potential risks by classifying customers into:

✅ Good Credit Risk
⚠️ Bad Credit Risk

This model can support faster and smarter loan approval decisions.

---

# 🎯 Project Objective

The main objective of this project is to:

* Analyze customer financial history
* Predict credit risk automatically
* Compare different Machine Learning algorithms
* Build an efficient credit scoring model

---

# 🛠️ Technologies Used

| Category             | Tools               |
| -------------------- | ------------------- |
| Programming Language | Python              |
| Data Processing      | Pandas, NumPy       |
| Visualization        | Matplotlib, Seaborn |
| Machine Learning     | Scikit-Learn        |
| Model Saving         | Joblib              |
| Development          | Jupyter Notebook    |

---

# 📂 Dataset Information

**Dataset:** German Credit Dataset

### Features Used:

| Feature          | Description         |
| ---------------- | ------------------- |
| Age              | Customer age        |
| Sex              | Customer gender     |
| Job              | Employment category |
| Housing          | Living status       |
| Saving Accounts  | Customer savings    |
| Checking Account | Bank account status |
| Credit Amount    | Loan amount         |
| Duration         | Loan period         |
| Purpose          | Loan purpose        |

### Target Variable:

```
Risk
```

Classes:

```
Good ✅
Bad ⚠️
```

---

# 🔍 Exploratory Data Analysis

The project includes detailed analysis:

📊 Credit Risk Distribution
📊 Age Distribution
📊 Credit Amount Analysis
📊 Loan Duration Analysis
📊 Housing Analysis
📊 Loan Purpose Analysis
📊 Savings & Checking Account Analysis
📈 Correlation Heatmap

---

# 🤖 Machine Learning Models

Three classification algorithms were implemented:

## 1️⃣ Logistic Regression

A statistical classification model used for binary credit risk prediction.

## 2️⃣ Decision Tree Classifier

Creates decision rules based on customer financial attributes.

## 3️⃣ Random Forest Classifier 🌳

An ensemble learning algorithm that improves prediction accuracy using multiple decision trees.

---

# 📈 Model Evaluation

Models are evaluated using:

| Metric    | Purpose                              |
| --------- | ------------------------------------ |
| Accuracy  | Overall prediction correctness       |
| Precision | Correct risk predictions             |
| Recall    | Finding risky customers              |
| F1 Score  | Balance between precision and recall |
| ROC-AUC   | Model classification performance     |

---

# 🏆 Model Performance Comparison

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 75%      | 78%       | 82%    | 80%      |
| Decision Tree       | 70%      | 73%       | 75%    | 74%      |
| Random Forest       | 78%      | 81%       | 84%    | 82%      |

🏆 **Best Model: Random Forest Classifier**

---

# 💾 Model Deployment

The trained model is saved as:

```
credit_scoring_model.pkl
```

This saved model can be integrated into real-world banking applications.

---

# 📁 Project Structure

```
CodeAlpha_CreditScoringAI
│
├── Dataset
│   └── german_credit_data.csv
│
├── Visualisation.ipynb
│
├── Notebook
│   └── Credit_Scoring_Model.ipynb
│
├── Model
│   └── credit_scoring_model.pkl
│
├── requirements.txt
└── README.md
```

---

# ▶️ How to Run Project

### Install Libraries

```bash
pip install -r requirements.txt
```

### Run Python File

```bash
python credit_scoring_model.py
```

---

# 🌟 Key Highlights

✨ Complete Machine Learning Pipeline
✨ Data Cleaning & Preprocessing
✨ Exploratory Data Analysis
✨ Multiple ML Model Comparison
✨ Performance Evaluation
✨ Model Saving for Future Prediction
📊 Results

The Credit Scoring AI model successfully predicts customer credit risk by analyzing financial and personal attributes. Multiple classification algorithms were trained and evaluated to identify the best-performing model.

Model Performance
Model	Accuracy	Precision	Recall	F1 Score	ROC-AUC
Logistic Regression	75%	78%	82%	80%	74%
Decision Tree	70%	73%	75%	74%	69%
Random Forest	78%	81%	84%	82%	77%
Key Results:

✅ Successfully developed an automated credit risk prediction system.
✅ Compared multiple Machine Learning classification algorithms.
✅ Random Forest achieved the best overall performance.
✅ Identified important financial factors affecting credit decisions.
✅ Saved the trained model (credit_scoring_model.pkl) for future predictions.

🚀 Future Improvements

The project can be enhanced further with the following improvements:

1. Advanced Machine Learning Algorithms
Implement advanced models such as:
XGBoost
LightGBM
Gradient Boosting
Neural Networks
2. Real-Time Credit Prediction Application
Develop a web/mobile application where users can enter financial details and receive instant credit risk predictions.
3. Better Feature Engineering
Create additional financial features:
Debt-to-income ratio
Payment history score
Loan repayment behavior
Income stability score
4. Model Optimization
Apply:
Hyperparameter tuning
GridSearchCV
RandomizedSearchCV
Cross-validation
5. Explainable AI Integration
Use techniques like:
SHAP
LIME

to explain why a customer is classified as high or low risk.

6. Larger Real-World Dataset
Train the model using larger banking datasets to improve accuracy and reliability.
7. Deployment
Deploy the model using:
Flask/FastAPI backend
Streamlit dashboard
Cloud platforms (AWS/Azure/GCP)
8. Security & Privacy Enhancement
Implement secure handling of customer financial information and follow data privacy standards.

---

# 👨‍💻 Author

**Priyadharshini Pazhanisami**

🎓 MCA Student
💡 Interested in Machine Learning, Artificial Intelligence & Data Science

---

# 🏢 Internship

Completed as part of:

**CodeAlpha Machine Learning Internship**

#CodeAlpha #MachineLearning #ArtificialIntelligence #Python #DataScience
