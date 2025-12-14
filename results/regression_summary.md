# Regression Results Summary (Organic Products Spending)

Models compared:
- Linear Regression
- Lasso
- CART
- KNN
- Random Forest
- Support Vector Regression (SVR)

Evaluation metrics:
MAE, MAPE, MSE, RMSE

Key observations:
- Linear models (Linear Regression, Lasso) showed stable performance across seeds.
- Tree-based and ensemble models did not significantly outperform linear models
  on this dataset.
- KNN and SVR showed higher variance and less stable performance.

Full model comparison tables and feature importance rankings
are provided in `codebook/regression_data_description_and_analysis.pdf`.
