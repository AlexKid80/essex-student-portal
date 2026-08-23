# Algorithms

This folder contains the main Machine Learning algorithms used in the energy consumption analysis.

## K-Means Clustering

K-Means was used to identify groups of observations with similar energy consumption characteristics.

The analysis included:

- Feature selection
- Standardisation using `StandardScaler`
- Elbow Method
- Silhouette Score
- Selection of the optimal number of clusters
- Interpretation of the resulting consumption profiles

K-Means was applied to both the PJME energy dataset and the household electricity consumption dataset.

## Linear Regression

Linear Regression was used to estimate household `Global_active_power` from electrical measurements.

Two models were evaluated:

- Multiple Linear Regression using six predictors
- Simple Linear Regression using only `Global_intensity`

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The models were trained and tested using a chronological train-test split.