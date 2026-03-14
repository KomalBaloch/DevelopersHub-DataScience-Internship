# **Predicting Insurance Claim Amounts**

This project predicts medical insurance claim amounts (`charges`) based on personal and demographic data using a **Linear Regression** model.

---

## **Objective**

Estimate the medical insurance charges for individuals using features like age, BMI, smoking status, and other personal data.

---

## **Dataset**

- **Source:** Kaggle 
- **Description:** The dataset contains features for 1,338 individuals:
  - `age` – Age of the primary beneficiary  
  - `sex` – Gender (male/female)  
  - `bmi` – Body mass index  
  - `children` – Number of children covered by health insurance  
  - `smoker` – Smoking status (yes/no)  
  - `region` – Residential area  
  - `charges` – Medical insurance charges (target variable)

---

## **Data Preprocessing**

- Checked for missing values – **none found**.  
- Encoded categorical variables:  
  - `sex`: Male → 0, Female → 1  
  - `smoker`: No → 0, Yes → 1  
  - `region`: One-hot encoded (`northeast`, `northwest`, `southeast`; `southwest` as reference)

---

## **Model**

- **Algorithm:** Linear Regression  
- **Features:** All columns except `charges`  
- **Target:** `charges`  
- **Train-Test Split:** 80% training, 20% testing  

**Performance Metrics:**  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)

---

## **Visualization & Insights**

- **BMI vs Charges:** Higher BMI generally leads to higher charges.  
- **Age vs Charges:** Older individuals tend to have higher insurance costs.  
- **Smoking Status vs Charges:** Smokers pay significantly more than non-smokers.  

Plots and visualizations were used to observe these relationships and understand feature impact.

---

## **Conclusion**

- The Linear Regression model effectively predicts insurance charges.  
- **Key factors influencing charges:** Smoking status, age, and BMI.  
- The model provides a baseline for estimating insurance costs.  

## **Skills Applied**

- Regression modeling  
- Data preprocessing and feature encoding  
- Feature correlation and visualization  
- Model evaluation using MAE and RMSE