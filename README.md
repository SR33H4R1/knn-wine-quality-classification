# 🍷 KNN Wine Quality Classification  
Simple Binary Classification using the Red Wine Quality Dataset

## 📌 Overview
This project applies **K-Nearest Neighbours (KNN)** to classify red wine as **good (1)** or **bad (0)** based on its physicochemical properties.

Dataset: Red Wine Quality (Cortez et al., 2009)  
Binary label:
- 1 → quality ≥ 6  
- 0 → quality < 6  

## 🔧 Steps
- Loaded and explored the dataset  
- Converted multi-class target to binary  
- Scaled features using StandardScaler  
- Split data into train/test  
- Trained KNN for k = 1 to 30  
- Evaluated accuracy and confusion matrix  

## 📊 Results
- **Best accuracy:** ~75.4%  
- **Best k:** 1  
- KNN performance drops with larger k values due to class overlap and imbalance.

## 📁 Files
- `knn_wine.ipynb` — full code  
- `winequality-red.csv` — dataset  
- `/confusion_matrix.png`  

## 🚀 How to Run
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
jupyter notebook knn_wine_quality.ipynb
