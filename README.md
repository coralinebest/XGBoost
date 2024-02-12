# XGBoost Implementation for California House Price Prediction

**Overview:**
This project implements the XGBoost algorithm to predict median house values in California using the California House Price dataset from the 1990 census. The XGBoost algorithm, an extension of the Gradient Boosting algorithm, is known for its versatility and superior predictive performance.

**Key Findings:**
- XGBoost is effective for prediction and classification purposes, excelling in forecasting competitions.
- The algorithm offers enhanced parameter tuning, making it less prone to overfitting and allowing for better generalization compared to Gradient Boosting.
- Applications in economics showcase XGBoost's popularity in various research domains, including economic policy uncertainty forecasting, treatment effects estimation, and direct estimation of economic indicators.

**Implementation:**
- The project utilizes the California House Price dataset, comprising 10 numerical features such as location, housing age, and income and is implemented in R.
- Hyperparameter tuning, including learning rate (eta), maximum depth, and regularization parameter (lambda), is performed through grid search to optimize model performance.
- Results indicate optimal hyperparameter values (eta=0.2, max depth=9, lambda=5) leading to the lowest Root Mean Squared Error (RMSE) on the test set.

**Conclusion:**
- XGBoost proves to be a powerful and versatile machine learning algorithm, offering superior predictive accuracy, regularization techniques, and parallel processing efficiency.
- Challenges include hyperparameter tuning complexity and potential difficulties in interpreting complex models.

*Note: The project's detailed results, methodology, and insights can be found in the provided documentation.*
