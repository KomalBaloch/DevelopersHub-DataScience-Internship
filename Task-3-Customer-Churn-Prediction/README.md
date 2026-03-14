# **Customer Churn Prediction**

Predict whether a bank customer is likely to leave (churn) using demographic and account information.

---

## **Dataset**

- **Source:** Kaggle
- **Description:** 10,000 customers with features like:
  - `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`
  - `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`  
- **Target Variable:** `Exited`  
  - `1` → Customer churned  
  - `0` → Customer stayed

---

## **Data Preprocessing**

- Dropped identifiers: `RowNumber`, `CustomerId`, `Surname`  
- Encoded categorical features:
  - `Gender`: Male → 1, Female → 0  
  - `Geography`: One-hot encoded (`Germany`, `Spain`; France as reference)

---

## **Model**

- **Algorithm:** Decision Tree Classifier  
- **Train-Test Split:** 80% training, 20% testing  

---

## **Evaluation**

- Confusion matrix shows prediction performance  
- Feature importance highlights factors affecting churn

---

## **Conclusion**

- The model predicts customers likely to churn  
- Helps banks target retention strategies for high-risk customers

---