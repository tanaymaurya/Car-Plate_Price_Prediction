# Russian Car Plate Price Prediction 🚘

Predicting the value of car license plates in Russia using CatBoost and feature engineering.

### Key Highlights:
- Achieved SMAPE score: **38.5%**
- Engineered features: plate digit patterns, region prestige, government flags
- Trained using log-transformed target for stability
- Tried LightGBM, XGBoost, Ridge, and blended models

### Model
- Main model: `CatBoostRegressor` with early stopping and native categorical support
- Data: from Kaggle competition [link]

### File
- `car_plate_price_prediction.ipynb` — full training + prediction pipeline
