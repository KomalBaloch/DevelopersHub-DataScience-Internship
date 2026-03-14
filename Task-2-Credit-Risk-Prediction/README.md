# **Credit Risk Prediction**

This project aims to predict whether a loan applicant is likely to default or be considered a credit risk using machine learning techniques.

---

## **Dataset**

The dataset contains demographic and financial information of loan applicants, including:

- Income
- Age
- Work Experience
- Marital Status
- House & Car Ownership
- Profession
- City & State
- Current Job & House Duration
- Target: `Risk_Flag` (0 → No Risk, 1 → Risk)

Dataset source: Kaggle Loan Prediction Dataset

---

## **Tools & Libraries**

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## **Project Workflow**

1. **Data Exploration & Cleaning**  
   - Checked for missing values (dataset is complete, no imputation required).  
   - Explored key numerical and categorical features.

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions of Income, Experience, and Age.  
   - Examined relationships between categorical features and risk flag (Marital status, House/Car ownership, Profession).  
   - Boxplots and countplots used for insights.

3. **Feature Preparation**  
   - Dropped unnecessary columns (`Id`).  
   - Encoded categorical variables using one-hot encoding.

4. **Model Training**  
   - Logistic Regression  
   - Decision Tree Classifier

5. **Model Evaluation**  
   - Accuracy Score: **Decision Tree → 88.46%**  
   - Confusion Matrix visualizations  
   - Comparison of model performance

---

## **ey Insights**

- Applicants with higher income and longer work experience generally have lower credit risk.  
- Ownership of house or car may influence loan risk.  
- Decision Tree model performed well in predicting loan risk, achieving **88.46% accuracy**.  

---

## **Conclusion**

Machine learning can help financial institutions evaluate credit risk more effectively by analyzing applicant demographic and financial information.  
The Decision Tree model demonstrates strong predictive capability, assisting in reducing potential loan defaults.

---

## Author

**Komal Baloch**