# 📊 Regression Model Optimization & Diagnostics

This project explores the process of building, evaluating, and refining regression models to predict tip values based on customer behavior and bill characteristics.

Rather than focusing only on model performance, this analysis emphasizes **model selection, statistical validity, and residual diagnostics** to ensure robustness and interpretability.

---

## 🎯 Problem Statement

How can we build a regression model that not only predicts well but also satisfies key statistical assumptions?

---

## 🧠 Approach

The project follows an iterative modeling strategy:

1. Start with a **simple linear regression**
2. Evaluate model performance (R², Adjusted R², AIC)
3. Diagnose residual patterns
4. Apply transformations and feature engineering
5. Introduce additional explanatory variables
6. Compare models and select the best candidate

---

## 📈 Models Evaluated

- Linear Regression → `tip ~ net_bill`
- Log Transformation → `tip ~ log(net_bill)`
- Polynomial Regression → capturing non-linearity
- Multiple Linear Regression → adding variables such as `size`
- Log-Log Model → variance stabilization and elasticity interpretation

---

## 📊 Model Evaluation Criteria

- **R² / Adjusted R²** → explanatory power  
- **AIC (Akaike Information Criterion)** → model quality vs complexity  
- **Residual Analysis** → randomness, homoscedasticity, and model adequacy  

---

## 🔍 Key Findings

- The **bill amount (`net_bill`)** is a strong predictor of tips  
- Adding **group size (`size`)** significantly improves model performance  
- Log transformations help reduce heteroscedasticity  
- The **multiple linear regression model** provided the best balance between performance and interpretability  

---

## ⚠️ Diagnostics & Limitations

- Residual plots indicate **mild heteroscedasticity** in some models  
- Further improvements could include:
  - Robust regression techniques  
  - Interaction terms  
  - Non-linear models  

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **Seaborn & Matplotlib**
- **Statsmodels**

---


## 🚀 Future Improvements

- Implement cross-validation  
- Test regularization methods (Ridge, Lasso)  
- Explore machine learning models (e.g., Random Forest, XGBoost)  

---

## 👤 Author

Karolainy de sousa arantes

---

## ⭐ Final Note

This project highlights the importance of going beyond performance metrics and focusing on **model reliability, assumptions, and interpretability** in regression analysis.
