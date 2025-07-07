# 🫐 Blueberry Regression — Kaggle Challenge

This repository contains a regression solution for predicting blueberry yield in a Kaggle competition.

## 📂 Project Structure

- `train.csv` — training dataset with features and target variable  
- `test.csv` — test dataset without target variable  
- `submission.csv` — submission file with predictions for Kaggle  
- `blueberry_model.ipynb` — Jupyter notebook with analysis, training, and predictions  
- `requirements.txt` — project dependencies  
- `README.md` — project documentation  

## 🔧 Technologies Used

- Python 3  
- Pandas, NumPy  
- Scikit-Learn  
- Jupyter Notebook  

## 📊 Dataset Description

The dataset contains agricultural features used to predict blueberry yield.

## 📈 Project Workflow

1. 📥 Load and explore data  
2. 🧹 Data preprocessing (missing values handling, encoding)  
3. 📊 Exploratory data analysis (EDA)  
4. 🤖 Train regression models (`RandomForestRegressor`, `PolynomialFeatures` + `LinearRegression`)  
5. 🧪 Evaluate model performance (MAE, Root MAE)  
6. 💾 Generate `submission.csv` file for Kaggle submission  

## 🚀 How to Run

Install dependencies:

```bash
pip install -r requirements.txt
