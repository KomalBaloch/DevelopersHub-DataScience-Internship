# **Personal Loan Acceptance Prediction**

This project predicts which customers are likely to accept a personal loan or deposit offer using customer demographic and financial information. The model helps banks identify target customers for marketing campaigns.

---

## **Objective**

Predict whether a customer will accept a personal loan offer based on features such as age, job, marital status, balance, and previous banking behavior.

---

## **Dataset**

**Bank Marketing Dataset (UCI Machine Learning Repository)**

**Features include:**
- `age` – Customer age  
- `job` – Job type  
- `marital` – Marital status  
- `education` – Education level  
- `default` – Has credit in default?  
- `balance` – Average yearly balance  
- `housing` – Has housing loan?  
- `loan` – Has personal loan?  
- `contact` – Contact communication type  
- `day`, `month`, `duration`, `campaign`, `pdays`, `previous`, `poutcome` – Marketing campaign details  
- `deposit` – Target variable (Yes/No)

---

## **Data Preprocessing**

- Encoded categorical variables using **one-hot encoding**.  
- Converted the target variable `deposit` to numeric (Yes → 1, No → 0).  
- Split dataset into **80% training** and **20% testing**.

---

## **Model**

- **Algorithm:** Logistic Regression (can also use Decision Tree)  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix  

**Model Performance:**
- Accuracy: **81%**  
- F1-score: ~0.81 for both classes  
- Precision & Recall balanced for both acceptors and non-acceptors  

---

## **Conclusion**

The classification model achieves good accuracy (~81%) and balanced performance between acceptors and non-acceptors. It provides **actionable insights** to optimize bank marketing strategies and improve campaign conversion rates.
