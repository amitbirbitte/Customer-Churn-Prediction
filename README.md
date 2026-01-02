# 📊 Customer Churn Prediction – Telecom Industry

![Customer Churn Prediction](cover-image.png)

---

## 🔍 Project Overview
Customer churn is a major challenge in the telecom industry, where retaining existing customers is more cost-effective than acquiring new ones.
This project uses Machine Learning to predict customer churn and generate churn risk scores, enabling proactive and targeted retention strategies.

---

## 🎯 Business Objectives
- Identify key factors influencing customer churn
- Predict whether a customer is likely to churn
- Create a Churn Flag (1 = Yes, 0 = No)
- Generate Churn Risk Scores to support retention campaigns

---

## 📂 Dataset Description
The dataset contains customer-level telecom usage and service details, including:
- Call usage (Day, Evening, Night, International)
- Service plans (International Plan, Voice Mail Plan)
- Customer service interactions
- Churn status (target variable)

---

## 🛠️ Technologies & Tools Used
- Programming Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Machine Learning: Scikit-learn
- Models: Logistic Regression, Random Forest
- Techniques: EDA, Feature Engineering, Hyperparameter Tuning
- Evaluation Metrics: Accuracy, Recall, Precision, F1-score

---

## ⚙️ Project Workflow
1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature selection and encoding
5. Train–test split with stratification
6. Baseline model (Logistic Regression)
7. Recall optimization and imbalance handling
8. Random Forest model with hyperparameter tuning
9. Final model selection
10. Churn risk score generation

---

## 🏆 Model Performance
- Final Model: Tuned Random Forest Classifier
- Accuracy: ~0.85
- Recall: ~0.75–0.85

Recall was prioritized to minimize missed churn customers, making the model suitable for real-world retention use cases.

---

## 📈 Business Impact
- Identifies high-risk customers before churn occurs
- Enables targeted retention offers
- Reduces revenue loss
- Supports data-driven decision-making

---

## 📦 Model Deployment Readiness
The final trained model is saved as a .pkl file, allowing easy reuse for deployment without retraining.

---

## 📌 Conclusion
This project demonstrates an end-to-end churn prediction pipeline with a strong balance of technical rigor and business relevance.
The final model provides actionable insights that can significantly improve customer retention strategies in the telecom domain.

---

## 👤 Author
Amit Birbitte  
MSc Data Science Graduate
