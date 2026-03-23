# 🌍 Life Expectancy Prediction using Linear Regression

## 📌 Project Overview
This project uses **Linear Regression** to predict life expectancy based on various health, economic, and social factors. The dataset includes features such as adult mortality, alcohol consumption, GDP, schooling, and HIV/AIDS prevalence.

The goal is to analyze how these factors influence life expectancy and evaluate the performance of a regression model.

---

## 📂 Dataset
- File: `Life Expectancy Data.csv`
- The dataset contains country-wise health and economic indicators.
- Some columns used in this project:
  - Adult Mortality  
  - Alcohol  
  - GDP  
  - Schooling  
  - HIV/AIDS  
  - Life expectancy  

---

## ⚙️ Technologies Used
- Python 🐍  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🧠 Machine Learning Model
- **Model Used:** Linear Regression  
- The dataset is split into training and testing sets.
- The model is trained on 80% of the data and tested on 20%.

---

## 🚀 Steps Performed
1. Load dataset using Pandas  
2. Handle missing values (removed using `dropna()`)  
3. Select important features  
4. Split dataset into training and testing sets  
5. Train the Linear Regression model  
6. Predict life expectancy values  
7. Visualize results using scatter plot  
8. Evaluate model performance  

---

## 📊 Evaluation Metrics
- **Mean Squared Error (MSE):** Measures prediction error  
- **R² Score:** Indicates model accuracy  

---

## 📈 Output Visualization
- Scatter plot comparing:
  - Actual values vs Predicted values  

---

## 🧾 Code Snippet
```python
model = LinearRegression()
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
