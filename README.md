# deep-learning-challenge

# Report on Performance of Deep Learning Model for Alphabet Soup Overview of the Analysis:

This analysis aims to develop a deep learning model using neural networks to classify whether or not the nonprofit foundation Alphabet Soup will be successful based on various features. The model aims to achieve high accuracy in predicting the success of a charity, which can assist Alphabet Soup in making informed decisions about funding allocation.

# Results:

Data Preprocessing:

Target Variable: The target variable for the model is the "IS_SUCCESSFUL" column, which indicates whether a charity is successful or not.

Features: All columns except "IS_SUCCESSFUL," "EIN," and "NAME" are considered features for the model.

Variables to Remove: The "EIN" and "NAME" columns are removed from the input data as they are neither targets nor features and do not contribute to the prediction.

Compiling, Training, and Evaluating the Model:

Neurons, Layers, and Activation Functions:

The selected neural network model consists of 128 neurons in the first hidden layer, 64 in the second hidden layer, and 32 in the third hidden layer. The activation function used in all hidden layers is the rectified linear unit (ReLU), effectively capturing non-linear patterns. In addition, the output layer has one neuron with a sigmoid activation function for binary classification.

Target Model Performance: The target model performance is to achieve an accuracy higher than 75%.

Model Performance Results:

Loss: 0.5529006123542786, Accuracy: 0.7257142663002014

Loss: 0.5560992956161499, Accuracy: 0.723498523235321

Loss: 0.5512644052505493, Accuracy: 0.72967928647995

Loss: 0.5579925775527954, Accuracy: 0.728863000869751

# Summary:

The deep learning model achieved an accuracy ranging from 72.57% to 72.85% in predicting the success of charity organizations. The deep learning model performed reasonably well but fell short of the target accuracy of 75%. To improve the model's performance, we can:

Increase model complexity by adding more layers or neurons.
Experiment with different activation functions to find.
Perform more extensive data preprocessing, including feature engineering and selection techniques, to identify the most relevant features for the classification task.
By implementing these recommendations and refining the model, higher accuracy and better predictive power can be achieved in identifying successful charities. .
