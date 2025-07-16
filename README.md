# House Price Prediction (Zameen.com Dataset)

This project is a **Machine Learning regression model** designed to predict house prices in major Pakistani cities using data from Zameen.com. The entire pipeline includes preprocessing, outlier removal, feature encoding, model training using **XGBoost**, evaluation, and model saving.

---

## Dataset

- **Dataset File**: `zameen-updated.csv`
- **Columns Used**:
  - property_id, property_type, price, city, province_name, baths, bedrooms, Area Type, Area Size, latitude, longitude, purpose

---

## ML Techniques Used

| Step               | Method                          |
|--------------------|----------------------------------|
| Data Cleaning      | Missing/duplicate removal        |
| Outlier Handling   | IQR (Interquartile Range)        |
| Encoding           | One-Hot Encoding                 |
| Scaling            | Min-Max Scaling                  |
| Model              | XGBoost Regressor                |
| Tuning             | RandomizedSearchCV               |
| Saving Model       | joblib (`house_price_model.pkl`) |

---

## Evaluation Metrics

- **R² Score**
- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**

## Deploy (Streamlit)

This project has been deployed using **Streamlit** to make predictions via a simple web interface.
 <!-- **[Click here to visit the House Price Prediction Web App](./app.py)** -->

