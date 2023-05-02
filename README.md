# Cat-vs-Non-cat-nn

Designed a deep neural network to classify images as either containing a cat or not containing a cat.

The network consists of an input layer, l hidden layers, and an output layer. The input layer of the neural network consists of a flattened vector representation of the input image. Each pixel in the image is treated as a feature, and all the features are combined into a single long vector.

The l hidden layers of the network each contain a certain number of neurons.Each neuron in the hidden layer applies an activation function to the weighted sum of its inputs. I have chosen to use the Rectified Linear Unit (ReLU) activation function for all the hidden layers.

The output layer of the network consists of a single neuron with a sigmoid activation function. The sigmoid function takes the weighted sum of the inputs from the previous layer and produces a value between 0 and 1, which represents the probability that the input image contains a cat. If the output value is greater than 0.5, the neural network classifies the input image as a cat. Otherwise, it classifies the image as non-cat.

![Blank 4 Grids Collage](https://user-images.githubusercontent.com/74449359/235656728-56d39543-67d0-4fda-835f-37d59b149c44.png)
