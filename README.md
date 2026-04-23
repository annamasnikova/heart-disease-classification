# 🫀 Heart Disease Prediction (Logistic Regression)

## 📌 Project Goal
Build a model to predict the risk of heart disease using survey-based health indicators.

## 📊 Dataset
Heart Disease Health Indicators Dataset  
- 253,680 observations  
- Target: `HeartDiseaseorAttack` (binary)  
- Slight class imbalance (~9% positive cases)

## ⚙️ Methods
- Logistic Regression (`class_weight='balanced'`)
- Train/Test split
- Feature usage: all available variables

## 📈 Evaluation
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix
- ROC-AUC
- Distribution of predicted probabilities

## 💡 Key Insights
- High Recall for class 1 → model captures most high-risk patients  
- Lower Precision → more false positives (acceptable in medical screening)  
- ROC-AUC shows overall separability of classes  

## 📊 Visualizations
- Confusion Matrix  
- ROC Curve  
- Score distribution by class  

