# 📊 Customer Churn Prediction using Machine Learning

## 🔹 Project Description
Customer churn is when clients stop doing business with a company. Retaining customers is more cost-effective than acquiring new ones, so predicting churn helps businesses take proactive measures.  

This project builds a **machine learning model** to predict whether a customer will churn based on demographic, service usage, and account details. By identifying churn-prone customers, businesses can improve retention strategies.

---

## 🔹 Features
- Preprocessed and cleaned raw customer data.  
- Performed **Exploratory Data Analysis (EDA)** with visualizations.  
- Built and compared ML models: Logistic Regression, Decision Tree, Random Forest, SVM, XGBoost.  
- Evaluated models using **Accuracy, Precision, Recall, F1-score, ROC-AUC**.  
- Identified important features influencing churn.  

---

## 🔹 Dataset
- Includes features like:  
  - Customer demographics (gender, senior citizen, dependents, etc.)  
  - Account details (contract type, payment method, tenure, charges)  
  - Target variable: **Churn (Yes/No)**  

> 📌 Dataset Source: [IBM Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  

---

## 🔹 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- **Tools:** Jupyter Notebook, GitHub

---

## 🔹 Project Structure
│── Customer_Churn_Prediction_using_ML.ipynb # Main Jupyter Notebook
│── README.md # Documentation
│── requirements.txt # Dependencies
│── data/ # (optional) dataset
│── results/ # (optional) plots, outputs

---

## 🔹 Results
- Customers with month-to-month contracts are more likely to churn
- High monthly charges increase churn probability
- Customers with short tenure show higher churn rates
- Random Forest and XGBoost performed the best with strong ROC-AUC

---

## 🔹 requirements.txt
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost
- jupyter

---

## 🔹 Future Improvements
- Fine-tune hyperparameters for higher accuracy
- Deploy as a web app with Flask or Streamlit
- Use real-time customer data for live predictions
- Explore deep learning methods for churn prediction
