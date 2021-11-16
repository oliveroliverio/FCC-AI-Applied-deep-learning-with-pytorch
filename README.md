# RNN: recurrent neural networks
RNNs and LSTMs
- used for time series analysis
- stock price predicition: can't predict price based on current month based on one input. Need to observe trend data previously
- text generation: can't predict next word based on previous word: need to see whole sentence as context.
- Think of RNNs as having "memory," and they make predictions based on this memory

RNNs are multiple copies of the same network that recieve inputs at different times as well as its previous hidden state.

![](2021-11-15-21-04-57.png)

Time steps are how many times you copy the network.  Passes the hidden state or output of the hidden neurons to the next neural network

## Difference between RNN and normal feed foward neural networks.

Pic below: input layer (4 input neurons) -> hidden (3 hidden neurons) layer  -> output layer (2 output neurons)
![](2021-11-15-21-07-16.png)

Were going to take this network and flip it and pack it up (represent it as multidimension)

![](2021-11-15-21-09-15.png)

