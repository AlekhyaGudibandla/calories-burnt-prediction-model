# 🔥 Calories Burnt Prediction Using Machine Learning

This project predicts the number of calories burnt during exercise using machine learning.  
It uses physical attributes and workout metrics such as age, weight, duration, heart rate, and body temperature to build a highly accurate predictive model.

## 📌 Features
- Complete data preprocessing pipeline  
- Exploratory Data Analysis (EDA) with PDF & QQ plots  
- Outlier detection using the IQR method  
- Correlation heatmap and feature insights  
- XGBoost Regressor model  
- Hyperparameter tuning using RandomizedSearchCV  
- Evaluation using R² and RMSE  
- Actual vs Predicted visualization  

## 📁 Dataset
Two CSV files are used:

- `exercise.csv` → Contains demographic and workout attributes  
- `calories.csv` → Contains calories burnt values  

The datasets are merged using `User_ID`.

## 🚀 Model Performance
- **R² Score:** ~0.99999  
- **RMSE:** ~2.07  
The model predicts calorie burn with extremely high accuracy.

## 🧠 Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- XGBoost  

## 📄 Project Structure
```

📦 Calories-Burnt-Prediction
├── Caloris-Burnt-Prediction-Model.ipynb   # Main notebook
├── exercise.csv                            # Exercise dataset
├── calories.csv                             # Calories dataset
└── Report.pdf                               # Final project report

````

## 📊 Visualizations Included
- Distribution plots (PDF)
- QQ plots
- Correlation heatmap
- Actual vs Predicted scatter plot

## 📜 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/AlekhyaGudibandla/calories-burnt-prediction-model.git
````

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook

   ```bash
   jupyter notebook Caloris-Burnt-Prediction-Model.ipynb
   ```
