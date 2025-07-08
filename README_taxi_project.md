
# 🚖 Taxi Fare Prediction using Machine Learning

This project predicts taxi fares based on trip-level information using supervised machine learning models. The dataset was sourced from a Kaggle competition: [Taxi Fare Guru - Total Amount Prediction Challenge](https://www.kaggle.com/competitions/taxi-fare-guru-total-amount-prediction-challenge/).

---

## 📌 Overview

- **Train Data:** `train.csv`
- **Test Data:** `test.csv`
- **Sample Submission:** `sample.csv.csv`
- **Goal:** Predict `fare_amount` from pickup/dropoff and ride metadata
- **Model Type:** Regression
- **Evaluation Metric:** R² Score

---

## 🧠 Tools & Libraries Used

- Python
- NumPy, Pandas (Data manipulation)
- Matplotlib, Seaborn (Data visualization)
- Scikit-Learn (Preprocessing and Modeling)
- XGBoost (Boosting model)

---

## ⚙️ ML Workflow

- **Data Cleaning**: Handled missing values using `SimpleImputer` and `KNNImputer`
- **Feature Scaling**: `StandardScaler`, `MinMaxScaler`
- **Encoding**: `OneHotEncoder`, `LabelEncoder`
- **Column Transformation**: `ColumnTransformer` pipeline
- **Model Training**:
  - `LinearRegression`
  - `KNeighborsRegressor`
  - `RandomForestRegressor`
  - `GradientBoostingRegressor`
  - `XGBRegressor`

---

## 📈 Results

- Compared model performance using **R² Score**
- Found that ensemble models like **RandomForest** and **XGBoost** gave better results on validation data

---

## 📊 Visualizations

- Fare Amount distribution
- Outlier detection using boxplots
- Heatmap of feature correlations

---

## 🚀 Future Improvements

- Add date-time based feature engineering (hour, day of week, etc.)
- Add geospatial features (pickup/dropoff distance)
- Deploy best model using Streamlit

---

## 🧾 How to Run

1. Clone the repo and install dependencies:

```bash
pip install -r requirements.txt
```

2. Run the notebook:

```bash
Open taxi_fare_prediction.ipynb
```

---

## 👩‍💻 Author

**Akansha Gautam**  
- [GitHub](https://github.com/yourusername)  
- [LinkedIn](https://linkedin.com/in/yourprofile)

---
