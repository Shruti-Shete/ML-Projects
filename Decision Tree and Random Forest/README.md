**Overview:**

This analysis focuses on predicting customer churn using a dataset containing information about telecom customers. The goal is to build a predictive model that can identify customers likely to churn, enabling proactive retention strategies.

**Dataset:**
The dataset contains various features related to customer behavior, including account length, international plan usage, voicemail plan status, call statistics, and more. The target variable is 'Churn,' indicating whether a customer has churned (True) or not (False).

**Decision Tree Classifier:**

Model Creation: Used a Decision Tree Classifier for predicting churn.<br />
Model Training: Fit the model using the training data.<br />
Model Evaluation: Achieved an accuracy of approximately 94% on the test set.<br />
Visualization: Plotted the decision tree for better understanding.<br />

**Decision Tree Results:**

Accuracy: The Decision Tree Classifier achieved a high accuracy of 94% on the test set.<br />
Confusion Matrix: Visualized the confusion matrix and analyzed precision, recall, and F1-score for each class.

**Random Forest Classifier:**

Model Creation: Implemented a Random Forest Classifier for predicting churn.<br />
Model Training: Fit the model using the training data.<br />
Model Evaluation: Achieved an accuracy of approximately 91% on the test set.<br />
Confusion Matrix: Visualized the confusion matrix for analysis.

**Random Forest Results:**

Accuracy: The Random Forest Classifier achieved an accuracy of 91% on the test set.<br />
Confusion Matrix: Examined the confusion matrix to understand the model's performance.<br />

**Prediction:**

Used both the Decision Tree and Random Forest models to make predictions on new data. The results demonstrate the predicted churn status for hypothetical customer scenarios.

**Conclusion:**

The Decision Tree and Random Forest models show promising results in predicting customer churn based on telecom customer data. The Decision Tree model achieved higher accuracy, but further evaluation and fine-tuning of hyperparameters can improve model performance. 
