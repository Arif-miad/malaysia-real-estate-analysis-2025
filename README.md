# Malaysia Real Estate Market Analysis (2025)

## 📌 Overview
This project explores **2,000 entries of house price data** from Malaysia's real estate market, sourced from **Brickz**, a trusted platform for property insights. The analysis provides a detailed view of the country's real estate trends for 2025, including property location, tenure, type, median prices, and transaction counts.

This repository contains the full implementation of **data analysis, preprocessing, visualization**, and **machine learning regression models** for predictive modeling of property prices and transactions.

---

## ⚡ Key Features
- Comprehensive **Exploratory Data Analysis (EDA)** using detailed visualizations:
  - Histograms, Boxplots, Scatter Plots, Violin Plots, Heatmaps, and more.
- **Data Preprocessing**:
  - Encoding categorical variables and normalizing numerical features.
- **Machine Learning Models**:
  - Built 10 regression models (e.g., Linear Regression, Random Forest, XGBoost, CatBoost).
  - Compared models using performance metrics (R², RMSE, MAE).
- **Performance Comparison**:
  - Visualized model performance using bar charts and comparison tables.

---

## 📊 Dataset
The dataset contains the following columns:
- `Township`: The township where the property is located.
- `Area`: The area of the property.
- `State`: The Malaysian state.
- `Tenure`: The tenure type (e.g., Freehold, Leasehold).
- `Type`: The property type (e.g., Terrace, Condo, Bungalow).
- `Median_Price`: Median price of the property.
- `Median_PSF`: Median price per square foot.
- `Transactions`: Total number of transactions.

---

## 🔧 Setup and Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-arifmiah/malaysia-real-estate-analysis-2025.git
cd malaysia-real-estate-analysis-2025

3. Explore the Notebooks
Navigate to the notebooks/ folder and start exploring:

01_EDA.ipynb: For Exploratory Data Analysis.
02_Data_Preprocessing.ipynb: For data preprocessing steps.
03_Regression_Models.ipynb: For machine learning model building.
04_Performance_Evaluation.ipynb: For model evaluation and comparison.
🧪 Results
The CatBoost Regressor model achieved the best performance with the following metrics:
R² Score: 0.97
RMSE: 0.003

Key insights were derived from visualizations, highlighting property trends across states and tenure types.
📁 Folder Structure
php
Copy
Edit
malaysia-real-estate-analysis-2025/
├── data/                                  # Dataset files
├── notebooks/                             # Jupyter notebooks for analysis and modeling
├── results/                               # Visualization outputs
├── requirements.txt                       # Python dependencies
├── LICENSE                                # License file
├── README.md                              # Project documentation
📚 Libraries Used
Python 3.8+
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
CatBoost
✨ About Me
I'm a Machine Learning Engineer passionate about leveraging data science to solve real-world problems. Feel free to check out my other projects on Kaggle or GitHub.

🤝 Connect
📧 Email: your-email@example.com
🌐 Kaggle: Your Kaggle Profile
💼 LinkedIn: Your LinkedIn Profile


