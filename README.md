# Visualise Neural Network
Generates a static diagram of a neural network, where each neuron is connected to every neuron in the previous layer.

For example, this code:

    network = NeuralNetwork()
    network.add_layer(3)
    network.add_layer(4)
    network.add_layer(1)
    network.draw()

Will generate this diagram:

![Diagram of a neural network with 3 neurons in the first layer, 4 neurons in the second layer and 1 neuron in the 3rd layer](http://i.stack.imgur.com/8oxCO.png)
