# 🎓 Student Performance Prediction Using Machine Learning

This project aims to predict student academic performance by leveraging both academic and non-academic features using various machine learning models. It identifies key factors influencing student success and compares model performance to support educational decision-making.

## 📊 Project Overview

- Collected and preprocessed a dataset containing 6,600+ records with features like study hours, internet access, parental education, physical activity, and academic scores.
- Explored and visualized data using scatter plots, KDE, and boxplots to identify trends.
- Applied 8 regression models to compare performance using RMSE, MAE, and R² metrics.
- Used 5-fold cross-validation to ensure consistency and prevent overfitting.

## 🧠 Machine Learning Models Used

- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor (SVR)  
- K-Nearest Neighbors (KNN)

## 📈 Results Summary

| Model                    | R² Score (Test) | RMSE (Lower is Better) | Notes |
|--------------------------|----------------|-------------------------|-------|
| Linear Regression        | ~0.77          | Moderate                | Basic model |
| Ridge/Lasso Regression   | ~0.78          | Improved overfitting    | Feature selection |
| Decision Tree Regressor | ~0.79          | Captures complexity     | Non-linear |
| Random Forest Regressor | ~0.82          | Best generalization     | Ensemble |
| Gradient Boosting        | **0.83**       | **Lowest RMSE**         | Top performer |
| SVR                      | ~0.76          | Computationally heavy   | Works on high dimensions |
| KNN                      | ~0.75          | Needs normalization     | Local prediction power |

## 🔍 Key Findings

- Past academic performance, study hours, and parental support were top predictors.
- Non-academic features like internet access and physical activity also played a significant role.
- Ensemble models (Random Forest, Gradient Boosting) outperformed linear models in accuracy and generalization.

## 🚀 Future Work

- Integrate data from other institutions or countries.
- Explore deep learning models for further performance boost.
- Develop a time-series based student monitoring system.

## 🧾 References

Research papers and academic sources cited for model comparison and educational data mining techniques are included in the full paper.

## 📁 Dataset Source

-  https://www.kaggle.com/datasets/lainguyn123/student-performance-factors
---

## 👩‍💻 Author

**Khushboo Verma**
