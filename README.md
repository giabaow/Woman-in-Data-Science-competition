# 🧠 Women in Data Science (WiDS) Datathon – Budapest | 1st Place 🥇

**Year:** 2025  
**Competition:** Women in Data Science (WiDS) Datathon – Budapest  
**Result:** 🥇 1st Place Winner  

---

# 📌 Project Overview

This project focuses on **AI-driven analysis of female brain patterns** using neuroscience and mental health datasets from the Women in Data Science (WiDS) Datathon.

The main objective was to build a robust machine learning pipeline capable of predicting **ADHD outcomes** while addressing **class imbalance across ADHD diagnosis and sex distribution**. The project emphasizes reliable model evaluation, effective feature selection, and scalable model design.

---

# 🎯 Objectives

- Predict **ADHD outcomes** from neuroscience and behavioral data
- Address **imbalanced class distributions** for both ADHD diagnosis and sex
- Identify **important brain and behavioral features**
- Build reliable and interpretable machine learning models

---

# ⚠️ Handling Imbalanced Data

The dataset exhibited significant **class imbalance** in:

- ADHD Outcome labels
- Sex distribution

To address this issue, several strategies were implemented:

- **Resampling techniques**
  - Oversampling minority classes
  - Balanced sampling strategies

- **Class-weighted learning**
  - Applied model weighting to penalize misclassification of minority classes

- **Stratified cross-validation**
  - Ensured balanced representation of classes during model training and validation

These methods helped improve **model fairness and predictive reliability**.

---

# 🧠 Feature Selection

Feature selection was performed to reduce noise and improve model performance.

Methods included:

- Correlation-based filtering
- Feature importance analysis
- Model-based selection

Tree-based models were also used to identify the **most influential predictors of ADHD outcomes**, helping to focus on the most meaningful neurological and behavioral indicators.

---

# 🤖 Machine Learning Models

Multiple models were trained and evaluated:

### Random Forest
- Robust ensemble learning approach
- Effective for high-dimensional data
- Provided strong baseline performance
- Used for feature importance analysis

### XGBoost
- Gradient boosting framework
- Optimized for predictive accuracy
- Handled complex nonlinear relationships
- Tuned using cross-validation for best performance

---

# 📊 Model Evaluation

Models were evaluated using **robust validation techniques**, including:

- Stratified Cross-Validation
- Multiple performance metrics:
  - Accuracy
  - F1-score
  - ROC-AUC
  - Precision / Recall

This ensured **reliable generalization and fair performance across classes**.

---

# 🏗️ Project Pipeline

1. Data preprocessing and cleaning  
2. Handling class imbalance  
3. Feature selection  
4. Model training (Random Forest & XGBoost)  
5. Hyperparameter tuning  
6. Cross-validation and evaluation  

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Jupyter Notebook

---

# 🏆 Results

The developed machine learning pipeline achieved **top performance in the WiDS Datathon – Budapest**, earning **1st Place**.

Key strengths included:

- Effective handling of **imbalanced ADHD and sex distributions**
- Strong predictive performance using **ensemble models**
- Clean, modular, and maintainable ML pipeline

---

# 🔮 Future Work

- Apply **deep learning models** to brain imaging data
- Improve **model interpretability with SHAP values**
- Extend the pipeline to other **mental health prediction tasks**

---

# 🤝 Acknowledgements

Thanks to the **Women in Data Science (WiDS)** community for organizing this impactful datathon and providing access to valuable neuroscience datasets.
