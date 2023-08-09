In this model I downloaded dataset of breast cancer from Kaggle. 
Then, preproccesed it to fit various libraries. 
Normalizing the data helps in improving the accuracy of the model.
Train, Test, Validation split are in the ratio = 72:20:8
Neural Network added contains two hidden layer of 32 neurons and 80 neurons
using activation 'selu' and 'relu' respectievely. It was chosen arbitrarily.
Since, our output is in terms of Malignant and Benign which comes under 
probabilistic output. I had used softmax activation function for the output layer.
Adam helps in optimisation faster, so we used it. It consumes more memory which
was not a concern for us. As, our dataset was small.
