**Overview:**

This project aims to predict the miles per gallon (MPG) of a car based on various features such as the number of cylinders, displacement, horsepower, weight, acceleration, model year, and origin. The dataset used for this project is sourced from the auto-mpg.data file, where each row represents a different car.

**Data:**

The dataset includes the following columns:

mpg: Miles per gallon<br />
cylinders: Number of cylinders in the engine<br />
displacement: Engine displacement<br />
horsepower: Horsepower of the car<br />
weight: Weight of the car<br />
acceleration: Acceleration of the car<br />
model year: Year the car was manufactured<br />
origin: Origin of the car (1: USA, 2: Europe, 3: Japan)<br />

**Data Preprocessing:**

Loaded the dataset, handling missing values in the 'horsepower' column.<br />
Utilized one-hot encoding for the 'origin' column.<br />
Concatenated the one-hot encoded columns with the original dataset.<br />
Renamed the one-hot encoded columns to 'USA', 'Europe', and 'Japan'.<br />
Explored the correlation between different features using a heatmap and pair plot.<br />
Scaled the feature variables using Min-Max scaling.<br />
Split the data into training and testing sets.<br />

**Neural Network Model:**

Built a feedforward neural network using Keras.<br />
The model architecture includes an input layer, two hidden layers, and an output layer.<br />
Utilized the RMSprop optimizer and mean squared error loss for regression.<br />
Trained the model for 400 epochs with a batch size of 25.<br />
Evaluated the model performance using mean squared error and mean absolute error.<br />

**Model Evaluation:**

Plotted the training and validation mean squared error over epochs.<br />
Evaluated the model on the test set.<br />
Calculated the R-squared score to assess the goodness of fit<br />

**Prediction:**

Made predictions on a new set of feature values.<br />
The model predicts the MPG for a car based on the given input.<br />

**Conclusion:**
The neural network model achieved a high R-squared score, indicating a good fit to the data. The project demonstrates the application of a regression model to predict a continuous variable, MPG, from various car features. The model can be useful for understanding the factors influencing fuel efficiency in cars.
