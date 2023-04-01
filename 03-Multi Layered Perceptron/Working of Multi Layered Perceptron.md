 MLP is a type of artificial neural network (ANN) that is used for supervised learning tasks such as classification and regression.
 
 Components of Multilayered Perceptron :-
1. Input layer: The input layer is the first layer of the MLP and it takes in the input data for processing. Each node in the input layer represents a feature or attribute of the input data. For instance, in a handwritten digit recognition task, each node may represent the brightness value of a pixel in the input image.

2. Hidden layers: The hidden layers in an MLP are sandwiched between the input layer and the output layer. They are composed of multiple neurons, and each neuron takes in the outputs of all the neurons in the previous layer as inputs. The number of hidden layers in an MLP can vary depending on the complexity of the problem. The weights between the nodes in the hidden layers are learned during the training process.

3. Activation functions: Each neuron in the MLP applies an activation function to the weighted sum of inputs received from the previous layer. The activation function introduces non-linearity into the model, which makes it capable of approximating non-linear relationships between the input and output. Some commonly used activation functions include sigmoid, hyperbolic tangent (tanh), and Rectified Linear Units (ReLU).

4. Output layer: The output layer of the MLP produces the final prediction or output of the network. The number of output nodes depends on the task being performed. For example, in a binary classification task, there would be a single output node that produces a value between 0 and 1, indicating the probability of the input data belonging to the positive class. In a multiclass classification task, the number of output nodes equals the number of classes, and the output node with the highest probability is taken as the final prediction.

Steps involved in working of Multilayered Perceptron :-
1. Forward Propagation: The MLP takes in input data and passes it through the input layer. The values of the input nodes are multiplied by the weights and passed through the activation function to produce the output of the first hidden layer. This process is repeated for all the hidden layers until the final output layer is reached, which produces the final prediction.

2. Backpropagation: After the output of the MLP is generated, the error between the predicted output and the true output is calculated. The error is then backpropagated through the network from the output layer to the input layer. The weights between the neurons are adjusted during backpropagation to minimize the error.

3. Weight Update: The weights are updated using an optimization algorithm such as stochastic gradient descent (SGD) or Adam. The optimization algorithm adjusts the weights by computing the gradient of the error with respect to the weights and updating them in the direction of the negative gradient. This process is repeated for multiple epochs until the error is minimized and the MLP produces accurate predictions.

4. Dropout: To avoid overfitting, dropout is often applied to the MLP during training. Dropout randomly drops out some of the neurons in the hidden layers during each training iteration. This helps the model generalize better to new data and improves its accuracy on test data.
