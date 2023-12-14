**Overview**

This project aims to predict the likelihood of diabetes in individuals based on various health-related features using Artificial Neural Network. <br />
The classification model utilizes a neural network architecture implemented using the Keras library.

**Dataset**

It consists of 768 instances with 9 features, including pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age, and the target variable 'Outcome' indicating the presence or absence of diabetes.

**Model Architecture**

The neural network model consists of multiple dense layers:

Input Layer: 64 neurons, ReLU activation <br />
Hidden Layer I: 128 neurons, ReLU activation <br />
Hidden Layer II: 128 neurons, ReLU activation <br />
Output Layer: 1 neuron, Sigmoid activation (for binary classification) <br />
The model was compiled using the Adam optimizer with a learning rate of 0.001 and binary cross-entropy loss, which is suitable for binary classification problems.

**Evaluation**
The model achieved an accuracy of approximately 72.73% on the test set. Evaluation metrics, including precision, recall, and F1-score, were computed and presented through a confusion matrix and a classification report.

**Results**
Accuracy: 72.73% <br />
Precision: 0.54<br />
Recall: 0.47<br />
F1-Score: 0.50

