# 🛒 Walmart Retail Sales Analysis & Forecasting

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow)
![NumPy](https://img.shields.io/badge/Library-NumPy-lightgrey)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview
This project analyzes Walmart retail sales data to uncover trends, seasonality, and key business insights. It also builds machine learning models to forecast future sales, helping improve inventory management and decision-making.

---

## 🎯 Objective
- Analyze historical sales data  
- Identify seasonal trends and patterns  
- Understand the impact of external factors  
- Build predictive models for sales forecasting  

---

## 📊 Dataset Information
- **Dataset:** Walmart Retail Dataset  
- **Records:** 6,435  
- **Features:** 8  

### 🔑 Columns:
- `Store` → Store number  
- `Date` → Weekly sales date  
- `Weekly_Sales` → Sales amount (Target Variable)  
- `Holiday_Flag` → Holiday indicator (0 = No, 1 = Yes)  
- `Temperature` → Temperature on that day  
- `Fuel_Price` → Fuel price  
- `CPI` → Consumer Price Index  
- `Unemployment` → Unemployment rate  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:**
  - Pandas & NumPy → Data manipulation  
  - Matplotlib & Seaborn → Visualization  
  - Scikit-learn → Machine Learning  

---

## 🔍 Project Workflow

### 1️⃣ Data Preprocessing
- Converted `Date` column to datetime format  
- Extracted `Year` and `Month`  
- Checked for missing values and duplicates  

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Monthly and weekly sales trends  
- Seasonal patterns  
- Store-wise performance analysis  
- Correlation between features  

---

### 3️⃣ Feature Engineering
- Created time-based features  
- Aggregated sales data for insights  

---

### 4️⃣ Model Building
Implemented multiple regression models:
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

---

### 5️⃣ Model Evaluation
Models evaluated using:
- MAE (Mean Absolute Error)  
- MSE (Mean Squared Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  

---

## 📈 Key Insights
- 📊 Sales show strong seasonal trends  
- 📅 Certain months consistently generate higher revenue  
- ⛽ Fuel price and unemployment impact sales  
- 🌲 Random Forest performed best among models  

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/walmart-sales-analysis.git
```

### 2. Navigate to Folder 
```bash
cd walmart-sales-analysis
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Notebook 
```bash
jupyter notebook
```

## 📂 Project Structure
```bash
walmart-sales-analysis/
│── Walmart_Retail_Sales_Analysis_Project.ipynb
│── Walmart Dataset.csv
│── README.md
```

##💡 Future Improvements
- Implement time-series forecasting (ARIMA / Prophet)
- Deploy using Streamlit or Flask
- Build interactive dashboards (Power BI / Tableau)
- Perform hyperparameter tuning
- Add real-time data pipeline


Author 
Jayendar A
