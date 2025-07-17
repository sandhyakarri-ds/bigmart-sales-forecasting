# bigmart-sales-forecasting
Built a sales prediction model for BigMart using Python and Scikit-learn. Performed EDA and model evaluation using RMSE.
# 🛒 BigMart Sales Prediction – Regression Modeling Project

This project involves building a regression model to predict the sales of products across multiple BigMart outlets based on historical data. The dataset includes product details, outlet types, and sales volumes.

---

## 📑 Table of Contents
- [Objective](#objective)
- [Tools & Technologies](#tools--technologies)
- [Project Workflow](#project-workflow)
- [Key Features](#key-features)
- [Model Evaluation](#model-evaluation)
- [Dataset](#dataset)
- [Author](#author)

---

## 🎯 Objective

To predict the sales of various products in different stores using regression models and to understand the key factors affecting sales such as product type, outlet location, MRP, and visibility.

---

## 🧰 Tools & Technologies
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn
- Jupyter Notebook
- Regression Models (Linear, Decision Tree, Gradient Boosting)

---

## 🧠 Project Workflow

1. **Data Cleaning**
   - Handled missing values in `Item_Weight` and `Outlet_Size`
   - Standardized inconsistent category labels

2. **Exploratory Data Analysis (EDA)**
   - Analyzed sales distribution across outlet types and item categories
   - Visualized relationships between item MRP, visibility, and sales
   - Applied label encoding to categorical variables

3. **Model Building**
   - Trained multiple regression models:
     - Linear Regression
     - Decision Tree Regressor
     - Gradient Boosting Regressor (best performing)

---

## 🌟 Key Features Used

- Item Weight, Visibility, and MRP
- Outlet Establishment Year
- Outlet Size, Location Type, and Type
- Item Category and Type

---

## 📈 Model Evaluation

- **Metric**: Root Mean Squared Error (RMSE)
- **Best Model**: Gradient Boosting Regressor
- Achieved high R² score and lowest RMSE among models tested

---

## 📂 Dataset Source

[Kaggle – BigMart Sales Dataset](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data)

---

## 👩‍💻 Author

**Sandhya Karri**  
Career Transitioner | Aspiring Data Scientist  
🔗 [LinkedIn](https://www.linkedin.com/in/sandhya-karri-2a3b84212)

