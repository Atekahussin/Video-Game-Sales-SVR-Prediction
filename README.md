# 🎮 Video Game Sales Prediction using SVR

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)
![Machine Learning](https://img.shields.io/badge/Focus-Machine%20Learning-green.svg)

## 📌 Project Overview
This project focuses on predicting the **Global Sales** of video games by analyzing various factors such as platform, genre, publisher, and critic/user ratings. Using a dataset of over 16,000 games, I developed a predictive model that helps understand market trends and sales drivers in the gaming industry.

## 🚀 Key Results
- **Model:** Support Vector Regression (SVR)
- **Accuracy:** Achieved an **R² Score of 0.83**, demonstrating high predictive power even with noisy real-world data.
- **Insights:** Identified that critic scores and regional sales are the strongest predictors of global success.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.
- **Tools:** Jupyter Notebook, VS Code.

## 📊 Methodology
1. **Data Preprocessing:** Handled missing values, standardized data types, and encoded categorical variables (Genre, Platform, etc.).
2. **Feature Selection:** Implemented a **Hybrid Approach** combining:
   - Pearson Correlation.
   - Random Forest Feature Importance.
3. **Model Development:** Optimized a Support Vector Regression (SVR) model to capture non-linear relationships within the features.
4. **Evaluation:** Measured performance using R² score and Mean Squared Error (MSE).

## 📁 Dataset
The project uses the *Video Game Sales with Ratings* dataset from Kaggle, which includes metadata for games across multiple decades.

## 💡 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/Video-Game-Sales-SVR-Prediction.git](https://github.com/YourUsername/Video-Game-Sales-SVR-Prediction.git)
