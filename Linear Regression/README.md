**House Sales Price Prediction**

**Overview:**

This Python code is focused on predicting house prices based on various features using a Linear Regression model.

**Workflow:**

*Data Loading:*

The dataset is loaded from the provided CSV file using Pandas.

*Data Exploration:*

Basic exploratory data analysis (EDA) is performed, including viewing data samples and checking correlations.

*Data Cleaning:*

Missing values are checked, and columns deemed unnecessary for prediction are dropped.

*Data Preprocessing:*

Data is scaled using Min-Max scaling to bring all features to a common scale.

*Feature Selection:*

Correlation analysis is conducted to identify multicollinearity.<br />
Features are selected based on their relevance to the target variable.

*Train-Test Split:*

The dataset is split into training and testing sets using the train_test_split() method.

*Linear Regression Model:*

A Linear Regression model is implemented using the LinearRegression class from scikit-learn.<br />
The model is trained on the training set and evaluated on the test set.

*Regression Metrics:*

Regression metrics such as R-squared score, mean squared error, and mean absolute error are calculated to assess model performance.

*Coefficient and Intercept Analysis:*

Coefficients and intercept values of the trained model are examined.

*Prediction for New Samples:*

Predictions are made for new samples to demonstrate the model's application.

*Conclusion:*

The Linear Regression model achieves an R-squared score of approximately 0.71 on the test set, indicating reasonable predictive performance. The code provides a structured workflow for house price prediction and serves as a foundation for further improvements and feature engineering.

**Dependencies:**

NumPy<br />
Pandas<br />
Matplotlib<br />
Seaborn<br />
Scikit-learn
