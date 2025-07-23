# fraud-detection-ml
Machine Learning Fraud Detection Model using a financial transactions dataset (6.3M+ records). Includes data cleaning, handling imbalanced data with SMOTE, and training Logistic Regression, Random Forest, and XGBoost models. Achieved 98% fraud recall and 0.999 ROC-AUC with XGBoost.

# Fraud Detection using Machine Learning  

This project detects **fraudulent financial transactions** from a dataset with **6.3M+ records**.  

## 🚀 Project Highlights  
- Handled **highly imbalanced data (~0.13% fraud)**  
- Applied **data cleaning & preprocessing**  
- Used **SMOTE oversampling** to balance fraud cases  
- Trained and compared **Logistic Regression, Random Forest, and XGBoost**  
- Achieved **98% recall & 0.999 ROC-AUC** with XGBoost  

## 🛠 Tech Stack  
- Python (Pandas, NumPy, Scikit-learn, XGBoost)  
- Google Colab  
- Imbalanced-learn for SMOTE  

## 📊 Key Insights  
- Fraud mostly happens in **TRANSFER & CASH_OUT**  
- Suspicious **large amounts** and **balance mismatches** are strong fraud indicators  
- Recommended **real-time alerts & velocity rules** for prevention  

## 📈 Results  
| Model | Recall (Fraud) | Precision (Fraud) | ROC-AUC |
|-------|---------------|-------------------|--------|
| Logistic Regression | 100% | 2% | 0.995 |
| Random Forest | 98% | 3% | 0.998 |
| **XGBoost** | **98%** | **29%** | **0.999** |

## 📌 How to Run  
1. Clone this repo  
2. Open `Fraud_Detection.ipynb` in Jupyter/Colab  
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
