# Final Project — Predicting Housing Prices in Lyon

An individual end-to-end data science project: predicting the sale prices of residential properties in **Lyon, France**.

**Data and features**
- `lyon_housing.csv`: housing transactions with property type, rooms, surface areas, parking, location, district, and construction and sale dates.
- `station_coordinates.json`: metro and tram station coordinates, used to engineer a **distance-to-nearest-station** feature.
- Cleaning, date conversion, column-by-column analysis, statistical tests (e.g. mean-price differences between groups) and derived features.

**Models** (k-fold cross-validation with manual grid search):

| Model | Test R² | Test RMSE (€) |
|---|---|---|
| Linear regression | 0.71 | ~83.5k |
| Lasso / Ridge | 0.73 | ~82k |
| Random forest | 0.78 | ~73k |
| Neural network (5-layer MLP, Keras) | 0.80 | ~70k |
| Weighted-average ensemble | 0.80 | ~70k |
| Stacking ensemble | 0.82 | ~67k |
| **XGBoost** | **0.82** | **~66k** |

XGBoost performed best, ahead of both the neural network and the stacking ensemble. The notebook also includes a feature-importance analysis and a short experiment on how the random train/test split affects R².

Notebook: [`Lyon_Housing_Price_Prediction.ipynb`](Lyon_Housing_Price_Prediction.ipynb)
