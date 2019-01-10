# -Forward-Propagation-with-Relu
To do forward propagation (prediction) for a simple neural network: 
Each data point is a customer. The first input is how many accounts they have, and the second input is how many children they have. 
The model will predict how many transactions the user makes in the next year.
The input data is pre-loaded as input data, and the weights are in a dictionary called weights. 
The array of weights for the first node in the hidden layer are in weights [‘node_0’], and for the second node in the hidden layer are in weights[‘node_1’]
respectively. 
The weights feeding into the output node are available in weights.
An "activation function" is a function that works at each node. 
It transforms the node's input into some output.
The rectified linear activation function (called ReLU) is widely used in very highperformance networks. 
This function takes a single number as an input, returning 0 if the input is negative, and input as the output if the input is positive.
Here are some examples:
 relu(4) = 4
 relu(-2) = 0
We fill in the definition of the relu() function:
We use the max() function to calculate the value for the output of relu().
We apply the relu() function to node_0_input to calculate node_0_output.
We apply the relu() function to node_1_input to calculate node_1_output.
