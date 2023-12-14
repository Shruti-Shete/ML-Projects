**Overview:**

This project focuses on recognizing handwritten digits using the famous MNIST dataset. The MNIST dataset consists of 70,000 images of handwritten digits (0 to 9) with each image being 28x28 pixels.

**Data Exploration:**

Loading Data: The MNIST dataset was loaded using the fetch_openml function from scikit-learn.<br />
Data Shape: The dataset contains 70,000 samples, each with 784 features representing the 28x28 pixels.<br />
Target Data: The target values are the actual digits represented in the images.

**Data Preprocessing:**

Typecasting: Converted target values to integers.<br />
Normalization: Scaled pixel values to the range [0, 1].<br />
Data Splitting: Split the data into training and testing sets.

**Logistic Regression Model:**

Model Creation: Used Logistic Regression for multiclass classification.<br />
Model Training: Fit the model using the training data.<br />
Model Evaluation: Achieved an accuracy of approximately 92% on the test set.<br />
Classification Report: Generated a classification report providing precision, recall, and F1-score for each digit.

**Results:**
Accuracy: The Logistic Regression model achieved an accuracy of 92% on the test set.<br />
Confusion Matrix: Visualized the confusion matrix to understand the model's performance on each digit.<br />
Classification Report: Provided detailed precision, recall, and F1-score for each digit

**Conclusion:**

The Logistic Regression model demonstrates effective performance in recognizing handwritten digits from the MNIST dataset. The accuracy of 92% indicates its capability, and the model can be further optimized or replaced with more advanced techniques for higher accuracy.
