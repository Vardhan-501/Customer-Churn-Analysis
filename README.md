# 🏦 Customer Churn Analytics Project

## 📌 Project Overview
This project focuses on analyzing customer churn behavior and predicting whether a customer will exit the bank or not using Machine Learning techniques.

The project includes:
- 🧹 Data Cleaning
- 📊 Exploratory Data Analysis (EDA)
- 📈 Data Visualization
- 🤖 Machine Learning Model
- 📉 Model Evaluation
- 💡 Business Insights

# 🗂️ Dataset Information

The dataset contains customer banking details such as:

- 👤 Customer Demographics
- 💳 Credit Score
- 🌍 Geography
- 👨‍💼 Gender
- 📅 Age
- 💰 Balance
- 🏦 Number of Products
- 💵 Estimated Salary
- 🚪 Exited (Target Variable)

# 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| 🐍 Python | Data Analysis |
| 🐼 Pandas | Data Manipulation |
| 🔢 NumPy | Numerical Operations |
| 📊 Matplotlib | Visualization |
| 🎨 Seaborn | Statistical Visualization |
| 🤖 Scikit-learn | Machine Learning |
| 📓 Google Colab | Development Environment |
   
# 🔄 Project Workflow

## 1️⃣ Data Loading
- Imported dataset using Pandas

## 2️⃣ Data Cleaning
- Removed null values
- Removed duplicate rows
- Dropped unnecessary columns:
  - `RowNumber`
  - `CustomerId`
  - `Surname`

## 3️⃣ Exploratory Data Analysis (EDA)
Performed analysis using:
- Countplots
- Histograms
- Boxplots
- Heatmaps
- Scatterplots


# 🤖 Machine Learning

## ✅ Model Used
- Logistic Regression

## ⚙️ Preprocessing Steps
- One-Hot Encoding
- Train-Test Split
- Feature Scaling using StandardScaler


# 📉 Model Evaluation

## ✅ Accuracy Score
- Achieved good prediction accuracy for customer churn classification.

# 💡 Business Insights

✔️ Older customers tend to churn more frequently.  

✔️ Inactive members have higher churn rates.  

✔️ Geography plays an important role in customer churn.  

✔️ Customers with higher balances are more likely to exit.  

✔️ Active customers are less likely to churn.  


# 🙌 Conclusion

This project demonstrates an end-to-end Machine Learning workflow including:
- Data preprocessing
- Data visualization
- Predictive modeling
- Business insight generation
