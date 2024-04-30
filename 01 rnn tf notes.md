## Vanishing gradient:
RNNs: as more layers are added to the network with same activation funtion the gradient of the loss becomes smaller and smaller. This is because the gradient of the loss (chain rule) are multipied by small values. This means that the initial layers of the network are not getting updated through backpropagation. This is called the vanishing gradient problem.

