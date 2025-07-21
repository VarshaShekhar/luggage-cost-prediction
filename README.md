# 🎒 Luggage Bag Cost Prediction — Linear Regression Project

A mini machine learning project built during my AI/ML postgraduate program at BITS Pilani. It predicts the cost of luggage bags based on real product data using various gradient descent techniques.

---
![Project Thumbnail](thumbnail.jpg)

## 🔍 Problem Statement

Predict luggage bag **cost** using physical attributes: `Height`, `Width`, `Length`, `Weight`, and `Weight1`.  
Built using 160 samples of real-world data.

---

## 🧠 Models Implemented

- ✅ Batch Gradient Descent (Manual)
- ✅ Mini-Batch Gradient Descent (Manual)
- ✅ Stochastic Gradient Descent (Manual)
- ✅ Scikit-learn Linear Regression (Baseline)

---

## ⚙️ Data Preprocessing

- Mean imputation for missing values  
- Outlier handling with **relaxed IQR**  
- Standardized scaling for feature normalization  
- Converted to numeric using `pandas.to_numeric()`

---

## 📊 Model Evaluation

| Model                  | R² Score | MSE     | RMSE    |
|------------------------|----------|---------|---------|
| Sklearn LinearRegression | 0.9013   | ~10043   | ~100.21  |
| Batch Gradient Descent   | 0.9029   | ~9876   | ~99.38  |
| Mini-Batch GD            | 0.9028   | ~9888   | ~99.44  |
| Stochastic GD            | 0.9017   | ~9999  | ~99.99 |

---

## 📈 Visualizations

- Actual vs Predicted scatter plots  
- Coefficient bar charts  
- Metrics summary tables

---

## 💡 Takeaways

- Batch GD gave best performance  
- Manual implementation improved intuition on optimization  
- Proper preprocessing stabilized all models

---

## 🚀 Future Enhancements

- Polynomial regression for nonlinear trends  
- Regularization (Ridge/Lasso) for multicollinearity  
- Flask/Streamlit deployment

---

## 📁 Project Structure

- `Luggage_Cost_Prediction.ipynb` – Jupyter notebook  
- `Luggage_Cost_Prediction.pdf` – Printable version  

---

## 🤝 Connect

- [LinkedIn](https://www.linkedin.com/in/varsha-shekhar)
- 📧 varshaiyer96@gmail.com

