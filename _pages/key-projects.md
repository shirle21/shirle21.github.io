---
title: "Key Projects"
permalink: /key-projects/
layout: single
author_profile: true
---

## 🧠 Fraudulent and Non-Fraudulent Transaction Detection  
Built a supervised machine learning model to detect fraudulent credit card transactions within a highly imbalanced dataset of 284,807 transactions (only 0.172% fraud). The project focused on maximizing the Area Under the Precision-Recall Curve (AUPRC) to effectively identify fraud while minimizing false positives.

**Tools & Techniques:**  
- Dataset: Kaggle Credit Card Fraud Detection  
- Models: Support Vector Machines (Linear & RBF kernels), Stochastic Gradient Descent, Dummy Classifier baseline  
- Data Handling: PCA-transformed features, class imbalance addressed via class weighting, SMOTE, and downsampling  
- Evaluation: Primary metric AUPRC (target ≥ 0.80), secondary F1-score (target ≥ 0.80)  

**Key Outcome:**  
The SVM model with an RBF kernel (without SMOTE) achieved the best results, with an AUPRC of 0.98 and an F1-score of 0.76, successfully capturing complex patterns for fraud detection without synthetic oversampling. This project highlights the challenges of imbalanced data and the importance of robust evaluation metrics.

<!-- Optionally add a link to code repository or blog post here -->
