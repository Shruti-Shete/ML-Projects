**Overview:**

This project focuses on predicting housing prices in Boston using the famous Boston Housing dataset. The dataset contains 13 features, such as crime rate, room count, and proximity to employment centers, that influence the median value of owner-occupied homes (MEDV).

**Data Exploration:**

Loading Data: The dataset was loaded using the scikit-learn library.<br />
Data Description: The dataset consists of 506 instances and 13 features, with the target variable being the median value of homes.<br />
Data Attributes:
CRIM: Crime rate per capita<br />
ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.<br />
INDUS: Proportion of non-retail business acres per town<br />
... (and more)

**Data Preprocessing:**

Creating DataFrame: Converted the data into a Pandas DataFrame for easier manipulation.<br />
Handling Missing Values: Checked for missing values (none found).<br />
Data Types: All features are of type float64.<br />
Data Visualization: Visualized the distribution of the target variable (MEDV) and explored feature correlations using a heatmap.<br />

*Feature Scaling:*
MinMax Scaling: Scaled the feature variables using MinMaxScaler to bring them into a uniform range (0 to 1).

**Model Building:**

*Lasso Regression:*

Feature Selection: Applied Lasso Regression with alpha = 0.001 for feature selection.<br />
Model Training: Fitted the Lasso model on the training data.<br />
Model Evaluation: Obtained an R-squared score of approximately 0.79 on the test set.

*Ridge Regression:*

Model Training: Applied Ridge Regression with alpha = 0.001 on the training data.<br />
Model Evaluation: Achieved an R-squared score of around 0.79 on the test set.<br />
Performance Metrics: Computed mean squared error and R-squared for further evaluation.

**Results:**

*Lasso Regression:*

R-squared Score: 0.79<br />
Key Coefficients: CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT<br />
Intercept: 25.34

*Ridge Regression:*

R-squared Score: 0.79<br />
Mean Squared Error: 17.29<br />
Key Coefficients: Similar to Lasso Regression

**Conclusion:**

The Lasso and Ridge Regression models achieved a good R-squared score of approximately 0.79, indicating a decent fit to the data. Feature selection in Lasso Regression revealed the most influential features affecting housing prices. Further fine-tuning and optimization can be explored to improve model performance.
