# Missing Data Imputation Strategies: A Comparative Analysis

## 📌 Overview
Missing data is a critical challenge in real-world machine learning pipelines, often leading to biased models and reduced predictive performance. This project presents a comprehensive comparative study of various data imputation techniques, ranging from classical statistical approaches to modern deep learning methods.

---

## 🧠 Objective
The goal of this study is to evaluate and compare the effectiveness of different imputation strategies across diverse datasets and missingness conditions, and provide practical insights for selecting appropriate methods.

---

## ⚙️ Key Contributions
- Compared **8 imputation methods**:
  - Mean/Median Imputation  
  - KNN Imputation  
  - MICE (Ridge, Random Forest)  
  - MissForest  
  - Datawig  
  - GAIN  
  - HyperImpute  

- Conducted experiments on **5 benchmark datasets**:
  - UCI Heart Disease  
  - Titanic Dataset  
  - Breast Cancer Wisconsin  
  - Air Quality Dataset  
  - NHANES Health Survey  

- Evaluated performance under different missingness mechanisms:
  - MCAR (Missing Completely At Random)  
  - MAR (Missing At Random)  
  - MNAR (Missing Not At Random)  

- Used multiple evaluation metrics:
  - RMSE (Root Mean Square Error)  
  - MAE (Mean Absolute Error)  
  - Downstream Classification Accuracy  

---

## 📊 Key Findings
- **HyperImpute** achieved the best overall performance across datasets  
- Deep learning methods performed better on large, high-dimensional datasets  
- Classical methods like **MissForest** remained competitive on smaller datasets  
- No single method works best universally — performance depends on dataset characteristics  

---

## 🛠️ Tech Stack
- Python 3.10  
- scikit-learn  
- PyTorch  
- HyperImpute  
- Pandas, NumPy  

---

## 👩‍💻 My Contribution

- Designed and conducted all experiments  
- Implemented imputation techniques using Python  
- Evaluated models across multiple datasets and missingness mechanisms  
- Analyzed results and derived practical insights

---

## ⭐ If you found this useful
Consider giving the repo a star!
