# 📊 Customer Churn Prediction

This project focuses on predicting customer churn using a publicly available telecom dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) . It explores key patterns in customer behavior and applies machine learning models to predict the likelihood of churn.

---

## 📁 Files in the Repository

- `customer_churn_prediction.ipynb`: Jupyter Notebook with full EDA, preprocessing, model building, and evaluation.
- `customer_churn.csv`: The dataset used (from Kaggle).
- `Summary and Findings.pdf`: A concise summary of model performance and insights.

---

## 📌 Project Highlights

- ✔️ **Data Preprocessing**: Handled categorical variables using one-hot encoding. Addressed class imbalance with SMOTE.
- ✔️ **Models Used**:
  - Logistic Regression
  - Decision Tree Classifier
  - Neural Network Classifier
- ✔️ **Evaluation Metrics**: Accuracy, F1-Score, ROC-AUC Score, Classification Report.
- ✔️ **Model Performance**:
  - **Logistic Regression**: ROC-AUC = 0.95, Accuracy = 80.3%, F1-Score = 59.3%
  - **Decision Tree**: ROC-AUC = 0.83, Accuracy = 79.1%
  - **Neural Network**: Accuracy = 80.4%, F1-Score = 60.2%

---

## 🔍 Key Findings

- The most important features across models include:
  - `Contract_Month-to-month`
  - `TotalCharges`
  - `InternetService_Fiber optic`
  - `PaperlessBilling_Yes`
- Customers with electronic check payment methods, short tenure, and high monthly charges are more likely to churn.
- Logistic Regression showed the best ROC-AUC score, while Neural Networks slightly outperformed in F1-Score.

---

## 🔮 Next Steps

- Explore cost-sensitive learning or ensemble techniques to improve recall and F1-score for churners.
- Use these insights to target high-risk customer groups with retention strategies.

---

## 📚 Dataset Source

- Kaggle: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 🛠 Tools Used

- Python, Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- SMOTE (from imbalanced-learn)

---

## 🧠 Author

**Vishnu B**  
*MSc Data Science Student*  
[LinkedIn](www.linkedin.com/in/vishnu-b-) 

---


