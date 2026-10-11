# Gold Price Prediction using Random Forest Regression

## 📌 Project Overview
This project predicts gold prices using a Random Forest Regression model and historical gold market data. The model learns relationships between gold prices and other financial indicators to predict gold prices on unseen data.

## 🎯 Objectives
- Explore and analyze historical gold price data.
- Visualize correlations between numerical features.
- Train a Random Forest Regression model.
- Evaluate model performance using the R² score.
- Compare actual and predicted gold prices.

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 🤖 Machine Learning Model
**Random Forest Regressor**

The dataset's `GLD` column is the target variable. The `Date` column is excluded from the input features, and the remaining numerical columns are used to train the model.

## 📊 Model Evaluation
The model is evaluated using the R² score. A plot compares actual gold prices with predicted gold prices on the test dataset.

## 📁 Project Structure
```text
Gold Price Prediction Random Forest/
├── README.md
└── gold_price_prediction_random_forest.ipynb
```

## 🚀 How to Run
1. Download or clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the gold price dataset.
4. Run the notebook cells in order.

## 📚 Dataset
Source: [Gold Price Data — Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data)