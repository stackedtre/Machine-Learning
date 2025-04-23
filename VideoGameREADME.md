# 🎮 Video Game Sales Prediction with Random Forest

This project uses a **Random Forest Regressor** to predict the **global sales** of video games based on regional sales and release year. The dataset was sourced from Kaggle and includes thousands of popular titles across platforms and genres.

## 📁 Dataset

- **Source**: [Video Game Sales](https://www.kaggle.com/datasets/anandshaw2001/video-game-sales)
- **Filename**: `vgsales.csv`
- **Features Used**:
  - `Year`: Release year of the game
  - `NA_Sales`: North America sales (in millions)
  - `EU_Sales`: Europe sales
  - `JP_Sales`: Japan sales
  - `Other_Sales`: Other regions
- **Target**: `Global_Sales` (total worldwide sales in millions)

## 🧠 Model Overview

- **Model**: Random Forest Regressor
- **Library**: `sklearn.ensemble.RandomForestRegressor`
- **Performance**:
  - **RMSE**: ~0.76
  - **R² Score**: ~0.823
- **Key Insight**: NA and EU sales are the strongest predictors of global performance.

## 📊 Visualizations

- 🔍 Feature Importance Bar Chart
- 📈 Model evaluation using RMSE & R²

## 🚀 How to Run

1. Clone the repo
2. Install dependencies from `requirements.txt`
3. Run `VideoGameSales.ipynb` in Jupyter or Google Colab

## 📦 Dependencies

See `requirements.txt` for full package list.

## ✍️ Author

Tre Manciel  
Built with 💻, 🎮, and some Random Forest magic 🌲
