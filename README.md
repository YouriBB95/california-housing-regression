# 🏠 California Housing Price Prediction

This project uses machine learning to predict median house values in California using census data from the 1990 U.S. Census, available via `sklearn.datasets`.

The goal was to explore the full regression modeling pipeline: loading data, performing EDA, preprocessing, training multiple models, evaluating them, and interpreting feature importance.

---

## 📊 Project Summary

- 📦 **Dataset**: California Housing (20,640 rows, 8 features)
- 🧹 **Preprocessing**: Feature scaling, train-test split (80/20)
- 🔍 **EDA**: Found strong correlation between `MedInc` and `MedHouseVal`, no missing values, right-skewed target
- 🤖 **Models Trained**:
  - Linear Regression
  - Decision Tree
  - Random Forest (tuned)
- 🏆 **Best Performance**: Random Forest Regressor
  - R²: **0.805**
  - MAE: $32,700
  - RMSE: $50,500

---

## ✅ Tools & Skills Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (regression models, scaling, train/test split, GridSearchCV)
- Model evaluation: MAE, MSE, RMSE, R²
- Feature importance interpretation
- Hyperparameter tuning

---

## 📈 Feature Importance

Top features used by the Random Forest model:

1. `MedInc` – Median Income (most predictive)
2. `AveOccup` – Average household occupancy
3. `Latitude` / `Longitude` – Location-based variation

---

## 🚀 Future Improvements

- Add models like XGBoost or LightGBM
- Engineer new features (e.g., `rooms_per_person`)
- Visualize predictions vs actual values
- Deploy as a web app using Streamlit

---

## 📁 How to Use

```bash
# Clone the repo
git clone https://github.com/your-username/california-housing-regression.git
cd california-housing-regression

# Open the notebook
# (recommended to use Google Colab or Jupyter Notebook)

---

---

## 📬 Contact

Created by **Youri Benschop ** – aspiring remote-ready, future-proof Data Scientist.  
📧 Email: YouriBB95@outlook.com  
🔗 LinkedIn: https://www.linkedin.com/in/youri-benschop-133045b1/  
🌐 Portfolio: https://ruby-petroleum-57d.notion.site/Welcome-to-Notion-23bb6b65b21180d399e0d75d1198d151?source=copy_link


Feel free to reach out about collaborations, questions, or freelance work!
