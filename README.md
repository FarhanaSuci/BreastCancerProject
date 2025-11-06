#  Breast Cancer Diagnostic — Machine Learning Framework

##  Project Overview
The early and accurate diagnosis of breast cancer is a crucial aspect of reducing mortality 
and improving treatment outcomes among women. This project leverages the **Breast Cancer 
Diagnostic dataset**, derived from fine needle aspirate (FNA) of breast masses, to develop a 
robust **machine learning-based diagnostic framework** capable of distinguishing between 
**benign** and **malignant** tumors.

Our goal is to enhance diagnostic reliability through an interpretable, high-performance 
classification system that supports clinicians in making early and accurate decisions.

---

##  Key Features
-  **Machine Learning Framework** for breast cancer diagnosis using ensemble algorithms.  
-  **Feature Selection & Dimensionality Reduction** using PCA, Forward Selection (FS),  
  mRMR, and RFE.  
-  **Model Optimization** via grid and randomized search with cross-validation.  
-  **Best Performing Models:** XGBoost and CatBoost combined with Forward Selection.  
-  **Explainable AI (XAI)** using SHAP for interpreting model predictions.  
-  **Clinician-Oriented Insight:** Enables transparent, trustworthy medical decision-making.

---

##  Methodology Summary
We evaluated several **ensemble classifiers**, including **AdaBoost, LightGBM, XGBoost, 
CatBoost, and Random Forest**. 

Feature extraction and dimensionality reduction techniques such as **Principal Component 
Analysis (PCA)**, **Forward Selection (FS)**, **Maximum Relevance Minimum Redundancy 
(mRMR)**, and **Recursive Feature Elimination (RFE)** were employed to identify the most 
informative attributes contributing to accurate diagnosis.Hyperparameter tuning was performed using **Grid Search CV** 
and **Randomized Search CV** with stratified cross-validation to ensure optimal model performance.


---

##  Results
Experimental results indicate that **XGBoost** and **CatBoost classifiers**, when integrated 
with **Forward Selection**, achieved the highest classification accuracy. To ensure model 
interpretability, a **SHAP-based explainable model** was incorporated, enabling transparent 
understanding of feature contributions.

This interpretable framework empowers clinicians to make **informed, data-driven decisions**, 
improving both the accuracy and reliability of breast cancer diagnosis.



---

  

