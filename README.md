
This project builds and trains an Artificial Neural Network (ANN) to classify citrus fruits using physical and chemical features such as diameter, weight, and acidity levels. It demonstrates data preprocessing, model building, and evaluation using scikit-learn and TensorFlow.

##  Libraries Used
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn
- tensorflow / keras

##  What the Code Does
- Loads and preprocesses the citrus dataset
- Encodes target labels (fruit names)
- Scales input features
- Splits data into training and test sets
- Builds a neural network with Keras
- Trains the model and evaluates its performance using classification metrics

##  Model Summary
- 3 hidden layers with ReLU and tanh activations
- Output layer with sigmoid activation for binary classification
- Trained with `binary_crossentropy` and `Adam` optimizer

##  Results
- Prints classification report (Precision, Recall, F1-score)
