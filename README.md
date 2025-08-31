# Bank Customer Churn Prediction  

Customer churn is a critical problem in the banking sector, where retaining customers is far more cost-effective than acquiring new ones. This project uses machine learning to predict whether a customer is likely to leave the bank based on demographic, financial, and account-related data.  

---

## 📌 Project Overview  
- **Dataset:** 10,000 bank customer records (credit score, age, tenure, balance, products, activity, salary, etc.)  
- **Goal:** Predict the probability of a customer leaving (churn)  
- **Approach:**  
  1. **Exploratory Data Analysis (EDA):** Studied churn distribution by country, gender, credit card usage, and account activity.  
  2. **Feature Engineering:**  
     - Converted categorical variables (e.g., gender, country) into numerical form.  
     - Handled scaling for continuous features.  
  3. **Model Training:** Trained a **Random Forest Classifier** to predict churn.  
  4. **Evaluation:** Achieved **~85% accuracy**, with insights from the confusion matrix to analyze misclassifications.  

---

## ⚙️ Tech Stack  
- **Python** (pandas, numpy, matplotlib, seaborn, plotly)  
- **Scikit-learn** (train/test split, preprocessing, RandomForestClassifier, metrics)  

---

## 📊 Results  
- Random Forest Classifier achieved **85.4% accuracy**  
- Identified key factors influencing churn:  
  - Credit score  
  - Account balance  
  - Activity status (active/inactive members)  
  - Country differences  

---

## 🚀 Key Takeaways  
- Predictive analytics can help banks identify customers at risk of churn.  
- Such models can be integrated into CRM systems to trigger retention campaigns.  
- Machine learning provides a data-driven way to improve customer loyalty.  

---

## 📂 Repository Structure  
├── data/ # Dataset (CSV file)
├── notebooks/ # Jupyter notebooks with EDA & model training
├── Customer Churn.pdf # Full project report
├── README.md # Project documentation
└── requirements.txt # Dependencies

---

## 🔗 Link  
👉 [View the Project on GitHub](https://github.com/Thunderer9506/Bank-Customer-Churn-Prediction)  
  
