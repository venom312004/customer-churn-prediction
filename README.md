# 🧠 Customer Churn Prediction Using Machine Learning

## 📄 Overview

This project aims to predict customer churn (i.e., whether a customer will discontinue services) using machine learning techniques.  
The dataset used is the **Telco Customer Churn dataset**, which includes demographic, service usage, and billing information.

---

## 📊 Dataset Information

- **Dataset Name:** Telco Customer Churn
- **Source:** Kaggle / IBM Sample Dataset
- **Rows:** 7,043
- **Columns:** 21
- **Target Variable:** `Churn` (Yes / No)

### Features Overview

| Feature Type  | Examples                                                           |
| ------------- | ------------------------------------------------------------------ |
| Customer Info | `customerID`, `gender`, `SeniorCitizen`, `Partner`                 |
| Services      | `PhoneService`, `InternetService`, `OnlineSecurity`, `TechSupport` |
| Account Info  | `Contract`, `PaymentMethod`, `PaperlessBilling`                    |
| Numerical     | `tenure`, `MonthlyCharges`, `TotalCharges`                         |
| Target        | `Churn`                                                            |

---

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
2. **Exploratory Data Analysis (EDA)**
   - Visualization of churn distribution
   - Correlation analysis
3. **Model Building**
   - Models used: Decision Tree, Random Forest, XGBoost
   - Hyperparameter tuning
4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix

---

## 🧩 Technologies Used

- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, imbalanced-learn
- **IDE/Environment:** Jupyter Notebook / Google Colab

---

## 🚀 Results

- Achieved an accuracy of **X%** using the **best-performing model (e.g., Random Forest/XGBoost)**.
- Model shows strong performance in identifying potential churn customers.

---

## 📈 Future Improvements

- Implement deep learning models for comparison.
- Deploy the model using Flask or Streamlit.
- Automate model retraining with new data.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📧 Contact

**Author:** Pranjal Pandey

**Email:** Pranjalpandey0301@gmail.com

**LinkedIn:** https://www.linkedin.com/in/pranjal-pandey-501a5a244

