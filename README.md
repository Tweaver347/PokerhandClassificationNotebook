# Machine-Learning Analysis of Poker-Hand Classification

A comparative study of Decision Tree and Multi-Layer Perceptron models on the UCI Poker Hand dataset, demonstrating the impact of class imbalance and exploring methods (class weighting, SMOTE) to improve “long-tail” performance.

---

## 🚀 Project Overview

- **Objective:** Automatically classify five-card poker hands into ten categories (No-Pair → Royal Flush)  
- **Dataset:** UCI Poker Hand dataset (1 025 010 samples; 10 features + 1 label)  
- **Models:**  
  - **Decision Tree** (interpretability, fast training)  
  - **MLPClassifier** (neural network for nonlinear patterns)  
- **Key Challenges:**  
  - Extreme class imbalance (No-Pair/One-Pair ≈ 90 %)  
  - Rare events (Royal Flush occurs only twice)  
- **Techniques Explored:**  
  - Stratified train/test split (80/20)  
  - `class_weight='balanced'`  
  - SMOTE oversampling  
  - Baseline logistic regression & tree-ensemble comparisons

---
