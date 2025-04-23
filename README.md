# 🏡 USA Housing Linear Regression Model

This project uses a linear regression model to predict house prices based on the **USA Housing Dataset**. It includes data preprocessing, training, evaluation, and visualization of model performance.

## 📁 Dataset
- **Source**: Kaggle  
- **File Used**: `USA Housing Dataset.csv`

## 🧠 Features Used
- Bedrooms, Bathrooms, Sqft Living, Sqft Lot, Floors  
- Waterfront, View, Condition, Sqft Above, Sqft Basement  
- Year Built, Year Renovated

## 🎯 Target
- `price`

## 📊 Model
- `LinearRegression` from `scikit-learn`
- Evaluated using **RMSE** and **R² Score**
- Plotted residuals and feature importances

## 📈 Results
- **RMSE**: ~256,000  
- **R² Score**: ~0.375  
- **Top Influential Features**: `waterfront`, `bedrooms`, `bathrooms`

## 📸 Visuals
- ✅ Actual vs Predicted Scatter Plot  
- ✅ Residual Plot  
- ✅ Coefficient-based Feature Importance

## 🧰 Libraries Used

See `requirements.txt` or install manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
