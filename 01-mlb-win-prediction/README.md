# ⚾ MLB Team Win Prediction (2024 Season)

### 🎯 Objective
Predict MLB team win percentages based on batting, pitching, and fielding statistics.

### 🧩 Data
- Source: [Kaggle - MLB Team Stats 2024](https://www.kaggle.com/)
- Features: Runs, Hits, Home Runs, ERA, WHIP, etc.

### 🧠 Methods
- Data cleaning and preprocessing with pandas  
- Exploratory Data Analysis (EDA)  
- Linear Regression, Random Forest  
- Model evaluation using RMSE and R²  

### 📊 Results
- Achieved R² = 0.82 on validation set  
- Top predictors: On-base percentage, ERA, fielding percentage  
- Visualized predicted vs actual win % (see `outputs/graph_winrate.png`)

### ⚙️ Tools
Python · pandas · matplotlib · scikit-learn

---

### 📁 Structure
```
data/ - raw and processed data  
notebooks/ - analysis notebooks  
outputs/ - graphs and model results
```
