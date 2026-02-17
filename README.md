# Function-Approximation-Demo
This repo Contains Python code implementing a neural network with the DeepXDE library.
The model is used to approximate the Harmonic-Oscilator function
<pre> mẍ + μẋ + kx = 0 </pre>

The model is first trained with 200 data points in [NN](/NN.ipynb) and then 30(randomly selected) data points in [NN2](/NN2.ipynb)
## Architecture
A Feedforward Neural network is used. The network has 1 input node, 1 output node and 3 hidden layers with 50 nodes per layer.

## Data
A dataset from [kaggle](https://www.kaggle.com/datasets/cici118/damped-harmonic-oscillator) was used to [train](/train_clean.csv) and [test](/test_clean.csv) the model.

## References
[DeepXDE docs](https://deepxde.readthedocs.io/en/latest/demos/function/dataset.html#implementation)
