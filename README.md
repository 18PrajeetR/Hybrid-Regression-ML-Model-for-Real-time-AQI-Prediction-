# LIDGE: Hybrid Linear–Ridge Regression Model for Urban Air Quality Assessment

This repository contains the implementation of **LIDGE**, a **hybrid regression-based machine learning model** developed to estimate and analyze **urban air quality levels**. The study focuses on improving prediction accuracy by intelligently combining **Linear Regression** and **Ridge Regression**, leveraging the strengths of both models.

---

## 📌 Research Objective

The primary objectives of this research are:

- To develop a **hybrid regression framework (LIDGE)** for air quality prediction.
- To reduce overfitting while preserving interpretability in urban pollution modeling.
- To evaluate the effectiveness of combining Linear and Ridge Regression models.
- To support **data-driven environmental monitoring and decision-making**.

---

## 🌍 Problem Context

Urban air pollution is influenced by multiple correlated factors, often leading to multicollinearity in traditional regression models.  
While Linear Regression offers interpretability, it struggles with multicollinearity, whereas Ridge Regression improves stability at the cost of interpretability.

**LIDGE bridges this gap** by integrating both approaches into a unified predictive framework.

---

## 🛠️ Methodology

1. **Data Preprocessing**
   - Cleaning and normalization of air quality datasets
   - Feature selection and correlation analysis

2. **Model Architecture**
   - Linear Regression for baseline prediction
   - Ridge Regression for regularization and stability
   - Hybrid weighting mechanism to combine predictions

3. **Model Evaluation**
   - Performance comparison against standalone models
   - Error evaluation using standard regression metrics

---

## 🧪 Model Evaluation Metrics

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics are used to validate the effectiveness of the hybrid model over individual regression approaches.

---

## 🛠️ Tools & Technologies

- **Python**
- **Scikit-learn**
- **NumPy**
- **Pandas**
- **Matplotlib / Seaborn** (for analysis and visualization)

---

