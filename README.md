# Customer Churn Prediction

## Project Overview

In this project, I worked on predicting customer churn using a telecom dataset.  
The main goal was to understand why customers leave and whether high-paying customers behave differently compared to general customers.

I built and compared different machine learning models to see which one performs better in detecting churn.

---

## Dataset

The dataset used is the Telco Customer Churn dataset.  
It contains customer information such as:

- Contract type
- Monthly charges
- Total charges
- Churn status (target variable)

---

## Project Steps

1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Visualization of churn patterns  
4. Analysis of high-paying customers  
5. Data preprocessing (encoding categorical variables)  
6. Train-test split  
7. Model training  
8. Model evaluation  
9. Feature importance analysis  

---

## Models Used

- Logistic Regression  
- Random Forest  
- Gradient Boosting  

---

## Results

After comparing the models:

- Logistic Regression gave the most balanced performance.
- Random Forest and Gradient Boosting had good accuracy but lower recall for churn.
- Model performance slightly decreased when focusing only on high-paying customers.

Since churn detection is important for business decisions, recall and F1-score were considered more important than accuracy.

---

## Key Insights

- High-paying customers show slightly different churn behavior.
- Some features like contract type and monthly charges play an important role.
- A balanced and interpretable model (like Logistic Regression) can be a good choice for churn prediction.

---

## Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Conclusion

This project helped me better understand how machine learning models behave in real-world business problems.  
It also showed the importance of interpreting results, not just looking at accuracy.
