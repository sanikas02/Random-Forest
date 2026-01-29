# Random-Forest
This project is part of the AI & ML Internship under the Ministry of MSME, Govt. of India. The goal is to build a fraud detection model using the Random Forest algorithm and compare its performance against a baseline Logistic Regression model.


### – Credit Card Fraud Detection (Random Forest)

## 📌 Project Overview
This project is part of the **AI & ML Internship** under the Ministry of MSME, Govt. of India.  
The goal is to build a **fraud detection model** using the **Random Forest algorithm** and compare its performance against a baseline Logistic Regression model.  

Fraud detection is a classic example of **imbalanced classification**, where fraudulent transactions are rare compared to legitimate ones. This project demonstrates how ensemble learning methods like Random Forest can improve detection performance.

---

## 📂 Dataset
- **Source**: Fraud Detection Sample Datasets – Khaled Abdo (Kaggle) [(kaggle.com in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fkhaledabdo%2Ffraud-detection-sample-datasets")  
- **File Used**: `creditcard_sampledata.csv`  
- **Target Column**: `Class` (0 = Non-Fraud, 1 = Fraud)

---

## ⚙️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn (Logistic Regression, Random Forest, metrics)  
- Matplotlib, Seaborn (visualization)  
- Joblib (model saving)

---

## 🚀 Workflow
1. **Data Loading & Exploration**
   - Loaded dataset into Pandas.
   - Checked fraud vs non-fraud counts to understand imbalance.

2. **Preprocessing**
   - Separated features (`X`) and target (`y`).
   - Stratified train-test split to preserve fraud ratio.

3. **Baseline Model**
   - Trained Logistic Regression.
   - Evaluated with precision, recall, F1-score.

4. **Random Forest Model**
   - Trained with `n_estimators=100`.
   - Compared performance against baseline.

5. **Feature Importance**
   - Plotted top features contributing to fraud detection.

6. **Model Saving**
   - Exported best model as `random_forest_fraud.pkl` using Joblib.

---

## 📊 Results
- **Logistic Regression**: Provided baseline metrics but struggled with recall on fraud cases.  
- **Random Forest**: Achieved better balance between precision and recall, showing stronger fraud detection capability.  
- **Feature Importance Plot**: Highlighted key transaction features influencing fraud predictions.  

---

## 📁 Deliverables
- ✅ Jupyter/Colab Notebook (`Random Forest.ipynb`)  
- ✅ Feature Importance Plot (`feature_importance.png`)
- ✅ Saved Model (`random_forest_fraud.pkl`)  
- ✅ README.md (this file)  

---

## 🎯 Learning Outcomes
- Handling **imbalanced datasets** in classification problems.  
- Understanding **ensemble learning** and Random Forest.  
- Importance of **precision, recall, and F1-score** over accuracy in fraud detection.  
- Saving and reusing trained models.  
