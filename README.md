# -Recurrent-Neural-Network-RNN-

1. Introduction
- A Recurrent Neural Network (RNN) is a type of neural network designed to process sequential data (text, speech, time series, video, etc.).
Unlike traditional feedforward networks, RNNs have loops that allow information to persist across time steps.

2. Architecture of RNN
- Input 
- Hidden State
- Output 
#### Lets understand RNN with a example:
- Imagine reading a sentence and you try to predict the next word, you don’t rely only on the current word but also remember the words that came before. RNNs work similarly by “remembering” past information and passing the output from one step as input to the next i.e it considers all the earlier words to choose the most likely next word. This memory of previous steps helps the network understand context and make better predictions.

### Key Components of RNNs
There are mainly two components of RNNs that we will discuss.

1. Recurrent Neurons : - The fundamental processing unit in RNN is a Recurrent Unit. They hold a hidden state that maintains information about previous inputs in a sequence.Recurrent units can "remember" information from prior steps by feeding back their hidden state, allowing them to capture dependencies across time

2. RNN Unfolding : RNN unfolding : is the process of expanding the recurrent structure over time steps. During unfolding each step of the sequence is represented as a separate layer in a series illustrating how information flows across each time step.
4. 
