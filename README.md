
# 🌦️ Australia Weather Prediction using Logistic Regression

This repository contains a Jupyter Notebook that performs exploratory data analysis (EDA), preprocessing, and logistic regression modeling on weather data from Australia to predict if it will rain the next day.

## 📁 Project Structure

- `Australia Weather Data LogisticRegression.ipynb`: Main notebook with step-by-step implementation including:
  - Data loading
  - Data cleaning and preprocessing
  - Feature selection
  - Logistic Regression modeling
  - Performance evaluation

## 🔧 Requirements

Install the dependencies with:

```bash
pip install -r requirements.txt
```

### Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn (for resampling, if used)

You can generate a `requirements.txt` using:

```bash
pip freeze > requirements.txt
```

## 📊 Dataset

The dataset used is the [Australian weather dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) available on Kaggle. It contains daily weather observations from numerous Australian weather stations.

**Target Variable**: `RainTomorrow` — whether it will rain the next day (Yes/No)

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/australia-weather-logistic.git
   cd australia-weather-logistic
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Run all cells in `Australia Weather Data LogisticRegression.ipynb`

## 📈 Model Evaluation

The logistic regression model is evaluated using:
- Confusion Matrix
- Accuracy Score
- ROC AUC Curve

## 🧠 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Try other classification models (Random Forest, XGBoost, etc.)
- Deploy the model via Flask or Streamlit

## 📬 Contact

For queries or suggestions:
- Email: vaibhavdesai682@gmail.com


⭐️ If you find this useful, consider giving it a star!
