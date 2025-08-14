# Employee Burnout Analysis & Prediction (VOIS Project)

## 📌 Overview
This project explores **employee burnout issues** in product- and service-based companies.  
It uses **exploratory data analysis (EDA)**, **feature engineering**, and **machine learning techniques** to analyze patterns and predict burnout levels among employees.

The goal is to help organizations — from **startups** to even **global health bodies like WHO** — understand and proactively address employee burnout.

---

## 🎯 Problem Statement
Employee burnout is a critical issue impacting productivity, mental health, and retention rates.  
The objective of this project is to:
1. **Analyze** employee data to identify burnout patterns.
2. **Predict** burnout scores using machine learning.
3. Provide actionable insights to organizations.

---

## 📂 Dataset
- **File:** `employee_burnout_analysis-AI.csv`
- **Columns:**
  - Employee ID  
  - Date of Joining  
  - Gender  
  - Company Type  
  - WFH Setup Available  
  - Designation  
  - Resource Allocation  
  - Mental Fatigue Score  
  - Burn Rate *(target variable)*
- **Size:** 22,750 records  
- **Source:** Provided as part of a **VOIS project/training assignment**.

---

## 🛠 Technologies & Libraries Used
- **Python**: Data analysis & modeling
- **Pandas**: Data manipulation
- **NumPy**: Numerical computations
- **Matplotlib / Seaborn / Plotly**: Data visualization
- **Scikit-learn**:
  - Preprocessing (`LabelEncoder`, `SimpleImputer`)
  - Machine Learning Models (`AdaBoostRegressor`, `RandomForestRegressor`)
  - Dimensionality Reduction (`PCA`)

---

## 📊 Steps in the Project
1. **Data Loading & Cleaning**
   - Removed duplicates  
   - Filled missing values (mean imputation)  
   - Removed irrelevant columns (`Employee ID`)

2. **Exploratory Data Analysis (EDA)**
   - Count plots for categorical features  
   - Histograms for numerical features  
   - Correlation heatmap

3. **Feature Engineering**
   - Label encoding for categorical columns  
   - Normalization of feature names

4. **Dimensionality Reduction**
   - Applied **PCA** to reduce dimensionality while retaining 95% variance

5. **Predictive Modeling**
   - Implemented **AdaBoost Regressor** & **RandomForest Regressor** for burnout prediction

---

## 📈 Key Insights
- **Mental Fatigue Score** and **Resource Allocation** show strong correlation with burnout.
- Burnout levels vary across **company types** and **WFH setup availability**.
- PCA reduced the feature space while preserving most information.

---

## 🚀 How to Run the Project

### 1. Clone this repository
```bash
git clone https://github.com/<your-username>/employee-burnout-analysis.git
cd employee-burnout-analysis
2. Install dependencies
pip install -r requirements.txt

3. Run the notebook
jupyter notebook ProjectVOIS.ipynb


Or execute the Python script:

python employee_burnout_analysis.py
````bash
📌 Future Improvements

Hyperparameter tuning for better model performance.

Deploy as a web dashboard using Streamlit/Flask.

Incorporate additional features such as work hours, leave records, etc.

📜 License

This project is for educational purposes.
Dataset provided as part of VOIS training/assignment — not for commercial use.

