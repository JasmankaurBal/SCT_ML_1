# 🏠 House Price Prediction using Linear Regression

This project is part of **SkillCraft Technology Data Science Internship – Task 1**.  
The task was to apply **Linear Regression** on the Kaggle "House Prices: Advanced Regression Techniques" dataset to predict house prices based on features like **square footage, number of bedrooms, and bathrooms**.

---

## 📌 Problem Statement
Predict house sale prices using supervised learning (Linear Regression) with key house attributes.

---

## 📂 Dataset
- Source: [Kaggle Competition – House Prices](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- Files used:
  - `train.csv` → Training data
  - `test.csv` → Test data
- Target variable: `SalePrice`

---

## ⚙️ Libraries Used
- Python 3
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis
- Heatmap of feature correlation
- Scatter plots (e.g., Living Area vs Price)
- Distribution of SalePrice
- Actual vs Predicted Price visualization

---

## 🤖 Model
- Algorithm: **Linear Regression**
- Training Features:
  - `GrLivArea` → Living Area (sqft)
  - `BedroomAbvGr` → Number of Bedrooms
  - `FullBath` → Number of Bathrooms
- Evaluation Metrics:
  - Mean Squared Error (MSE)
  - R² Score
- Visualizations: Actual vs Predicted Sale Prices

---

## 📑 Results
- The model successfully predicted house prices with reasonable accuracy.
- Generated a `submission.csv` file as per Kaggle competition requirements.

---

## 🚀 How to Run
1. Open the provided Google Colab notebook.
2. Upload your Kaggle API key (`kaggle.json`).
3. Run all cells to:
   - Download dataset
   - Train Linear Regression model
   - Visualize results
   - Generate `submission.csv`

---

## 📌 Screenshots
- Heatmap of correlation
- Scatter plot of Living Area vs Sale Price
- Actual vs Predicted Plot

---

## 🏆 Outcome
- Built and trained a regression model on housing data
- Understood feature impact on sale price
- https://colab.research.google.com/drive/1k5cbF6cgPb4QWAz0bG9gv_R62fsW-lfF?usp=sharing

---

## 🙌 Acknowledgments
- Dataset: Kaggle  
- Internship: SkillCraft Technology
