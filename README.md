# **Customer Churn Prediction**

A machine learning project focused on predicting customer churn using the Telco Customer dataset. This project explores data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation to identify key drivers of churn and support data‑driven retention strategies.

---

## **📂 Project Overview**
Customer churn is a major challenge for subscription‑based businesses. The goal of this project is to build a predictive model that identifies customers at high risk of leaving, enabling targeted retention efforts.

This project includes:
- Exploratory data analysis  
- Feature engineering  
- Model comparison  
- Hyperparameter tuning  
- Evaluation using AUC‑ROC and other metrics  
- Interpretation of churn drivers  

---

## **🧰 Tools & Technologies**
- **Python**  
- **pandas, NumPy**  
- **scikit‑learn**  
- **matplotlib, seaborn**  
- **LightGBM, XGBoost, CatBoost**  
- **Jupyter Notebook**

---

## **📊 Key Steps**

### **1. Data Preprocessing**
- Handled missing values and cleaned inconsistent entries  
- Encoded categorical variables using one‑hot encoding  
- Scaled numerical features  
- Created engineered features such as tenure in months and number of subscribed services  

### **2. Exploratory Data Analysis**
- Visualized churn distribution  
- Analyzed correlations between churn and contract type, payment method, tenure, and monthly charges  
- Identified patterns in customer behavior  

### **3. Modeling**
Trained and compared multiple models:
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- LightGBM  
- XGBoost  
- CatBoost  

### **4. Hyperparameter Tuning**
- Used GridSearchCV / RandomizedSearchCV  
- Optimized parameters for boosting models  
- Addressed class imbalance using class weights  

### **5. Evaluation**
Primary metric: **AUC‑ROC**  
Secondary metrics: accuracy, precision, recall, F1‑score  

Best model achieved:  
- **AUC‑ROC: 0.85**  
- Strong recall for identifying high‑risk customers  

---

## **🔍 Insights & Findings**
- Short‑tenure customers were significantly more likely to churn  
- Month‑to‑month contracts had the highest churn rate  
- Electronic check payment method correlated strongly with churn  
- Higher monthly charges increased churn likelihood  
- Auto‑pay and long‑term contracts reduced churn risk  

---

## **📈 Business Impact**
This model can help businesses:
- Identify at‑risk customers early  
- Target retention campaigns more effectively  
- Reduce revenue loss  
- Improve customer satisfaction through proactive outreach  

---

## **📁 Repository Structure**
```
customer-churn-prediction/
│── README.md
│── churn_prediction.ipynb
│── data/ (excluded or sample only)
│── images/ (optional for charts)
```

---

## **🚀 How to Run**
1. Clone the repository  
2. Install required libraries  
3. Open the Jupyter notebook  
4. Run all cells to reproduce the analysis and results  

---

## **📬 Contact**
If you have questions or want to connect:  
**Email:** iking.mika@gmail.com  
**LinkedIn:** www.linkedin.com/in/mika-willis  
