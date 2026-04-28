# California Housing Price Prediction 🏠

Is project mein maine California housing dataset ka use karke ek Machine Learning model banaya hai jo gharon ki prices predict karta hai. Maine Linear Regression se lekar Random Forest tak ka safar tay kiya aur model ko optimize kiya.

## 🚀 Project Overview
Maine is project mein end-to-end ML pipeline follow ki hai:
- **Data Preprocessing:** Missing values ko handle kiya (`SimpleImputer`) aur categorical data ko encode kiya (`OneHotEncoder`).
- **Models Tested:** Linear Regression, Decision Tree, aur Random Forest.
- **Fine-Tuning:** `GridSearchCV` ka use karke best hyperparameters (max_features: 4, n_estimators: 30) dhoondhe.

## 📊 Key Results
Model ne final testing mein kaafi achha perform kiya:
- **Best Model:** Random Forest Regressor
- **Final RMSE (Test Set):** 18,900.94
- **Training RMSE:** 17,923.45

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib
- **Platform:** Google Colab

## 📈 Feature Importance
Model ke mutabik ghar ki price decide karne mein ye factors sabse zaroori hain:
1. `median_income` (Sabse zyada asar)
2. `INLAND` (Location category)
3. `longitude` & `latitude`

## 📁 How to use
1. `California_Housing_Prediction.ipynb` ko open karein.
2. `housing.csv` dataset upload karein.
3. Saare cells run karke aap final prediction dekh sakte hain.

---
**Developed with ❤️ using Scikit-Learn**
