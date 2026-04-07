# Wildfire Impact Prediction in Alberta

## Project Overview
This project predicts the impact of wildfires in Alberta using historical wildfire data (2006–2025). The workflow includes data cleaning, preprocessing, feature engineering, exploratory data analysis (EDA), and machine learning modeling to classify wildfire events into low- or high-impact categories.

---

## Tech Stack & Libraries
**Programming Language:** Python  

**Libraries Used:**  
- Data Processing: `pandas`, `numpy`  
- Visualization: `matplotlib`, `seaborn`  
- Machine Learning: `scikit-learn`, `xgboost`  
- Deep Learning: `tensorflow`, `keras`  

---

## Algorithms Implemented
- **XGBoost (Extreme Gradient Boosting)**  
- **Deep Neural Network (DNN)**  

---

## Results
- **XGBoost:**  
  - Test Accuracy: ~79.37%  
  - ROC-AUC: ~0.88  
- **Deep Neural Network:**  
  - Test Accuracy: ~77.22%  
- **Insights:**  
  - XGBoost outperforms DNN with more stable and reliable predictions  
  - Key factors influencing wildfire impact: fire spread rate, temperature, wind speed, and fire start hour  

---

## How to Use
1. The Jupyter Notebook 607_project_final.ipynb) is included with the full workflow. 
2. The dataset (fp-historical-wildfire-data-2006-2025.csv) is also attached.
